# Thermography

Board: NUCLEO-L476RG board (STM32L476RGT6 Microcontroller)

### Arudino shield for Panasonic AMG8833

I use the infrared array sensor "AMG8833" for hand gesture recognition.

<img src="doc/AMG8833_breakout.jpg" width=200>

=> [Schematic of the Arduino shield](kicad/RockPaperScissors/arduino_board.pdf)

#### STM32L4 I2C pin assignment for Arduino shield

Arduino shield uses PB8 and PB9 for I2C SCL and SDA.

<img src="doc/I2C1_SCL.png" width=300>

<img src="doc/I2C1_SDA.png" width=300>

### Thermography implementation

=> [Code for NUCLEO-L476RG with the Arduino shield](stm32/Thermography)

=> [Thermography GUI(Python3)](python/ThermographyGUI)

Configuration for data collection
```
[NUCLEO L476RG] --- UART (VCP via ST-Link) --- COM port [Thermography GUI]
```

### Integration test

#### Rock
<img src="python/ThermographyGUI/screenshots/screen_shot_rock.png" width=400>

#### Paper
<img src="python/ThermographyGUI/screenshots/screen_shot_paper.png" width=400>

#### Scissors
<img src="python/ThermographyGUI/screenshots/screen_shot_scissors.png" width=400>

#### Interpolation
<img src="doc/thermography_interporated.png" width=300>
