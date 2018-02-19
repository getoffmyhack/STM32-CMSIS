# STM32 CMSIS Build Environment

This is a repackaging of the STM32 CMSIS build files included with [STMCube](http://www.st.com/en/embedded-software/stm32cube-mcu-packages.html) package.  I am creating this repository as a bare minimum build environment for the STM32 line of ARM Cortex-M micro controllers.  Currently, this repository only includes the STM32F1xx Cube package.

The following list of modifications have been made in order to properly build STM32 projects:

File: Device/STM32F1xx/linker/STM32F103XB_FLASH.ld
	- Each blank line contained the '0' character.  Removed '0' from blank lines.

