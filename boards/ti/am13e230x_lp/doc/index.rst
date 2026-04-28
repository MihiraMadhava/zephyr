.. zephyr:board:: am13e230x_lp

Overview
********

The AM13E230x LaunchPad is a development board based on the AM13E230x SoC, a 200MHz ARM Cortex M33 real-time motor control MCU with edge AI, TMU and 512KB on-chip flash.

See the `TI AM13E230x Product Page`_ for details.

|

Hardware
********

* Processor:

  + Arm Cortex M33 @ 200MHz

* Memory:

  + 128KB SRAM
  + 512KB on-chip flash

* Debug:

  + XDS110 based JTAG

Details present in `AM13E230x Microcontrollers datasheet`_

|

Supported Features
******************

.. zephyr:board-supported-hw::

|

Flashing and Debugging
**********************

Builds can be flashed and debugged using `TI Code Composer Studio`_.

|

References
**********

*   `TI AM13E230x Product Page`_ 

*   `AM13E230x Microcontrollers datasheet`_

*   `AM13E230x OpenOCD support patch`_

*   `TI Code Composer Studio`_

.. _TI AM13E230x Product Page:
    https://www.ti.com/product/AM13E23019

.. _AM13E230x Microcontrollers datasheet:
    https://www.ti.com/lit/gpn/am13e23019

.. _AM13E230x OpenOCD support patch:
   https://github.com/TexasInstruments/asm-hal_ti/blob/master/am13/openocd_am13e230x_support.patch

.. _TI Code Composer Studio:
   https://www.ti.com/tool/CCSTUDIO
|

License
*******

This document Copyright (c) 2026 Texas Instruments Incorporated

SPDX-License-Identifier: Apache-2.0