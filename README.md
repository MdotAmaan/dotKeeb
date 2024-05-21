
# dotKeeb

A wireless ergonomic keyboard inspired by the dactyl.

![Render](assets/render.png)
>  ## Table of contents
>  - [Why?](#reasons)
>  - [Part List](#parts)
>  - [Bulid Notes](#build)

## Why? <a name="reasons"></a>

This keyboard shares most of the same benefits as other dactyl variants while being compact, and aesthetically pleasing (in my opinion). Some adjustments have also been made to accommodate those with shorter pinky fingers (More aggressive stagger, and a slight rotation and elevation to bring the keys closer).

## Part list <a name="parts"></a>

Here are the parts used in this build, along with links to where I purchased them from. I'd encourage you to try and get as much stuff from local vendors if possible.
Note that the quantities listed are for building 2 halves.

### Required
| Quantity | Part | Notes |
| -------- | ---- | -------------------------------------------------------------------------------- |
| 50 | **Choc V1 Switch** | |
| 50 | **Choc V1 Compatible Keycap** | I used MBK keycaps for my build. Other choc V1 keycaps should also work |
| 50 | **THT Diode** | |
| 2 | **nice!nano V2** | |
| 2 | **>150mAh 3.7V LiPo Battery** | LiPo batteries are the recommended type of batteries for use with the nice!nanos. Li-ion might work but you could run into issues.|
| 8 | **4mm M3 Heat-set Insert** | |
| 8 | **5mm M3 Screws** | Try to find screws with a flat head |
| ~3m | **Wire** | I used 24 AWG wire, but you can use whatever you are comfortable working with. You don't *need* 3 meters, but I'd recommend having some excess wire just in case. |

### Optional
| Quantity | Part | Notes |
| -------- | ----------------------------- | -------------------------------------------------------------------------------- |
| 50 | Choc V1 Hotswap Socket | These are only required if you build the hotswap model |
| 2 | nice!view Display | The displays aren't required for the keyboard to function |
| 2 | Power Switch | ZMK's sleep actually does a very good job of putting the keyboard to sleep and saving power, so these aren't necessary. However if you want to carry the keyboard in a bag or another place where accidental keypresses could occur, then a switch may be useful. |
| 12 | Small Rubber Feet | [These](https://www.aliexpress.us/item/3256802432366448.html) are the ones I used. There are circular cutouts for them on the base plate, but you could use anything else. |

The total part cost can range anywhere between $150 to $200 depending on various factors, like whether you choose to have displays or your shipping charges.

## Build Notes [Work in Progress] <a name="build"></a>
#### I would highly recommend watching Joe Scotto's video on [creating better hand-wired keyboards](https://www.youtube.com/watch?v=m7Q5ZjqN-ao) prior to assembly.

Follow the wiring diagram below. Note that the physical columns do not always match the columns of the circuit.
![GuideLeft](assets/guideleft.png)
![GuideRight](assets/guideright.png)
##### *nice!nano V2 and nice!view graphics were taken from https://nicekeyboards.com*

If your batteries are larger than 500mAh, bridge the pads under the board. Be careful not to put too much solder here as the plate may not close properly. **Don't bridge them if your batteries are less than 500mAh**

//*Insert image of nice nano pads*

- mention diode direction and legs
- make diagram for other side
	- include displays

