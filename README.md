# ESP32 LED Blink

Blinks an LED connected to GPIO 2 of an ESP32 every 1 second.

- Board: ESP32 DevKit C
- Components: 1 LED (a 220 ohm resistor is needed on real hardware)
- Language: Embedded C/C++ (Arduino framework)
- Simulation: https://wokwi.com/projects/481310242409693185

## How it works
GPIO 2 is set as output. The program turns the pin HIGH and LOW with a 1000 ms delay, so the LED blinks.
