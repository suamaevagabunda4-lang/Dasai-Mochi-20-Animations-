# Dasai-Mochi-20-Animations-ESP8266 NodeMCU
ESP8266 + SSD1306 GIF Player
How to compile and flash (without IDE)
Option 1: Gitpod (easiest)
Upload this project to GitHub
Access: `https://gitpod.io/#https://github.com/YOUR_USER/YOUR_REPO`
Wait for automatic compilation (~2-3 min)
Download the file `.pio/build/esp8266/firmware.bin`
Flash with ESP Web Flasher or ESPTool Web
Option 2: Local PlatformIO
```bash
pip install platformio
pio run
# Firmware in: .pio/build/esp8266/firmware.bin
```
Hardware
ESP8266 (ESP-12E / NodeMCU / Wemos D1 Mini)
SSD1306 128x64 I2C
SDA → D2 (GPIO4)
SCL → D1 (GPIO5)
VCC → 3.3V
GND → GND



