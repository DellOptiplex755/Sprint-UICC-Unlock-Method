# Sprint UICC Unlock Guide

> [!WARNING]
> Your mileage may vary! I'm not 100% certain this will work for you! <br/>
> ***ONLY*** for Samsung Galaxy devices as of now.


# Prerequisites: 
Please make sure to download and set up everything before reading further!

+ A Windows PC
+ (Active?) T-Mobile Sim Card
  - (T-Mobile MVNOs *should* work too)
  - (WiFi only is untested, but may work!)
+ [Bifrost](https://github.com/zacharee/SamloaderKotlin/releases/download/1.20.2/bifrost.exe)
+ [ODIN](https://xdaforums.com/attachments/odin3-v3-14-1_3b_patched-zip.5158507/)
+ [Official Samsung USB Drivers](https://developer.samsung.com/android-usb-driver)
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

⭐ After you're done downloading both firmware files, you should have one with *"U1"* AND one with *"U"* in the filename, like this:

<img width="812" height="89" alt="image" src="https://github.com/user-attachments/assets/95b21787-b21f-46bf-902d-bdb66731e2d6" />

⭐ Unzip both of the files, you should have two folders with the firmware files inside!

<img width="652" height="179" alt="image" src="https://github.com/user-attachments/assets/84092568-a691-46c8-a8c6-3be391fd8220" />

⭐ You can now open ODIN and begin flashing.

</div>

---

<div align="center"> 

# ⚡ Flashing Firmware (1/2):

</div>

> [!CAUTION]
> Be careful when flashing, if you have any data you want to back up... ***PLEASE DO SO NOW!***<br/>
> I am ***NOT*** responsible for bricked devices or data loss if you mess up!

> [!CAUTION]
> ***BEFORE FLASHING REMOVE YOUR SCREEN LOCK AND FINGERPRINTS!!!!!***

<div align="center"> 

> ⚠️ You may ignore this popup, but if you want to be on the safe side remove your Google and Samsung account before flashing! ⚠️ <br/>

<img width="399" height="397" alt="image" src="https://github.com/user-attachments/assets/c58c4970-21b3-45d5-becd-07b93c987330" />

---

## Enter Download Mode:
### Most "newer" Samsung devices without a Bixby button enter Download Mode like this:
### 1. Plug your phone into your PC then turn your phone off
### 2. Wait for your phone to fully turn off and then hold Vol up + Vol down
### 3. When the warning screen pops up, press the Vol up button
### 4. If it worked you should see your device pop up in ODIN as "0:[COM#]"
### If you are trying this on an older device, look up a guide on how to enter Download Mode on YOUR device.
### If for some reason ODIN does not detect your device in Download Mode, make sure you installed the Samsung USB Drivers!

---


> ❗❗ **Use the *"U1"* firmware files for this first flash!!** ❗❗ <br/>

⭐ In ODIN make sure to put the files in their corrisponding slots:

<img width="870" height="649" alt="image" src="https://github.com/user-attachments/assets/b6ec607c-4463-4423-8eaf-afd2d1198dd9" />

> ❗❗ **MAKE SURE TO USE HOME_CSC IN THE CSC TAB OR YOU WILL WIPE YOUR DATA!** ❗❗ <br/>
> ❗❗ **YOU DO NOT NEED TO PUT THE USERDATA FILE IN IT'S RESPECTIVE SLOT** ❗❗

⭐ Once you have every file in place, click **Start**, and your device should begin to flash<br/>

⭐ If everything went well, you should see PASS in ODIN, and your device should reboot!

> ❗❗ **IF THE FLASH FAILS, YOU WILL BE UNABLE TO CONTINUE.. DOUBLE CHECK THAT YOU DOWNLOADED REGION CODE "SPR"** ❗❗

<img width="871" height="649" alt="image" src="https://github.com/user-attachments/assets/d7d73c3f-56da-42d7-858a-de9ca38f55d8" />

</div>

---

<div align="center"> 

# 🔓 Attempting UICC Unlock (1/2):

</div>

> [!WARNING]
> This is where I'm very unsure of how it works, so if UICC Unlock fails for you,<br/>
> or UICC Unlock doesn't show up, you may be unable to get your device unlocked.

> [!NOTE]
> You may be able to use T-Mobile's network pass to get an active eSIM to unlock<br/>
> However this requires having a Sim inserted from a T-Mobile MVNO.<br/>
> There may be an update in the future showing how to achieve this..

<div align="center"> 

> **❗❗ Make sure your ***Model Name*** ends in *"U1"* in settings! ❗❗** 

<img width="360" height="33" alt="image" src="https://github.com/user-attachments/assets/40683cd7-10fb-42ea-97b6-c4beafe972f1" />

⭐ Insert your T-Mobile (or T-Mobile MVNO) Sim Card to make sure it gets service OR at least shows in <br/> ***Settings > Connections > SIM Manager***
> 💡 You may be prompted to restart your phone! 💡
<img width="408" height="139" alt="image" src="https://github.com/user-attachments/assets/c5e65c8a-c96c-454a-890a-71ca286e5afd" />

⭐ After confirming that your Sim can be read and displayed, go to ***Settings > Software Update*** <br/>
and make sure that ***UICC Unlock*** is displayed.
> 💡 If you have an active Sim Card, make a test call, or browse the internet to make sure service is working before continuing. 💡 <br/>
> ⚠️ If you do NOT have an active Sim Card, connect to Wifi before continuing if you haven't already. ⚠️

⭐ After ensuring ***UICC Unlock*** is showing in Software Update you can now move on to flashing firmware again.

<div/>

---

<div align="center"> 

# ⚡ Flashing Firmware (2/2):

⭐ Place your phone into [Download Mode](#enter-download-mode) once again.<br/>
> ❗❗ **Use the *"U"* firmware files for this second flash!!** ❗❗ <br/>

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


