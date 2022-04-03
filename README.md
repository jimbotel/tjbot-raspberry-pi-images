# tjbot-raspberry-pi-images
Images for raspberry pi3 and pi4 ready to start with Node-RED TJBot nodes

More info about TJBot activities:
 [What’s Possible With AI – TJ Bot](https://www.ibm.com/ibm/responsibility/initiatives/activitykits/tjbot/)


## New 2022 (April 3) !! Renewed common image for rpi3 and rpi4:
**Available at:** https://ibm.box.com/s/48dt61a6i03lascj52q1jctlk50d97za 

### What's New:
 - Support for Common Anode LEDs (as well as NeoPixel ones)
 - Watson services credentials are supplied to TJBot Node-RED nodes using a credentials file
 - Several forms of Visual Recognition added using [Model Asset eXchange](https://ml-exchange.org/models/) [Node-RED nodes](https://flows.nodered.org/node/node-red-contrib-model-asset-exchange) (can be consumned using [docker images](https://hub.docker.com/u/codait) installed on a separate PC)

### Changes:
 - Based on tjbot lib v2.0.2 (well, right now a [patched version](https://github.com/jimbotel/tjbotlib) of it until a Pull Request I did is accepted)
 - Using a new ["patched" version](https://github.com/jimbotel/node-red-contrib-tjbot) of Jean Carl's TJBot Node-RED nodes 
 - Using current (as of Feb 2022) Node.js (v14.19.0) / Node-RED (v2.2.0) versions
 - Using latest (January 28th 2022) release of "Raspberry Pi OS (Legacy) with desktop":  
   - System: 32-bit  
   - Kernel version: 5.10  
   - Debian version: 10 (buster)  

**Note**: Raspberry Pi OS latest version, ["Bullseye"](https://www.raspberrypi.com/news/raspberry-pi-os-debian-bullseye/) introduced [some changes](https://www.raspberrypi.com/news/new-old-functionality-with-raspberry-pi-os-legacy/) that may not be retro-compatible, so I preferred to go with the "legacy" version until I have more time to do testing with Bullseye.  

## Previous versions:

Raspberry pi 4 image available at:
https://ibm.box.com/s/79bzh69h8brin2ppislct52d88z5kod5

Raspberry pi 3 image available at: 
https://ibm.box.com/s/8d1qcj8v2cwdvcwgetgwtphrq8nqe2vw


Additional info will be added here...

