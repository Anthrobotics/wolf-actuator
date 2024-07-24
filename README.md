![alt text](https://github.com/Anthrobotics/.github/blob/main/profile/images/banner.jpg?raw=true)

# wolf-actuator [V1.1]
# Description
The WOLF actuator is a high-torque 3D-printable planetary robotic actuator. The design is based on the Wolfrom PGT, and does not require a planet gear carrier or planet gear bearings. All planet gears are equally spaced, and provide a large contact area for both the sun gear and ring gears. All gears are replaceable for added modularity and easy maintenance. [Modular crossed-roller bearings](https://github.com/Anthrobotics/modular-bearing) on both ends of the actuator provide WOLF with improved load-bearing capabilities, and smoother motion. The actuator is fully-backdriveable, and is capable of compliant control and force sensing. WOLF can be manufactured using a number of methods, including FDM and SLS 3D printing, and CNC machining.

![alt text](https://github.com/Anthrobotics/.github/blob/main/profile/images/wolf-v1.1-angle-view-bw.png?raw=true)

# Improvements from V1.0
- [Modular bearings](https://github.com/Anthrobotics/modular-bearing) for easy maintenance
- Separate mounting points - no more risking actuator disassembly when mounting loads
- 67 mm height has been maintained - thin form factor
- reduced unique part count - from 14, down to 12.

# Specifications
The specs of the V1.1 WOLF actuator are as follows:
- (Theoretical) Continuous Torque: 80 Nm
- (Theoretical) Peak Torque: 120 Nm
- Reduction: 34:1
- Weight: 1.2 Kg
- Max Operating Current: 58 A
- Operating Voltage Range: 24 VDC - 52 VDC
- Diameter: 202.3 mm
- Height: 67 mm
- Encoder: AS5047P

![alt text](https://github.com/Anthrobotics/.github/blob/main/profile/images/wolf-v1.1-cross-section.png?raw=true)

# Testing
A number of tests have been performed on V1.0 of WOLF. The test model of WOLF was entirely 3D-printed using Polysonic PLA. Initial torque testing demonstrated that WOLF could output ~40.8 Nm of continuous torque, while consuming 10 A @ 30 VDC. Further testing will be performed to evaluate WOLF's performance at higher current limits, and with SLS-printed nylon gears.

The actuator was capable of rotating the entire leg of our humanoid robot approximately 75 degrees in both forward and reverse directions. The weight of the leg is ~6 Kg, and 110 cm in height. 

Test video below (redirects to YouTube):

<div align="center">
      <a href="https://www.youtube.com/watch?v=Vza2nBm8GV0">
     <img 
      src="https://img.youtube.com/vi/Vza2nBm8GV0/maxresdefault.jpg" 
      alt="Test Video" 
      style="width:100%;">
      </a>
    </div>

V1.1 testing is underway.

# Bill of Materials
You will need the following:

Printed components:
- 1x back plate
- 1x front plate
- 1x encoder magnet holder
- 1x encoder housing
- 2x internal ring gears
- 2x outer rings
- 12x planet gears
- 1x sun gear
- 2x [modular bearings](https://github.com/Anthrobotics/modular-bearing), WOLF actuator edition
- 1x planet gear alignment tool

**NOTE**: Some printable parts are labeled as *A* or *B*. Print one of each.

COTS components:
- 1x Eaglepower 8318 100KV brushless motor
- 1x AMS AS5047P (ABI/ABZ) encoder **OR** 1x AMS AS5048A (SPI) encoder
- 1x 6mmx2mm diametric encoder magnet (usually included with encoder)
- 27x M3x5mm heat-set inserts, brass (24x to mount actuator using front/back plates, and 3x to secure encoder housing)
- 12x M3x70mm bolts, socket head cap (to secure load)
- 12x M3x35mm bolts, socket head cap (to secure outer rings)
- 12x M3x0.5mm hex nuts, 2mm height (to secure outer rings)
- 3x M3x8mm bolts, countersunk (to secure encoder housing)
- 4x M2x6mm bolts, countersunk (to secure encoder into housing)
- 12x M3x0.5mm nylock nuts, 4mm height (to secure load)
- 4x M4x12mm bolts, countersunk (to secure motor to backplate)
- 4x M3x10mm bolts, countersunk (to secure sun gear to motor)

Tools:
- 3D printer
- Soldering iron w/ heat-set insert attachment
- Hex head drivers (M2, M3, M4)
- M3 wrench or compatible socket
- Tweezers (to assist with bearing assembly)
- PTFE lubricant (Super-Lube) for bearings and gears

# Assembly Guide
See the included V1.1 Assembly and Usage Guide PDF.

# Usage
WOLF can be used in a number of applications, including:
- Humanoid robots
- Large quadruped robots
- 3-Axis motion systems
- Unmanned Ground Vehicles (UGV)

**WARNING: DO NOT place fingers or appendages near the gearing of the actuator while it is in motion.**

# Contribute

Contributions from the community are welcomed! Please send us a message if you are interested in collaborating.

# License

Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg

# Contact

If you have any questions or need support, please feel free to open an issue or contact us at:

Email: support@anthrobotics.ca

Website: [anthrobotics](https://anthrobotics.ca/)

Twitter: [@anthrobo](https://x.com/Anthrobo)

# Gallery

![alt text](https://github.com/Anthrobotics/.github/blob/main/profile/images/wolf-v1.1-front-view.png?raw=true)

![alt text](https://github.com/Anthrobotics/.github/blob/main/profile/images/wolf-v1.1-side-view.png?raw=true)

![alt text](https://github.com/Anthrobotics/.github/blob/main/profile/images/wolf-v1.1-front-view-bw.png?raw=true)

![alt text](https://github.com/Anthrobotics/.github/blob/main/profile/images/wolf-v1.1-dimensions-front.png?raw=true)

![alt text](https://github.com/Anthrobotics/.github/blob/main/profile/images/wolf-v1.1-dimensions-side.png?raw=true)

# Attribution

This design is inspired by from the RFX gearbox by Robin Fröjd.
