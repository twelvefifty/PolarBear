# Drone Building Project - Parts List

## Build Examples

![3D Printed Drone Frame Example](images/completed_drone_example.png)
*Example of a 3D printed drone frame with electronics mounting in progress. Note the purple frame color and XT30 connector setup.*

### Frame ($13-24 CAD)
- **BM Aether 4 Unibody Frame**
  - 4-inch unibody design
  - 3D printed frame (PLA+ or PETG recommended)
  - Source: MakerWorld (https://makerworld.com/en/models/541413-bm-aether-4)
  - Cost: $8-15 CAD (filament)

- **TPU Protection Parts**
  - Material: Flexible TPU filament
  - Components:
    - VTX antenna mount
    - Camera mount
    - Motor soft mounts
    - Battery pad
    - Source: [AliExpress TPU Parts](https://www.aliexpress.com/item/1005006096723868.html)
  - Cost: $5-9 CAD (filament)
  - Note: These parts should be printed in TPU for flexibility and vibration dampening

### Flight Controller & ESC Stack ($81 CAD)
- **SpeedyBee F405 Mini BLS 35A 20x20 Stack**
  - Flight Controller Features:
    - F405 MCU with ICM42688P gyro
    - Built-in Bluetooth for wireless configuration
    - Built-in barometer
    - 8MB Blackbox storage
    - Supports DJI Air Units
    - 4x UART ports
    - Dual BEC: 5V 2A and 9V 3A
    - Compatible with 3-6S LiPo
    - Size: 30mm x 32mm x 7.8mm
    - Weight: 9.6g
  - ESC Features:
    - BLHeli_S 35A 4-in-1 ESC
    - Continuous current: 35A per motor
    - DSHOT300/600 support
    - Built-in current sensor
    - Size: 35mm x 35mm x 5.5mm
    - Weight: 7.2g
  - Stack mounting: 20x20mm (M2/M3 compatible)
  - Total stack weight: 13.5g
  - Source: [SpeedyBee Official](https://www.speedybee.com/speedybee-f405-mini-bls-35a-20x20-stack/)

### Motors ($72 CAD)
- **4x EMAX ECO II Series 2004 3000KV Brushless Motors** ($18 CAD each)
  - Size: 2004 (20mm diameter, 4mm height)
  - KV rating: 3000KV (optimal for 3S battery)
  - Perfect size for 4-inch builds
  - Lightweight and efficient design
  - Source: [EMAX Official](https://emaxmodel.com/products/emax-eco-ii-series-2004-1600kv-2000kv-2400kv-3000kv-brushless-motor-for-rc-drone-fpv-racing)

### Propellers ($22 CAD)
- **Gemfan Hurricane 4023 Props**
  - Size: 4-inch (4x2.3 pitch)
  - Material: Durable polycarbonate
  - Sets needed: 
    - 2x sets (8 props) minimum
    - 4x sets recommended for spares
  - Configuration per set:
    - 2x CW (clockwise) rotation
    - 2x CCW (counter-clockwise) rotation
  - Color options available
  - Perfect match for EMAX ECO II 3000KV motors
  - Source: [AliExpress Gemfan Hurricane](https://www.aliexpress.com/item/1005002525276207.html)
  - Cost: $5.50 CAD per set

### Power System ($143 CAD)
- **2× GNB 850mAh 4S 120C HV LiPo** ($47.98 CAD)
  - Voltage: 14.8V (4S)
  - Capacity: 850mAh
  - Discharge rate: 120C continuous
  - HV (High Voltage) capable
  - XT30 connector
  - Size optimized for 4-inch builds
  - Weight: ~110g per battery
  - Quantity: 2 batteries included
  - Source: [RotorVillage GNB Battery](https://rotorvillage.ca/search.php?search_query=GNB+850mah+4S+120C+HV+LiPo+XT30)

Note: Prices in CAD from RotorVillage. Consider local shipping times vs AliExpress.

- **HOTA D6 Pro Charger** ($95 CAD)
  - AC/DC Dual Power (100W AC / 200W DC)
  - 15A maximum charge current
  - Supports: LiPo/LiHV/Life/Lion/NiMH/NiCd/Pb
  - Color touchscreen interface
  - Built-in balance charging
  - Storage charge function
  - Multiple safety protections
  - USB firmware updates
  - Source: [AliExpress HOTA D6 Pro](https://www.aliexpress.com/item/1005007867516544.html)

### Radio System ($56 CAD)
- **Controller**: PlayStation DualShock 4 (PS4 Controller)
  - Uses existing gaming controller ($0 CAD - existing)

- **BETAFPV Nano TX V2 Module ELRS** ($38 CAD)
  - Multi-band support: 2.4GHz/915MHz/868MHz
  - Bluetooth connectivity for PS4 controller
  - Compact and lightweight design
  - Perfect for gaming controller conversion
  - Lower cost than traditional RC transmitters

- **ExpressLRS EP1 Receiver** ($18 CAD)
  - Protocol: ExpressLRS 2.4GHz
  - Ultra-low latency (500Hz refresh rate)
  - Tiny size perfect for 4-inch build
  - Built-in antenna
  - Weight: ~1g
  - Source: [AliExpress ELRS EP1](https://www.aliexpress.com/item/1005006739782044.html)

### FPV System ($95 CAD)
- **RunCam WiFiLink Digital FPV System**
  - Camera Features:
    - IMX415 image sensor
    - 160° Field of View
    - Resolution: 1080P@60/90FPS, 720P@120FPS
    - Lens module: 19x19mm/M12 lens
    - MIPI cable: 200/130mm included
  - VTX Features:
    - Power input: DC 9-30V
    - WiFi transmission
    - 29dBm PA output power
    - 5G antenna (IPEX1 connector)
  - Mounting: 25.5mm x 25.5mm
  - Weight: 30g total
  - Source: [RunCam Official](https://shop.runcam.com/runcam-wifilink-based-on-openipc/)

- **Display System**
  - **Meta Quest 3** (existing VR headset)
    - High resolution display
    - Comfortable head mounting
    - Built-in battery
    - Cost: $0 (if already owned)
  - **RunCam OpenIPC Ground Link**
    - Connects WiFiLink to Quest 3
    - Low latency video streaming
    - Compatible with OpenIPC protocol
    - Integrates with Quest's display system

Note: This setup uses existing VR hardware instead of traditional FPV goggles, providing high-quality digital FPV at a lower additional cost.

### Additional Components ($34 CAD + Optional GPS $24 CAD)
- Battery Straps & Misc Hardware
  - 20x200mm size (suitable for 4-inch build)
  - Non-slip design with rubber lining
  - Multiple color options
  - Quantity: 4-6 straps (always have spares)
  - Source: [AliExpress Battery Straps](https://www.aliexpress.com/item/4001346931735.html)

- Heat shrink tubing
- Wire (20-24 AWG)
- Zip ties
- Double-sided tape
- GPS Module (Optional)
  - M9N GPS Module with Compass
  - Features:
    - Built-in compass (magnetometer)
    - Compatible with BetaFlight/INAV
    - Supports GPS positioning and navigation
    - Compact size for 4-inch builds
    - Plug and play with most flight controllers
  - Power: 4.5-5.5V (compatible with FC's 5V output)
  - Source: [AliExpress M9N GPS](https://www.aliexpress.com/item/1005007014772754.html)
  - Cost: $15-20 CAD

## Total Project Cost
- Base Build: $516 CAD
- With Optional GPS: $540 CAD
- Estimated Shipping: $54-81 CAD
- **Grand Total: $570-620 CAD**

Note: 
1. All prices in CAD
2. Exchange rate calculated at approximately 1 USD = 1.35 CAD
3. Excludes tools and printing equipment
4. Significant savings from using existing Quest 3 and PS4 controller
5. Some components may be found cheaper locally

## Recommended Suppliers
- **AliExpress**
  - Best prices for most components
  - Wide selection of parts
  - Longer shipping times
  - Recommended for: Motors, ESCs, frame parts, accessories

- **RotorVillage**
  - UK/EU based supplier
  - Fast shipping within Europe
  - Excellent customer service
  - Premium component selection

- **DroneGeek**
  - Local/regional supplier
  - Fast shipping
  - Technical support available
  - Ready-to-fly options

- **SpeedyBee**
  - Official flight controller supplier
  - Direct manufacturer support
  - Specialized in FC/ESC stacks
  - Excellent documentation

- **RunCam**
  - Official camera and FPV systems
  - Latest digital FPV technology
  - Direct warranty support
  - Specialized in video equipment

## Next Steps
1. Research and finalize component choices
2. Create a build guide
3. Gather necessary tools
4. Plan the assembly process
5. Configure GPS features in Betaflight
6. Test navigation features in a safe environment 