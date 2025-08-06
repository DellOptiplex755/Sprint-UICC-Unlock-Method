# Sprint UICC Unlock Guide

> [!WARNING]
> Your mileage may vary! I'm not 100% certain this will work for you! <br/>
> ***ONLY do this if you have the free time, and are willing to do lots of troubleshooting if it DOES NOT WORK!***


# Prerequisites: 

+ A Windows PC
+ T-Mobile Sim Card
  - (T-Mobile MVNOs *should* work too)
+ [Bifrost](https://github.com/zacharee/SamloaderKotlin/releases/download/1.20.2/bifrost.exe)
+ [ODIN](https://xdaforums.com/attachments/odin3-v3-14-1_3b_patched-zip.5158507/)
+ [Offical Samsung USB Drivers](https://developer.samsung.com/android-usb-driver)
+ Most importantly **PATIENCE!**

---

<div align="center"> 

# ⤵️ Downloading Firmware:
 
⭐ Get the ***Model Name*** and  ***Serial Number*** of your device, under ***Settings > About Phone***

⭐ Once you have your ***Model Name*** and ***Serial Number***, open Bifrost and type them in, along with the Reigon code of ***"SPR"***

<img width="783" height="591" alt="image" src="https://github.com/user-attachments/assets/4102ed8a-bf77-4c3a-ab40-6571b5f7405a" />

> 💡 It should look like this! 💡


⭐ Next, click the *"Check for updates"* button on the top left, and then the *"Download"* button.

---

> ❗❗ **Bifrost will prompt you to save the firmware in a folder, make sure you put it somewhere you'll remember!** ❗❗

> ⚠️ **This also may take some time to download!** ⚠️

---

⭐ When your download completes, go **BACK** to Bifrost and enter your all your information again<br/>but this time at the end of the ***Model Name***, add "*U1*" 

> 💡 OR just "*U*" if your model ended in "*U1*" in the previous step! 💡

⭐ After you're done downloading both firmware files, you should have one with "U1" AND one with "U" in the filename, like this:

<img width="812" height="89" alt="image" src="https://github.com/user-attachments/assets/95b21787-b21f-46bf-902d-bdb66731e2d6" />

⭐ You can now unzip both files, and we can begin the flashing process! 🥳

</div>

---

<div align="center"> 

# ⚡ Flashing Firmware:

</div>

> [!CAUTION]
> Be careful when flashing, if you have any data you want to back up... ***PLEASE DO SO NOW!***<br/>
> I am ***NOT*** responsible for bricked devices or data loss if you mess up!

> [!CAUTION]
> ***BEFORE FLASHING REMOVE YOUR SCREEN LOCK AND FINGERPRINTS!!!!!***

<div align="center"> 

⭐ When both files have been unzipped, you should have a folder with the firmware files inside!

<img width="652" height="179" alt="image" src="https://github.com/user-attachments/assets/84092568-a691-46c8-a8c6-3be391fd8220" />

❗❗ Use the *"U"* firmware files for this first flash!! 💡 <br/>
⭐ Open ODIN and make sure to put the files in their corrisponding slots:

<img width="870" height="648" alt="image" src="https://github.com/user-attachments/assets/ceda485a-7534-4dc2-a5a6-7b4cbd0574f8" />

❗❗ ***MAKE SURE TO USE HOME_CSC IN THE CSC TAB OR YOU WILL WIPE YOUR DATA!*** ❗❗ <br/>
❗❗ ***YOU DO NOT NEED TO PUT THE USERDATA FILE IN IT'S RESPECTIVE SLOT*** ❗❗

---

## Enter Download Mode:
### Most "newer" Samsung devices without a Bixby button enter Download Mode like this:
### 1. Power off your device
### 2. Plug your phone into your PC while holding Vol up + Vol down
### 3. When the warning screen pops up, press the Vol up button
### If you are trying this on an older device, look up a guide on how to enter Download Mode on YOUR device.

---
