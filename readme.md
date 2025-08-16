# FC-ABSS (Feedback-Controlled Algae-Bacteria Symbiotic System)

## Description
FC-ABSS is a compact tank-based system that purifies tilapia aquaculture wastewater by using a synergistic mix of microalgae and bacteria. It leverages feedback control systems to maintain optimal growth conditions.

## Why I Built It
Aquaculture systems often produce nutrient-rich wastewater that, if untreated, leads to environmental degradation. I wanted to build a sustainable, automated solution to biologically treat this wastewater while learning real-world applications of embedded systems, feedback loops, and ecological engineering.

## System Overview
- Microalgae-bacteria consortia remove nitrogen and phosphorus from the wastewater.
- Light feedback loop: An LDR monitors intensity; ESP32 adjusts a high-CRI LED strip accordingly.
- Temperature feedback loop: A DS18B20 sensor monitors water temperature; the microcontroller switches a heater via a relay module.
- An oxygen pump ensures aerobic conditions for both bacteria and algae.

## Images
- ![alt text](images/Picture51.png) 
- ![alt text](images/por.jpg) 
- ![alt text](images/porr.jpg) 
- ![alt text](images/porrr.jpg)
## Bill of Materials (BOM)

| Component                         | Quantity | Estimated Cost | Link                                                                                  |
|----------------------------------|----------|----------------|---------------------------------------------------------------------------------------|
| Arduino Mega             | 1        | $75.00        | [RAM-E-Shop](https://www.amazon.eg/-/en/DIY-Kit-Arduino-Mega-Microcontroller-Rev3/dp/B0D7WG8BZF) |
| Custom I/O Expansion Shield for Arduino Mega	            | 1        | $21         | [RAM-E-Shop](https://www.ram-e-shop.com/ar/shop/rpi-phat-io-exp-io-expansion-hat-for-raspberry-pi-5-4b-3b-8267) |
| Channel 5V Relay Module          | 1        | $10.00         | [link](https://www.amazon.eg/Relay-Module-16-Channel-5V/dp/B0B6RP69BT/)                                                                 |
| 12V LED Strip (High-CRI)         | 1        | $6.00         |   [Link](https://www.amazon.eg/-/en/dobestyou-Decorative-Purposes-SMD2835-Waterproof/dp/B0B1DP8685/)                                    |
| DS18B20 Temp Sensor (Premium)    | 1        | ~$50.00        | [Link](https://ar.aliexpress.com/item/1005008477970186.html?)                                                                       |
| LDR Light Sensor Module          | 1        | ~$8.50         | [Link](https://www.amazon.eg/-/en/10Pcs-Photosensitive-Resistor-Sensor-Module/dp/B0CGNJ5CRT/)                                                                      |
| Aquarium Heater                  | 1        | $13.00         | [Link](https://ar.aliexpress.com/item/1005001803652936.html?)                                                                                       |
| Oxygen Pump | 1        | $26.20         | [Link](https://ar.aliexpress.com/item/1005009196812461.html?)                                                                                       |
| Light Shielding Frame	 | 1        | $4.30          | [Link](https://ar.aliexpress.com/item/1005005534687013.html?)                                                                                       |
| 12V, 5A Power Adapter            | 3        | $36.00         | [Link](https://ar.aliexpress.com/item/1005004623323483.html?)                                                                                       |
| Jumper Wires  | 1        | $6.00          | [Link](https://ar.aliexpress.com/item/1005008637857128.html?)                                                                                       |
| Plastic IP-rated Control Box    | 2        | $13.40         | [Link](https://ar.aliexpress.com/item/1005004340658589.html?)                                                                                       |

**Total: $269.4**

---



