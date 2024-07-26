# Interactive SAO for DEF CON 32 Badge Documentation

## YOUTUBE TUTORIAL / DEMONSTRATION
https://youtu.be/WPPUDujF5oE

## Introduction

Today, we're going to take a look at the interactive SAO for the DEF CON 32 badge.

## What's Inside the Bag?

- **Interactive SAO**
- **Hacker Summer Camp sticker**
- **Make it Hacken sticker**
- **DC32 Engage sticker**
- **Googly eyes**
- **DC32 Flipboard sticker**

## Interactive SAO Overview

The interactive SAO for the DEF CON 32 badge, although compatible with any badge, is specifically designed with the DEF CON 32 badge in mind. 

### Badge Simulator

To demonstrate, we use a badge simulator (an Arduino with a shield). The badge will have an SAO port with a notch on the top. The SAO will have a corresponding notch to ensure correct insertion.

### Pinout Details

When looking at the SAO from the perspective of the badge, the pinout is as follows:
- **Top Left Pin**: 3.3V
- **Bottom Left Pin**: Ground
- **Middle Top**: I2C SDA line
- **Middle Bottom**: I2C clock line
- **Top Right**: User 1 line (GPIO28)
- **Bottom Right**: User 2 line (GPIO29)

User 1 and User 2 lines are broken out for GPIO functionality. I2C lines are not tested in this demo but are available for debugging.

## Using the Interactive SAO

### Output Mode

1. **LED Type**:
    - **NeoPixel (WS2812 RGB LED)**: Demonstrates signal transmission from the badge to the SAO.
    - **Discrete LED**: Turns on or off based on high or low signal.

2. **Switching Output Modes**:
    - Slide User 1 switch to LED for output.
    - Use the badge simulator to test the LED outputs.

### Input Mode

1. **Button Input**:
    - Slide User 1 switch to button for input.
    - Configure the signal type (low or high).

2. **Signal Configuration**:
    - Default low with button press high.
    - Default high with button press low.

## Demonstration

1. **Testing Output**:
    - Insert the SAO into the badge simulator.
    - Test NeoPixel and discrete LED outputs using the simulator's menu.

2. **Testing Input**:
    - Slide User 1 switch to button.
    - Configure signal type and observe changes upon button press.

### Summary of Options

- **Output**: 
    - NeoPixel (RGB LED) or discrete LED (on/off).
    - Controlled via User 1 and User 2 lines independently.
  
- **Input**:
    - Button press can send high or low signal based on configuration.

## Conclusion

We hope this tutorial helps you understand the interactive SAO for the DEF CON 32 badge. Have a great time at DEF CON, and see you at summer camp!


For more details, visit the [GitHub repository](#).
