# CAN-Shield for NUCLEO-G474RE

NUCLEO-G474RE compatible CAN shield, which is our main microcontroller for the battery management system (BMS/AMS).

### Overview

Acts as can transciever for the BMS. 
Has two 12V output pins, one in case of a BMS fault. The other to set the state (on/off) of the HV charger.

CAN 1 is designated for the communication with FSGs datalogger, because of the high 1Mbit CAN baudrate.

CAN 2 is designated to communicate with the rest of the car, at a lower baudrate.

Compatible to the Analog Devices EVAL-ADBMS6822 board, can be directly slotted onto the nucleo board at the same time.

WR-TBL 3.5mm Connectors for signals to and from the board.

### Used parts

> [!WARNING]  
> Part list is not complete.

| Article                          | Description                  | Link                                                                                                                                        | Quantity |
| -------------------------------- | ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- | -------- |
| Infineon TLE6250GV33XUMA1        | can transiever               | https://www.mouser.de/ProductDetail/Infineon-Technologies/TLE6250GV33XUMA1?qs=OwbwYO03UsJ9UcCPEQ3lNA%3D%3D                                  | 2        |
| Omron G5V-2-DC12                 | relais                       | https://www.mouser.de/ProductDetail/Omron-Electronics/G5V-2-DC12?qs=lK7M36XCk6JxdWY%2FV6sVqw%3D%3D                                          | 1        |
| STMicroelectronics ESDCAN01-2BLY | dual-line TVS diode          | https://www.mouser.de/ProductDetail/STMicroelectronics/ESDCAN01-2BLY?qs=Ok1pvOkw6%2FpNzC2RQnWwPA%3D%3D                                      | 2        |
|                                  | transistor                   |                                                                                                                                             |          |
| Samsung CL10B104KB8NNNC          | capacitor 100nF              | https://www.mouser.de/ProductDetail/Samsung-Electro-Mechanics/CL10B104KB8NNNC?qs=349EhDEZ59rvGc2rLwVOdA%3D%3D                               | 2        |
| Vishay CRCW060368R1FKEA          | resistor 68ohm               | https://www.mouser.de/ProductDetail/Vishay-Dale/CRCW060368R1FKEA?qs=6z8JnUK2jyMngsBXu5il1A%3D%3D                                            | 4        |
| Samtec SSW-119-01-T-D-LL         | 02x19  Mounting Pin, 2.54 mm | https://www.mouser.de/ProductDetail/Samtec/SSW-119-01-T-D-LL?qs=F1JzWfReSMQC5N%252BZEM9ULw%3D%3D                                            | 2        |
| Würth Elektronik 691321100002    | 2-pin header                 | https://www.mouser.de/ProductDetail/Wurth-Elektronik/691321100002?qs=sGAEpiMZZMvPvGwLNS6715pX%252BQgp6lhzMFLUiDaj9KJjOeguQ8XvHQ%3D%3D       | 1        |
| Würth Elektronik 691361100002    | 2-pin plug                   | https://www.mouser.de/ProductDetail/Wurth-Elektronik/691361100002?qs=sGAEpiMZZMvPvGwLNS6715pX%252BQgp6lhzc8iD6dL%252BnREnLxTu%2F6qxUQ%3D%3D | 1        |
| Würth Elektronik 691321100004    | 4-pin header                 | https://www.mouser.de/ProductDetail/Wurth-Elektronik/691321100004?qs=sGAEpiMZZMvPvGwLNS6716dt6ZVWwiEWhH92dgOeUJ3PgxyzktJ1Fw%3D%3D           | 2        |
| Würth Elektronik 691361100004    | 4-pin plug                   | https://www.mouser.de/ProductDetail/Wurth-Elektronik/691361100004?qs=2kOmHSv6VfRmrzXJBP%2F4Sg%3D%3D                                         | 2        |
