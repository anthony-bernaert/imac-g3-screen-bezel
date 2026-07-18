# 3D-printable screen bezel for the iMac G3
<p align="center">
  <img alt="GitHub release" src="https://img.shields.io/github/v/release/anthony-bernaert/imac-g3-screen-bezel?" />
  <img alt="GitHub License" src="https://img.shields.io/badge/License-CC--BY--NC%204.0-blue" />
  <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/anthony-bernaert/imac-g3-screen-bezel" />
</p>

This repository contains a 3D model of the screen bezel for a slot-loading iMac G3.

The inner screen bezel of these computers deteriorates over time, becoming yellow and brittle; very few iMacs seem spared from this fate. As this part holds the heavy CRT, it will need replacing sooner or later.

Note that this model is not intended to be a perfect replica of the original part. Instead, it has been redesigned for easy 3D printing and for strength as a printed part. This means the ribs, constant thickness, and other typical features for injection-molded parts have been replaced by larger volumes where possible, in an attempt to make the print stronger.

## Features
- Designed for 3D printing
- Drop-in replacement
- Compatible with the original CRT
- Same look as the original part

## Pictures
CAD model:

<img height="300" alt="CAD Model Front" src="https://github.com/user-attachments/assets/a83d4307-21d8-49eb-bede-758b582e1903" />
<img height="300" alt="CAD Model Back" src="https://github.com/user-attachments/assets/060c4424-4981-4d82-b4de-05a697f6d607" />

Print (in ASA, light gray):

<img height="300" alt="Print_Front" src="https://github.com/user-attachments/assets/b3859641-ec22-43e3-99b0-215162449f42" />
<img height="300" alt="Print_Back" src="https://github.com/user-attachments/assets/6aa8d402-3729-4260-8e69-643704125bac" />
<img height="300" alt="Print_Assembled" src="https://github.com/user-attachments/assets/09d1f01d-31d8-47b0-875e-3e78da189e2d" />


## Support this project
The model is made available free of charge under the CC-BY-NC 4.0 (non-commercial) license. 

If this project has been useful to you and you want to help me paying back all the plastic that went into the development of this bezel, you can always [buy me a coffee](https://ko-fi.com/abernaert)!


## Print instructions

>[!IMPORTANT]
> **I strongly recommend printing in ABS, ASA or similar**, as the iMac gets hot when used. PETG might be just good enough, but I cannot guarantee this.
>
> **Please do NOT print this in PLA.**

>[!WARNING]
> **Keep in mind the CRT weighs about 8 kg and is a fragile vacuum tube**: make sure you have a well-tuned printer (i.e. check layer adhesion, extrusion, ...) and use dry filament for strong results. 
> 
> Also be warned **that these CRTs can remain charged up to 20-30 kV after power-off and require a proper discharging procedure before handling**.
>
> Proceed at your own risk!

To print the bezel, a print bed of at least 220 mm x 220 mm is recommended. The parts to be printed are:
- The four quadrants of the bezel
- Four dowels
- Power button
- Screw cover tabs

Printing each quadrant is obviously the trickiest part: I suggest printing them at an angle to obtain a good surface finish on all sides. To help with this, separate STL files are provided with custom-designed supports (note that only the critical sections have custom supports — you still have to add supports and brims where you think they are needed).

I also recommend checking the shrinkage of your filament (on the 3 axes) using a calibration STL of some kind, and scaling the part accordingly. On large parts, this matters: using my ASA filament, I have to scale the part to 100.5% to obtain the intended dimensions.

Examples:

<img height="200" alt="Slicer_Example" src="https://github.com/user-attachments/assets/b770880c-c448-4417-8f38-cec0cf7db2ee" />
<img height="200" alt="Print_Example" src="https://github.com/user-attachments/assets/75dd925a-a93a-4b82-8f5e-ae15977d51c0" />

Settings I used:
- 0.2 mm layer height
- 15% gyroid infill
- 3 perimeters wall thickness
- Arachne wall generation, to properly handle the thin walls of the custom supports

After printing, verify the alignment of the parts. Slight warping may occur where the parts meet, but normally some quick sanding should be enough to get all faces flush again.

All parts can now be welded using acetone (gluing is also possible). The advantage of acetone is that it makes it easy to smooth out the seams.

Glue the power button into position; it has an integrated printed spring, so the original spring is not required.

For assembly of the bezel, you can now follow any online guide and proceed as with the original part.
