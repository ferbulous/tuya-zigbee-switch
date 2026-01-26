# Supported devices

### Quick-picks
- **modules:** AVATTO, Aubess, iHseno
- **switches:** Moes 1-3gang (any design)

Support new devices: [contribute/porting.md](/docs/contribute/porting.md)  

### Legend

| Symbol | Meaning  |                    |                      |                    |                |           |
| :----: | ---------| ------------------ | -------------------- | ------------------ | -------------- | ----------|
|   🚧   | Status   | 🟩 Fully supported | 🟨 Mostly supported  | 🟧 In progress     | 🟥 Unsupported |           |
|   📦   | Build    | ✔️ Available       | ❌️ Unavailable       |                    |                |           |
|   💡   | Category | 🇲 Module          | 🇸 Switch            | 🇴  Outlet         | 🇷 Remote      | 🇧  Board |
|   ⚡   | Power    | 🔌 Mains           | 🔋 Battery           | 🔱 USB             |                |           |
|   📲   | Install  | 🛜 Wireless        | ➿ By wire           | ❓ Some by wire    |                |           |
|   🏭   | MCU      | `TL` Telink        | `SL` Silicon Labs    |                    |                |           |
|   🅰    | Variant  | 🅰                  | 🅱                    | 🅲                  | 🅳              | 🅴         |

<!-------------------------------------------------------------------
  `supported.md` is generated. 
  
  Do not edit it directly! Instead, edit:
  - `device_db.yaml`             - add or edit devices
  - `supported_devices.md.jinja` - update the template
  - `make_supported_devices.py`  - update generation script

  Generate with: `make tools/update_supported_devices`
-------------------------------------------------------------------->

> [!IMPORTANT]  
> Identify your device by **Zigbee Manufacturer** and linked threads/stores!  
> *Z2M pages are sometimes generic.*

### Device list

| 🚧 | 📦 | 💡 | ⚡️ | 📲 | 🏭 | Zb&nbsp;Manufacturer <br> Zb&nbsp;Model | Name <br> Z2M&nbsp;page&nbsp;🔗 | Store | Threads | Status |
| -- | -- | -- | -- | -- | -- | :-------------------------------------- | :------------------------------ | ----: | ------: | :----- |
| 🟩 | ✔️ | 🇸 | 🔌 | 🛜 | **TL** | `_TZ3000_ewgtuk8o` <br> `TS0004` | [Tuya 4 Gang Switch](https://www.zigbee2mqtt.io/devices/TS0004.html) |   |   | Supported | 
| 🟩 | ✔️ | 🇸 | 🔌 | 🛜 | **TL** | `_TYZB01_mqel1whf` <br> `TS0013` | [Tuya 3 Gang Switch](https://www.zigbee2mqtt.io/devices/TS0013.html) |   |   | Supported | 
| 🟩 | ✔️ | 🇸 | 🔌 | ➿ | **SL** | `_TYZB01_mqel1sil` <br> `TS0013` | [Tuya 3 Gang Switch Sil](https://www.zigbee2mqtt.io/devices/TS0013.html) |   |   | Supported | 
| 🟩 | ❌️ | 🇸 | 🔌 | ➿ | **SL** | `_TZE200_g1ib5ldv` <br> `TS0601` | [ZTS-EU_2gang](https://www.zigbee2mqtt.io/devices/TS0601.html) |   |   | Supported | 
| 🟩 | ✔️ | 🇸 | 🔌 | ➿ | **SL** | `_TZ3000_z6zplt0y` <br> `TS0726` | [Tuya-EU_4gang_CN](https://www.zigbee2mqtt.io/devices/TS0726.html) |   |   | Supported | 

Data from [`device_db.yaml`](/device_db.yaml)
