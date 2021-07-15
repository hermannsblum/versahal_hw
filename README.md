VersaVIS Board package for arduino IDE

## Add board support
* To use, add https://github.com/ethz-asl/versavis_hw/raw/master/package_VersaVIS_index.json in Arduino IDE -> File -> Preferences -> Additional Boards Manager URLs.
* Add the VersaVIS board to the board manager (Tools -> Board -> Board Manager)

## Pinout for VersaHAL 0.1


| Port ||        Pin      ||||                                     | Periphery |
|------|--------|----------|------|-----------|---------|----------|-----------|
| Port | Number | Physical | Kind | Direction | SERCOM  | Function |           |
|      |        |          |      |           |         | DAUX1    | AUX       |
|      |        |          |      |           |         | AAUX1    | AUX       |
|      |        |          |      |           |         | AAUX2    | AUX       |
|      |        |          |      |           |         | DAUX2    | AUX       |
| A    | 05     | 10       | D    | I         |         | ExpC1    | CAM1      |
| A    | 04     | 9        | D    | O         |         | TrigC1   | CAM1      |
| A    | 07     | 12       | D    | I         |         | ExpC2    | CAM2      |
| A    | 06     | 11       | D    | O         |         | TrigC2   | CAM2      |
| A    | 27     | 39       | D    | I         |         | PPS      | GPS       |
|      |        |          |      |           |         | ExtClk   | GPS       |
| A    | 22     | 31       | D    | IO        | 5       | SDA      | I2C       |
| A    | 23     | 32       | D    | O         | 5       | SCL      | I2C       |
| A    | 30     | 45       | D    | I         |         | SWCLK    | PROG      |
| A    | 31     | 46       | D    | IO        |         | SWDIO    | PROG      |
| A    | 15     | 24       | D    | O         | 1       | SS1      | SPI1      |
| A    | 13     | 22       | D    | I         | 1       | MISO1    | SPI1      |
| A    | 14     | 23       | D    | O         | 1       | MOSI1    | SPI1      |
| A    | 12     | 21       | D    | O         | 1       | SCK1     | SPI1      |
| A    | 19     | 28       | D    | I         | 1       | DR1      | SPI1      |
| A    | 00     | 1        | S    |           |         | XTAL     | System    |
| A    | 01     | 2        | S    |           |         | XTAL     | System    |
| B    | 03     | 48       | D    | I         | 5       | RX2      | UART      |
| B    | 02     | 47       | D    | O         | 5       | TX2      | UART      |
| B    | 08     | 7        | D    | O         | 4       | TX1      | DIST1     |
| B    | 09     | 8        | D    | I         | 4       | RX1      | DIST1     |
| A    | 08     | 13       | D    | O         | 2       | TX3      | DIST2     |
| A    | 09     | 14       | D    | I         | 2       | RX3      | DIST2     |
| A    | 16     | 25       | D    | O         | 3       | TX4      | DIST3     |
| A    | 17     | 26       | D    | I         | 3       | RX4      | DIST3     |
| A    | 21     | 30       | D    | O         |         | USB_HE   | USB       |
| A    | 24     | 33       | D    | IO        |         | USB-     | USB       |
| A    | 25     | 34       | D    | IO        |         | USB+     | USB       
