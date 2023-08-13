# Bill of materials

Quantity | Material | Link | Price (Unit)
--- | --- | --- | ---
TODO | PLA filament (or any non-flex filament) | |
TODO | Flex filament | |
7 | CAN bus cables (see below for lengths, JST-PH3 connectors) | |
7 | power cables (see below for lengths) | |
1 | Battery (12V to 44V, >= 2000mAh) with XT90 connector | | 
1 | Battery charger | |
6 | QDD 100 beta 3 (NOT beta 2) | https://mjbots.com/products/qdd100-beta-3 | $539+VAT
2 | moteus dev kits | https://mjbots.com/products/moteus-r4-11-developer-kit | $244+VAT
1 | power dist board | https://mjbots.com/products/mjbots-power-dist-r4-5b | $149+VAT
1 | pi3hat | https://mjbots.com/products/mjbots-pi3hat-r4-5 | $149+VAT
1 | Raspberri by rev 4 | | £40 to £80 depending on RAM
1 | screen for raspberri pi (TODO) | https://www.amazon.co.uk/dp/B0B455LDKH?psc=1&ref=ppx_yo2ov_dt_b_product_details | £38
1 | ~30cm ribbon cable for the screen | https://www.amazon.co.uk/dp/B075PBTQPG?ref=ppx_yo2ov_dt_b_product_details&th=1 | £3
1 | slim 80x80 computer fan, 2 pins | https://amzn.eu/d/8T4fS8s | £10
6 | 608 bearings | | <£10
TODO | M3x6 socket head machine screws | |
TODO | M3x10 socket head machine screws | |
TODO | M3x20 socket head machine screws | |
TODO | M3 heat inserts | https://amzn.eu/d/d2RtyQ6 | £7
4 | M2.5 female to female 12mm (TODO confirm) spacers | https://www.amazon.co.uk/dp/B093FQH5WS?ref=ppx_yo2ov_dt_b_product_details&th=1 | <£10
TODO | M2.5 TODO get length | maybe above link |
1 | (Optional) bluetooth keyboard and mouse | | ~£25

# 3d Print

Print all the `.stl` files. Some files have (or will have) a `.3mf` version if the print is difficult. Notes:
* The femurs and tibia print vertically. Adding a brim is recommended.
* Print the files with names starting with FLEX in flex filament.
* The tyres need to be softer than what you would get with the regular slicer settings. See the `.3mf` file, or experiment with slicer settings.
* The parts are designed to be printed with a maximum overhang threshold of 60 degrees. Anything lower may result in unwanted support (may be hard to remove).
* Files with x2 in the name need to be printed twice.

# Assembly (unfinished)
Order of operation (experimental):
Legs (x2):
* Tyre on wheelset
* Screw wheelset to motor with 3 M3x10 screws (TODO confirm length)
* bearing in wheelset
* Insert motor plate into tibia
* Attach motor with 4 M3x20 screws (TODO)
* Add and attach ankle cap with 1 M3x6 or M3x10 screw
* Attach bottom ankle cap with 2 M3x10 screws (TODO)

# Notes
Wheel radius: 80.66mm
Tibia cable length: 290mm
Femur cable length: 340mm
