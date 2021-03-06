---
layout: post
title: "MUV Proximity Sensor"
date: 2018-12-24 16:42:24 +100
categories: jekyll update
---
## **Making a case for the MUV proximity sensor:**




**Proximity sensor, PCB + Components Dimensions:**

Screw holes: 51.5mm x 38.75mm

H: 70mm

W: 59mm x 59mm

**Proximity Sensor Case, Key points for design:**

-Allow NFC to function

-Design for manufacture with Fablab machines

-Ease of assembly

-Access to all buttons and USB port

-Access to battery

-B,C and Tag LEDs all visible

**Research and Preparation:**

I chose 4mm poplar triplex as a material for the proximity sensor as I think it well suited to the intended application of the proximity sensor; they will be indoors and there will be many of them. The 4mm poplar triplex is a good value for its level of durability.

I did tests to find the right sizing and settings for making press fit components on our lasercutter. After some time I decided that Speed 100 and Power 100 gave a good balance between keeping corners sharp and minimizing burning. It also has the added benefit of cutting quickly.

Next I had to find out the kerf of my lasercutter with this material at these settings. Cutting the slots of my press fit joints to 3.7mm gave a good fit with the 4mm triplex I have decided to use for the proximity sensor case.

Here's a guide on how to figure out the kerf of your lasercutter:
http://fab.academany.org/2018/labs/fablabuae/laser.html

All of the designs here were made with the .15 (each side) kerf of my lasercutter, you will have to adjust the sizing of the joints for the characteristics of your lasercutter.

## **Designing & Making:**




**Designing:**

![MUV Prox.](assets\images\MUVProx\Sketch.jpg)

If I make the box with press-fit finger joints on all sides, then the enclosures can be stacked in the x and y axis, providing opportunity for expansions to the proximity sensor in the future.

For this project, I think its the most time effective to use an online lasercut box generator.

A quick google search gave me some online options for designing lasercut joints. I liked "makercase.com" because of its  simplicity and visual preview.

![MUV Prox.](assets\images\MUVProx\Makercase.png)

I used makercase to quickly design the joints of the box. The website allows you to enter the kerf of your lasecutter and adjusts the files it outputs to press fit together nicely.

I then edited the parts in illustrator to make the width of the joints the same along the whole length of all sides of the case.(makercase.com makes the first and last joints larger, I don't want this)  This will allow the boxes to be stacked together as per my design.

I cut out small sections of each part to check the fit without wasting much material:

![MUV Prox.](assets\images\MUVProx\Tests.jpg)

After I had the basic box shape, I measured and mapped out the required holes for the buttons and LEDs to be usable/ visible, again testing as I went.

Here is the plans for the final design of my case for the MUV proximity sensor:

![MUV Prox.](assets\images\MUVProx\Plans.png)

Each part of the design can be cut halfway and the joint pattern can be extended to make any height or width box.



**Materials Needed:**

4mm triplex poplar (300mm x 320mm)

Small pieces of frosted acrylic to act as diffusers for the LEDs ( can be cut from scrap)

Small piece of double sided tape

2x m2.6 x 20 screws and nuts

4x m2.6 x 7.5 screws and nuts

Sandpaper, CA glue and rubber hammer (if needed to help with assembly)

**Making/ Instructions:**

Step 0:

Collect your parts:
![MUV Prox.](assets\images\MUVProx\Step 0.jpg)

Step 1:

![MUV Prox.](assets\images\MUVProx\step 1.jpg)

Step 2:

Stick battery to the back of NFC sensor:
![MUV Prox.](assets\images\MUVProx\step 2.jpg)

Step 3:

Screw the PCB to the floor plate with the NFC sensor facing the arrow:
![MUV Prox.](assets\images\MUVProx\step 3.jpg)
Step 4:

Insert Acrylic piece into the front plate:
![MUV Prox.](assets\images\MUVProx\step 4.jpg)

Step 5:

Attach the front to base plate:
![MUV Prox.](assets\images\MUVProx\step 5.jpg)

Step 6:

Attach the side plate with the USB and ON/OFF holes:
![MUV Prox.](assets\images\MUVProx\step 6.jpg)

Step 7:

Insert the ON/OFF switch into the side plate:
![MUV Prox.](assets\images\MUVProx\step 7.jpg)

Step 8:

Attach the side plate without any holes halfway:
![MUV Prox.](assets\images\MUVProx\step 8.jpg)

Step 9:

Insert the top plate with the hole for the lid:
![MUV Prox.](assets\images\MUVProx\step 9.jpg)

Step 10:

Insert the acrylic piece into the back plate:
![MUV Prox.](assets\images\MUVProx\step 10.jpg)

Step 11:

Attach the back plate halfway:
![MUV Prox.](assets\images\MUVProx\step 11.jpg)

Step 12:

Insert the buttons into the back plate:
![MUV Prox.](assets\images\MUVProx\step 12.jpg)

Step 13:

Make sure they fit securely enough, use some CA glue if needed:
![MUV Prox.](assets\images\MUVProx\step 13.jpg)

Step 14:

Attach the speaker with the longer screws:
![MUV Prox.](assets\images\MUVProx\step 14.jpg)

Step 15:

Then secure with the nuts:
![MUV Prox.](assets\images\MUVProx\step 15.jpg)

Step 16:

Gather the 3 lid parts:
![MUV Prox.](assets\images\MUVProx\step 16.jpg)

Step 17:

Join the middle and bottom pieces of the lid:
![MUV Prox.](assets\images\MUVProx\step 17.jpg)

Step 18:

Attach the top of the lid:
![MUV Prox.](assets\images\MUVProx\step 18.jpg)

Step 19:

Insert the whole lid into the top plate of the box and turn to close:
![MUV Prox.](assets\images\MUVProx\step 19.jpg)

Step 20:

Attach the bottom cover on one side:
![MUV Prox.](assets\images\MUVProx\step 20.jpg)

Step 21:

Carefully join the other sides of the bottom cover with the rest of the box:
![MUV Prox.](assets\images\MUVProx\step 21.jpg)

Step 22:

Sit back and admire your finished MUV Proximity Sensor case!
![MUV Prox.](assets\images\MUVProx\step 22.jpg)
