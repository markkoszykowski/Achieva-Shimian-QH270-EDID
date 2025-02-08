# [Achieva Shimian QH270](https://www.amazon.com/Refurbished-ACHIEVA-SHIMIAN-QH270-2560x1440/dp/B00MDDN0HC) EDID

This repo contains the EDID binary (```shimian.bin```) required to set up the Achieva Shimian QH270 monitor on Linux (tested on Arch Linux with an Apple Mini DisplayPort to Dual-Link DVI Adapter).

The EDID binary was extracted using MacOS, and then hand modified to make it compliant with the EDID standard. In specific, the additional extension block, which contained nullified data, was removed
and Block 0's checksum was updated accordingly.

Display configuration:
1) Built-in 1080p 144Hz display
2) [Samsung 27” T55 Curved Monitor](https://www.samsung.com/us/computing/monitors/curved/27-t55-curved-monitor-lc27t550fdnxza/) via HDMI
3) [Achieva Shimian QH270](https://www.amazon.com/Refurbished-ACHIEVA-SHIMIAN-QH270-2560x1440/dp/B00MDDN0HC) w/ Apple Mini DisplayPort to Dual-Link DVI Adapter via Mini DisplayPort
