# EasyTFT_Screen_Driver

This is a driver for EasyTFT screen (both for touch screen and visualization purposes).

The board used in this project is STM32 EasyMx-Pro-V7.

## Example usage

Using the driver to draw images and type texts are shown in the src/main.c


## Including the library

Library is stored in Drivers/ILI9341. The following headers are required to be included to use the library.

```
#include "ILI9341_STM32_Driver.h"
#include "ILI9341_GFX.h"
```

The driver requires the HAL library. 
