### Link Budget Models for the DxWiFi Channel

The source of these link model spreadsheets are from Jan King and are located at the [AMSAT-UK IARU website](http://www.amsatuk.me.uk/iaru/spreadsheet.htm).  The spreadsheets have been customized from revision 2.5.5 which are signified by a suffix letter.  In addition, for OreSat protocol information please visit our [GitHub protocol page](https://github.com/oresat/oresat-design/tree/gh-pages/protocol).  For OreSat's primary communication link models please visit our [Github C3 RF page](https://github.com/oresat/oresat-c3-rf/link-models)

* The bulk-data mission uplink and downlink using UniClOGS (University Class Open Ground Station)
  * ___OreSat1_link_model_v2.5.5a_mission_data_uniclogs.xlsx  (PDF summary)___
  * S band - 2422 MHz - 1Mbps 802.11b
  * 45 deg minimum elevation
  * 1.4 dBi canted turnstile on satellite and 23 dBi parabolic reflector at ground station for uplink
  * 12 dBi helix on satellite and 23 dBi parabolic reflector at ground station for downlink

* The bulk-data mission downlink using a handheld ground station receiver
  * ___OreSat1_link_model_v2.5.5a_mission_data_handheld.xlsx  (PDF summary)___
  * S band - 2422 MHz - 1Mbps 802.11b
  * 45 deg minimum elevation
  * 12 dBi helix on satellite and 15 dBi quad helix/patch at ground station

Notes:
- The 'Transmitters' and 'Receivers' sheets have been customized
  - Block diagrams reflect correct design
  - System noise temperature is more precise
- The 'System Performance Summary' sheet has been customized
  - Power levels in dBm
  - More link losses details
