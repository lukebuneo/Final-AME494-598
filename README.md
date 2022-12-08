# Final-AME494-598

Final project for AME 494/598

Repository includes code, 3D models of enclosure, and demo photos of my end result. 

For my original idea for this project, I wanted to create a leak detector similar to one that can be bought online.
I couldn’t get my hands on a sensor that would be able to detect itself being submerged in water, so I felt like trying to use humidity 
(to detect presence of water) would be close. 
I ended up using an ESP32C3 microprocessor with a sparkfun HIH-4030 humidity sensor to serve as my humidity detector. 
I connected the 5V pin to the corresponding 5V on the microprocessor. 
I then soldered the OU of the sensor to pin 8, and connected the ground on both. 

I started the code with a sparkfun humidity/temperature sensor example, and used the basics of 
that code to get my humidity sensor to give me live output data in my port window on Arduino. 

The third and final piece of my project was creating a 3D printed enclosure, which I designed in Fusion 360 and attached to this repo
with .stl files. 
