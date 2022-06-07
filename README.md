# CYBT-353027-EVAL

### Overview

The Infineon CYBT-353027-EVAL Evaluation Kit enables you to evaluate and develop single-chip Bluetooth&#174; applications using the EZ-BT AIROC&#8482; Module CYBT-353027-02. The CYBT-353027-02 EZ-BT AIROC&#8482; Module is an integrated, fully certified, 9.0 mm x 9.0 mm x 1.75 mm, programmable dual-mode Bluetooth&#174; module designed to reduce your time-to-market. CYBT-353027-EVAL can be used as a standalone evaluation kit or can be combined with Arduino-compatible shields.

* CYW20706-based dual-mode (LE/BR/EDR) Bluetooth&#174; 5.0-compliant fully certified module (CYBT-353027-02)
* Arduino compatible headers for hardware expansion
* User switches and LEDs
* FCC, ISED, MIC, and CE Certified Module on board (CYBT-353027-02)
* USB connector for power, programming, and USB-UART bridge

### Standalone Usage

To use the CYBT-353027-EVAL:

1) Configure the evaluation board headers/switches to the desired settings

2) Connect the evaluation board to a PC via a USB cable

3) Refer to KBA226703 for platform files, Makefile target generation, and HCI UART switch position setting for programming

4) Use ModusToolbox&#8482; 2.0 and BTSDK 2.0 (or higher) to develop your application, program, and test

Note: Recover the CYBT-353027-EVAL before programming. The Arduino-compatible headers(J3/J4/J6/J7) are optional connections, which provide additional I/O connections to the module and allow for other Arduino shields to be used during development.

Optional Usage with Arduino Shield:

Arduino compatible shields can be connected through the Arduino compatible headers (J3/J4/J6/J7) to provide additional I/O connections and functionality.

### Kit Contents

* 1 X EZ-BT Module Arduino Evaluation Board (CYBT-353027-EVAL) with on-board EZ-BT AIROC&#8482; Module (CYBT-353027-02)
* 1 X USB Cable

### Additional Information

Max UART baud rate is 1M. Use baud rate of 115200 for Client Control.

For more information, see [CYBT-353027-EVAL](https://www.infineon.com/cms/en/product/evaluation-boards/cybt-353027-eval/)
