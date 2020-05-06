Dies ist eine Abzweigung von JeeLabs fantastischer Echtzeituhrbibliothek für Arduino.

Einzelheiten zur Verwendung dieser Bibliothek mit einem RTC-Modul wie DS1307, PCF8523 oder DS3231 finden Sie im Handbuch unter: https://learn.adafruit.com/ds1307-real-time-clock-breakout-board-kit/overview

Herunterladen. Klicken Sie rechts auf die Schaltfläche DOWNLOADS und benennen Sie den unkomprimierten Ordner RTClib um.

Place the RTClib folder in your *arduinosketchfolder*/libraries/ folder. You may need to create the libraries subfolder if its your first library. Restart the IDE.

Bitte beachten Sie, dass dayOfTheWeek () von 0 bis einschließlich 6 reicht, wobei 0 'Sonntag' ist.

<!-- START COMPATIBILITY TABLE -->

## Kompatibilität

MCU | Getestete Werke | Funktioniert nicht | Nicht getestet | Anmerkungen
--- | :-: | :-: | :-: | ---
Atmega328 bei 16 MHz | X. |  |  |
Atmega328 bei 12 MHz | X. |  |  |
Atmega32u4 bei 16 MHz | X. |  |  | Verwenden Sie SDA / SCL für die Pins D3 und D2
Atmega32u4 bei 8 MHz | X. |  |  | Verwenden Sie SDA / SCL für die Pins D3 und D2
ESP8266 | X. |  |  | SDA / SCL ist standardmäßig auf die Pins 4 und 5 eingestellt, aber zwei beliebige Pins können mit Wire.begin (SDA, SCL) als SDA / SCL zugewiesen werden.
Atmega2560 bei 16 MHz | X. |  |  | Verwenden Sie SDA / SCL für die Pins 20 und 21
ATSAM3X8E | X. |  |  | Verwenden Sie SDA1 und SCL1
ATSAM21D | X. |  |  |
ATtiny85 @ 16MHz | X. |  |  |
ATtiny85 @ 8MHz | X. |  |  |
Intel Curie bei 32 MHz |  |  | X. |
STM32F2 |  |  | X. |

- ATmega328 bei 16 MHz: Arduino UNO, Adafruit Pro Trinket 5 V, Adafruit Metro 328, Adafruit Metro Mini
- ATmega328 @ 12MHz: Adafruit Pro Trinket 3V
- ATmega32u4 bei 16 MHz: Arduino Leonardo, Arduino Micro, Arduino Yun, Teensy 2.0
- ATmega32u4 bei 8 MHz: Adafruit Flora, Bluefruit Micro
- ESP8266: Adafruit Huzzah
- ATmega2560 bei 16 MHz: Arduino Mega
- ATSAM3X8E: Arduino fällig
- ATSAM21D: Arduino Zero, M0 Pro
- ATtiny85 @ 16MHz: Adafruit Trinket 5V
- ATtiny85 @ 8MHz: Adafruit Gemma, Arduino Gemma, Adafruit Trinket 3V

<!-- END COMPATIBILITY TABLE -->
