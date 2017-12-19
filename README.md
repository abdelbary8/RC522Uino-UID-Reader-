# RC522Uino-UID-Reader
Very Cheap Arduino Nano & RC522 RFID module based UID reader for authentication/identification


## Parts list

- Arduino Nano v3.0
- Wires
- RC522 RFID Module

## Download and install library

In order to use RC522 module you will need SPI library and MFRC522 library
you can download it from the following links
https://github.com/miguelbalboa/rfid

In the Arduino IDE go to “Sketch → Include Library →” and select “Add .ZIP Library…” then chose the downloaded files to add them into your Arduino IDE.


## Wires Connection

Arduino Nano v3.0

| Signal | Pin |
| ---------- | ---- |
| RST/Reset | D9 |
| SPI SS | D10 |
| SPI MOSI | D11 |
| SPI MISO | D12 |
| SPI SCK | D13 |

You can now start soldering your own RFID reader

## Finally
Open the rc522uidreader.ino and upload it

Congratulations, you made it :+1:
