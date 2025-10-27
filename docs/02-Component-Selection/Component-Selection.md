---
title: Component Selection Example
---

**IR Distance Sensor**

| **Solution**                                                                                                                                                                                      | **Pros**                                                                                                                                    | **Cons**                                                                                            |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| ![](image.png)<br>Option 1.<br> TSSP53038 SENSOR OPT 940NM IR RADIAL 3 <br>$0.84/each<br>[link to product](https://www.digikey.com/en/products/detail/vishay-semiconductor-opto-division/TSSP53038/20379937)                 | \* Inexpensive<br>\* Falls under voltage constraints<br>\* Easy to mount to PCB                                               | \* Requires external components and support circuitry for interface<br>\* Needs special PCB layout. |
| ![](image-1.png)<br>\* Option 2. <br>\* CTX936TR-ND surface mount oscillator <br>\* $1/each <br>\* [Link to product](http://www.digikey.com/product-detail/en/636L3I001M84320/CTX936TR-ND/2292940) | \* Outputs a square wave <br>\* Stable over operating temperature <br> \* Direct interface with PSoC (no external circuitry required) range | * More expensive <br>\* Slow shipping speed                                                         |
| ![](image-2.png)<br>\* Option 3. <br>\* SEN0413 SENSOR OPT 850NM IR MODULE <br>\* $19.90/each <br>\* [Link to product](https://www.digikey.com/en/products/detail/dfrobot/SEN0413/14322644) | \* Outputs a square wave <br>\* Stable over operating temperature <br> \* Direct interface with PSoC (no external circuitry required) range | * More expensive <br>\* Slow shipping speed                                                         |

**Choice:** Option 2. TSSP53038 SENSOR OPT 940NM IR RADIAL 3

**Rationale:** This sensor is both the cheapest and easiest to work with.

**Audio Amp**

| **Solution**                                                                                                                                                                                      | **Pros**                                                                                                                                    | **Cons**                                                                                            |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| ![](image-3.png)<br>Option 1.<br> PAM8302AADCR IC AMP CLASS D MONO 2.5W 8SOP <br>$0.48/each<br>[link to product](https://www.digikey.com/en/products/detail/diodes-incorporated/PAM8302AADCR/4033280)                 | \* Inexpensive<br>\* Falls under voltage constraints<br>\*                                                | \* Surface mounted component<br>\* Needs special PCB layout. |
| ![](image-1.png)<br>\* Option 2. <br>\* CTX936TR-ND surface mount oscillator <br>\* $1/each <br>\* [Link to product](http://www.digikey.com/product-detail/en/636L3I001M84320/CTX936TR-ND/2292940) | \* Outputs a square wave <br>\* Stable over operating temperature <br> \* Direct interface with PSoC (no external circuitry required) range | * More expensive <br>\* Slow shipping speed                                                         |
| ![](image-2.png)<br>\* Option 3. <br>\* SEN0413 SENSOR OPT 850NM IR MODULE <br>\* $19.90/each <br>\* [Link to product](https://www.digikey.com/en/products/detail/dfrobot/SEN0413/14322644) | \* Outputs a square wave <br>\* Stable over operating temperature <br> \* Direct interface with PSoC (no external circuitry required) range | * More expensive <br>\* Slow shipping speed                                                         |

**Choice:** Option 1. PAM8302AADCR IC AMP CLASS D MONO 2.5W 8SOP

**Rationale:** This Audio amp is the only one I could find that fell within the desired voltage constraints.


**Speaker**

| **Solution**                                                                                                                                                                                      | **Pros**                                                                                                                                    | **Cons**                                                                                            |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| ![](image-3.png)<br>Option 1.<br> PAM8302AADCR IC AMP CLASS D MONO 2.5W 8SOP <br>$0.48/each<br>[link to product](https://www.digikey.com/en/products/detail/diodes-incorporated/PAM8302AADCR/4033280)                 | \* Inexpensive<br>\* Falls under voltage constraints<br>\*                                                | \* Surface mounted component<br>\* Needs special PCB layout. |
| ![](image-1.png)<br>\* Option 2. <br>\* CTX936TR-ND surface mount oscillator <br>\* $1/each <br>\* [Link to product](http://www.digikey.com/product-detail/en/636L3I001M84320/CTX936TR-ND/2292940) | \* Outputs a square wave <br>\* Stable over operating temperature <br> \* Direct interface with PSoC (no external circuitry required) range | * More expensive <br>\* Slow shipping speed                                                         |
| ![](image-2.png)<br>\* Option 3. <br>\* SEN0413 SENSOR OPT 850NM IR MODULE <br>\* $19.90/each <br>\* [Link to product](https://www.digikey.com/en/products/detail/dfrobot/SEN0413/14322644) | \* Outputs a square wave <br>\* Stable over operating temperature <br> \* Direct interface with PSoC (no external circuitry required) range | * More expensive <br>\* Slow shipping speed                                                         |

**Choice:** Option 1. PAM8302AADCR IC AMP CLASS D MONO 2.5W 8SOP

**Rationale:** This Audio amp is the only one I could find that fell within the desired voltage constraints.


**Op-Amp**

| **Solution**                                                                                                                                                                                      | **Pros**                                                                                                                                    | **Cons**                                                                                            |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| ![](image-3.png)<br>Option 1.<br> PAM8302AADCR IC AMP CLASS D MONO 2.5W 8SOP <br>$0.48/each<br>[link to product](https://www.digikey.com/en/products/detail/diodes-incorporated/PAM8302AADCR/4033280)                 | \* Inexpensive<br>\* Falls within voltage constraints<br>\* Does not generate much heat                          | \* Surface mounted component<br>\* Needs special PCB layout. |
| ![](image-4.png)<br>\* Option 2. <br>\* IS31AP4991A-GRLS2-TR IC AMP CLASS AB MONO 1.15W 8SOIC <br>\* $0.41/each <br>\* [Link to product](https://www.digikey.com/en/products/detail/lumissil-microsystems/IS31AP4991A-GRLS2-TR/5319733) | \* Great sound quality <br>\* Falls within voltage constraints <br> \* Inexpensive | \* Moderate heat generation <br>\* Slow shipping speed                                                         |
| ![](image-2.png)<br>\* Option 3. <br>\* SEN0413 SENSOR OPT 850NM IR MODULE <br>\* $19.90/each <br>\* [Link to product](https://www.digikey.com/en/products/detail/dfrobot/SEN0413/14322644) | \* Outputs a square wave <br>\* Stable over operating temperature <br> \* Direct interface with PSoC (no external circuitry required) range | * More expensive <br>\* Slow shipping speed                                                         |

**Choice:** Option 1. PAM8302AADCR IC AMP CLASS D MONO 2.5W 8SOP

**Rationale:** This audio amp is the class D amplifier I could find that fell within the desired voltage constraints.

**Voltage Regulator**

| **Solution**                                                                                                                                                                                      | **Pros**                                                                                                                                    | **Cons**                                                                                            |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| ![](image-3.png)<br>Option 1.<br> AP7375-33SA-7 IC REG LIN 3.3V 300MA SOT23-3 <br>$0.48/each<br>[link to product](https://www.digikey.com/en/products/detail/diodes-incorporated/PAM8302AADCR/4033280)                 | \* Inexpensive<br>\* Falls under voltage constraints<br>\*                                                | \* Surface mounted component<br>\* Needs special PCB layout. |
| ![](image-1.png)<br>\* Option 2. <br>\* CTX936TR-ND surface mount oscillator <br>\* $1/each <br>\* [Link to product](http://www.digikey.com/product-detail/en/636L3I001M84320/CTX936TR-ND/2292940) | \* Outputs a square wave <br>\* Stable over operating temperature <br> \* Direct interface with PSoC (no external circuitry required) range | * More expensive <br>\* Slow shipping speed                                                         |
| ![](image-2.png)<br>\* Option 3. <br>\* SEN0413 SENSOR OPT 850NM IR MODULE <br>\* $19.90/each <br>\* [Link to product](https://www.digikey.com/en/products/detail/dfrobot/SEN0413/14322644) | \* Outputs a square wave <br>\* Stable over operating temperature <br> \* Direct interface with PSoC (no external circuitry required) range | * More expensive <br>\* Slow shipping speed                                                         |

**Choice:** Option 1. PAM8302AADCR IC AMP CLASS D MONO 2.5W 8SOP

**Rationale:** This Audio amp is the only one I could find that fell within the desired voltage constraints.
