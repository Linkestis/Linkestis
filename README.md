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

I am independently developing a private end-to-end AirSense 11 interoperability
platform, covering authenticated Bluetooth Low Energy communication, validated
data acquisition and reconstruction, historical processing, and Home Assistant
presentation.

The work is substantially more than a simple Home Assistant custom component.
At a high level, the architecture follows:

device communication → authenticated session → transport and acquisition →
validation and reconstruction → data processing → Home Assistant presentation

The end-to-end implementation has been independently developed through
protocol research, implementation and validation, rather than being based on
an existing publicly available complete solution.

Current engineering work includes:

- authenticated BLE communication and session/transport lifecycle handling;
- safe fragmented spool acquisition and offline-validated bounded multi-round continuation;
- sequence, size, Base64 and integrity validation;
- controlled TherapyOneMinute data processing;
- historical Summary-data handling and normalized data models;
- privacy-conscious diagnostics and fail-closed behavior;
- offline regression and compatibility testing;
- controlled deployment and rollback methodology.

The reusable engineering layer could potentially support interoperability,
diagnostics, research, device testing, desktop or mobile applications, and
other local platforms in the future. These are potential directions, not
existing products.

To the best of my knowledge, after reviewing publicly available AirSense 11
projects and technical references, I have not found another publicly documented
implementation that combines authenticated AirSense 11 BLE session handling,
offline-validated multi-round spool acquisition, TherapyOneMinute processing,
historical-data handling and Home Assistant integration in one complete
end-to-end system.

The work is intended for interoperability, monitoring, diagnostics,
engineering and research, and historical data access. It is not intended to
replace the official ResMed application, modify therapy settings, control
treatment, or act as an approved medical device. It is not affiliated with
ResMed.

### 🔒 Source code and development status

The implementation and core engineering work remain private. Licensing terms
are currently under review.

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
