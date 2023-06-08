# LED Blink Control via Serial Monitor input using Arduino Uno in Proteus
An LED and a Serial Monitor connected to the Arduino. The user will input an integer value to the Serial Monitor, and the LED should blink that number of times.

<p align="center"><img src="https://user-images.githubusercontent.com/52858312/244291297-9acd3fdd-084f-4809-9404-95e5f479c884.png"width=40% height=40%></p>

For instance, if the user enters 5, the LED should blink 5 times.

# How to run this?
Now, first clone the repository. Then, inside the `Task` folder, open the `Task.ino` file in the Arduino IDE. If the `Arduino IDE` is opening for the first time on your operating system, after opening the Task.ino file, go to `File` > `Preferences` > tick the `Compile` option beside `Show verbose output during`. Then, click `OK`. (No need to repeat this task from the second time onwards.)

Now, click the `Verify` button located in the upper left corner, and from the output, copy the following path: `C:\Users\Username\AppData\Local\Temp\arduino\sketches\XXXXXXXXXX/Task.ino.elf`.

![Screenshot](https://github.com/imSamirOFFICIAL/Arduino-LED-Blink-Control-via-Serial-Monitor-input/assets/52858312/7d331b03-62ce-4393-a08e-a789c2ffa7c7)

Next, open the `Task.pdsprj` file in Proteus. Double-click on `Arduino Uno` and paste the `...ino.elf` link into the `Program File` field. Then, click `OK`.

![Screenshot](https://github.com/imSamirOFFICIAL/Arduino-LED-Blink-Control-via-Serial-Monitor-input/assets/52858312/745c357d-ba39-48cc-97b6-cb70f245f028)

Boom! Everything is set up properly. Now, just click the `Run` button located in the bottom left corner and simulate the experiment.

# Note
After running the simulation, a `Virtual Monitor` will pop up. Click on it and type an integer. There is no need to press the `Enter` button on the keyboard after typing the value. Remember, if the `Echo Typed Characters` option is turned off, what you type on the Virtual Monitor will not be shown on the display. So, don't panic, just type an integer.
