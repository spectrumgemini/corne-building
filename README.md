# corne-building

I built a corne keyboard from [Typeractive](https://typeractive.xyz/). Experience documented here for archival purposes.

# presets

I bought the 42-key version with choc spacing and nice!views. I went with no-solder spring headers, though if you have access to a soldering iron, the EZ-solder is more affordable. I opted for [ambient twilight switches from lowprokb](https://lowprokb.ca/products/ambients-silent-choc-switches) and the blank MBT switches offered by typeractive.

# the process

![E849664F-BC9C-4152-905C-407A17FCB26C_1_105_c](https://github.com/user-attachments/assets/591c22ba-16e1-4eac-be76-a41715557a31)

The build process is [documented very well](https://docs.typeractive.xyz/build-guides) by Typeractive themselves, so this will mostly be my images and commentary.

![056B8E8F-8125-4720-8B1A-E6E6A2CCF4A2_1_105_c](https://github.com/user-attachments/assets/7c36f598-4050-4c2a-97e5-3743c116069a)

I began by installing the batteries, the nice!nano, and the nice!view. Typeractive provides both the normal headers and the non-solder ones (distinguishable through shape and the fact that their pins are gold). One thing I did not expect is that this stack does not lay flat:

![0D671FB5-D924-475F-94C4-B7950EB91A4C_1_105_c](https://github.com/user-attachments/assets/8ad6fe7d-f79c-4e22-96de-e8cf9978e8c8)

The pins of the nice!nano push the nice!view upward somewhat. The nice!nano also wiggles as it's only attached by pins on its bottom edge.

I then screwed on the nice!view covers.

![E620BE27-9824-43EF-8AD5-7C420F7C84B6_1_105_c](https://github.com/user-attachments/assets/6a304059-b139-4c94-b7b2-21090c1f8c8f)

Installing the switches into the plate was easy. Snapping the switchplate into the PCB will require more force than you expect. It's also not indicated in the Typeractive docs that the switch on the innermost key needs to be rotated sideways. Screwing on the case afterwards wasn't difficult.  

![958CF545-B88B-4D2B-A749-B67AC8E2F15C_1_105_c](https://github.com/user-attachments/assets/ad6098c8-bb7b-4620-a5a7-7859c770a9b5)

The keycaps were the only place in which I needed to make any significant modification. In the same place on both sides, the keycaps rubbed against each other significantly enough that they would get stuck depressed. I solved this by filing down the innermost keycaps with a metal file (coarse enough sandpaper would probably also work, they didn't require very much abrasion), and this thankfully caused no issues cosmetically.

![0B800E83-A4F0-4DD2-99C6-764F4938A7B4_1_105_c](https://github.com/user-attachments/assets/8aea0b24-a464-44fc-b1f9-d6fd6fd8d243)

Firmware was easy to flash with their provided Github template and [Nick Coutsos' GUI editor.](https://github.com/nickcoutsos/keymap-editor)


