# Keyboard Map

This is a 34 keys layout using ZMK. I use it with most of my low
profile keyboards. The keyboards are 5 columns, 3 rows and 2
thumb keys.

## Objectives

 Use both hands instead of contortions. While multi-keys shortcuts are available on same hand as an option, they aren't a must.

 Avoid home row modifiers. While `IGNORE_MOD_TAP_INTERRUPT` did
 reduce false triggering of modifiers, it was none zero false
 triggering which required lot of timing tweaks. Instead opting
 to use one shot modifiers as explained at https://github.com/callum-oakley/qmk_firmware/tree/master/users/callum#why-no-mod-tap

## What Next?

I would like to figure out a way to have a dedicated layer for
symbols. Currently, symbol and numbers are same layer and use
SHIFT for a lot of the symbols. I would like to have a dedicated
symbols layer so I don't have to press two keys - layer trigger
and SHIFT.

I don't like contortions and prefer two hands so I need shift on
both hands. This means I have only two keys for layer trigger. I
use layer toggle for some infrequent layers, but I want to use
momentary layer for symbols. Current thought is to have non-thumb
layer trigger in the base layer.

I am not able to use combo keys with horizontal adjacent keys
because of the column stagger. Might experiment with combos based
on vertical adjacent keys once I build with switches that need
less force.