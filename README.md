# 12KEMP
12KEMP is a 12 key 4 by 3 macropad, that features an Arduino Pro Micro with vial-qmk support, a rotary encoder, and a custom pcb with support for 3/5-pin switches.
All PCB files are in this repo, and you may create any form of case to mount the pcb onto. Additionally, a bill of materials (BOM) is included. This project does require soldering.

![12KEMP Image](https://d4h2y4j1ag16u.cloudfront.net/12KEMP/12KEMP.jpg#)
P.S. My keys look a little bit wonky since I used some 3-pin switches I had laying around. 5-pin switches are preferred since they are already aligned.

# [Gerber Download](https://d4h2y4j1ag16u.cloudfront.net/12KEMP/12KEMPGerbers.zip)

# Bill of Materials

> 1. Qty. 1 [Arduino Pro Micro](https://www.amazon.com/diymore-ATmega32U4-Replace-ATmega328-Leonardo/dp/B01KJR41J4/ref=sr_1_7?crid=2TV1OV7X80R84&dib=eyJ2IjoiMSJ9.jKYez29mK6YK_f88w-bgz3mYgCO3U3ROUKi0wRmtN2kDuCeBVRQpC_ccrqG2pYjG2s_7hehBz2tWRilt03edBe30PSgfh7yMx-AH5YFJlQzmBc1oBAz5di5YIxvEaDWW3IQMuuvNOEwT4wzSnCYAyABNuGAy4x8eTRF2ibkGfM5qGxep7NiMdLiKxkcrSfIW_Kh1h9zkkntEETOG11ksWR9l-3sSsmbHMOWphog07v4.Wwd1CEMn-VoI6fzyggWqVfDeRN28I6T6iWlPUQWukNk&dib_tag=se&keywords=arduino+pro+micro&qid=1710992664&sprefix=arduino+pro+micro%2Caps%2C168&sr=8-7)
> 2. Qty. 1 [Rotary Encoder](https://www.digikey.com/en/products/detail/bourns-inc/PEC12R-4020F-S0024/4699271)
> 3. Qty. 1 [Headers](https://www.digikey.com/en/products/detail/cnc-tech/220-1-24-006/3441519) --- (Only required if Pro Micro doesn't come with some.) 
> 4. Qty. 12 MX Switches --- Any 3/5-pin MX switch you would like. 5-pins are recommeded.
> 5. Qty. 1 PCB --- For mine, I used JLCPCB. It cost around 10 dollars for the pcb and shipping. Took about two weeks to finish manufacturing and arrival. You may use any other service you would like for a pcb (Gerbers are linked above).
> 6. Qty. 12 Keycaps --- Any Cherry MX style keycap will do.
> 7. Qty. 1 Encoder Knob --- This can be 3D printed or bought online. Make sure its for a 6mm "D" shape encoder.

# Firmware

To install firmware on the Arduino Pro Micro, you can use [QMK Toolbox](https://github.com/qmk/qmk_toolbox).
1. Download and install [QMK Toolbox](https://github.com/qmk/qmk_toolbox)
2. Download the [firmware](https://d4h2y4j1ag16u.cloudfront.net/12KEMP/12KEMP.hex)
3. Plug in your Pro Micro into your computer
4. Open QMK Toolbox and load
5. After the keyboard reboots, it should be configurable in [Vial](https://get.vial.today)

# Credits
Kudos to:<br>
[Jeroen94704's "klepcbgen"](https://github.com/jeroen94704/klepcbgen)<br>
[Contributors of the "vial-qmk" repo](https://github.com/vial-kb/vial-qmk)<br>
[xwing's Rotary Encoder Knob](https://www.printables.com/model/168924-rotary-encoder-knob/comments/1590018)
