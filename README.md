# CamTwist-LUT
LUT Effect for CamTwist (MacOS)

This CamTwist Effect allows you to apply 3D Look-up Tables (LUT's) for Color Grading to your videos. CamTwist effects are built on Quartz Composers, so this utilizes the Apple Core Image filter to apply the LUT to the image. Credit to [@YuAo](https://github.com/YuAo) for use of his [YUCIColorLookup.cikernal](https://github.com/YuAo/Vivid/blob/master/Sources/YUCIColorLookup.cikernel) used in the Quartz Composer file. Note that this only allows you to use an LUT PNG file. You'll need to [convert your CUBE or 3D LUT to a PNG](https://streamshark.io/obs-guide/converting-cube-3dl-lut-to-image) using this [reference image](https://github.com/YuAo/Vivid/blob/master/Sources/YUCIColorLookupTableDefault.png). I've included a few converted PNG's based on publicly available free LUT's (see credits below).

**Installation & Use Instructions**
1. Place the "LUT.qtz" file under CamTwist>Effects
2. Open CamTwist, Select LUT under Effects.
3. Drag and drop an LUT PNG of your choice under the Settings pane.
4. Adjust the Intesity slider between 0 and 1

**Note:**
CamTwist doesn't seem to be in active development anymore but is still a very verstile tool for simple and quick video broadcasting/livestreaming. Its ability to output a virtual webcam interface at this moment is very useful feature, and I developed this after being unable to find any way to apply LUT color grading to webcam streams via Hangouts/Meet, Zoom, Skype etc. This was hacked together for personal use, but I thought I would share it in case anyone would find this useful.

**Credits**
- [@YuAo](https://github.com/YuAo) for use of his [YUCIColorLookup.cikernal](https://github.com/YuAo/Vivid/blob/master/Sources/YUCIColorLookup.cikernel)
- [RocketStock](https://www.rocketstock.com/free-after-effects-templates/35-free-luts-for-color-grading-videos/) for the 35 free LUT's converted to PNG
- [Lutify.me and Skylum](https://skylum.com/luminar/marketplace/luts/6) Free LUT's
- [Richard Harrington and Skylum](https://skylum.com/luminar/marketplace/luts/7) Free LUT's
