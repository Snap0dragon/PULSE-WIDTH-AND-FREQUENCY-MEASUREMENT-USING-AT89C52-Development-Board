# PULSE-WIDTH-AND-FREQUENCY-MEASUREMENT-USING-AT89C52-Development-Board
The project's major goal is to design a system that accurately measures input signal frequency and duty cycle. An 8051 microcontroller will capture and analyze the signal and show the measured results on an LCD. The device will also notify and display the frequency deviation on the LCD screen if it deviates from 50Hz.
Another objective is to accept two input signals, calculate their frequencies, and synthesize a new signal using the sum of their frequencies. The 8051 microcontroller accurately measures each input signal's frequency and facilitates the creation of a composite signal that accurately represents the sum of its frequencies. The project uses task-specific indicators to improve the user interface and provide rapid feedback on ongoing operations. Indicators use LEDs. LED 1 will light up when the system monitors signal frequency and duty cycle. LED 2 activity shows that the microcontroller is mixing two input frequencies to form a new signal.

![image](https://github.com/Snap0dragon/PULSE-WIDTH-AND-FREQUENCY-MEASUREMENT-USING-AT89C52-Development-Board/assets/86599809/f8b22f6f-4936-451b-afd6-535b3dcec0d2)

Mandatory Features:
i) The microcontroller has to take input from the signal generator on pin 3.4, display the frequency and duty cycle of a signal, and display it on the LCD. If it is less/more than 50Hz sound an alarm and specify the difference on the LCD.

ii) The microcontroller takes another signal from pin 3.5, measures the frequencies, and generates a new signal equal to the sum of those frequencies.

iii) It continuously carries out the above tasks and LED 1 should be turned on when the first task is being carried out, and LED 2 should be turned on when the second task is being carried on.

Additional Features:
i) The microcontroller is not bound to the 255hz range. It can measure up to 65535 using 2 16-bit arithmetic sub-routines.
ii) The output is given in decimal rather than hexadecimal.

![image](https://github.com/Snap0dragon/PULSE-WIDTH-AND-FREQUENCY-MEASUREMENT-USING-AT89C52-Development-Board/assets/86599809/ca5e1e86-f20e-43c4-9290-65ba2fd248ab)

![image](https://github.com/Snap0dragon/PULSE-WIDTH-AND-FREQUENCY-MEASUREMENT-USING-AT89C52-Development-Board/assets/86599809/520bd3dc-18f5-4a55-898f-57fc9f6b23df)


