
# WCH example code

## SRC

[SRC/Core/](SRC/Core/) - kernal system header file

[SRC/Debug/](SRC/Debug/) - delay fuction, UART debugging source file and header file

[SRC/Ld/](SRC/Ld/) - Linker Description file

[SRC/Peripheral/](SRC/Peripheral/) - basic peripheral driver source file and header file

[SRC/Startup/](SRC/Startup/) - startup file

## ADC - Analog-to-Digital Converter

Direct Memory Access (DMA) with an Analog-to-Digital Converter (ADC)

[ADC/ADC_DMA/](ADC/ADC_DMA/) - ADC DMA sampling routines

[ADC/AnalogWatchdog/](ADC/AnalogWatchdog/) - analog watchdog routine

[ADC/Auto_Injection/](ADC/Auto_Injection/) - automatic injection mode routine

[ADC/Discontinuous_mode/](ADC/Discontinuous_mode/) - discontinuous mode routine

[ADC/ExtLines_Trigger/](ADC/ExtLines_Trigger/) - external lines trigger ADC conversion routine

[ADC/TIM_Trigger/](ADC/TIM_Trigger/) - TIM trigger ADC conversion routine

## APPLICATION

[APPLICATION/SoftUART/](APPLICATION/SoftUART/) - I/O port simulation serial port routine

## DMA - Direct Memory Access

[DMA/DMA_MEM2MEM/](DMA/DMA_MEM2MEM/) - Memory to memory mode routine

[DMA/DMA_MEM2PERIP/](DMA/DMA_MEM2PERIP/) - Memory to peripheral mode, and peripheral to memory mode routine, see peripheral sub-routines

## EXTI

[EXTI/EXTI0/](EXTI/EXTI0/) - external interrupt line routine

## FLASH

[FLASH/FLASH_Program/](FLASH/FLASH_Program/) - FLASH erase/read/write, and fast programming

[FLASH/BootAsUser/](FLASH/BootAsUser/) - Boot Flash used for user flash

## GPIO

[GPIO/GPIO_Toggle/](GPIO/GPIO_Toggle/) - GPIO routine

## I2C

[I2C/I2C_7bit_Mode/](I2C/I2C_7bit_Mode/) - 7-bit addressing mode, master/slave mode, transceiver routine

[I2C/I2C_10bit_Mode/](I2C/I2C_10bit_Mode/) - 10-bit addressing mode, master/slave mode transceiver routine

[I2C/I2C_DMA/](I2C/I2C_DMA/) - I2C DMA, master/slave mode transceiver routine

[I2C/I2C_EEPROM/](I2C/I2C_EEPROM/) - I2C interface routine to operate EEPROM peripheral

[I2C/I2C_PEC/](I2C/I2C_PEC/) - PEC error check, master/slave mode transceiver routine

[I2C/I2C_7bit_Interrupt_Mode/](I2C/I2C_7bit_Interrupt_Mode/) - Use interrupt to receive and send routine

## IAP

[IAP/V00x_APP/](IAP/V00x_APP/) - APP go to IAP routine

## IWDG

[IWDG/IWDG/](IWDG/IWDG/) - independent watchdog routine

## INT

[INT/Interrupt_VTF/](INT/Interrupt_VTF/) - VTF IRQ interrupt routine

[INT/VectorInRAM/](INT/VectorInRAM/) - Vector in RAM routine

## OPA

[OPA/OPA/](OPA/OPA/) - OPA as voltage follower output routine

## PWR

[PWR/Sleep_Mode/](PWR/Sleep_Mode/) - low power, sleep mode routine

[PWR/Standby_Mode/](PWR/Standby_Mode/) - low power, standby mode routine

[PWR/PVD_Wakeup/](PWR/PVD_Wakeup/) - STOP mode PVD wakeup MCU Routine

[PWR/PVD_VoltageJudger/](PWR/PVD_VoltageJudger/) - PVD voltage Judger Routine

## RCC

[RCC/Get_CLK/](RCC/Get_CLK/) - Get system-HCLK-AHB1-AHB2 clock routine

