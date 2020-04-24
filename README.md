# ventil-8

### Open-source ventilation assistance device project developed by Griffith 

#### General

** Please check with your local medical oficials before use.**

For distribution and use to assist medical professionals with:

* Continuous positive airway pressure (CPAP), 
* Non-invasive Ventilation (NIV), and 
* Ventilation via intubation (potentially) 

![GitHub Logo](/images/cad1.PNG)
Format: ![Alt Text](url)

Adjustments available:

1. Breaths Per Minute (BPM) - adjustment of PWM controller knob next to Power supply unit will increade/decrease speed of motor, therefore adjusting breathing frequency.
1. Tidal Volume (Vt) - the volume of air inhalation and exhalation can be adjusted with the lower platform level underneath the bag. A range of pre-determined adjustment positions provided via pins and locating holes on the back end of machine.
1. Inspiratory/Expiratory (I/E) ratio - three cams are provided for different ratios:
  1. 1:1
  1. 1:1.5
  1. 1:3



#### Powersupply and speed control 

PWM Controller to adjust Breaths per Minute

https://www.jaycar.com.au/12vdc-8a-dimmer-motor-speed-controller/p/MP3209

Powersupply made from any cheap computer PSU

https://www.electronics-tutorials.ws/blog/convert-atx-psu-to-bench-supply.html

A single 12V PSU connection was used from Molex connector. PSU case must be seperated from main ventilator case (if made of metal)
using nylon washers or equiv.
