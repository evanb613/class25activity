<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

Our project is a gated latch, which means no changing of the Set or Reset switches alter the output until the Enable switch is activated.
Once turned on, flipping the switch of the Reset input disables Q, but only if it was previously on, otherwise nothing happens.

## How to test

Pull the reset and set switches to see that nothing changes, then flip the enable switch on and see how the set and reset switches work

## External hardware

DIP switches with 1k ohm pull-down resistors, 74LS08 IC, 74LS02 IC, 2 LEDs each with a 220 ohm resistor
