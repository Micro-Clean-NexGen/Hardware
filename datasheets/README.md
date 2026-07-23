# Datasheets

Manufacturer datasheets and manuals for the components used on (or offered as options for) the
Autonomous Steam Cleaning & Air Sterilization Robot **base**. 


> ⚠️ **Third-party documents — copyright of their respective manufacturers.** These PDFs are
> **re-hosted for convenience** with attribution to the source (see each folder). They are **not**
> covered by this repository's licence; all rights remain with the manufacturers.

## What applies to the base build vs. what is optional

The base of the robot documented in this repo uses the **ZD** motor + driver. The **ZLTech** and
**TZBot** parts are **alternative / optional** components for larger product configurations
(higher-power drives, wireless charging, lift, larger battery) — they are **not** on the base build as in the current version for MVP.

| Folder | Component | On the base build? |
|---|---|---|
| ZD BLDC motor (Z4BLD60-24GN-30S) + **ZBLD.C20-120L2R** driver | ✅ **yes — this is the base** |
| ZLAC8015D / ZLAC8030L industrial drivers (CANopen/RS485) | ⚙️ option (higher-power variant) |
|  ZLLG80 hub-motor wheel | ⚙️ option (alternative drivetrain) |
| 24 V 20 Ah battery + BMS (serial protocol) | ⚙️ option (product battery/BMS) |
| WCM-300 wireless charger | ⚙️ option (auto-docking charge) |
| Lift reducer (TZDSXZ-48-400) | ⚙️ option (lift attachment) |

