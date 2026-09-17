# STM32F407-Discovery
STM32F407‑Discovery Board Overview
🔹 1. Board Description
The STM32F407‑Discovery is an evaluation board featuring the STM32F407VGT6 ARM Cortex‑M4 microcontroller running at 168 MHz. It includes on‑board peripherals such as LEDs, push‑buttons, an accelerometer, audio codec, and USB OTG.

🔹 2. Microcontroller Specifications
MCU: STM32F407VGT6

Core: ARM Cortex‑M4

Clock: Up to 168 MHz

Flash: 1 MB

SRAM: 192 KB

Floating‑point unit: Yes

Timers: 17

Communication: I2C, SPI, UART, CAN, USB OTG

🔹 3. On‑Board Components
LEDs
LD3	Orange	PD13
LD4	Green	PD12
LD5	Red	    PD14
LD6	Blue	PD15

Used for:
GPIO testing
Task activity indicators
Bootloader status signals

User Button
B1 (Blue) → PA0
Used for:
Interrupt testing
Input events
Mode switching

Accelerometer (LIS302DL or LIS3DSH)
Interface: SPI
SCK → PA5
MISO → PA6
MOSI → PA7
CS → PE3

Used for:
Sensor reading tasks
FreeRTOS queue messaging
Motion‑based demos

Audio Codec (CS43L22)
Interface: I2C + I2S
I2C → PB6 (SCL), PB9 (SDA)
I2S → PA4, PC7, PC10, PC12

Used for:
Audio output experiments
DMA + interrupt practice

USB OTG FS
PA11, PA12

Used for:
USB device/host demos
Optional firmware update transport

🟧 Power & Debug Interfaces
Power Options
USB mini‑B
External 5V supply

Debug Interface
On‑board ST‑Link/V2  

Used for:
SWD debugging
Breakpoints
Flash programming


