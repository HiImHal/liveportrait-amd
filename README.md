# LivePortrait — AMD port (Radeon 8060S)

One-click Windows installer for LivePortrait, ported from NVIDIA-only to AMD. Free.

## What it does

LivePortrait animates a still portrait photo using a driving video — the face in the photo follows the movement and expression of the video.

## Tested on

- AMD Ryzen AI Max+ 395 with Radeon 8060S (gfx1151)
- BOSGAME M5

**Honest status:** this 1.0.0 build is an early hardware-check build. An earlier test package was run on the test machine and reached the GPU; a complete end-to-end animation run of this exact 1.0.0 build has not yet been finished by our developer team. Treat it as an early build, not a finished one.

## Before you install

**Hardware check — please read first.** The installer checks your hardware before it installs. This build is made for a machine with an AMD Radeon 8060S (gfx1151).

If your machine does not match, the installer shows the specs it found and offers to let you send them to us for review. It then exits without installing anything (exit code 10). Other hardware is not supported by this build.

## Download

Installer: `LivePortrait-AMD-Setup-1.0.0.exe` — 625,596,736 bytes
SHA-256: `d225fccdbceaec3b399fdcf826ad377c4474eb77099f71b227c2a4bf03a53f27`

## We port NVIDIA software to AMD

Hi I'm Hal ports AI software that was made for NVIDIA only, so it runs on AMD hardware.

Got a program you'd like to see ported? Suggest it. And if your AMD machine isn't on our tested list, you can offer your specs for testing through our compatibility program.

Contact us at https://hiimhal.com

## Licence and credit

Licence: MIT License (upstream LivePortrait, © Kuaishou Visual Generation and Interaction Center). Face detection in this build uses a MediaPipe detector (Apache License 2.0) instead of the non-commercial InsightFace models, which are not included.

Upstream project: https://github.com/KlingAIResearch/LivePortrait — credit to the LivePortrait authors. This port is not affiliated with or endorsed by the upstream project.

Ported by a developer from Ontario.
Home and full catalogue: https://hiimhal.com
Support: hello@hiimhal.com
