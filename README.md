# Proiect-TSC

  OpenBook E-Reader
OpenBook este un e-book reader open source si accesibil, proiectat pentru a oferi o experiență bună de citire la un preț competitiv.

![image](https://github.com/user-attachments/assets/ffdae3f3-8aec-4c6b-8c47-b3d643de8a12)

## Bill of Materials (BOM)

| Nr. | Componenta | Descriere | Cantitate | Link achizitie | Datasheet |
|-----|------------|-----------|-----------|----------------|-----------|
| 1 | ESP32-C6-WROOM-1-N8 | Modul WiFi/Bluetooth/Zigbee | 1 | [Model](https://www.snapeda.com/parts/ESP32-C6-WROOM-1-N8/Espressif+Systems/view-part/?ref=eda) | [Datasheet](https://www.espressif.com/sites/default/files/documentation/esp32-c6_datasheet_en.pdf) |
| 2 | W25Q512JVEIQ | Memorie Flash NOR 64MB | 1 | [Model](https://www.snapeda.com/parts/W25Q512JVEIQ/Winbond+Electronics/view-part/?ref=eda) | [Datasheet](https://www.winbond.com/resource-files/W25Q512JV%20RevI%2005132020%20Plus.pdf) |
| 3 | DS3231SN# | Modul RTC de inalta precizie | 1 | [Model](https://www.snapeda.com/parts/DS3231SN%23/Analog+Devices/view-part/?ref=eda) | [Datasheet](https://datasheets.maximintegrated.com/en/ds/DS3231.pdf) |
| 4 | MAX17048G+T10 | Controlor pentru monitorizarea bateriei | 1 | [Model](https://www.snapeda.com/parts/MAX17048G+T10/Analog+Devices/view-part/?ref=eda) | [Datasheet](https://datasheets.maximintegrated.com/en/ds/MAX17048-MAX17049.pdf) |
| 5 | BME688 | Senzor integrat de mediu | 1 | [Model](https://www.snapeda.com/parts/BME680/Bosch/view-part/?welcome=home) | [Datasheet](https://www.bosch-sensortec.com/media/boschsensortec/downloads/datasheets/bst-bme688-ds000.pdf) |
| 6 | MCP73831 | Controler de incarcare baterie Li-Po | 1 | [Model](https://www.mouser.co.uk/ProductDetail/Microchip-Technology/MCP73831T-5ACI-OT?qs=hH%252BOa0VZEiAcgAcEkuamXg%3D%3D) | [Datasheet](https://ww1.microchip.com/downloads/en/DeviceDoc/20001984g.pdf) |
| 7 | BD5229G-TR | Detector de tensiune cu timp de intarziere | 1 | [Model](https://componentsearchengine.com/part-view/BD5229G-TR/ROHM%20Semiconductor) | [Datasheet](https://fscdn.rohm.com/en/products/databook/datasheet/ic/power/voltage_detector/bd52xxg-e.pdf) |
| 8 | PFMF.050.1 | Conector USB Type-C | 1 | [Model](https://www.mouser.com/ProductDetail/Amphenol-FCI/PFMF0501?qs=sGAEpiMZZMulM8LYMF8bxyg6IYwX%252B5CgQVcIoLYkYiM%3D) | [Datasheet](https://cdn.amphenol-cs.com/media/wysiwyg/files/drawing/pfmf.pdf) |
| 9 | USBLC6-2SC6Y | Protectie ESD pentru linii USB | 1 | [Model](https://www.snapeda.com/parts/USBLC6-2SC6Y/STMicroelectronics/view-part/?ref=eda) | [Datasheet](https://www.st.com/resource/en/datasheet/usblc6-2.pdf) |
| 10 | 112A-TAAR-R03 | Slot pentru card microSD | 1 | [Model](https://www.mouser.com/ProductDetail/Attend/112A-TAAR-R03?qs=sGAEpiMZZMsg%2By7HCF96QHhTCuZhYGBTHJ9NEpPMzZc%3D) | [Datasheet](https://www.attend.com.tw/sites/default/files/2022-05/112A-TAAR-R03.pdf) |
| 11 | FH34SRJ-24S-0.5SH | Conector pentru ecran e-paper | 1 | [Model](https://www.hirose.com/product/p/CL0684-0832-7-99) | [Datasheet](https://www.hirose.com/product/document?clcode=CL0684-0832-7-99&productname=FH34SRJ-24S-0.5SH(99)&series=FH34&documenttype=Catalog&lang=en&documentid=D49681_en) |
| 12 | DMG2305UX-7 | Tranzistor MOSFET-P 20V/4.2A | 1 | [Model](https://www.diodes.com/part/view/DMG2305UX) | [Datasheet](https://www.diodes.com/assets/Datasheets/DMG2305UX.pdf) |
| 13 | SI1308EDL-T1-GE3 | Tranzistor MOSFET-N 30V/1.5A | 1 | [Model](https://www.snapeda.com/parts/SI1308EDL-T1-GE3/Vishay+Siliconix/view-part/?ref=snap) | [Datasheet](https://www.vishay.com/docs/68732/si1308edl.pdf) |
| 14 | SD0805S020S1R0 | Inductor 1.0µH | 1 | [Model](https://eu.mouser.com/ProductDetail/KYOCERA-AVX/SD0805S020S1R0?qs=jCA%252BPfw4LHbpkAoSnwrdjw%3D%3D) | [Datasheet](http://datasheets.avx.com/schottky.pdf) |
| 15 | MBR0530 | Dioda Schottky 30V/500mA | 3 | [Model](https://www.snapeda.com/parts/MBR0530/Onsemi/view-part/?ref=eda) | [Datasheet](https://www.onsemi.com/pdf/datasheet/mbr0520lt1-d.pdf) |
| 16 | PGB1010603MR | Dioda TVS pentru protectie ESD | 5 | [Model](https://www.snapeda.com/parts/PGB1010603MR/Littelfuse/view-part/?ref=eda) | [Datasheet](https://www.littelfuse.com/media?resourcetype=datasheets&itemid=3d1e98b7-4d37-463c-9380-c56c83b11c3c&filename=littelfuse-pulseguard-pgb1) |
| 17 | CPH3225A | Cristal RTC 32.768kHz | 1 | [Model](https://www.snapeda.com/parts/CPH3225A/Seiko+Instruments/view-part/?ref=eda) | [Datasheet](https://www.sii.co.jp/en/quartz/files/2021/03/CPH3225A_E.pdf) |
| 18 | XC6220A331MR-G | Regulator LDO de tensiune 3.3V | 1 | [Model](https://www.torexsemi.com/products/voltage-regulators/ldo-regulators/xc6220/) | [Datasheet](https://www.torexsemi.com/file/xc6220/XC6220.pdf) |
| 19 | Buton tactil | Butoane pentru Reset, Boot, Change | 3 | [Model](https://industry.panasonic.com/ww/products/industrial-devices/mechanical-components/switches/light-touch-switches/light-touch-switches/evqpuj02k) | [Datasheet](https://industry.panasonic.com/ww/components/devices/mechanical-components/switches/light-touch-switches/products/evqpuj02k) |
| 20 | LEDs SMD 0603 | LED indicator | 1 | [Model](https://www.snapeda.com/parts/KP-1608SURCK/Kingbright/view-part/?ref=search&t=LED%200603) | [Datasheet](https://www.kingbrightusa.com/images/catalog/SPEC/APHHS1608LSURKCGKC.pdf) |
| 21 | QWIIC_RIGHT_ANGLE | Conector I²C Qwiic | 1 | [Model](https://www.sparkfun.com/products/14417) | [Datasheet](https://cdn.sparkfun.com/assets/1/4/d/8/3/Qwiic_Connector_Datasheet.pdf) |
| 22 | Rezistor 10K | SMD 0402 | 12 | [Model](https://componentsearchengine.com/part-view/R0402%201%25%20100%20K%20(RC0402FR-07100KL)/YAGEO) | - |
| 23 | Rezistor 5.1K | SMD 0402 | 2 | [Model](https://www.yageo.com/en/Product/resistors) | - |
| 24 | Rezistor 2K | SMD 0402 | 1 | [Model](https://www.yageo.com/en/Product/resistors) | - |
| 25 | Rezistor 2.2 | SMD 0402 | 1 | [Model](https://www.yageo.com/en/Product/resistors) | - |
| 26 | Rezistor 200 | SMD 0402 | 1 | [Model](https://www.yageo.com/en/Product/resistors) | - |
| 27 | Rezistor 100K | SMD 0402 | 1 | [Model](https://www.yageo.com/en/Product/resistors) | - |
| 28 | Rezistor 15 | SMD 0402 | 1 | [Model](https://www.yageo.com/en/Product/resistors) | - |
| 29 | Rezistor 0.47 | SMD 0402 | 1 | [Model](https://www.yageo.com/en/Product/resistors) | - |
| 30 | Capacitor 100nF | SMD 0402 | 10 | [Model](https://componentsearchengine.com/part-view/CC0402MRX5R5BB106/YAGEO) | - |
| 31 | Capacitor 4.7µF | SMD 0402 | 5 | [Model](https://www.yageo.com/en/Product/mlcc) | - |
| 32 | Capacitor 1µF | SMD 0402 | 10 | [Model](https://www.yageo.com/en/Product/mlcc) | - |
| 33 | Capacitor 1µF/50V | SMD 0402 | 10 | [Model](https://www.yageo.com/en/Product/mlcc) | - |
| 34 | Capacitor 10µF | SMD 0402 | 1 | [Model](https://www.yageo.com/en/Product/mlcc) | - |
| 35 | Capacitor 100µF TANT | SMD CT3528 | 1 | [Model](https://a360.co/4iZy6AA) | - |
| 36 | Test pads | Puncte de testare TP20R | 17 | [Model](https://www.keyelco.com/product.cfm/product_id/1543) | - |
| 37 | SMD Solder Jumper | Jumper SMD | 1 | [Model](https://grabcad.com/library/solder-jumpers-1) | - |

## Functionalitatea Hardware

### Componente Principale

1. **Microcontroller ESP32-C6**
   - Procesor RISC-V cu 8MB Flash
   - WiFi 6 (802.11ax), Bluetooth 5, suport Zigbee si Thread
   - Management optimizat al energiei pentru durata de viata a bateriei

2. **Interfata Display E-Paper**
   - Conectata prin interfata SPI si semnale de control dedicate
   - Circuit special pentru generarea tensiunilor e-paper
   - Consum de energie aproape zero in stare statica

3. **Sistem de Stocare**
   - Flash extern 64MB (W25Q512JVEIQ) pentru fonturi si elemente UI
   - Slot card MicroSD pentru biblioteca extinsa de carti

4. **Management Energie**
   - Circuit incarcare baterie LiPo folosind MCP73831
   - Regulator de tensiune XC6220A331MR-G pentru 3.3V stabil
   - MAX17048G+T10 pentru monitorizare precisa a nivelului bateriei
   - Moduri deep sleep pentru durata extinsa de viata a bateriei

5. **Periferice Auxiliare**
   - Senzor de mediu BME688 (temperatura, umiditate, calitatea aerului)
   - Modul RTC DS3231SN de precizie inalta
   - Conector Qwiic/Stemma QT pentru expansiune
   - Trei butoane tactile pentru navigare

