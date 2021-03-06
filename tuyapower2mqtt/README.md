# TuyaPower2MQTT - PyPi Module
Author: Phill Healey
https://github.com/codeclinic/TuyaPower2MQTT

# Description
Python module to pull power and state data from Tuya / Smart Life / Jinvoo WiFi smart socket/switch devices.  _Tested on RaspberryPi, Linux, Windows 10 and MacOS._ 

Compatible with Home Assistant.

# Preparation
All python dependencies for TuyaPower2MQTT will be automatically installed. However, you may need to install ```python-crypto``` via apt/yum/etc. If this is your first pip package then you may also need to install ```python-pip```.

```bash
 sudo apt-get install python-crypto python-pip		
```

You'll need a Mosquitto (MQTT) server to publish the data to. If you don't already have one running, I recommend following this simple tutorial: [Installing an MQTT server on Debian](https://medium.com/@rossdanderson/installing-mosquitto-broker-on-debian-2a341fe88981). Note, you can try installing MQTT without adding the repo suggested in the first step.

# Functions
* deviceInfo - Poll device and return on, w, mA, V and err data.
```python
tuyapower.deviceInfo(PLUGID, PLUGIP, PLUGKEY, PLUGVERS)
```

# Usage
Gathers full power stats / data from Tuya sockets &amp; switches and reports results as JSON via MQTT

Full details coming soon.
