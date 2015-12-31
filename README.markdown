# ErgoDox EZ

All about the ErgoDox EZ

- Configuring your ErgoDox
    - [Installing a configuration](#installing-a-configuration)
    - [Keyboard configuration tools](#keyboard-configuration-tools)
    - [Existing configurations you can examine or download](https://github.com/ErgoDox-EZ/docs/wiki/Existing-configurations)
    - [Write/update your own configuration (in c!)](#writeupdate-your-own-configuration (in c!))
- Information about the ErgoDox EZ
    - [Original Crowdfunding campaign](https://www.indiegogo.com/projects/ergodox-ez-an-incredible-mechanical-keyboard)
    - [Purchase one](https://www.indiegogo.com/projects/ergodox-ez-an-incredible-mechanical-keyboard)
    - [Specifications](#technical-specifications)
    - [Accessories](#accessories)
- [Articles and reviews](#articles-and-reviews)


## Configuring your ErgoDox


### Installing a configuration

a.k.a. flashing the firmware

First, make sure:

* Your keyboard is plugged in
* You know what the "Teensy reset button" is ([the tiny hole in the upper right](tiny_reset_button.jpg)). Alternatively, you can use the "teensy" key if it's in your keymap.
* Download the [firmware.eep](firmware.eep) from this repository

Then:

1. Download and run the [Teensy Loader app](http://www.pjrc.com/teensy/loader.html)
2. Press and release the Teensy reset button
3. Click the "Auto" button on the upper right hand side of the Teensy-Loader window
4. Drag and drop the '.eep' file onto the Teensy loader window. 
5. Drag and drop the '.hex' file onto the Teensy loader window.
6. Press and release the Teensy reset button

Notes:

* If this process fails in the "Auto" button stage, try dragging in a .eep and a .hex file, then pressing auto and restarting the process from the beginning.
* For a more detailed account, check out the [ergodox-firmware repository](https://github.com/benblazak/ergodox-firmware#load-firmware-onto-the-teensy)

### Keyboard configuration tools

- [keyboard-configurator from massdrop](https://keyboard-configurator.massdrop.com/ext/ergodox)
    - Works and looks good *check the comments on that page for information about special keys, like hold-key-for-layer and media keys*
    - Isn't open source. Doesn't provide all options.
- [fusion](https://github.com/ErgoDox-EZ/fusion)
    - Open source. Work in progress. Will and be useable soon!

### Existing configurations

[Look at the list of existing configurations on the wiki](https://github.com/ErgoDox-EZ/docs/wiki/Existing-configurations)



### Write/update your own configuration (in c!)

This requires a little bit of familiarity with coding.

1. Go to [github.com/jackhumbert/qmk_firmware](https://github.com/jackhumbert/qmk_firmware) and read the Readme at the base of the repository, top to bottom.
2. Follow the instructions for [ergodox_ez configuration](https://github.com/jackhumbert/qmk_firmware/tree/master/keyboard/ergodox_ez)
3. Create a repository to track your configuration and [add it to this readme](#existing-configurations)


## Information about the ErgoDox EZ

The ErgoDox EZ was created by Erez, who ran a [successful Indiegogo campaign](https://www.indiegogo.com/projects/ergodox-ez-an-incredible-mechanical-keyboard) in 2015 and shipped keyboards in December of 2015

You can still purchase one on the indiegogo page.

### Technical Specifications

The compact and ergonomic open-source ErgoDox mechanical keyboard, fully assembled in Taiwan in an injection-molded ABS plastic case, with:

- Two independent halves connected by a TRRS (tip, ring, ring, sleeve) cable (replace cable for custom length)
- USB jack and starter cable (replace cable for custom length)
a full (including flashing alternative firmware, switching keycaps, but not opening case or dunking in aquarium) 2-year manufacturer's warranty
- A Teensy 2 (32 KB) micro-controller running QMK firmware with support for N-key rollover (NKRO), unicode input up to at least 0xfff, mouse keys, and fully customizable layouts

## Options and accessories

#### Official options/accessories

- Printed keycaps in DSA (flat) profile
- Blank keycaps come in DCS (sculptured) profile.
- Tilt/Tent kit: six rubber-footed metal legs for custom tilt (front-to-back) and tent (side-to-side) angle adjustments of each keyboard half, standard thumb screw size
- Wing wrist rest
- one-handed version (seen by computer as 2 keyboards)

#### Unofficial options/ideas for accessories

This list is ongoing and a work in progress. Please update with more information!

- home row indicators, [e.g. Part # 223-999-0253](http://shop.hooleon.com/)
- [o-ring dampers](http://www.wasdkeyboards.com/index.php/cherry-mx-rubber-o-ring-switch-dampeners-125pcs.html)
- [graffiti wrist rests](http://www.grifiti.com/products/ergodox-fat-wrist-pad-set-custom-fit-massdrop-split-keyboard-set)
- Custom TRRS and/or USB cables
- New/custom keycaps: WASD, Signature, etc.
- carrying cases & trays: [Mechanical Keyboards ergodox case](http://mechanicalkeyboards.com/shop/index.php?l=product_detail&p=1095), [KeyChatter massdrop ergodox case](https://www.massdrop.com/buy/ergodox-hard-case/), [wood ergodox tray/case](http://www.key64.org/news/wood-case-for-ergodox-with-trackball-tray)
- Bluetooth adapters, e.g. [Nulaxy](https://www.indiegogo.com/projects/keyboard-mouse-bluetooth-adapter/x/10804964) (compatibility?)


## Articles and Reviews

- [Deskthority ErgoDox article](http://deskthority.net/wiki/ErgoDox)
- [Why any developer should check out the ErgoDox keyboard](http://jjt.io/2013/11/25/why-any-developer-should-check-out-the-ergodox-keyboard/)
- makeuseof: [Why Hardware Startups Are Hard: Bringing the ErgoDox to Life](http://www.makeuseof.com/tag/time-founding-hardware-startup/)
- [The Evolution And Commercialization Of The ErgoDox Keyboard](http://trauring.org/the-evolution-and-commercialization-of-the-ergodox-keyboard/)
- [Typing an DIY ErgoDox — video](https://www.youtube.com/watch?v=M8aQS4bRv6w)
- geekhack: [How are you liking your ErgoDox?](https://geekhack.org/index.php?topic=42231.0)
- [DIY Infinity ErgoDox](https://www.massdrop.com/buy/infinity-ergodox)


#### Also

Much thanks to [@inkthink](https://github.com/inkthink) for his original unofficial wiki, [@sethherr](https://github.com/sethherr) and [@ezuk](https://github.com/ezuk)
