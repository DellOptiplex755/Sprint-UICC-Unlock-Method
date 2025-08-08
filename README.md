# Sprint UICC Unlock Guide

> [!WARNING]
> Your mileage may vary! I'm not 100% certain this will work for you! <br/>
> ***ONLY*** for Samsung Galaxy devices as of now.


# Prerequisites: 
+ A Windows PC
+ Active T-Mobile Sim Card
  - T-Mobile MVNOs *should* work
  - You can try [Network Pass](https://github.com/DellOptiplex755/Sprint-UICC-Unlock-Method/blob/main/Network-Pass.md) too
+ [Bifrost](https://github.com/zacharee/SamloaderKotlin/releases/download/1.20.2/bifrost.exe)
+ [ODIN](https://xdaforums.com/attachments/odin3-v3-14-1_3b_patched-zip.5158507/)
+ [Official Samsung USB Drivers](https://developer.samsung.com/android-usb-driver)
+ Most importantly **PATIENCE!**


❗ **Please make sure to download and set up everything before reading further** ❗

### [Let's Go! →](https://github.com/DellOptiplex755/Sprint-UICC-Unlock-Method/blob/main/Firmware.md#%EF%B8%8F-downloading-firmware)

---

<div align="center"> 

# ⚡ Flashing Firmware (2/2):

⭐ Place your phone into [Download Mode](#enter-download-mode) once again.<br/>

⚠️ <ins>**Use the *"U"* firmware files for the second flash!**</ins> ⚠️

⭐ In ODIN make sure to put the files in their corrisponding slots:

<img width="870" height="649" alt="image" src="https://github.com/user-attachments/assets/b6ec607c-4463-4423-8eaf-afd2d1198dd9" />

> ❗❗ **MAKE SURE TO USE HOME_CSC IN THE CSC TAB OR YOU WILL WIPE YOUR DATA!** ❗❗ <br/>
> ❗❗ **YOU DO NOT NEED TO PUT THE USERDATA FILE IN IT'S RESPECTIVE SLOT** ❗❗

⭐ Once you have every file in place, click **Start**, and your device should begin to flash<br/>

⭐ If everything went well, you should see PASS in ODIN, and your device should reboot!

> ❗❗ **IF THE FLASH FAILS, YOU WILL BE UNABLE TO CONTINUE.. DOUBLE CHECK THAT YOU DOWNLOADED REGION CODE "SPR"** ❗❗

<img width="871" height="649" alt="image" src="https://github.com/user-attachments/assets/d7d73c3f-56da-42d7-858a-de9ca38f55d8" />

<div/>

---

<div align="center"> 

# 🔓 Attempting UICC Unlock (2/2):

> 💡 Booting should take a bit longer than usual, do not panic! 💡<br/>
> 💡 Your phone may show a Sprint or T-Mobile boot logo this time, this is good! 💡

⭐ Once you are fully booted back into android, make sure you're connected to Mobile Data. (or Wifi if you dont have an active Sim)

> ⚠️ Do not be alarmed if random apps have appeared or start to download, this is Carrier Bloat and (*Unfortunately*) normal! ⚠️

⭐ Let your phone settle for a little bit (approx. 5-10min), and then head to ***Settings > Software Update***<br/>
⭐ Tap on ***UICC Unlock***, you should hopefully get a popup like this:

<img width="341" height="750" alt="image" src="https://github.com/user-attachments/assets/91b01c71-99c1-4fad-9e98-27978f09f8e3" />

> ⚠️ If the ***UICC Unlock*** popup, opens and instantly closes, wait a bit longer or check your connection.⚠️

⭐ If everything went smoothly.... CONGRATULATIONS!!!! YOU DID IT!!!!! You should recieve a popup like this:

<img width="339" height="747" alt="image" src="https://github.com/user-attachments/assets/6d7ffd35-1970-4e22-9b49-1757e96809dd" />

🎉 [You should now have an UNLOCKED Sprint phone!!!!](https://www.youtube.com/watch?v=mD3v1B_aXw0) 🎉

---

### Apologies if this is a bit confusing and not the best looking, this is my first time doing a "write up" on something so... complex lmfao

### I'll be trying to get more Sprint locked devices to iron our any issues, or if I missed a step, but this is exactly how I got my S20+ unlocked.

### Thank you so much for reading, and I hope it worked for you!!!!


[Go HERE!](https://github.com/DellOptiplex755/Sprint-UICC-Unlock-Method/blob/main/Network-Pass.md#hello-world)
