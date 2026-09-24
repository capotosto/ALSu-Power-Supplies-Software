# ALSu PSC Software

This repository provides a central index for the software, firmware, EPICS IOCs, calibration, and test tools associated with the ALSu Power Supply Controller (PSC).

## Current / Working Repositories

These repositories contain the software currently used for PSC development, operation, first-article testing, and automated test equipment.

| Repository | Purpose |
|---|---|
| [pdu-ioc](https://github.com/jamead/pdu-ioc) | EPICS IOC for the Built to Print (BTP) PDU |
| [zpsc-fw](https://github.com/jamead/zpsc-fw) | zPSC firmware |
| [zpsc-ioc](https://github.com/jamead/zpsc-ioc) | EPICS IOC for the zPSC |
| [ALSu_First_Article_PSC](https://github.com/capotosto/ALSu_First_Article_PSC) | ALSu PSC first-article calibration and test scripts, calibration and test reports, and related files |
| [ALSu-PSC_ATE-ioc](https://github.com/capotosto/ALSu-PSC_ATE-ioc) | EPICS IOC for the ALSu PSC automated test equipment (ATE) | 

## AR/BTA Production Unit Repositories

The following repositories were used for calibration and testing of the AR/BTA production PSC units. Many fuctions will not work with newer firmware versions than the version shipped on SD cards during the AR/BTA production (Firmware version likely from November-December)

### Calibration

[ALSu-PSC_CAL](https://github.com/dibergman/ALSu-PSC_CAL)

Used for **calibration of the AR/BTA production units**.

### Production Test

[ALSU-PSC-CAL-AND-TEST-SUITE](https://github.com/capotosto/ALSU-PSC-CAL-AND-TEST-SUITE)

Used for **TEST ONLY** on the AR/BTA production units. 

> **Important:** Do **not** use `ALSU-PSC-CAL-AND-TEST-SUITE` for calibration.  
> Calibration of the AR/BTA production units should be performed using `ALSu-PSC_CAL`, with the `pscCALdib.py` script.

## Repository Overview

```text
ALSu Power Supplies Software
│
├── Current / Working Software
│   ├── pdu-ioc
│   ├── zpsc-fw
│   ├── zpsc-ioc
│   ├── ALSu_First_Article_PSC
│   └── ALSu-PSC_ATE-ioc
│
└── AR/BTA Production Units
    ├── Calibration
    │   └── ALSu-PSC_CAL
    │
    └── Test
        └── ALSU-PSC-CAL-AND-TEST-SUITE
