# MakeTech PX4 v1.17 Baseline

Date: 2026-08-27
PX4 version: v1.17.0
Base commit: d6f12ad1c4

## Build environment

- Ubuntu 24.04
- Native Linux installation
- ARM GCC 13.2.1
- Python 3.12.3
- CMake
- PX4 v1.17.0

## Verified builds

### SITL

Target:
    px4_sitl

Result:
    PASS

### NxtPX4 V2

Target:
    hkust_nxt-dual_default

Result:
    PASS

Flash:
    1,807,128 / 1,792 KB
    98.48%

### MicoAir743 V2 AIO-45A

Target:
    micoair_h743-aio_default

Result:
    PASS

Flash:
    1,899,192 / 1,920 KB
    96.60%

### MicoAir743 V2 FC/ESC

Target:
    micoair_h743-v2_default

Result:
    PASS

Flash:
    1,903,784 / 1,920 KB
    96.83%

## Notes

All targets compiled using the default PX4 v1.17.0
board configurations without manually disabling modules.

No PX4 source modifications have been made.
