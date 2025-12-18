<div align="center">
  <img width="1500" height="900" alt="Anicept Cel Title Image" src="https://github.com/user-attachments/assets/6fb595c3-2b03-4d57-a414-f163f46c0cf4" />

  <h2>By Anicetus</h2>

  <p display="inline">
  
  <a href="https://creativecommons.org/licenses/by-nc/4.0/">
    <img src="https://licensebuttons.net/l/by-nc/4.0/88x31.png" alt="Creative Commons Attribution-NonCommercial 4.0 International License"></a> <a href="https://hackclub.com/highway">
    <img alt="Funded by Hack Club" src="https://img.shields.io/badge/Hack_Club-Funded-ec3750?style=for-the-badge&logo=hackclub&logoColor=ec3750"></img>
  </a>

  </p>

  <h4>A tiny yet mighty, sturdy and swift 3D printer, designed and optimized to run at tremendous speeds.</h4>
</div>

<sub>This work is licensed under a
[Creative Commons Attribution-NonCommercial 4.0 International License](https://creativecommons.org/licenses/by-nc/4.0/).
</sub>

## Table of Contents

- [About](#about)
- [Features and Specifications](#features-and-specifications)
- [Assembly](#assembly)
- [Bill of Materials](#bill-of-materials)
- [Contributing](#contributing)

# About

Well, here we go again. My name is Anicetus, and this is my second 3D printer design to date. The first flopped miserably, due to numerous issues in the design phase that either I overlooked or missed due to a lack of research.

Not this time.

This time, I'm making a _real_ printer. Not just another mid ender 3 clone, this is (or should be; as I'm writing this I haven't built it lol) something special. But let's start with the name, shall we? It's called the Anicept Cel. The first part is easy enough to explain--any dedicated hardware enthusiast should have a brand name. Anicept is a combination of Anicetus and concept, and I like how it feels. As for Cel, it's my newfound custom to name my printers with three-letter words. I took Cel from the Latin word celer, or "fast". Maybe that tells you a bit about what I was going for here.

That's right, this printer is made for speed. Everything about it, from the head to the feet (ha) was specifically bent on pure speed. Of course, I'm not an infinite money generator, so I had limits. But not _that_ many limits.

# Features and Specifications

- 180 x 180 x 160 mm print size, plenty for almost all applications
- 300°C max printing temp
- Uses the Peopoly Lancer Long Melt Zone hotend, capable of up to 60mm<sup>3</sup>/s flow rate
- Powerful sheet cooling, best for PETG and ABS/ASA, with the use of two 5020 part cooling fans
- Uses the CR-Touch, one of the most precise (and expensive lol) ABL probes available
- All-4040 extrusion frame, increasing sturdiness exponentially
- MGN12H rails all-around, minimizing wobble
- AWD (all wheel drive) on both Y and X axes, exponentially increasing its power
- Belted Z axis
- Separate electronics enclosure, for ease of use/assembly and to allow enclosing the main printer
- Extra 48V PSU for motors only, increasing their torque
- 9mm belt on X and Y axes
- Uses the powerful Octopus Pro mainboard, equipped with TMC5160T Pros for the X and Y axes
- Uses the Protoextruder, an open-source, DIY filament extruder
- Compatible with the Pico MMU and filament cutter, enabling 4-color and multimaterial printing

# Assembly

coming soon...

# Bill of Materials

Very WIP!! Also this is my personal BOM, like what I own and don't own. Aliexpress prices subject to change _violently_.

|Item                                      |Link                                                                                   |Alt link                                            |Cost   |Quantity|Extended Cost|Notes                                 |
|------------------------------------------|---------------------------------------------------------------------------------------|----------------------------------------------------|-------|--------|-------------|--------------------------------------|
|Electronics                               |$172.85                                                                                |                                                    |       |        |             |                                      |
|24V 600W PSU                              |https://www.digikey.com/en/products/detail/mean-well-usa-inc/LRS-600-24/16394242       |                                                    |$70.00 |1       |$0.00        |Owned                                 |
|48V 480W PSU                              |https://www.amazon.com/REALSUN-Universal-Switching-Converter-Transformer/dp/B096VJMQFM/|                                                    |$26.99 |1       |$26.99       |                                      |
|BigTreeTech Octopus Pro + TMC5160T Pro x 4|https://www.aliexpress.us/item/3256803375036597.html                                   |                                                    |$100.26|1       |$100.26      |                                      |
|TMC2209                                   |https://www.aliexpress.us/item/3256805074646808.html                                   |                                                    |$0.99  |4       |$3.96        |                                      |
|24v 4010 Axial Fan                        |https://www.aliexpress.us/item/3256803185681643.html                                   |                                                    |$0.99  |1       |$0.99        |(2 pcs needed, 1 owned)               |
|RPi 4B 1GB RAM                            |https://www.ebay.com/itm/167900769294                                                  |                                                    |$24.99 |1       |$24.99       |                                      |
|Power inlet                               |https://www.aliexpress.us/item/3256806175041706.html                                   |                                                    |$1.53  |1       |$0.00        |Owned                                 |
|Power cord                                |https://www.aliexpress.us/item/3256802936747637.html                                   |                                                    |$2.61  |1       |$0.00        |Owned                                 |
|On button                                 |https://www.adafruit.com/product/481                                                   |                                                    |$4.95  |1       |$0.00        |Owned                                 |
|Heated bed                                |https://www.aliexpress.us/item/3256807101964868.html                                   |                                                    |$14.67 |1       |$14.67       |2M cable?                             |
|1M 13mm Wire sleeve                       |https://www.aliexpress.us/item/3256802043851957.html                                   |                                                    |$0.99  |1       |$0.99        |                                      |
|Zip ties                                  |                                                                                       |                                                    |$2.00  |1       |$0.00        |Owned                                 |
|12AWG Wire                                |https://www.aliexpress.us/item/3256806250298216.html                                   |                                                    |$0.99  |1       |$0.99        |2 M - 1m red, 1m black                |
|12AWG Fork Connectors (18 min)            |https://www.aliexpress.us/item/3256805357612913.html                                   |                                                    |$0.99  |1       |$0.99        |8mm outer width, >= 4mm ID            |
|12AWG Female Fork Connectors              |                                                                                       |                                                    |$0.99  |3       |$0.00        |Owned                                 |
|Frame                                     |$91.47                                                                                 |                                                    |       |        |             |                                      |
|4040 x 600mm extrusion (4 pack)           |https://www.amazon.com/gp/product/B09MYL6XMY/                                          |                                                    |$62.99 |1       |$62.99       |Self-cut                              |
|2020 x 250mm extrusion                    |https://www.aliexpress.us/item/3256803124984194.html                                   |https://www.aliexpress.us/item/3256804493383834.html|$7.10  |1       |$7.10        |                                      |
|T Plates                                  |https://www.aliexpress.us/item/3256806516993865.html                                   |https://www.aliexpress.us/item/3256806574844240.html|$7.91  |1       |$7.91        |                                      |
|Bed plate                                 |https://www.aliexpress.us/item/3256802956143480.html                                   |                                                    |$12.48 |1       |$12.48       |                                      |
|M5 Tap                                    |https://www.aliexpress.us/item/3256805979008585.html                                   |                                                    |$0.99  |1       |$0.99        |                                      |
|Tap Wrench                                |https://www.aliexpress.us/item/3256808061844390.html                                   |                                                    |$0.99  |1       |$0.99        |                                      |
|Motion                                    |$41.74                                                                                 |                                                    |       |        |             |                                      |
|X/Y Motors                                |https://www.aliexpress.us/item/2255801033887365.html                                   |                                                    |$22.55 |1       |$0.00        |Owned                                 |
|MGN12H x 250                              |https://www.aliexpress.us/item/2255800576028509.html                                   |                                                    |$9.05  |3       |$27.15       |(owned: 2, total qty: 5)              |
|9mm 2GT Belt                              |https://www.aliexpress.us/item/3256806321466333.html                                   |                                                    |$13.35 |1       |$0.00        |Owned                                 |
|16T 10W 5B Pulley (5 pcs)                 |https://www.aliexpress.us/item/2251832595367020.html                                   |                                                    |$0.99  |1       |$0.99        |                                      |
|20T 10W 5B Pulley                         |                                                                                       |                                                    |       |2       |$0.00        |Y axis, owned                         |
|605 (5x14x5) Bearing (10pcs)              |https://www.aliexpress.us/item/3256807482131308.html                                   |                                                    |$0.99  |1       |$0.99        |4 Owned, 10 to buy                    |
|Z axis                                    |                                                                                       |                                                    |       |        |             |                                      |
|Motors                                    |https://www.aliexpress.us/item/3256808273084374.html                                   |                                                    |$2.46  |2       |$4.92        |                                      |
|80T - 20T pulley, 200mm belt reduction kit|https://www.aliexpress.us/item/3256808844764521.html                                   |                                                    |$1.37  |2       |$2.74        |                                      |
|20T 6W 5B Pulley                          |https://www.aliexpress.us/item/3256806031359840.html                                   |                                                    |$0.99  |1       |$0.99        |(owned: 1, total qty: 2)              |
|20T 6W 5B Idler                           |https://www.aliexpress.us/item/2251832631013486.html                                   |                                                    |$0.99  |2       |$1.98        |                                      |
|6mm 2GT belt (2M)                         |https://www.aliexpress.us/item/3256806321466333.html                                   |                                                    |$0.99  |1       |$0.99        |                                      |
|M5x45 Dowel pin                           |https://www.aliexpress.us/item/3256806837028480.html                                   |                                                    |$0.99  |1       |$0.99        |(6 pcs min, self cut)                 |
|Printhead                                 |$85.45                                                                                 |                                                    |       |        |             |                                      |
|Orbiter V2.0/V2.5                         |https://www.aliexpress.us/item/3256807258760130.html                                   |                                                    |$34.28 |1       |$0.00        |Owned                                 |
|Peopoly Lancer Long Melt Zone             |https://peopoly.net/products/magneto-x-lancer-melt-zone                                |                                                    |$58.00 |1       |$58.00       |                                      |
|5020 Fan (2pcs)                           |https://www.aliexpress.us/item/3256807407728580.html                                   |                                                    |$9.53  |1       |$9.53        |                                      |
|CR Touch                                  |https://www.aliexpress.us/item/3256806043295649.html                                   |                                                    |$14.95 |1       |$14.95       |                                      |
|Microswitch (3pcs; 2pcs used for X+Y axes)|https://www.aliexpress.us/item/3256804568049753.html                                   |                                                    |$0.99  |1       |$0.99        |                                      |
|ADXL345                                   |https://www.aliexpress.us/item/3256806996565152.html                                   |                                                    |$2.33  |1       |$0.00        |Owned                                 |
|3010 Heat Sink Cooling Fan                |https://www.aliexpress.us/item/3256803185681643.html                                   |                                                    |$0.99  |1       |$0.00        |Owned                                 |
|Filament Cutter + Sensor                  |                                                                                       |                                                    |       |        |             |                                      |
|4mm OD 2mm ID PTFE Tube                   |https://www.aliexpress.us/item/3256806056618135.html                                   |                                                    |$2.01  |1       |$0.00        |Owned                                 |
|Exacto Knife #11 Blade                    |https://www.aliexpress.us/item/3256808331067380.html                                   |                                                    |$0.99  |1       |$0.99        |                                      |
|4mm Ball Bearing                          |https://www.aliexpress.us/item/3256803905354831.html                                   |                                                    |$0.99  |1       |$0.99        |                                      |
|Fasteners and Miscellaneous               |$16.10                                                                                 |                                                    |       |        |             |EXACT SCREW NEEDS ARE WIP!            |
|Nozzle wiper                              |https://www.aliexpress.us/item/3256807315758369.html                                   |                                                    |$0.99  |1       |$0.99        |                                      |
|M3x22 SHCS                                |                                                                                       |                                                    |       |4       |$0.00        |Owned                                 |
|M3x30 SHCS                                |                                                                                       |                                                    |       |4       |$0.00        |Owned                                 |
|M3x8 SHCS                                 |                                                                                       |                                                    |       |7       |$0.00        |Owned                                 |
|M3x6 SHCS                                 |                                                                                       |                                                    |$0.99  |1       |$0.99        |for the electronics box               |
|M3x14 SHCS                                |                                                                                       |                                                    |       |12      |$0.00        |Owned                                 |
|M4x12 FHCS                                |                                                                                       |                                                    |       |6       |$0.00        |for the bed & X axis tensioner (owned)|
|M5x50 SHCS                                |https://www.aliexpress.us/item/2255800598515019.html                                   |                                                    |       |40      |$3.96        |                                      |
|M5x14 SHCS                                |https://www.aliexpress.us/item/2255800598515019.html                                   |                                                    |       |10      |$0.99        |(Total 22, owned 12)                  |
|2020 M3 T Nuts (50 pcs)                   |https://www.aliexpress.us/item/3256807638725964.html                                   |                                                    |       |1       |$0.99        |                                      |
|2020 M5 T Nuts (50 pcs)                   |https://www.aliexpress.us/item/2251832778465720.html                                   |                                                    |       |1       |$0.99        |                                      |
|M5 Two-Stage Drill Bit                    |https://www.aliexpress.us/item/3256805825438819.html                                   |                                                    |$6.20  |1       |$6.20        |                                      |
|M3x4mm 5mm OD inserts                     |https://www.aliexpress.us/item/3256803396040989.html                                   |                                                    |$0.99  |1       |$0.99        |                                      |
|M4x8mm 6mm OD inserts                     |                                                                                       |                                                    |       |        |$0.00        |Owned                                 |
|M5x8mm 7mm OD inserts                     |https://www.aliexpress.us/item/3256803396040989.html                                   |                                                    |$0.99  |1       |$0.99        |                                      |
|Total                                     |                                                                                       |                                                    |       |        |$411.57      |                                      |
|Tax                                       |                                                                                       |                                                    |       |        |$33.95       |                                      |
|Grand Total                               |                                                                                       |                                                    |       |        |$445.52      |                                      |


# Contributing

If you'd like to request something, give feedback, or wish to make your own changes, simply open an issue on this repository or email me! (My email is in my profile.)

<img width="1506" height="847" alt="image" src="https://github.com/user-attachments/assets/878a4eb6-72db-4ee9-b3fb-e4f78bdf98f6" />

