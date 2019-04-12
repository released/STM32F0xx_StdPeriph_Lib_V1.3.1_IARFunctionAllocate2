# STM32F0xx_StdPeriph_Lib_V1.3.1_IARFunctionAllocate2

update @ 2019/04/12

Add function allocate example in IAR

function between below section and define section in ICF file , will allocate to specific address

#pragma default_function_attributes

1. check USART_DMA_ENABLE , USART_DMA_DISABLE in Hw_config.c for example

2. check SpecFunctionLocation in stm32f030_flash.icf for example
