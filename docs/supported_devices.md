# Supported devices

Note that rebranded versions may have different internals, requiring different pinouts (and therefore custom builds).  
**Zigbee Manufacturer** is the most reliable device identifier.

If your device contains a **supported Tuya Zigbee module** (ZTU, ZT2S, ZT3L), porting is relatively simple.  
It consists of tracing (or guessing) the **board pinout**, adding an entry in the `device_db.yaml` file and running the build action. 

Also read:  
- [porting_to_new_device.md](./porting_to_new_device.md)
- [recommended_devices.md](./recommended_devices.md)
- [not_recommended_devices.md](./not_recommended_devices.md)

| Z2M device name | Vendor name | Zigbee Manufacturer | Type | Status | Issue |
| --- | --- | --- | --- | --- | --- |
| [LZWSM16-3](https://www.zigbee2mqtt.io/devices/LZWSM16-3.html) | AVATTO LZWSM16-3 (blue socket)  | _TZ3000_avotanj3 | router / end_device | Supported |   [link](https://github.com/romasku/tuya-zigbee-switch/issues/135)  | 

