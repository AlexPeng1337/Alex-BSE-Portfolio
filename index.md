# Voice Assistant with AI

My project can naturally speak with humans and comprehend their requests by sending it to ChatGPT and speaking the response aloud. Using Rasberry Pi, this voice assistant can help with a variety of tasks which the user can ask. A modification that can be added to this project is enabling bikers to say "left" or "right" where the robot will turn on a corresponding light to alert drivers behind them which way they are turning.


| **Name** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Alex P | Henry M Gunn High School | AI/ML | Rising Sophomore

<img src="BSE-Alex-headshot.jpg" width="443" height="593">




<!---**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**

![Headstone Image](logo.svg)-->
  
<!---# Final Milestone-->

<!---**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE-->



<!---# Second Milestone-->

<!---**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VAmNlER5Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your second milestone, explain what you've worked on since your previous milestone. You can highlight:
- Technical details of what you've accomplished and how they contribute to the final goal
- What has been surprising about the project so far
- Previous challenges you faced that you overcame
- What needs to be completed before your final milestone -->

# First Milestone

<!---**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**-->

<iframe width="560" height="315" src="https://www.youtube.com/embed/KPPbzZ2AoVM?si=vwx5OK1yuR2AlYvu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<!---**For your first milestone, describe what your project is and how you plan to build it. You can include:
- An explanation about the different components of your project and how they will all integrate together
- Technical progress you've made so far
- Challenges you're facing and solving in your future milestones
- What your plan is to complete your project**-->

## Description
My project is the Voice Assistant with AI. The first step is to insert the SD card in my Raspberry Pi, which will serve as the basic storage system for my robot. I plan to build this through using OBS to connect my Raspberry Pi to my computer and then inserting my code there in the terminal. So far, I have successfully managed to do this and have been able to edit in the terminal. The next step is installing the dependencies and changing the default mode for audio devices so that the robot may recognize human voice and then convert it to text. Then it will send the prompt to ChatGPT and speak out the response.


Challenges that occurred was connecting the Raspberry Pi to OBS. The result is a black screen displayed on OBS. The debugging process is selecting the "+" sign, selecting Video Capture Device, and then selecting USB Video.

# Starter project

<iframe width="560" height="315" src="https://www.youtube.com/embed/KVOnv4-s2qQ?si=DQyoTVDBob2fWpel" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Description
In my starter project, I created a Calculator which can solve basic arithmetic expressions by using an integrated circuit. Moreover, there is also a mode where the resisitor's resistance value will be displayed when given an input of a sequence of colors. I chose this project due to the practical use of a calculator in everyday life as well as the project's involvement with soldering, which is very important for many hardware projects.

## Challenges
A challenge that ocurred during the making of this project was soldering the wrong part. This led me to spending significantly more time desoldering and resoldering. Accidentally soldering parts also caused the top row of the LED display to malfunction and stop displaying.

## List of Materials
Here is the list of materials I used for my starter project:

| **Part** | **Note** | **Price**
|:--:|:--:|:--:|
| DIP-28 IC Socket | The integrated circuit is the device that calculates the arithmetic expressions. | $9.49
| LED display | This item displays the input and the output. | $7.69
| Micro USB Socket | This is where the USB charger goes in, to power the calculator | $9.99
| CR2032 battery | The battery is another way to power the calculator. | $5.69
| Acrylic plates | These plates surround the calculator, protecting the board and the wires. | $4.99

<!---# Schematics-->
<!---Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. -->

<!---# Code-->
<!---Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs. 

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
-->
<!---# Bill of Materials-->
<!---Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. 

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
-->
<!---# Other Resources/Examples-->
<!---One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here.-->
