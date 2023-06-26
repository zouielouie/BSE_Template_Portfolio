# Real Time Planet Tracking System

My intensive project was the Real Time Planet Tracking System

| **Name** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Bryan L | Mountain View High School | Aerospace Engineering | Incoming Senior

<!---**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**--->

<!---![Headstone Image](logo.svg)--->
  
<!---# Final Milestone
For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>--->

<!---# Second Milestone
For your second milestone, explain what you've worked on since your previous milestone. You can highlight:
- Technical details of what you've accomplished and how they contribute to the final goal
- What has been surprising about the project so far
- Previous challenges you faced that you overcame
- What needs to be completed before your final milestone 

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VAmNlER5Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>--->

# First Milestone
### Summary
My project involves a plethora of different parts, calculations and precise movements. Before working on the hardware I had to learn about the calculations necessary to get from the statistics of a planet to the degrees relative to the machine it has to "look". Then I had to work with the following hardware components which provide the variables necessary to do the calculations. 

Components: 
  - Arduino Mega
  - Breadboard
  - GPS Module
  - Servos and Laser Pointer Machine
  - Gyroscope

The Arduino Mega acts as the brains to my system, and stores all the code that goes towards everything. It connects its power to the breadboard which distributes power to the rest of the components. The GPS Module and Gyroscope connect to the arduino (to get and give information) and the breadboard (for power) through various ports. The Servos connect to the both the arduino and the breaboard however since it only recieves information (doesn't give information back) there is 3 wires (power, ground and recieve data). 

### Progress
I developed a general understanding behind the math required to solve ascension and declination. I also got all of my hardware components working through connections and test code. 

### Challenges
One challenge I had was with the servos. The servos only got 180 degrees and my top servo actually needs to go a whole 360 degrees (needs to be able to rotate its head to look anywhere in the night sky)

<iframe width="560" height="315" src="https://www.youtube.com/embed/CiB3LzFuGAQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

# Starter Project: Binary Blaster Game
### Summary
Before I started on my main project, I worked on my starter project, which was the Binary Blaster Game. It was mostly a solder focused project, where I needed to solder all the parts onto a circuit board. 

Components: 
- Resistors and Capacitors
- Batteries
- Switches and LED Buttons
- LED Lights
- Buzzer
- Microcontroller

The microcontroller acts as the brains as the whole system. The switches allow current from the batteries to flow or not, being an on/off switch, to both the buzzer and the system. If the current flows through (meaning it is on), connection flows to the rest of the system, and the buttons (when pressed) signals to the microcontroller, which signals to the LED lights to display.

### Challenges
One problem I had was with the direction of certain parts, and needed to do diode tests to figure out the positive and negative side of the piece. 

- Learned about polarization
- Continued practice of soldering
- Learned how to use the multimeter
- Learned about diode tests and bias in circuits

### Next Steps
Now I will begin on my intensive project
  
<iframe width="560" height="315" src="https://www.youtube.com/embed/cKlvox5fjQM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
In the video above I demonstrate how to play my game as well as explain different parts of it. 

# Schematics 
Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. 

<!---# Code
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
```--->

<!---# Bill of Materials
Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. 

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|
--->
<!---# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here.
--->
