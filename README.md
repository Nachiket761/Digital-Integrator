# Digital-Integrator
designed this product as part of DE250

Using a Black-Pill STM32F401CCU6 in USB Host mode in combination with a cheap Optical USB mouse, 0.96" OLED I2C display and VL53L0x ToF sensor

Concept: an optical mouse sensor can measure the displacements i.e. dX and dY and transmit this data over USB. using this data and the ToF sensor in theory it is possible to caluate, distance, area, and path length. 

<img width="1728" height="1080" alt="Untitled" src="https://github.com/user-attachments/assets/fd90a249-8287-4279-8dfb-8a74ce9bb09f" />

PART 1: Establishing Communication link between Black-pill and Mouse sensor
