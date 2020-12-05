# g305-re

![g305](https://resource.logitechg.com/e_trim/w_652,ar_4:3,c_limit,q_auto:best,f_auto/w_692,h_519,c_lpad,b_rgb:2f3132,dpr_auto/content/dam/gaming/en/products/g305/g305-gallery-1.png?v=1)

Reverse engineering of the [G305](https://www.logitechg.com/en-us/products/gaming-mice/g305-lightspeed-wireless-gaming-mouse.910-005280.html) mouse by [Logitech](https://www.logitech.com/en-us)

### Specs

| Spec | Range | Unit |
|:--|--:|:-:|
| DPI | 200 - 12000 | - |
| Max acceleration | 40 | g |
| Max Tracking speed | 400 | I/s |
| Report Rate | 1 | kHz |
| Processor Core | 32-bit ARM | - |
| Claimed Battery Life | 250 | hours |

#### Eletrical Characteristics


| Characteristic | Range | Unit |
|:--|--:|:-:|
| Active Power | 10 | mW |
| Idle Power * | 4 | mW |
| Deep Sleep Power ** | 200 | uW |
| Turn On Voltage *** | 1.35 | V |
| Max Voltage **** | 4.8 | V |

```
     * No movement
    ** After approximately 90 seconds idle 
   *** Below this voltage the device is consistently unable to start
  **** The device can tolerate more (tested up to 5.5V), but above 4.8V it seems to
            consume unusually high power during Deep Sleep
```
`These are rough conservative approximations (though measured with fairly good equipment). Measurements on a single personal device.`

#### Expected Battery Life

| Battery | Weight [g] | Nominal Voltage [V] | Capacity [mAh] | Capacity [mWh] | Active Battery Life [h] |
|:--|--:|--:|--:|--:|--:|
| ALkaline LR6 (AA) | | 1.5 | 1800 – 2850 | 2700 - 4275 | 270 - 428 |
| ALkaline LR03 (AAA) | | 1.5 | 860 – 1200 | 1290 - 1800 | 129 - 180 |
| Lithium 14500 (AA) | | 3.6 | 600 - 840 (1600 @ 1.5V) | 2160 - 3024 (2400 @ 1.5V) | 216 - 302 |
| Lithium 10440 (AAA) | | 3.6 | 350 | 1260 | 126 |
| PR675 | 1.85 | 1.4 | 550 - 600 | 770 - 840 | 77 - 84 |
| Super Capacitor 70F | | 2.7 | - | - | 5.83 |
| Super Capacitor 30F | | 2.7 | - | - | 2.5 |

[source](https://en.wikipedia.org/wiki/AAA_battery), [source](https://en.wikipedia.org/wiki/AA_battery)

