# Hillside Keyboard

Hillside is a split ergonomic keyboard with 3x6+6 choc-spaced keys. It has the aggressive stagger of the Ferris but a longer thumb arc and a break-off outer pinky column. So rather like a choc Kyria, minus two keys. With 42 to 48 keys it isn't minimalist, but is compact on finger travel while still allowing roomy keymaps. It uses a reversible 98 x 137mm PCB.

It has encoder support under each ring finger, a header for haptic feedback, mount points for a tenting puck and hand wiring a trackball, a little underglow from SK6812-MINI-Es, and a power switch for battery use with a nice!nano. It does use SMT SOT-23 diodes and other SMT parts.

I wanted choc spacing but a key or so more than the Ferris and an optional outer pinky column. Instead of tweaking the 3x6 choc Corne I started a new PCB for more flexibility, though it grew to fill its footprint....

## Details

* [Materials](doc/materials.md)
* [Building](doc/build.md)
* [QMK](qmk.com) firmware listed under keyboards/handwired/hillside, although it is not handwired.
* It is _only_ suitable for choc v1 switches and keycaps based on an 18 x 17mm switch spacing, such as the MBK keycaps. Not MX ones, nor 18 x 18mm ones such as Work Louder.
* [Future](doc/Future.md)

# Why

I wanted an aggressive stager 3x6+3 with choc spacing and switches, so moving around the switches of the Choc Corne seemed the easiest approach. But learning more than blind KiCad modification seemed a better idea, so I started a new PCB matching the Ferris column and thumb spacing.

I liked the bottom row keys of my Atreus, so I added two under the middle columns, where they seem unobtrusive. Then one shifted to the thumb arch, which seems more versatile. An upper thumb key seemed useful and combo-able without pushing the footprint. It has more keys than my initial idea, but that makes keymap evolution feel less tight.

It is like a Ferris Sweep on steroids, which wound up close to a Choc Kyria but requires board fabrication and SMT soldering.

## Images

![render](doc/image/hillside-front.png "Front Render")
![Schematic](doc/image/hillside-schema.svg "Schematic")
![pcb](doc/image/hillside-board.png "PCB")
