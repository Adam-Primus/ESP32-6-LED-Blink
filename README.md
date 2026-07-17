# ESP32 Controlled LED

This is a simple, extremely beginner friendly project that uses an ESP32 DevKit v1 microcontroller to create a pattern on 6 white LEDs using a program.

# Why Make This Project?
The Truth is, I am currently starting my journey of microcontrollers & programming and had minimal knowledge about Those stuff. Earlier, I used to make simple circuit projects. So, to upgrade my journey I am now acquiring my knowledge in this field.

## Components Used
* ESP32 Development Board
* 6x LED (i.e. white)
* Breadboard and Jumper Wires
* resistors as per led.(variable)(if your supply voltage is more than the led's volt rating)

## Circuit Connection
* **LEDs Anode (Long pin)** -> ESP32 Pin GPIO **[13,12,14,27,26,25]**
* **LED Cathode (Short pin)** -> ESP32 **Common GND**

## Live Simulation
I first tested and run this project virtually in my browser using Wokwi, Before doing it physically.

**[Launch Wokwi ESP32 LED Simulation](https://wokwi.com/projects/469460512073851905)**

<img width="1366" height="632" alt="Screenshot of Simulation" src="https://github.com/user-attachments/assets/00da28f2-647f-42f2-a8b5-f15cd424767c" />

## Bill of Materials (BOM)
This is the full parts list, & prices in the [BOM spreadsheet](./bom.csv).