[RCC/MCO/](RCC/MCO/) - MCO pin clock output routine

## SPI

[SPI/1Lines_half-duplex/](SPI/1Lines_half-duplex/) - single wire half duplex mode, master/slave mode, data transceiver

[SPI/2Lines_FullDuplex/](SPI/2Lines_FullDuplex/) - two-wire full duplex mode, master/slave mode, data transceiver

[SPI/FullDuplex_HardNSS/](SPI/FullDuplex_HardNSS/) - Hardware NSS mode, master/slave mode, data transceiver

[SPI/SPI_CRC/](SPI/SPI_CRC/) - CRC error check and master/slave mode transceiver routine

[SPI/SPI_DMA/](SPI/SPI_DMA/) - SPI DMA, master/slave mode transceiver routine

## SDI_Printf

[SDI_Printf/SDI_Printf/](SDI_Printf/SDI_Printf/) - debug interface SDI, virtual serial port.   

## SYSTICK

[SYSTICK/SYSTICK_Interrupt/](SYSTICK/SYSTICK_Interrupt/) - systick interrupt routine  

## TIM

[TIM/Clock_Select/](TIM/Clock_Select/) - clock source selection routine

[TIM/ComplementaryOutput_DeadTime/](TIM/ComplementaryOutput_DeadTime/) - complementary output and deadband insertion mode routines

[TIM/ExtTrigger_Start_Two_Timer/](TIM/ExtTrigger_Start_Two_Timer/) - external trigger routines to start two timers synchronously

[TIM/Input_Capture/](TIM/Input_Capture/) - input capture routine

[TIM/One_Pulse/](TIM/One_Pulse/) - single pulse output routine

[TIM/Output_Compare_Mode/](TIM/Output_Compare_Mode/) - output comparison mode routine

[TIM/PWM_Output/](TIM/PWM_Output/) - PWM output routine

[TIM/Synchro_ExtTrigger/](TIM/Synchro_ExtTrigger/) - slave mode routine, including reset mode, gating mode and trigger mode

[TIM/Synchro_Timer/](TIM/Synchro_Timer/) - timer synchronization mode

[TIM/TIM_DMA/](TIM/TIM_DMA/) - timer DMA routines

[TIM/Encode/](TIM/Encode/) - Timer encoder mode routines

[TIM/TIM_INT/](TIM/TIM_INT/) - Timer interput routines

[TIM/TIM_Continuous/](TIM/TIM_Continuous/) - Timer Continuous mode routines

[TIM/PWM_Phase-shifted/](TIM/PWM_Phase-shifted/) - Timer PWM Phase shifted routines

[TIM/PWM_6_Step/](TIM/PWM_6_Step/) - Timer 6_Step PWM routines

## USART

[USART/USART_DMA/](USART/USART_DMA/) - USART DMA, master/slave mode transceiver routine

[USART/USART_HalfDuplex/](USART/USART_HalfDuplex/) - single wire half duplex mode, master/slave mode transceiver routine

[USART/USART_HardwareFlowControl/](USART/USART_HardwareFlowControl/) - hardware flow control mode, master/slave mode, transceiver routine

[USART/USART_Interrupt/](USART/USART_Interrupt/) - USART interrupt routine, master/slave mode transceiver routine

[USART/USART_MultiProcessorCommunication/](USART/USART_MultiProcessorCommunication/) - multiprocessor communication mode routine

[USART/USART_Polling/](USART/USART_Polling/) - polling transceiver mode, master/slave transceiver routine

[USART/USART_Printf/](USART/USART_Printf/) - USART Print debugging routine

[USART/USART_SynchronousMode/](USART/USART_SynchronousMode/) - synchronous mode, master/slave mode, transceiver routine

## USART-IAP 

[USART-IAP/](USART-IAP/) - IAP Upgrade Routine - Built-in Hex to Bin Tool and IAP Upgrade Tool

## WWDG - Window Watchdog Timer

[WWDG/WWDG/](WWDG/WWDG/) - window watchdog routine

_______________
Tauno Erik ♥ Väimela ♥ 2025
