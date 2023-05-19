Instruction on the process of setting up the Blinky app 

Open STM32CubeIDE. Click “Start new STM32 project” and choose STM32f446 in the “Part Number Search” as the microcontroller.
Give the project name as intended (Blink).
Let the “Pinout & Configuration” and “Clock Configuration” as default settings
Click on file>save. 
Click “Yes” when being prompt to generate Code. The IDE will then automatically generate files.
In the “while (1)” which is the forever loop, write the codes “HAL_GPIOA_TogglePin(GPIOA, GPIO_PIN_5); HAL_Delay(1000);”
Click project>build project.
When that completes, click run>Debug As>STM32 Application.
When the Debug Configuration tab appears, leave all the settings as default.
Then, click the “Play” button to run the program on the Nucleo board.

