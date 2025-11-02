# 🚗 Ford ECM Flash Program

This repository provides tooling for flashing Ford Engine Control Modules (ECMs) via J2534-compatible interfaces. It is designed for technicians and developers working with Ford vehicles from 1996 onward.

---

## 🔧 Supported Tools

- **Ford J2534 Diagnostic Software (FJDS)**  
  Official Ford software for ECM reprogramming  
  [Motorcraft FJDS Portal](https://www.motorcraftservice.com/diagnostic/Support?channelId=46&categoryId=286)

- **PCMFlash (Modules 53, 71, 75)**  
  Supports Ford EMS2204, MED17, PowerShift TCM  
  [ECUTools PCMFlash](https://ecutools.eu/chip-tuning/pcmflash/)

- **Pass-Thru Pro III**  
  Snap-on interface for Ford J2534 software  
  [Snap-on Guide](https://www.snapon.com/Diagnostics/US/KB/Quick-Tip-Ford-Flash-Reprogramming.htm)

---

## 📦 Flashing Workflow

1. Connect J2534 device to vehicle OBD-II port  
2. Launch Ford J2534 software (FJDS or PCMFlash)  
3. Authenticate with Motorcraft or ECUTools  
4. Select vehicle model and ECM module  
5. Load calibration file or ROM  
6. Execute flash and verify checksum  
7. Confirm VIN and module integrity

---

## 🛠️ License

GPL-3.0 — Open for modification, redistribution, and integration.

---

## 📁 Status

This repo is focused exclusively on Ford ECM flashing. No other brands or modules are supported.
