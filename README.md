Apple Keyboard Layout for WASD V2 Keyboards
===========================================

A custom Mac keyboard layout that aims to reproduce the modern Apple Keyboard layout suitable for use with a WASD V2 keyboard or similar.

![Preview](https://raw.github.com/aasmith/mac-wasd-keyboard/master/custom-mac-layout.png)

Features
========

Based on the Mac layout provided by WASD Keyboards, this layout contains the following changes:

* Iconography, such as media keys, brightness and expose/dashboard on the 
  function key row.
* Function key text is capitalized and bottom-right aligned.
* Icons for option (⌥) and control (⌃), complimenting command (⌘).
* Fn key in place of insert.
* Enter key text is right-aligned.

Details
=======

* The font is VAG Rounded Light.
* The media player icons are from the Font Awesome set.
* The media volume icons use the Font Awesome speaker cone combined with
  the more accurate emanating lines from the originals in the WASD V2 template.
* The option and control icons are customized to match the rest of the font
  aesthetic.
* Pg Up/Pg Down have been expanded to Page Up/Page Down.

Font on most keys is VAG Rounded Light 11. Functions keys are size 10.
Multi-line keys (page up/down) are centered with line spacing 0.97.

Outstanding Issues
==================

* The key next to control doesn't exist on Apple keyboards. This is currently
  a second fn; maybe it should be something else? If used as fn, it can be
  physically swapped with the control key, as they are the same size on the
  WASD 104. (dimensions R1 1x1.25)
* The eject key shares F13. Should this become its own key, reducing the number
  of F-keys by one to F14?

Included Files
==============

* `custom-mac-layout.svg` The custom layout.
   Activate layer "Alpha Mac" to see the layout.
* `wasd-inkscape-104-10.15.2014.svg` The WASD-provided keyboard template.
* `wasd-keysizes.png` Key sizes used on WASD V2 104 key.

Resources
=========

* [Font Awesome](http://fortawesome.github.io/Font-Awesome/)
* [WASD Keyboards](http://www.wasdkeyboards.com)
