# Arduino-For-Keil AT32F43x
> https://github.com/FASTSHIFT/Arduino-For-Keil

# 更新日志
## [v1.0] - 2021.12.2
* 1.基于AT32F43x标准外设库(ArteryTek.AT32F435_437_DFP.2.0.1)，移植了gpio和delay

## [v1.1] - 2021.12.17
* 1.完成所有API，还剩ADC_DMA无法工作
* 2.添加内部的时钟初始化，默认主频288MHz
* 3.HardSerial新的SERIAL_Config_t
* 4.SPI库导出寄存器快速操作接口

## [v1.2] - 2022.1.2
* 1.GPIO_DRIVE_STRENGTH_DEFAULT -> GPIO_DRIVE_DEFAULT
* 2.去除extern_SRAM
* 3.去除i2c
* 4.添加wdg看门狗支持
* 5.优化TIMER_GPIO_MUX匹配

