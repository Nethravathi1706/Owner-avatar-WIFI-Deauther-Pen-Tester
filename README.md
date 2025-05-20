# WIFI-Deauther-Pen-Tester
A simple WiFi Deauthentication tool using ESP8266

# 🌟 About the Project
This firmware allows you to easily perform a variety of actions to test 802.11 networks using an ESP8266. It's also a great project for learning about WiFi, microcontrollers, Arduino, hacking and electronics/programming in general.

The deauthentication attack is the main feature, which can be used to disconnect devices from their WiFi network.
Although this denial-of-service attack is nothing new, a lot of devices are still vulnerable to it. Luckily this is slowly changing with more WiFi 6 enabled devices being used. But a lot of outdated WiFi devices remain in place, for example in cheap IoT hardware. With an ESP8266 Deauther, you can easily test this attack on your 2.4GHz WiFi network/devices and see whether it's successful or not. And if it is, you know you should upgrade your network.

## ⚙️ Requirements
- ESP8266 (NodeMCU or D1 Mini)
- Deauther Bin File
- ESP8266 Flasher

## 🚀 How to Flash
1. Connect ESP8266 to your PC
2. Download above nodemcu-flasher-master Zip file
3. Download above bin file
4. Run ESP8266Flasher
5. Load the `.bin` file from `firmware/`
6. Choose the correct COM port
7. Click **Flash**

# Here are some quick links:
- [ESP8266 Buy](https://deauther.com/docs/buy/)
- [Download](https://deauther.com/docs/download/)
- [Tutorial](https://deauther.com/docs/category/diy-tutorial/)
- [Usage](https://deauther.com/docs/category/usage/)
- [FAQ](https://deauther.com/docs/faq/)

# Password
The password for pwned is deauther

# Disclaimer
This project is a proof of concept for testing and educational purposes.
Neither the ESP8266, nor its SDK was meant or built for such purposes. Bugs can occur!

Use it only against your own networks and devices!
Please check the legal regulations in your country before using it.
We don't take any responsibility for what you do with this program.
