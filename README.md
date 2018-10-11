# Useless Box

Lab by Jamie Yu, jky32

## 3D Printing

**a. Include a photo of your printed part here.**

![printed](https://github.com/jamiekimyu/IDD-Fa18-Lab5/blob/master/20181010_180223.jpg)

**b. Include `.stl` or `.svg` files for your bopper, if 3d-printing.**

![bopper](https://github.com/jamiekimyu/IDD-Fa18-Lab5/blob/master/Screen%20Shot%202018-10-10%20at%206.58.35%20PM.png)

## Laser Cutting

**b. Include a photo of your box here.**

![box](https://github.com/jamiekimyu/IDD-Fa18-Lab5/blob/master/20181010_180617.jpg)

![box2](https://github.com/jamiekimyu/IDD-Fa18-Lab5/blob/master/20181010_180625.jpg)

## Electronics

**c. Upload code & a photo of your electronic circuit here.**

[code](https://github.com/jamiekimyu/IDD-Fa18-Lab5/blob/master/code.ino)

[video](https://www.youtube.com/watch?v=CSZseinA-y4)

**d. Reflection.**

In this lab I had a variety of issues getting the servo to work:
1. One servo burnt out because I connected the power to 9V instead of the 5V
2. The servos sometimes worked, sometimes did not work or were delayed
3. Servo was 'stuck' - gears wouldn't move
4. The servo worked with the USB power but not battery power
5. The servo didn't work when extra electronics(pentiometer, motor, resistor) were attached to it 

I learned a lot about debugging issues with servos - for example to check if the servo gears were still working by gently turning it while it was unattached from the breadboard/power; to disconnect other electronics on the breadboard because it might interfere; the battery wires might cross with other wires so its good to make sure they are all separate from one another; to debug using a simpler version of the code instead of the complex one to break down and pinpoint where the problem is, etc. 

Eventually I got the box to work, though it is with the USB power instead of the battery. 
