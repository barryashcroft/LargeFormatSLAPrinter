# Large Format SLA Printer
The concept for this project was to design and build a large format SLA printer Please note, this is still in the early stages of design and development. It may or may not function as expected and is subject to change.

## How it works
This project builds upon existing SLA/MSLA 3D printing technology but allows for larger prints or higher resolution depending upon the screen utilized. This is achieved by adding a moving XY ‘print head’ that features a high resolution UV backlit screen. 

The print head is able to move around the print area while displaying only a small part of the area The total print area represents a high resolution image mask. In printers where the screen area and print area are the same, this image would be show in in it’s entirety with the print surface raising and subsequent images being shown thereafter building cured 3D part layer by layer.  

With the large format SLA printer, the print area can in theory be of any size, with width, height and depth set by the designer or by hardware limitation. The print head will feature a single high resolution screen that is smaller than the print area. This will move around the print area (X/Y) revealing a small part of the image mask/print area. Once time has allowed the resin to cure where the print head is located it will move to the next part of the image mask and cure the resin, repeating until the entire image mask/print area has been covered and allowing the print surface to move upwards and starting over with the next layer.

There are currently two concepts for how the print head would move.
### Method one: Scrolling Print Head
This would involve a slow continuous moving print head that would follow a fixed path for each layer, from left to right, down, right to left, down, left to right etc… This would be carefully timed allowing each area to receive the same amount of cure time.
### Method two: Jumping Print Head
This would involve a print head that would split the total print area into zones equal to the print head size. It will start in zone 1 by displaying the relevant part of the image mask/print area allow adequate time for the resin to cure. Once it has cured it will move to the next zone ‘jumping’ to the next zone, repeating until all zones have been covered on the layer.

## State of Play
Currently there is no physical prototype, it is an untested idea. There is much work to do before this can become a reality. A 10,000 feet overview reveals the following tasks

* Build prototype unit
* Build printer firmware
* Build custom slicer / slicer integration with existing (i.e slic3r)

## What’s next
First and foremost is whether such a machine is a) feasible and b) of interest to the community? By putting the concept out there my first thought is should I continue with it? I’d like to build a community around this project, anyone interested please contact me.

I’m hoping that by putting this idea out there we can refine it and create a great printer. It is important to me that this project remains open hardware. There is no fixed hardware currently, but my idea is to use a Raspberry Pi 4 with 4GB memory. The dual HDMI will hopefully allow a high resolution screen for the print head and a separate smaller screen for controlling the printer.

## Supporting me
If anyone wants to support me in building and making things then I have a Patreon page for those so inclined.  https://www.patreon.com/barryashcroft.

## License
This project and all associated files are licensed under CC-BY-SA. Please visit https://creativecommons.org/licenses/by-sa/4.0/legalcode to find out more about how this affects you and your usage.
