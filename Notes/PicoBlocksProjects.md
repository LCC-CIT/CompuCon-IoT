<h1>PicoBlocks Projects</h1>

<h2>Contents</h2>

[TOC]

## Pico Blocks IDE
[Pico Bricks IDE](https://ide.picobricks.com/verticalblocks.html)

This can be used for either drag-and-drop visual programming or Python text based programming. It can run programs on a Pico board or a simulator.

- A **Chrome browser is required** to use this IDE.
- It takes about one minute for  the IDE web page to load.

## Pico Bricks Ebooks

[Project Book](../Books/project_book_v2_compressed.pdf)&mdash;This book gives instructions for programming projects using the PicoBlocks MicroBricks IDE, Thonny Python IDE and Arduino IDE with the C programming language.

[IDE Book](../Books/WEB-PicoBricks-IDE-ebook-v2_1_compressed.pdf)&mdash;This book only shows how to program the projects using MicroBricks but gives those instructions in more detail than the other book.

Both books have the same projects. Projects 1 through 10 and 15 can be done with just the Pico Blocks Base kit. Projects 11&ndash;14 and 16&ndash;25 require parts that are not included in the base kit.

## Projects

These are the projects described in the books listed above.

### Base Kit Projects

1. **Blink**&mdash;Make an LED blink on and off. Pg. 18

2. **Action - Reaction**&mdash;Turn on an LED when a button is pressed. Pg. 21

   - Uses an If, Else block with a true/false condition

3. **Autonomous Lighting**&mdash;Use the LDR light sensor to turn on the RGB  LED. Pg. 24
   Uses:

   - Serial Print block to monitor a value
   - If, Else block with a number condition

4. **Thermometer**&mdash;Measure the temperature using the temperature sensor (in the temperature and humidity brick) and show it on the OLED display. Pg. 28

5. **Graphic Monitor**&mdash;Use the potentiometer to change the brightness of the RGB LED. Pg. 31

   (Note that it doesn't graph anything nor does it use the diplay.) Uses:

   - Variables
   - Math operation block

6. **Dominate the Rhythm**&mdash;Play a tune on the  buzzer. Start playing when the button is pressed, control the playing speed with the potentiometer. Show the speed on the display. Pg. 34
   Uses these kinds of blocks:

   - Variables
   - Math operation
   - Function
   - If, Else with number condition

7. **Show Your Reaction**&mdash;Turn on the LED after a random delay, then measure the time it takes a player to press the button. Instructions and score are shown on the cisplay. Pg. 39
   Uses these types of blocks:

   - variables 
   - while with a true/false condition
   - while with a numeric condition
   - functions
   - random number generator

8. **My Timer**&mdash;Use the potentiometer to set a time in hours, minutes and seconds (press the button after entering each one). Press the button to start the timer. The screen will show the countdown. The buzzer will sound and the RGB LED will light when the time has elapsed. Pg. 43
   Uses these kinds of blocks:

   - Variables
   - If, else if, else with numeric condition
   - Functions
   - While loop with true/false condition
   - While loop with and condition
   - Math round operation

9. **Alarm Clock**&mdash;When the LDR (light sensor) detects light, it shows a "good morning" message on the display, when the button is pressed, it shows "have a nice day". Pg. 48

10. **Know Your Color**&mdash;The display shows a color name while the RGB LED shows different colors. When the color matching the name is shown, press the button. You get a score based on how many times you pressed the button at the right time. Pg. 51


15. **Night and Day**&mdash;A player moves their hand over the LDR when the word "night" is shown on the display. Pg. 67

### Advanced Kit Projects

11. **Magic Lamp**&mdash;Turn on an LED, or alternatively a desk lamp via the relay on the basic board, by clapping. Requires a <u>sound sensor</u> module that is not part of the basic board. Pt. 55
12. **Smart Cooler**&mdash;Run a fan when the  temperature drops below below a certain level. Requires a <u>motor</u> that is not in the basic kit. Pg. 58
13. **Buzz Wire Game**&mdash;When a wire is connected between two pins of a jumper cable the LED lights and the buzzer sounds. Uses a jumper cable included in the basic kit and requires <u>a piece of wire</u> which is not part of the basic kit. Pg. 61
14. **Dinosaur Game**&mdash;Uses the LDR, motor driver and a <u>servo</u> (not included in the base kit) to play the dino game hidden in the Chrome browser (chrome://dino). Pg. 64


16. **Voice Controlled Robot Car**&mdash; A car that is controlled by an IR keypad or optionally by a smart-phone app that accepts voice control.   Pg. 71
    Uses all the same extra components as the Maze Solver Robot car, as well as:

    -  <u>wireless (IR) control keypad</u>
    - IR sensor module

17. **Two Axis Robot Arm**. Pg. 74
    Requires <u>two servos</u>.

18. **Smart House**. Pg. 82

    Requires:

    -  HC-SR501 PIR (infrared) <u>motion sensor</u>
    - MQ-2 <u>toxic gas sensor</u>

19. **Piggy Bank**. Pg. 86
    Requires:

    - <u>Ultrasonic distance sensor</u>
    - <u>Servo</u>

20. **Automatic Trash Bin**. Pg. 91
    Requires:

    - <u>Ultrasonic distance sensor</u>
    - <u>Servo</u>

21. **Digital Ruler**. Pg. 93
    Requires an <u>ultrasonic distance sensor</u>

22. **Air Piano**. Pg. 95
    Requires:

    - <u>Ultrasonic distance sensor</u>

23. **Maze Solver Robot**. Pg. 97

    *Notes:*

    1. *that the code in the IDE Docs uses motor control blocks for V1, replance them with V2 blocks.*

    2. *There are construction instructions in the Resources section at the end of the IDE Project book.*

    3. *Upload the Python code to the RP Pi Pico on the car.*

       Requires:

    - Two <u>motors</u>
    - <u>Untrasonic distance sensor</u>
    - <u>Car body and wheel kit</u>
    - <u>Battery holder</u> and three AA batteries

24. **Smart Greenhouse**. Pg. 100

    Note, the instructions use an ESP8266 WiFi module, but this is not needed with the Pico W on our V2 Pico Blocks boards. This project does require:

    - Soil moisture sensor
    - Pump

---

Back to the [main page](../index.html)

------

[![Creative Commons License](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/) Reference materials compiled by [Brian Bird](https://profbird.dev), written in <time>2025</time>, licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/). 

------------



