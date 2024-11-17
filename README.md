# Ezabl NG 18 installation guide for Ender 3 v2
Thank you @TheEdgeofTech, and @minimal3dp from youtube for making tutorials about this. Those tutorials will be rewriten to text and images instead of videos.
Thank you Mriscoc from github for making the profesional firmware. 



# I, the writer of this github post, will not be responsible for any damages caused by the ones who followed this (for example of damages: broken toolhead, probe, etc...). This tutorial was writen based on my experience. All the firmwares compiling was done on Windows 11. Not sure about how to do it on Linux or MacOS.



# What to have to be able to do this.
## 1. Things
Ezabl NG 18 from TH3D.

Control box for the Ezabl (should come with the Ezabl when you purchase it).

Ender 3 v2 for this guide.

The mount for the probe. You could either 3d print it yourself [(INSIDE STL PACK)](https://support.th3dstudio.com/helpcenter/unified-2-stl-pack-ezabl-mounts-leveling-tests-more/) or get it from the TH3D store in ABS (material)

8gb MicroSD card and a reader for it.

## 2. Tools
Hex wrenches or also called allen wrenches that came with the printer.

Small screwdriver that comes with the Ezabl pack.

Wrench that came with the 3d printer, it should be 2mm in thickness. Or other completly flat 2mm thick object that can sit on the print bed.

Something to hold the nut for unscrewing and screwing. Reccomend using a pliers (can be found at local hardware store or amazon, and doesn't need to be very big).

## 3. Link to buy the tools and things if you don't already have it.

Allen wrenches + Wrenches (you could search for tool set or kits that are similar to this, or buy them separatly from different stores) [AMAZON LINK](https://www.amazon.com/dp/B0C9QRM1VM?th=1) 

[EZABL NG 18 for most printer version (cheaper)](https://www.th3dstudio.com/product/ezabl-ng-auto-bed-leveling-kit-for-unified-2-klipper-marlin-firmware/)

[EZABL NG 18 for specificly Ender 3 v2 version (more expensive because it also includes the OEM mount)](https://www.th3dstudio.com/product/ezabl-pro-abl-kit-for-creality-ender-3-v2/)

[Pliers](https://www.amazon.com/CRAFTSMAN-CMHT81645-Long-Nose-Pliers/dp/B08PFK8YWQ?dib=eyJ2IjoiMSJ9.o-O1PSyba37gMcRd8TYhAwJV4nOgTksfKue7RCmH3rKD6sHbP2Pk-w-9EZA2y6edcd4DFmjVp9MgTHKbb1MCixKmuY5GgF9C9Iig_YE2t_BOO9lQ0tt_TBpptdR6-qzLcqxKCAPNe_oHRECmKAWfy3jQJISZ6gCOlGeAQTTBOWqjyJ5Xc4YW2ildSNVtsorIEwaJFQDIgKTaia26PG3_5Ux_3QZSPTClWlmzYF7mjdRdrtO5Lp9_GhRcY__WNt_i-xxD3HXdD3LfUvSRoMqt1l-hltZU2j1PZTNuLJbMqoE.OaEUqARW2nEPwRtoG9DGAUbo3TCK8k7SLCE8a92ugKM&dib_tag=se&keywords=pliers&qid=1731833663&sr=8-5)

# Firmware guide
## Easy way with UNIFIED 2 FIRMWARE
[https://support.th3dstudio.com/helpcenter/creality-ender-3-v2-firmware/](https://support.th3dstudio.com/helpcenter/creality-ender-3-v2-firmware/)

**Note that the Unified 2 firmware is not free as it used to be. You can use the COUPON that came with the EZABL (check your TH3D account) to get the firmware for free for 3 months (it means that you can download the firmware during the 3 months period after you get it either free, then you have to pay after the period to get updates for it).**

## Hard but always free way WITH MRISCOC FIRMWARE
If you are not willing to pay for your firmware when the coupon or the 3 months period expires, it's time to do it the hard way. This method will give you more knowledge about changing and compile your own firmware!!!!!!

### To do this, you will need (Files and Programs):
1.  [Vscode or Visual Studio Code](https://code.visualstudio.com/)
  -  PlatformIO Extension (required for this guide)
  -  Auto build marlin Extension (optional but recommended)
  -  C/C++ Extention (just in case)
2.  Mriscoc special configurations source code from [github](https://github.com/mriscoc/Special_Configurations)

3.  [Marlin firmware](https://marlinfw.org/meta/download/). Note that I **Only tested Marlin 2.0 LTS**

# Comming soon
