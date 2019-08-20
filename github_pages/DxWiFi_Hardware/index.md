---
title: DxWiFi Hardware
layout: default
nav_data:
  - name: DxWiFi
    link: /github_pages/RF_Subsystem/DxWiFi/
    repo: /oresat-c3-rf
    defcolor: red
---
# oresat-dxwifi-hardware
This repository is for the DxWiFi hardware that will fly on the OreSat satellite. DxWiFi is our communication subsystem for high speed data (1 Mbps) using 2.4 GHz WiFi between the spacecraft and ground.

This is hardware for the **satellite** only; please see the other repos if you're looking for the [OreSat Live Handheld Ground Station](https://github.com/oresat/oresat-live-handheld-ground-station) or the [Mini-OreSat testing platform for high altitude balloons](https://github.com/oresat/oresat-live-mini-oresat).

We intend to use "ordinary WiFi" (IEEE 802.11b) as a high speed satellite communication system. What is _not_ ordinary is that we run the radio under the amateur radio rules and regulations (FCC Part 97) and thus can increase power levels and antenna gains necessary to make the link budget work.

### Ordinary WiFi
The plan is to use the Qualcomm Atheros AR9271 USB to WiFi adapter because of the driver support in Linux.

### Non ordinary bi-directional power amplifier
This project is intended to operate under the Amateur Radio Service [47CFR97](https://www.gpo.gov/fdsys/pkg/CFR-1996-title47-vol5/pdf/CFR-1996-title47-vol5-part97.pdf) whereby larger power levels and higher gain directional antennas can be used within the [13 cm band](https://en.wikipedia.org/wiki/13-centimeter_band) to close the link.

NB:  There are other DxWiFi materials on the PSAS GitHub repo, but those repos are deprecated.

Link budgets can be found [here](https://github.com/oresat/oresat-dxwifi-hardware/tree/master/Link-Model).
