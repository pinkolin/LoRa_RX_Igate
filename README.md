# LoRa_RX_Igate Update 28.5.2023
In the update, code for sending telemetry to the APRS network has been added. An option for decoding compressed location from an APRS packet has been included.
# LoRa_RX_Igate Update 22.5.2023
Simple LoRa Igate. The Igate operates using the LoRa.h library. Upon receiving a packet, it undergoes editing, checking, and is subsequently sent to an APRS server. The Igate includes safeguards against communication failure via Wi-Fi and connection drops between the Igate and the server. The Igate has a web interface with a fixed IP address that can be set by modifying it in Platformio. The website displays the five most recent stations with their respective distance and azimuth. Additionally, the RSSI and S/N parameters are shown. On the OLED display, five stations with their RSSI and SN are displayed
# LoRa_RX_Igate
Simple LoRa Igate. The Igate operates using the LoRa.h library. Upon receiving a packet, it undergoes editing, verification, and is subsequently sent to an APRS server. The Igate is equipped with safeguards against communication failure via WiFi and loss of connection between the Igate and the server.
