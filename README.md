# Hi, I'm Linkestis 👋

I build practical software and interoperability projects around:

- 🏠 Home Assistant
- 🔌 Local-first smart home integrations
- 📡 Bluetooth Low Energy and device interoperability
- 📺 Android TV / ADB automation
- 🐍 Python
- 🧪 Protocol research and working software development

I prefer local control, reproducible testing, clear documentation, and solutions that do not depend unnecessarily on cloud services.

## Featured projects

### 🫁 AirSense 11 interoperability development

I have developed a private Python codebase for local AirSense 11 interoperability.

The project began as a Home Assistant integration for personal use and has grown
into a reusable device-interoperability architecture.

The code developed so far includes work for:

- authenticated local BLE communication
- session and transport handling
- secure protocol communication
- read-only data acquisition
- therapy summary extraction
- one-minute therapy data decoding
- therapy event interpretation
- compatibility and profile handling
- spool validation and safety limits
- normalized device data models
- Home Assistant integration

The architecture is being separated from Home Assistant so the same core
technology can potentially support additional consumers in the future,
including Android applications, desktop applications, command-line tools,
SDK/OEM integrations, and other local interoperability platforms.

> Experimental interoperability research. Not a medical device and not affiliated with ResMed.

### 🔒 Source code and development status

Active AirSense development is private.

The current reusable core and private Home Assistant integration are not
publicly released. Private source code is not published, distributed, or
licensed for reuse, derivative applications, integrations, SDKs, or commercial
products without explicit authorization from the copyright owner.

Future public releases, if any, will have their scope and licensing decided
separately.

---

### 📺 [TCL Google TV ADB HDMI for Home Assistant](https://github.com/Linkestis/tcl-google-tv-adb-hdmi-ha)

Direct HDMI input switching on TCL Google TV using ADB, with practical Home Assistant examples.

Topics include:

- Android TV / Google TV
- ADB
- HDMI input control
- Home Assistant automations
- local device control

---

### 🌬️ [Home Assistant Vybra Fan](https://github.com/Linkestis/home-assistant-vybra-fan)

Verified LocalTuya DP mapping and Home Assistant configuration for the Vybra Tower Fan.

Focus:

- Tuya local control
- Home Assistant
- device DP mapping
- cloud-independent operation

## What I care about

- Local-first systems
- Privacy
- Device interoperability
- Reproducible testing
- Clean architecture
- Technical provenance
- Reliable automation
- Clear technical documentation
- Interoperability between devices and platforms

## Current interests

`Home Assistant` · `Python` · `BLE` · `ADB` · `Tuya` · `MQTT` · `Zigbee` · `IoT` · `Device interoperability`

---

Most of my projects start with a real device or problem in my own setup and grow from testing, measurement, and documentation.
