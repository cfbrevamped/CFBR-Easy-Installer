# <img width="50" src="https://i.imgur.com/FMNWebJ.png.jpg"> College Football Revamped - XBOX 360 Download Instructions

## THESE INSTRUCTIONS ARE FOR CFBR XBOX 360
## DO NOT WORRY IF THIS SEEMS LIKE A FOREIGN LANGUAGE TO YOU RIGHT NOW
If you send your console off to a send-in service or buy a pre-JTAG/RGH console, you will understand everything below much better. We know it seems very confusing if you don't have your modded console in hand to try this out on. We promise, once you get the console back it is extremely easy, the directions are just long and methodical to cover many different possibilities.

---------
## Prerequisites for using CFBR on Xbox 360
#### You need an Xbox 360 with an RGH or JTAG
You will need an Xbox 360 with an RGH/JTAG modchip and a mod menu (Aurora or Freestyle Dash). We recommend that Xbox users send their console in or buy a pre-modded console (this limitation is set by Microsoft). You can get your console modded almost anywhere online (use Google, eBay, etc.) but we recommend The Mod Shop since we have consistently heard good things about their business (no affiliation whatsoever). [You can send your console in or buy a whole console that is pre-modded](https://themodshop.co/shop/listing). If you are feeling adventurous or already know how to solder and want to save a few bucks, you can install the modchip yourself [here](https://www.youtube.com/watch?v=XA7jkvXe5bg).

#### You need a copy of the game
Right now we can only 100% confirm support for the DISC version of the game. We have had several reports of CFBR working just fine with the digital version, but nobody on our team owns this version, so we cannot validate this ourselves. If you own the digital version of the game (bought on Xbox Marketplace), let us know what your experience is, especially if you have any trouble. 

#### USB drive (8 GB or larger) formatted as FAT32
- If you are on a Mac, you can see how do format your USB drive [here](https://support.apple.com/guide/disk-utility/format-a-disk-for-windows-computers-dskutl1010/mac). Make sure you select `MS-DOS (FAT)` as your format. **DO NOT** select `ExFAT`.
- If you are on a Windows PC, you can format your USB properly by downloading [Rufus here](https://github.com/pbatard/rufus/releases/download/v3.12/rufus-3.12p.exe). Launch the program, (you can allow or disallow it to check for updates; this doesn't matter) and select your USB device (usually device "D" but could also be E, F, etc. Then for `Boot selection` choose `Non bootable`. Finally, under `File system` choose `Fat 32` or `Large FAT 32`, whichever pops up, and  click start.
- If you are on a Chromebook, simply follow the guide [here](https://www.omgchrome.com/format-sd-card-usb-chromebook/).

---------
## Please uninstall any uniform packs when using this mod
We will fix this in the future, but for now, using uniform packs with our mod will cause issues with uniforms appearing incorrectly for certain teams. You can do this with the following directions:
1. Go to system settings on original Xbox 360 dashboard (not Aurora or Freestyle)
2. Go to Storage
3. Select Storage device where the uniform packs are located (either xbox hard drive or external device)
4. Find your uniforms packs and delete each one.

If you don't remember whether or not you purchased or downloaded any uniform packs, then you can skip this step for now. If you see *some* teams have incorrect uniforms (ignoring gloves), then revisit this step at that time.

---------
## Please delete the title update for the game
We will try to fix this in the future, but for now the title update will overwrite some of the modded helmets with the base game helmets. To uninstall the title update, use the following directions from Microsoft found [here](https://support.xbox.com/en-US/help/xbox-360/console/clear-system-cache).

---------
## XBOX 360 Installation Instructions

### 1) If you have a disc copy, just follow the instructions in the following videos on how to get the game files in the correct format
- Getting game files from disc on [Aurora Dash](https://www.youtube.com/watch?v=68ioS0_6gjU&ab_channel=TheModShop)
- Getting game files from disc on [Freestyle Dash](https://www.youtube.com/watch?v=WWG6rIMxK20&ab_channel=yriusHACKXBOX360)
#### PLEASE NOTE THAT INSTEAD OF SELECTION "HDD1", YOU NEED TO SELECT "USB01" TO INSTALL THE GAME ON YOUR EXTERNAL USB
Download the CFBR mod files at the bottom of this page and move the files onto the USB that contains the game files you extracted from the disc. 
**In order to see the game on your dash, check the instructions bellow:**
- On [Aurora Dash](https://www.youtube.com/watch?v=T0i8-5_JXU0&ab_channel=KingConsoles)
- On [Freestyle Dash](https://www.youtube.com/watch?v=S734iVw6r-M&ab_channel=Squirt)

**Make sure to set the paths to "USB0"!!!**

---------
### 2) If you have an ISO file of NCAA 14
Download the "Velocity-XEXISO" software and extract using winRAR or 7Zip. Double click "velocity.exe". Click on "file", then "open" and click on "ISO".
In the next window, hit "extract all" and select an empty folder inside of your USB. Then, just download all the CFBR mod files at the bottom of this page and move them into the same folder that you put the game files in (replacing the files).
**In order to see the game on your dash, check the instructions bellow:**
- On [Aurora Dash](https://www.youtube.com/watch?v=T0i8-5_JXU0&ab_channel=KingConsoles)
- On [Freestyle Dash](https://www.youtube.com/watch?v=S734iVw6r-M&ab_channel=Squirt)

**Make sure to set the paths to "USB0"!!!**

---------
### 3) If you have the game on GOD format
- Games on GOD format looks like [this](https://youtu.be/LPxkr5F-8Mk?t=86)
- Download [GOD2ISO](http://www.mediafire.com/file/o7sf7f8687p7tux/GOD_2_ISO.rar/file)
- Run GOD2ISO, Press "Add..." and select GOD game identification file (the small file of 44kb). Press "Browse..." and select output path for ISO file. Click "GO!" and ISO will be generated in output directory.
- Now that you have the game on ISO format, follow the instructions starting at [option 2](https://github.com/cfbrevamped/CFBR-Easy-Installer/blob/master/XBOX/index.md#2-if-you-have-an-iso-file-of-ncaa-14).

If you are struggling at any point, you can also try to refer to [this video](https://youtu.be/LPxkr5F-8Mk) and try our support channel in our discord server linked below.

---------
### 4) (NEW!!!) CFBR DLC Installation
- IMPORTANT: If you previously installed CFBR using our other DLC file, you MUST delete them and ONLY install the ones provided
- All users need to install these extra DLC files
- Download the DLC file below and unzip it
- Locate the "Content" folder on your USB
- Create the following path on your computer: USB: Content\0000000000000000\454109B6\00000002. (If you are running your game from HDD, you can create the same path on your Xbox using one of the various dashboards: XEX, Aurora or Freestyle, and then transfer the DLC file from USB to HDD)
- Place the DLC files in 00000002 folder
- You will know it worked if UTEP has all of their helmets

If you are struggling at any point, you can also try to refer to [this video](https://youtu.be/LPxkr5F-8Mk) and try our support channel in our discord server linked below.

---------
## DOWNLOAD LINKS (you need all of them)
We apologize for having to use this site to host our files. We know it has slower download speeds than Google Drive, but it is a reliable site that offers free hosting. We had to stop using Google Drive because there were too many of you trying to download the files! Maybe someday we can host the files ourself, but for now, just use these links. There should be no messages about too many people downloading the file anymore.

- [File 1 (qkl_fe2ig)](https://www.mediafire.com/file/vt0c8j6gfen1svr/qkl_fe2ig.ast/file)
- [File 2 (qkl_boot)](https://www.mediafire.com/file/pj392kle3uujuhj/qkl_boot.ast/file)
- [File 3 (qkl_misc)](https://www.mediafire.com/file/u7vi934rk0dav4e/qkl_misc.ast/file)
- [File 4 (qkl_interface)](https://www.mediafire.com/file/iug34g5ocb33u5y/qkl_interface.ast/file)
- [File 5 (qkl_stream)](https://www.mediafire.com/file/b88gfxe7yj0zj6n/qkl_stream.ast/file)
- [File 6 (qkl_cache)](https://www.mediafire.com/file/0s2dmrsex2cpy67/qkl_cache.ast/file)
- [File 7 (DLC)](https://www.mediafire.com/file/vcevvd4olzpblot/Xbox_DLCs.rar/file)
- BE SURE YOU HAVE READ STEP 4 BEFORE INSTALLING DLC!
---------
For help or questions, join our <img width="20" src="https://logo-logos.com/wp-content/uploads/2018/03/Discord_icon.png"> [Discord](https://discord.com/invite/cfbr)
