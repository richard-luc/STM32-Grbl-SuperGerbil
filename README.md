# STM32-Grbl-SuperGerbil
STM32 driven ARM Grbl firmware
![Super Gerbil](https://awesome.tech/wp-content/uploads/2018/11/20181030_103220-1-e1547624499622.jpg)

***
Latest firmware (SG_stm32grbl11.hex) for the Super Gerbil CNC controller is available here
***

-Github repo grbl-1 is for Coocoox CoIde compiler
-Github repo STM32-Grbl-SuperGerbil is for Atollic compiler (preferred)

Grbl is a no-compromise, high performance, low cost alternative to parallel-port-based motion control for CNC milling. This version of Grbl runs on a STM32F10x processor.

The controller is written in highly optimized C utilizing every clever feature of the STM32-chips to achieve precise timing and asynchronous operation. It is able to maintain up to 100kHz of stable, jitter free control pulses and PWM up to 80kHz.

It accepts standards-compliant g-code and has been tested with the output of several CAM tools with no problems. Arcs, circles and helical motion are fully supported, as well as, all other primary g-code commands. Macro functions, variables, and most canned cycles are not supported, but we think GUIs can do a much better job at translating them into straight g-code anyhow.

Grbl includes full acceleration management with look ahead. That means the controller will look up to 16 motions into the future and plan its velocities ahead to deliver smooth acceleration and jerk-free cornering.

* [Licensing](https://github.com/gnea/grbl/wiki/Licensing): Grbl is free software, released under the GPLv3 license.

* For more information and help, check out our **[Wiki pages!](https://github.com/gnea/grbl/wiki)**. If you find that the information is out-dated, please help us keep it updated by editing it or notifying our community! Thanks!

* Lead Developer Gnea: Sungeun "Sonny" Jeon, Ph.D. (USA) aka @chamnit

* Lead Developer Super Gerbil: Richard aka [@richard-luc](https://github.com/richard-luc)

* Built on the wonderful Grbl v0.6 (2011) AND v1.1f firmware written by Simen Svale Skogsrud (Norway).

***
