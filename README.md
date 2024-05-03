# Arduino Countdown Timer

***This Arduino project implements a countdown timer using two 7-segment displays, two 7-segment decoders, and two buttons - one for start/stop and the other for set/reset functionalities.***
***The timer counts down from a preset value and can be controlled using the buttons.***

## Components Used
- x2 7-segment Displays used to display the countdown time.
- x2 7-segment Decoders that decode the input signals to display the digits on the displays.
- Start/Stop button that controls the start and stop functionality of the timer.
- Set/Reset button that sets the countdown timer or resets it to the initial value.

## Libraries Used
*None*

## How It Works
1. **Initialization :** The pins for the 7-segment displays, buttons, and blank pins are initialized in the setup phase.
2. **Steady Display :** The display is set to a steady state initially, showing no numbers.
3. **Button Inputs :** The state of the start/stop and set/reset buttons is continuously monitored.
4. **Countdown Logic :** The timer counts down from a preset value (initially set to 20 seconds) when the start button is pressed.
5. **Pause and Resume :** Pressing the start/stop button toggles between pausing and resuming the countdown.
6. **Reset Functionality :** Pressing the set/reset button resets the countdown timer to the initial value (20 seconds).
7. **Display Update :** The countdown value is displayed on the 7-segment displays, updating every second.
8. **Blanking :** Blank pins are used to control the blanking of the digits when necessary.

## Usage
- Press the set/reset button to initialize thhe countdown timer to 20 seconds.
- Press the start/stop button to start the countdown.
- Press the start/stop button again to pause the countdown.
- Press the set/reset button to reset the countdown timer to 20 seconds at any time.
- The countdown value is displayed on the 7-segment displays and updates every second.

## Ciruit Diagram
![](https://i.ibb.co/JKJ92sr/arduino-countdown.jpg)

## Note
- Customize the code or hardware configuration as needed for specific requirements or enchancements.
- Ensure correct connections and component functionality to avoid errors in operation.

[click to watch]()
