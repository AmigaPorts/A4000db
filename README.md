# A4000DB

This is a recreation of the Amiga 4000 Daughter Board made from ground using the A4000 original schematics. It includes all the Zorro slots and also include a VGA 15khz output connector to use with a VGA metal bracket. The ISA ports has been removed from the design. Some new options has beed added on the new version 1.2.

This work great on all the Amiga 4000 versions, except of course the A4000T.

# Note

This is a work in progress, several testing must be made but it should work as is. I take no responsibiltiy for any damage to any equipment that results from the use of this board. USE AT YOUR OWN RISK!

I will try to add more features to this DB when I can. The idea is to have a good DB replacement or a better one if you don't have any.

Gerbers are separated in two version / folders:  

Version 1.1 is the first release of the board.

Update 27/12/2018: Some users have found a little of difficulty to plug large boards like CV3D or Fastlane using the Daughterboard. An easy fix is to remove the plastic guides from the front of the a4000 (those brown ones) on the slots that is gonna be used for the large boards. The zorro slots are displaced like ½mm to the right and must go to the left.

Version 1.2 fixes a few mistakes and improves others.

* Adjusted Zorro slots ½ mm to the left.
* Video connector, less wide at bottom.
* Changed Molex connector to a floppy type.
* Changed entire board to make it 4 Layer instead of 2 layers and routed it again.
* Bottom connectors are now rounded so they can fit nicely on the onboard connectors.
* Added a breakout part than can be removed in case more space for cables needed.
* Add an external clock footprint to in case main clock must be different from the onboard clock. This can be enable or disabled by setting a jumper on place. Usefull for boards like videotoaster.
* Added the /C1 signal on the VGA connector (pin 16) in case a future S-VIDEO/Composite hat is developed. (thx. to Chucky for the tip).

# Images

V1.2  

<img src="https://github.com/arananet/A4000db/blob/master/img/v2top.png?raw=true" width="700"/>
<img src="https://github.com/arananet/A4000db/blob/master/img/v2bottom.png?raw=true" width="700"/>

V1.1  

<img src="https://github.com/arananet/A4000db/blob/master/img/1.png?raw=true" width="700"/>
<img src="https://github.com/arananet/A4000db/blob/master/img/2.png?raw=true" width="700"/>

# Vga bracket

<img src="https://github.com/arananet/A4000db/blob/master/img/vgabracket.jpg?raw=true?raw=true" width="400"/>

https://www.ebay.de/itm/original-Asus-Slotblech-VGA-FLATKabel-15P-TO-16P-P-N-14001-00450000/201663185333 

# Updates

09/01/2019 Release of the second version of the DB.

27/12/2018 Notes updated about using large boards.

21/08/2018 Initial release.

Note: For the videoslot you need to dremel a 100 pin connector in half in order to put it on place.
