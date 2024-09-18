[![Donate](https://img.shields.io/badge/donate-Pizza-yellow.svg)](https://www.buymeacoffee.com/ntguest)
[![Donate](https://img.shields.io/badge/donate-Yandex-blueviolet.svg)](https://yoomoney.ru/to/410011383527168)
# JSY-MK-354
### Esphome configuration for JSY-MK-354 Three Phase AC Bi-directional Energy Meter Module Detector
![image](https://github.com/user-attachments/assets/3ba7d97d-1dfc-460b-8d7e-08f90538f2a0)

[Can buy here](https://www.aliexpress.com/item/1005007224895885.html) 


### Installation

In your own yaml file:
* Specify the Substitution section with pins used for communication;
* Add link to remote package;
* Enjoy.

  
```
substitutions:
  txpin: GPIO17
  rxpin: GPIO16

packages:
  remote_package:
    url: https://github.com/ntguest/JSY-MK-354
    ref: main
    files:
      - jsy-mk-354.yaml
```

### ToDo
* Add write to registers Voltage limit,  Current limit, Communication
