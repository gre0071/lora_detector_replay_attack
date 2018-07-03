## THIS MODULE IS CURRENTLY UNDER DEVELOPMENT
---

---
# README
# LoRaWAN Detection - Replay attack ABP
This detector serves for detection replay attack in LoRaWAN infrastructure of ABP authentication method. ....

## Description

## Interfaces
- Input: One UniRec interface
Template must contain fields TIMESTAMP, PHY_PAYLOAD.

- Output: One UniRec interface
Template contain this fields DEV_ADDR, TIMESTAMP, FCNT.
  
## Parameters
### Common TRAP parameters
- `-h [trap,1]`      Print help message for this module / for libtrap specific parameters.
- `-i IFC_SPEC`      Specification of interface types and their parameters.
- `-v`               Be verbose.
- `-vv`              Be more verbose.
- `-vvv`             Be even more verbose.
