# CAN-Shield for NUCLEO-G474RE

NUCLEO-G474RE compatible CAN shield, which is our main microcontroller for the battery management system (BMS/AMS).

### Overview

Acts as can transciever for the BMS. Also has an output pin in case of a BMS fault.

CAN 1 is designated for the communication with FSGs datalogger, because of the high 1Mbit CAN baudrate.

CAN 2 is designated to communicate with the rest of the car, at a lower baudrate.

Compatible to the Analog Devices EVAL-ADBMS6822 board, can be slotted onto the board at the same time.

Accessible screw terminals for signals to the board.

Can be directly slotted on to the board.

### Used parts

> [!WARNING]  
> Part list is not complete.

| Article                          | Description                 | Link                                                                                                          | Quantity |
| -------------------------------- | --------------------------- | ------------------------------------------------------------------------------------------------------------- | -------- |
| STMircoelectronics L9615D013TR   | 12V can transiever          | https://www.mouser.de/ProductDetail/STMicroelectronics/L9615D013TR?qs=RNlBCa%2FBPH2bRRygw50SdQ%3D%3D          | 1        |
| STMicroelectronics ESDCAN01-2BLY | dual-line TVS diode         | https://www.mouser.de/ProductDetail/STMicroelectronics/ESDCAN01-2BLY?qs=Ok1pvOkw6%2FpNzC2RQnWwPA%3D%3D        | 2        |
| Samsung CL10B104KB8NNNC          | capacitor 100nF             | https://www.mouser.de/ProductDetail/Samsung-Electro-Mechanics/CL10B104KB8NNNC?qs=349EhDEZ59rvGc2rLwVOdA%3D%3D | 2        |
| Vishay CRCW060368R1FKEA          | resistor 68ohm              | https://www.mouser.de/ProductDetail/Vishay-Dale/CRCW060368R1FKEA?qs=6z8JnUK2jyMngsBXu5il1A%3D%3D              | 4        |
| WECO 950-08                      | 8-pin screw terminal        |                                                                                                               | 1        |
