# oresat-dxwifi
OreSat subsystem for high speed data using WiFi between Earth and spacecraft 

It is the intent to use ordinary WiFi to provide high speed data for the science missions on OreSat. Ordinary in the sense that the 802.11b standard is used. What is not ordinary are the power levels and link budget needed to do this. It also thought that the components would be mostly COTS, but that is not a requirement.

### Ordinary WiFi
The plan is to use the Qualcomm Atheros AR9271 USB to WiFi adapter because of the driver support in Linux.

### Non ordinary bi-directional power amplifier
This project is intended to operate under the Amateur Radio Service [47CFR97](https://www.gpo.gov/fdsys/pkg/CFR-1996-title47-vol5/pdf/CFR-1996-title47-vol5-part97.pdf) whereby larger power levels and higher gain directional antennas can be used within the [13 cm band](https://en.wikipedia.org/wiki/13-centimeter_band) to close the link.

NB:  There are other DxWiFi materials on the PSAS GitHub repo, in particular:
   - The efforts of testing and using [WiFi with the PSAS rocket](https://github.com/psas/DxWiFi)
   - A proposed WiFi [power amplifier design project](https://github.com/psas/dxwifi-pa)


