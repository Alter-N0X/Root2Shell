# Hardware Hacking Tooling — Recommended Kit

This document lists the core tools used for hardware hacking and firmware analysis, along with alternatives and purchasing references. Links are provided only for convenience — any equivalent tool with the same specifications is acceptable.

---

## 1. Phillips Screwdriver (PH1 / PH0 / PH00)

**Purpose**  
Used to remove the two retaining screws from the router enclosure.

**Alternatives**  
Any PH1, PH0, or PH00 precision Phillips screwdriver will work.

**Purchase Links**

- Precision Kit: https://www.amazon.com/Screwdriver-Eyeglass-Precision-Different-Screwdrivers/dp/B07YJG766F  
- PH1 Screwdriver: https://www.amazon.com/Wera-05118020001-Screwdriver-Electronic-Applications/dp/B0001P18LO  

---

## 2. UART to USB Adapter — CP2102 TTL

**Purpose**  
Interfaces with UART pins on the router PCB to obtain a serial console.

**Alternatives**  
No practical alternative. Without this, UART shell access is not possible.

**Notes**  
Any CP2102-based TTL adapter is sufficient regardless of branding.

**Purchase Links**

- https://www.amazon.com/IZOKEE-CP2102-Converter-Adapter-Downloader/dp/B07D6LLX19  
- https://www.amazon.com/HiLetgo-CP2102-Converter-Adapter-Downloader/dp/B00LODGRV8  
- https://www.amazon.com/CP2102-Serial-Adapter-Converter-Module/dp/B08ZS6H9VS  
- https://www.aliexpress.com/item/1005003536455256.html  

---

## 3. Male Through-Hole Header Pins

**Purpose**  
Used to connect UART signals to the PCB. The router exposes bare through-hole pads which require header pins for reliable connections.

**Alternatives**  
Some CH341A programmers include spare header pins that can be reused.

**Purchase Links**

- https://www.amazon.com/Proto-Advantage-HDR100IMP40M-G-V-TH-Vertical-Header-Through/dp/B098KLMT7T  
- https://www.digikey.com/en/products/detail/w%C3%BCrth-elektronik/61300311121/4846825  
- https://www.mouser.com/ProductDetail/Chip-Quik/HDR100IMP40M-G-V-TH  

---

## 4. Digital Multimeter — AstroAI AM33D

**Purpose**  
Used for voltage measurement, continuity testing, and general signal verification.

**Importance**  
This is the most critical safety tool in hardware hacking.

**Minimum Requirements**

- DC voltage measurement  
- Continuity tester  

**Purchase Links**

- https://www.amazon.com/AstroAI-Digital-Multimeter-Voltage-Tester/dp/B01ISAMUA6  
- https://www.astroai.com/digital-multimeter-2000-counts-am33d/ap/100071  

---

## 5. Logic Analyzer — USB 8-Channel

**Purpose**  
Captures UART and SPI traffic directly from PCB traces.

**Alternatives**  
You can analyze provided captures instead of recording your own.

**Purchase Links**

- https://www.amazon.com/Comidox-Analyzer-Device-Channel-Arduino/dp/B07KW445DJ  
- https://www.aliexpress.com/item/1005003375736481.html  
- https://www.amazon.com/HiLetgo-Analyzer-Ferrite-Channel-Arduino/dp/B077LSG5P2  

---

## 6. Flash ROM Programmer — CH341A

**Purpose**  
Extracts firmware directly from flash memory chips.

**Alternatives**  
Firmware can be downloaded from vendor support sites if available.

**Notes**  
Ensure the programmer uses the CH341A chipset.

**Purchase Links**

- https://www.amazon.com/KeeYees-SOIC8-EEPROM-CH341A-Programmer/dp/B07SHSL9X9  
- https://www.amazon.com/Geekstory-CH341A-EEPROM-Programmer-Module/dp/B098DYJ3LQ  
- https://www.aliexpress.com/item/32793476447.html  

---

# Optional Supporting Tools

### Spudger Set  
https://www.amazon.com/STREBITO-Spudger-Ultimate-Computer-Electronics/dp/B0BHPC2WB5  

### Soldering Station — Weller WLC100  
https://www.amazon.com/Weller-Digital-Soldering-Station-WLC100/dp/B000AS28UC  

### ESD Mat  
https://www.amazon.ca/Anti-Static-Electronic-Wristband-Grounding-HPFIX/dp/B07X7VL7VR  

### Third Hand Tool  
https://www.amazon.com/Helping-Soldering-Workshop-Non-slip-Weighted/dp/B07MDKXNPC  

### Test Clips  

- https://www.amazon.com/Tegg-Electrical-Testing-Multimeter-Grabber/dp/B07NY73PQF  
- https://www.amazon.com/Adapter-oscilloscope-multimeter-Generator-Programmer/dp/B07XNQ8CQW  

### Jumper Wires  
https://www.amazon.com/Elegoo-EL-CP-004-Multicolored-Breadboard-arduino/dp/B01EV70C78  
