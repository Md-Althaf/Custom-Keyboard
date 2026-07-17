---

title: "CUSTOM KEYBOARD"
author: "BOSE-NOVA"
description: "A custom mechanical keyboard designed  custom PCB, gasket-style case, and hand-wired microcontroller connections."
created_at: "2026-03-20"
------------------------

# 7/15/2026 9 PM - PCB & Case Adjustments

*Time spent: 3h*

Made the 3D case in Fusion 360. I decided to make a gasket-style case for a better typing experience.

I also updated the PCB by moving the SMD test points to the bottom and side of the board to make hand wiring the ESP32 much easier.

Initially, I redesigned the PCB to include addressable RGB LEDs, but I couldn't find a supplier that would ship them to my location. Because of that, I removed the LEDs from the design.

Unfortunately, KiCad crashed while I was rerouting the LED connections, and I lost around 40 minutes of work before recreating the changes.

https://lapse.hackclub.com/timelapse/sDkY3A9fhBC6

https://lapse.hackclub.com/timelapse/Y7V1vSpsZyBa

![image](image5.png)

![image](image.png)

---

# 7/4/2026 7 PM - Added Test Points

*Time spent: 20min*

Instead of soldering the ESP32 module directly onto the PCB, I decided to hand-wire it. To make this easier, I added SMD test points for every required connection.

The schematic and PCB footprints were updated to include these test points, making future assembly and debugging much simpler.

https://lapse.hackclub.com/timelapse/g559EpPcmXS4

https://lapse.hackclub.com/timelapse/MvN9gA9qz5nX

![image](image4.png)

---

# 7/1/2026 8 PM - Added Addressable LEDs

*Time spent: 3h*

Added addressable RGB LEDs to the keyboard schematic and completed placing all of their footprints on the PCB.

The LEDs were planned to provide per-key RGB lighting and improve the overall look of the keyboard.

https://lapse.hackclub.com/timelapse/sIvgukwVfNVC

![image](image3.png)

---

# 6/27/2026 6 PM - PCB Layout

*Time spent: 3h*

Started designing the PCB by placing all the switch footprints and diode footprints in their correct locations.

After arranging the components, I completed a good portion of the PCB routing and verified that the keyboard matrix connections were correct.

https://lapse.hackclub.com/timelapse/0YRYZKXZWah4

![image](image2.png)

---

# 6/24/2026 10 PM - Schematic Design

*Time spent: 30min*

Completed the keyboard schematic in KiCad.

Finished arranging all the keys, completed the annotation process, and connected the entire keyboard matrix to the ESP32 microcontroller. With the schematic complete, the project was ready for PCB layout.

![image](image1.png)

https://lapse.hackclub.com/timelapse/mBDHRPWSP0uq

https://lapse.hackclub.com/timelapse/3Ntblb2Ck1Zb
