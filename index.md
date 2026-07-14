# BlueStamp Broswer Controlled Robotic Arm
Replace this text with a brief description (2-3 sentences) of your project. This description should draw the reader in and make them interested in what you've built. You can include what the biggest challenges, takeaways, and triumphs from completing the project were. As you complete your portfolio, remember your audience is less familiar than you are with all that your project entails!

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Nuojie W | Miramonte High school | Not sure | Incoming Senior

**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**

![Headstone Image](NuojieW.jpg)
  
# Final Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE



# Second Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/_Dp6k8TR21Q?si=OyAmCXBaJie-dOUs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

Assembling the mechanical parts of arm is not hard, but it still takes me a few times. You can watch video and find that there are four servos. Each servo control different parts of robtic arm. For the controller, you can see there are two joysticks. The right joystick can control the opening and closing of the arm. The left joystick can control the turning of base and the turning of arm. The biggest challenge I faced absolutely is code problems. Because I am not good at coding, so I mainly use the code from the instruction. However, there are some problems by using code from the instruction. In the tutorial code, there was an error in line45.#include "src/CokoinoArm.h" I move the library of the Arduino IDE to the desktop and change the path in the code. Then, I try to verify again. It still repport an error called compilation error exit status 1. I am confused. After that I back to initial code. I open all the files in the library as the notebook. Then, I try to verify and it works. I actually do not know what the problem is. I think it probably is because of not fully loaded. Now, I have assembled the bluetooth module. I will try to test the bluetooth module by using some code in Arduino IDE. However, there is no tutorial code for the future paths. So I need to search them and learn how to code in the future paths. Also, after testing the bluetooth module, the controlling of the turning and moving of the robtic arm are still by four servos.  In the future plan, I will try to control the robtic arm by browser.

# First Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/RNaX80Mot9k?si=LezSoxHmxEJH6wmU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

My intensive project is Broswer Controlled Robtic arm. Depending on my plan, my first milestone is to make sure all servos are working. Although I have already assemble the base parts of mechanical parts of the arm, I still can show you about this. First, I need to make sure one servo is working before testing all of them. Luckliy, there are some tested code of one servo in the instruction. So I use them successfully. As showing in the video, you can see there are four servos turning around at the same time. However, I only have the tested code of one servo. Then, I try to change the code by myself. Compared to the tested code. I identity successfully about the ports. In the tested code, the port is number 10. I change it to number4,5,6,7. But I think the speed of turning around is too slow. Unfortunately, I do not know which code is about speed. So I search it. Finally, I change the speed of the turning around successfully.

# Starter Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/eAavtL_IkY4?si=-p9Xfx_S2d1FHGH0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

My starter project is LED slider. There are three sliders to control each colors which are red, green and blue. First, I learned how to use the soldering iron. Then, I assembled the mechanical parts of the board. However, there were still many holes. To make sure the system of the LED slider is working, I need to use the soldering iron to melt solder in order to connect with the board. Last, I tested it and controled to make different color successfully.

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
| Arduino NANO board | Control the arm | $22.0 | https://store-usa.arduino.cc/collections/nano-family/products/nano-r4-connector-bundle  |
| Smart Robtic Arm For Arduino | Mechanical parts of arm | $46.0 | https://cokoino.com/products/robot-arm-for-arduino  |
| Batteries | Power support | $6.49 | https://www.amazon.com/AmazonBasics-Performance-Alkaline-Batteries-Count/dp/B00O869KJE?th=1  |
| HC-05 bluetooth module | Connection with browser | $10.39 | https://www.amazon.com/HiLetgo-Wireless-Bluetooth-Transceiver-Arduino/dp/B071YJG8DR  |

# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here.
