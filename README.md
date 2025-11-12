![GitHub release (latest by date)](https://img.shields.io/github/v/release/stofakiller/FuelpricesNEW_DK)
![GitHub last commit](https://img.shields.io/github/last-commit/stofakiller/FuelpricesNEW_DK)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/stofakiller/FuelpricesNEW_DK)
[![Buy me a coffee](https://img.shields.io/static/v1.svg?label=Buy%20me%20a%20coffee&message=🥨&color=black&logo=buy%20me%20a%20coffee&logoColor=white&labelColor=6f4e37)](https://www.buymeacoffee.com/20205255)

Forked from J-Lindvig, he did a very good job, but sadly not maintained any longer...

Link: https://github.com/J-Lindvig/Fuelprices_DK

# EVprices DK
## Introduction
With EVprices DK it is possible to track EVprices in Denmark.

## Installation
At this ealy stage, it's by adding this repository manual in HACS...

## Configuration
EVcompanies:
- EV-EL
- Eviny
- NRGi
- Recharge
- Uno-X
- Tesla
- Norlys
- OK
- Shell/DCC
- Ionity
- CircleK
- Q8
- PowerGo
- Stella
- EDF
- E.ON
- EWII
- Allego
- FastNed
- Clever


From this - soo far - EVtype:
- Electric

  
## Configuration
```yaml
fuelprices_dk:
  # Optional entries
  # Bypass the default update interval (60 minutes)
  update_interval: 300
  companies:
  # possible values are: circlek, goon, ingo, ok and q8
    - ok
    - q8
  fueltypes:
  # Possible values are: oktan 95, oktan 95+, oktan 100, diesel, diesel+ and electric
    - oktan 95
    - diesel
    - electric
```
