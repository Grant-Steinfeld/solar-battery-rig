# HOW TO: create your own solar powered battery charger

## What you will learn:

* how to set about how to make a solar Lithium Ion battery charger 
* what Smart Load Sharing means
* incorporate a temperature monitor, to ensure a safe setup.  Lithium Ion batteries are notoriously `volatile` and potential fire hazards.
* hack the charger to handle larger and hence, higher Wattage solar panels

  
## Architecture


## Main components used
1) Solar panel - 6 Volts 9 Watts 
1) Solar Lithium Ion Polymer Battery Charger
1) Step up `transformer` boosts the 3.7V DC LiPoly Battery to 5.2V DC
1) Thermistor temperature sensor

<details><summary><strong> Learn more about Thermistor</strong></summary>
Thermistor is a resistor that accurately records, temperature 
  
  ( Resistance goes down as it gets warmer, and goes up when it gets cooler e.g. a hot summers day, 35 degrees celcius, the resistance is 6.538 K Ohms, and on the ski slopes it may be -2 degrees celcius and the resistance will be 34.97 K Ohms) 
  
  [see the specific temp. to resistance lookup table](https://cdn-shop.adafruit.com/datasheets/103_3950_lookuptable.pdf)
  </details>




## What problem does this solve
Supply off-grid power for any 5v device ( e.g. Raspberry Pi, iPhone, Arduido)

## Instructions
Follow along this excellent Adafruit tutorial, [USB, DC & Solar Lipoly Charger by lady ada](https://learn.adafruit.com/usb-dc-and-solar-lipoly-charger)

## Shortfalls
Need sunshine ( or an incandesant light source ), but you can also wire into a 5v usb charger in case there is no sunlight.

## Video
Quick run through on the parts, and how to connect them up to create a solar recharcable battery rig,  off the shelf components


## Part list ... from Adafruit (total outlay USD $155.30)

1) Colossal 6V 9W Solar Panel (9.0 Watt) [ID:2747](https://www.adafruit.com/product/2747) = $78.95

1) USB / DC / Solar Lithium Ion/Polymer charger (v2) [ID:390](https://www.adafruit.com/product/390) = $17.50

1) PowerBoost 1000 Charger - Rechargeable 5V Lipo USB Boost @ 1A (1000C) [ID:2465](https://www.adafruit.com/product/2465) = $19.95

1) Lithium Ion Battery Pack - 3.7V 6600mAh[ID:353](https://www.adafruit.com/product/353) = $29.50

1) 10K Precision Epoxy Thermistor - 3950 NTC [ID:372](https://www.adafruit.com/product/372) = $4.00

1) 3.8 / 1.3mm or 3.5 / 1.1mm to 5.5 / 2.1mm DC Jack Adapter Cable[ID:2788](https://www.adafruit.com/product/2788) = $1.50

1) JST-PH 2-pin Jumper Cable - 100mm long [ID:4714](https://www.adafruit.com/product/4714) = $0.95

1) JST 2-pin Extension Cable with On/Off Switch - JST PH2[ID:3064](https://www.adafruit.com/product/3064) = $2.95

1) 680 Ohm resistor ( donated, thanks to Courtland ) = $0





