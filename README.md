# Digital Signal Processing

(Work in progress)

## Digital Signal Processing basics

### [Digital Audio Processing](DigitalAudioProcessing)

The best text book that I have ever read in my life: [C言語ではじめる音のプログラミング―サウンドエフェクトの信号処理](https://www.ohmsha.co.jp/book/9784274206504/). This folder contains Python-version of the C programmes in the book.

### [Speech Processing for AI](SpeechProcessing)

In September 2018, I found this great paper on the net: https://haythamfayek.com/2016/04/21/speech-processing-for-machine-learning.html. I relearn the paper in this project.

### [AI Rock Paper Scissors](RockPaperScissors)

I developed Rock Paper Scissors on Nucleo L401RE board with Panasonic AMG8833 in January 2019, just after the first relase of STM32Cube.AI (December 2018) became available for developers: [The demo on YouTube](https://www.youtube.com/shorts/d6OYSllaVEs). I remember my excitement on STM32Cube.AI -- AI can run on such a tiny device!

I relearn it in this project by doing this: https://github.com/araobp/stm32-mcu/tree/master/NUCLEO-F401RE/Thermography

STMicroelectronics also developed a toy similar to mine, but with VL53L5: https://stm32ai.st.com/use-case/shifumi-gesture-recognition/

### [Edge AI on STM32](STM32)

This folder is to implement the hardware part of "RockPaperScissors" on STMicroelectronics NUCLEO-L476RG board with the latest version of CubeIDE/CubeMX and STM32Cube.AI.

### CMSIS-DSP

I learn CMSIS-DSP in this project.

- CMSIP-DSP: https://www.keil.com/pack/doc/CMSIS/DSP/html/index.html
- Python-version of CMSIS-DSP: https://pypi.org/project/cmsisdsp/

...

## Acoustic Scene Classification

This is a project to develop edge AI for Acoustic Scene Classification based on STM32Cube.AI, referring to my past project: https://github.com/araobp/acoustic-features which was the best thing I have ever developed in my carrier as an ICT engineer, although it was my hobby project (not a commercial product).

...

## Mic Array

...

## References

### Delta-Sigma ADCs

- [How delta-sigma ADCs work, Part 1](https://www.ti.com/lit/an/slyt423a/slyt423a.pdf?ts=1694396702991)
- [How delta-sigma ADCs work, Part 2](https://www.ti.com/lit/an/slyt438/slyt438.pdf?ts=1694411423855)
- [Getting started with sigma-delta digital interface
on applicable STM32 microcontrollers](https://www.st.com/resource/en/application_note/an4990-getting-started-with-sigmadelta-digital-interface-on-applicable-stm32-microcontrollers-stmicroelectronics.pdf)
---
## Misc

The below works are for training myself in the field of data science and Deep Learning.

### [Arduino-version of the thermography](misc/Arduino)

Make Jupyter Notebook collect data from this Arduino version of the thermograpy device with Panasonic AMG8833.

<img src='doc/me.jpg' width=200>

This is me.

### [CIFAR 10](misc/CIFAR10)

The best accuracy I have ever achieved is 75%. Can I get a higher score than 75%?

### [MINIST](misc/MNIST)

### [IMDb](misc/IMDb)

### [Titanic](misc/Titanic)

### [Audio](misc/Audio)
