# ventil-8

## Open-source ventilation assistance device project developed by Griffith 

** Please check with your local medical oficials before use.**


### General

For distribution and use to assist medical professionals with:

* Continuous positive airway pressure (CPAP), 
* Non-invasive Ventilation (NIV), and 
* Ventilation via intubation (potentially) 

![CAD file](/images/cad1.png)
<img align="left" width="100" height="100" src="/images/cad1.png">

Adjustments available:

1. **Breaths Per Minute (BPM)** - adjustment of PWM controller knob next to Power supply unit will increade/decrease speed of motor, therefore adjusting breathing frequency.
1. **Tidal Volume (Vt)** - the volume of air inhalation and exhalation can be adjusted with the lower platform level underneath the bag. A range of pre-determined adjustment positions provided via pins and locating holes on the back end of machine.
1. **Inspiratory/Expiratory (I/E) ratio** - three separate mechanical cams are provided for different ratios:
   * 1:2
   * 1:3
   * 2:3


### Motor
Any automotive windscreen wiper motor. Toyota sedan model used in CAD files and images.


### Powersupply and speed control 

[PWM Controller to adjust Breaths per Minute](https://www.jaycar.com.au/12vdc-8a-dimmer-motor-speed-controller/p/MP3209)

[Power supply unit (PSU) from personal computer](https://www.electronics-tutorials.ws/blog/convert-atx-psu-to-bench-supply.html)

A single 12V PSU connection was used from Molex connector. PSU case must be seperated from main ventilator case (if made of metal) using nylon washers or equivalent.
