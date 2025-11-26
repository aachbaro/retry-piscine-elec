## (BOM)

| Réf    | Composant                         | Valeur / Type              | Boîtier      |
| ------ | --------------------------------- | -------------------------- | ------------ |
| U1     | ATmega328P-AU                     | Microcontrôleur AVR 20 MHz | TQFP-32      |
| Y1     | Quartz 16 MHz                     | 9 pF                       | SMD 3225     |
| C1, C2 | Condensateurs charge quartz       | 12 pF C0G                  | 0603         |
| C3–C8  | Condensateurs découplage          | 100 nF X7R                 | 0603         |
| C9     | Condensateur découplage principal | 1 µF X5R                   | 0603         |
| R1     | Résistance LED                    | 330 Ω                      | 0603         |
| R2     | Résistance pull-up / pull-down    | 10 kΩ                      | 0603         |
| D1     | LED                               |                            | 0603         |
| SW1    | Bouton poussoir SMD               | 3×2.5 mm                   | SMD          |
| J1     | Header programmation ISP          | 2.54 mm                    | Through-hole |
| J2     | Header alimentation               | 2.54 mm                    | Through-hole |

## 🧷 Pinout

| Pin | Nom  | Fonction      |
| --- | ---- | ------------- |
| 1   | PD3  | D3 / INT1     |
| 2   | PD4  | D4            |
| 3   | GND  | Masse         |
| 4   | VCC  | Alim 5V       |
| 5   | GND  | Masse         |
| 6   | VCC  | Alim 5V       |
| 7   | PB6  | XTAL1         |
| 8   | PB7  | XTAL2         |
| 9   | PD5  | D5 / PWM      |
| 10  | PD6  | D6 / PWM      |
| 11  | PD7  | D7            |
| 12  | PB0  | D8            |
| 13  | PB1  | D9 / PWM      |
| 14  | PB2  | D10 / SS      |
| 15  | PB3  | D11 / MOSI    |
| 16  | PB4  | D12 / MISO    |
| 17  | PB5  | D13 / SCK     |
| 18  | AVCC | Alim ADC      |
| 19  | ADC6 | A6            |
| 20  | AREF | Référence ADC |
| 21  | GND  | Masse         |
| 22  | ADC7 | A7            |
| 23  | PC0  | A0            |
| 24  | PC1  | A1            |
| 25  | PC2  | A2            |
| 26  | PC3  | A3            |
| 27  | PC4  | A4 / SDA      |
| 28  | PC5  | A5 / SCL      |
| 29  | PD0  | RX            |
| 30  | PD1  | TX            |
| 31  | PD2  | D2 / INT0     |
| 32  | PD3  | D3            |
