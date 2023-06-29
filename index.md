# IOT weather station

 <!---Replace this text with a brief description (2-3 sentences) of your project. This description should draw the reader in and make them interested in what you've built. You can include what the biggest challenges, takeaways, and triumphs from completing the project were. As you complete your portfolio, remember your audience is less familiar than you are with all that your project entails!
You should comment out all portions of your portfolio that you have not completed yet, as well as any instructions:-->

| **engineer** | **school** | **area of interest** | **grade** |
|:--:|:--:|:--:|:--:|
| Keira Z | Crystal Springs Uplands School | Vocal synthesizers?? | 10th (when school starts)

<!---**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**

![Headstone Image](IMG_6498.HEIC)
![Headstone Image](IMG_6500.mov)
  
# Final Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE



# Second Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VAmNlER5Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your second milestone, explain what you've worked on since your previous milestone. You can highlight:
- Technical details of what you've accomplished and how they contribute to the final goal
- What has been surprising about the project so far
- Previous challenges you faced that you overcame
- What needs to be completed before your final milestone 
-->
# First Milestone


<iframe width="560" height="315" src="https://www.youtube.com/embed/CaCazFBhYKs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
my final project is the IOT weather station, which is a glorified lamp that changes color depending on the weather. 

## COMPONENTS

so far, my project consists of a breadboard, various wires, a Particle Argon, and a 12-pixel NeoPixel ring. i do have the rest of the components (the jar and cotton wool), but i will use them much later. currently, i have the Argon installed on the breadboard, and it is also connected to the NeoPixel light. it recieves power from a USB cord connected to my computer. here are brief descriptions of the components i have:
- breadboard: (connects the components, lets the power from the computer go to the NeoPixel
- Particle Argon: a wifi development kit for building connection-reliant projects
- 12-pixel NeoPixel ring: a ring with 12 lights on it.
- wires: lets the light be powered

## CHALLENGES

when first starting out on this project, i had absolutely no idea what i was doing, and all of the components were either completely new or barely familliar ot me. i wasted a lot of time just being confused and not really doing anything as a result. in my opinion, i had the most trouble regarding the Argon. for example, the tutorial i was given used the Photon instead of the Argon, which caused me a lot of confusion due to the Argon being able to handle less voltage (3.3v) compared to the Photon (5v). this also menat that i had to rework some of the wires and remove some things in general, which i also had some issues with due to my lackluster knowledge of circuitry. all previous knowledge i had of c++ completely vanished, so even when i had finished placing down all the components correctly, i still had to spend a lot of time on figuring out how to check that the project worked. overall, so far this project has made me feel mildly lacking in the intelligence department. in order to complete my project, i will need to make the lights change according to current weather data, which will most likely be my next step.

For your first milestone, describe what your project is and how you plan to build it. You can include:
- An explanation about the different components of your project and how they will all integrate together
- Technical progress you've made so far
- Challenges you're facing and solving in your future milestones
- What your plan is to complete your project


# Starter Project

![Headstone Image](IMG-6506.JPG){: height="30%" width="30%"}
<iframe width="560" height="315" src="https://www.youtube.com/embed/bR8ie5K5Cio" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

## SUMMARY

this starter project is the useless box, a box that genuinely has no purpose and is, as its name implies, useless. its only function is to turn itself off. the useless box is comprised of various components including a motor, arm, switch, and box parts. in general terms, when the switch is flipped, the motor is activated and turns the arm up, which un-flips the switch and lets the arm go back down. this project was relatively easy to create, as the instructions were simple and had effective diagrams. 

## COMPONENTS

-  laser-cut acrylic parts (used to construct the 'box' part of the useless box)
-  laser-cut wood piece that says 'useless box' (decoration)
-  door with hinge rod (the arm pushes it up every time it goes up, like a small turtle)
-  arm (used to flip the switch. it's attached to the motor spindle, so its rotation is controlled by the motor.)
-  motor mount parts (encloses the motor. shapes let them lock to the bottom of the box and attach to different components via screws.)
-  2" corner posts (supports the walls of the box. screws into the top/bottom of it.)
-  weld nuts/(self-tapping) screws/washers/switch nut & washer (attaches components together or helps reduce friction)
-  PCB board (contains all the circuitry needed to run the useless box)
-  3x AAA battery pack (holds 3 AAA batteries. powers the motor and connects to the PCB board)
-  adhesive velcro (attaches the battery pack to the bottom of the box)
-  motor (i'm not sure what kind of motor it is, but it has nubs/shapes on it that fit around the motor mount parts.)
-  resistors (used to provide a specific voltage to the motor?)
-  switch (the 'activator' of the useless box. when flipped, the box turns on.)
-  screw terminals (connects the battery pack and the motors to the PCB. lets the battery distribute energy and the motor recieve energy.)
-  led (for decoration. turns green when the arm rotates up and turns red when the arm rotates down.)
-  snap switch (used to detect when the arm has returned to its original position, turning off the LED.)

the useless machine works in this way: when the switch on top is flipped, the motor is activated using energy from the battery pack, which turns the LED on and makes it green. since the arm is attached to the motor spindle, the arm rotates up until it reverses the switch, whitch turns the LED red. the arm is then rotated down. when the arm goes back to its 'resting' position, it hits a snap switch on the bottom of the PCB, which turns off the LED.
  
## CHALLENGES

this project was easy to make, given that the project instructions were detailed and easy to follow. the most challenging parts of creating the useless box were learning how to solder and getting the box of the useless box around its mechanisms. all in all, i enjoyed making this project. i have named the box "pablo box" due to how pablo (the arm) lives in the box.

## NEXT STEPS

my next step will be working on the final project that i chose: a weather indicator with IOT. it is a little container with a light that changes color based on the weather.

<!---
# Schematics 
Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. 

# Code
Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs. 

```c++
void setup() {
  // put your setup code here, to run once:
  Serial.begin(9600);
  Serial.println("Hello World!");
}

void loop() {
  // put your main code here, to run repeatedly:

}
```
# Bill of Materials
Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. 

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |

# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)-->
