# Arduino-BlackBox
Arduino based CAN-Bus Diagnostic Tool

**ID-Config for SMART CDI 2003**

## Introduction

### I2C Display Connection

| Display | Arduino |
| ------- | ------- |
| SDA     | ANALOG4 |
| SCL     | ANALOG5 |
| GND     | GND     |
| VCC     | 5V      |

### MCP2515 Connection

| MCP2515 | Arduino |
| ------- | ------- |
| INT     | PIN2    |
| SCK     | PIN13   |
| MOSI    | PIN11   |
| MISO    | PIN12   |
| CS      | PIN10   |
| GND     | GND     |
| VCC     | 5V      |

### Libraries

* https://github.com/coryjfowler/MCP_CAN_lib

* https://bitbucket.org/fmalpartida/new-liquidcrystal/wiki/Home

### Parts

* MCP2515
* Arduino Uno
* I2C Display 4x20

## License

This project is licensed under the MIT License - see the [license file](LICENSE) for details.