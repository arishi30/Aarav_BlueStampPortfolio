# Smart Robot Car
Hi. My name is Aarav and I built a line-tracking, obstacle-avoiding rover with four motors and an ultrasonic sensor. The car is able to be either remote controlled or is also capabale of self-driving.

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Aarav R | Monte Vista High School | Mechanical Engineering | Incoming Sophomore

![Headstone Image](IMG_2099.png)
  
# Final Milestone
For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

# Second Milestone
For your second milestone, explain what you've worked on since your previous milestone. You can highlight:
- Technical details of what you've accomplished and how they contribute to the final goal
- In this milestone, I was able to successfully get the remote control to start working. To do this, I had to integrate some code from the Motor Test Run into the remote control code. 
- What has been surprising about the project so far
- Previous challenges you faced that you overcame
- One challenge that I had during this milestone was putting the right amount of code from the Motor Test Run into the Remote Control code. I had to take in consideration of all the different commands for the motors and their respective definitions.
- What needs to be completed before your final milestone
- Before the final milestone, the parts for my modification need to arrive. For my modification, I plan to attach a light sensor with a photoresistor and a couple of LEDs to the Arduino chip. By adding these objects, the car will be able to sense the amount of light present in an area. If the light is low or dim, the sensor will tell the LED to turn on and vice versa. 

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VAmNlER5Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

# First Milestone
For your first milestone, describe what your project is and how you plan to build it. You can include:
- In the project, there are four motors that correspond to the four different wheels. There is also a camera, an ultrasonic sensor (it allows the car to measure how far an obstacle is and then determines when to turn), and a line-tracking module. Furthermore, there is the Arduino Uno Chip, which acts as the microcontroller, where all the code and programming is run through. Additionally, there was a remote control included in the kit to manually control the car. 
- So far, the major breakthrough I have had is running and uploading a successful motor test run, which tested the functionality of all four motors on the base of the car. 
-  The main problem I had was getting the motors to run. In the beginning of the programming process, I spent a lot of time trying to upload the code  to the Arduino platform for the motors to move. I tried unplugging the cable and putting it in different ports and even restarted Arduino on my computer multiple times. However, my instrucutor and I soon figured out that there was a switch on the shield above the Arduino chip with two sides, camera and upload. Because it was on the camera side, the Arduino platform never recognized any of the code that was trying to be uploaded.
- Some of my future goals are to work on increasing the speed of the car, programming it to avoid different obstacles, and getting the motors to pair with the remote control. I also want some sort of modification, either a speaker or light-sensitvity.

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/CaCazFBhYKs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

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
| Elegoo Smart Robot Kit V4 | What the item is used for | $79.98 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> https://www.amazon.com/dp/B07KPZ8RSZ?maas=maas_adg_362A97D58CBCE8102DCB01CBFCC13F92_afap_abs&ref_=aa_maas&tag=maas&gclid=Cj0KCQjw4s-kBhDqARIsAN-ipH2jewmYpniPACk46WkTIe49PpDmUiXHb33lgDBl9sFuCHV7G10YU2MaAi1lEALw_wcB&th=1 </a> |
|:--:|:--:|:--:|:--:|
| 8-Pack 9-volt batteries | Used for powering entire project | $12.99 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> https://www.amazon.com/Amazon-Basics-Performance-All-Purpose-Batteries/dp/B00MH4QM1S/ref=sr_1_1_ffob_sspa?keywords=8+pack+9+volt+batteries&qid=1687467125&sr=8-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1 </a> |
|:--:|:--:|:--:|:--:|
| 9-volt DC Battery Power Cable Plug | What the item is used for | $6.79 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> https://www.amazon.com/Battery-Power-Barrel-Connector-Arduino/dp/B07NT79ZVB</a> |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|

# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here.
