# Line-Following Car

A line-following car based on STM32F103C8T6, built in the RoboMaster electrical control group.

## Hardware
- STM32F103C8T6 minimum system board
- 5-way TCRT5000 line-tracking module
- MG310 DC geared motors with Hall encoders x2
- L298N motor driver
- 12V battery, 5V/3.3V power module
- ATK-MS53L2M ToF ranging module

## Current status
- Car assembled
- Code not started yet

## Next steps
1. Read the 5 line sensors and print values via serial
2. Control motors with L298N and PWM
3. Simple line following with if-else logic
4. PID as a later optimization
