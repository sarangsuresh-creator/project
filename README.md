# STM32 mini data logger
## overview
I have developed a stm32f429zit6 based data logger system that uses ADC,DMA,Timer for setting sampling time,PWM for led brightness control,UART for realtime data logging and External interrupt for resume and pause of both data and pwm
## overall working
At 1st i have configured the timer for generating 1 KHz frequency to generate a timer of 1 ms.
