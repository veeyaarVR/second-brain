---
tags:
  - android
  - android-development
  - coding
---
`dp`

Density-independent pixels: an abstract unit that is based on the physical density of the screen. These units are relative to a 160 dpi (dots per inch) screen, on which 1 dp is roughly equal to 1 px. When running on a higher density screen, the number of pixels used to draw 1 dp is scaled up by a factor appropriate for the screen's dpi.

> [!Note] Using dp units instead of px units is a solution to making the view dimensions in your layout resize properly for different screen densities. 

> [!Note] It provides consistency for the real-world sizes of your UI elements across different devices.

---
`sp`

Scale-independent Pixels - This is like the dp unit, but it is also scaled by the user's font size preference. 
> [!Note] It is recommend you use this unit when specifying font sizes, so they will be adjusted for both the screen density and the user's preference.

---
`pt`

Points: 1/72 of an inch based on the physical size of the screen, assuming a 72 dpi density screen.

---
`px`

> [!Warning] We don't recommend using this unit, because the actual representation can vary across devices.

Pixels: corresponds to actual pixels on the screen.  Different devices can have a different number of pixels per inch and might have more or fewer total pixels available on the screen.

---
`mm`

Millimeters: based on the physical size of the screen.

---
`in`

Inches: based on the physical size of the screen.

---