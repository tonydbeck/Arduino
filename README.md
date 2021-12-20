# Arduino
All My Arduino Code!

## WebLights! - Use Tessellate with this to get web based control
## Libraries needed:
- WS2812FX
- Adafruit-Neopixel

### Make sure to change:
``` #define WIFI_SSID "xxxx"
#define WIFI_PASSWORD "xxxx"

#define STATIC_IP                       // uncomment for static IP, set IP below
#ifdef STATIC_IP
IPAddress ip(192,168,0,45);
IPAddress gateway(192,168,0,1);
IPAddress subnet(255,255,255,0);
#endif
```


## NOTE: IP Address will either be 192.168.0.x or 192.168.1.x depending on the router

Ping the address from a laptop before using it to ensure it is spare!


## For Tessellate board use the following for hardware definition:
```
#define LED_PIN 25                       
#define LED_COUNT 48
```

## Once Program is loaded from Arduino IDE:
Use Arduino Serial monitor at baud 115200 to view status when board is reset

If connected successfully to WiFi, then from a Web Browser put in the IP address used in the code into Chrome or Edge..... Eg. 192.168.0.45
Web interfae should come up!

