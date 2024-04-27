Caution: this currently only works with revision 3 of the M17

Boot logo replacement for the M17.

What you need:
An empty SD card, formatted to exFAT.
The size doesn't matter at first (Max 128GB). I used an old 4GB SD card.

OK let's go

1) Now you drag the file em_ui.sh to the empty SD card.
2) We choose a logo from the examples folder and drag the file to the SD card.
3) Now you need to rename the image file to logo.bmp .

The two files em_ui.sh and logo.bmp should now be on your SD card.

4) Now you insert the SD card into the M17 and switch it on.
5) Now you have to wait about a minute. 

You only see the old boot logo while the script does its work.

6) After a minute we can turn off the M17 and reinsert our other 
   SD card with the firmware (Emuelec or MinUi).

If you now turn on your M17 you will immediately see the new boot logo.
That's it.

You can also create your own logos, but these can only be 100x100 or 264x40 pixels in size.
File format is bmp with 8BIT.
Be careful, larger images appear in a bootloop.

Thanks to MinUI for the Script :)
