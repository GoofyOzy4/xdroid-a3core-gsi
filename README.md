# **xdroid ROM (Treble) for Samsung A03 Core (a3core)**

## 📱 • Maintained Unofficially by Goofy_Ozy4
This is a custom **AOSP-based** ROM, adapted specifically for the **Samsung A03 Core**.

**xdroid GSI** *(by ItzKaguya)*, tailored for the **Samsung A03 Core**, offers a minimalistic experience with a focus on performance and optimization.

---

## **⚠️ • Disclaimer:**
I am **not** responsible for any damage, bootloops, or bricked devices caused by using this GSI. Use at your own risk.

---

## **📖 • What is xdroid?**

**xdroid** is an **AOSP-based custom Android ROM** focused on simplicity and minimalism, while preserving the **smoothness** and **optimization** inherent to AOSP.  
[Official xdroid OSS GitHub](https://github.com/xdroid-oss)

---

## **📃 • Documentation**

**Note:** I am not the maintainer of the GSI itself. I am an **unofficial maintainer** of the device port. I will continue to update this fork, including any AIO modules for optimization if needed.

A big thanks to everyone tagged below for their contributions!

---

## **⭐ • Features**

- **Optimized** specifically for the Samsung A03 Core.
- **Removed unnecessary Treble overlays** that don’t provide benefits for the Samsung A03 Core.
- Added **full** Google Apps (almost all):
    ```
    • Play Store
    • Google App (Velvet)
    • Chrome
    • Gallery
    • And all necessary services and etc.
    ```
- Hidden Treble settings for a cleaner **full-ROM feel**.  
  To access them, use the following command in a superuser terminal (these will hide again after reboot):
    ```
    su -c "pm enable me.phh.treble.app/.TopLevelSettingsActivity"
    ```
- Offline charging now redirects to system reboot.
- **Lawnchair 14** launcher fork, for a cleaner, modern UI.  
  - [Official GitHub](https://github.com/LawnchairLauncher/lawnchair)  
  - [Fork Source](https://github.com/Goooler/LawnchairRelease)
- Replaced arm64 apps with arm32. *(Note: The app change list is missing, as the GSI was released two years ago)*
- **I love xdroid!**

---

## **⛔ • Bugs**

- **No VoLTE support.**
- No offline charging (now a feature due to redirection to system reboot instead of being stuck at the Samsung logo).
- **Please replace the wallpaper** to **avoid lag**.

---

## **♥️ • Acknowledgements**

- **[LiteGApps](https://litegapps.github.io/)** – For providing almost **full GApps**!
- **[yukiprjkt](https://t.me/shirayuki_plygrnd)** – For the **GSI**, and **[hiratazx](https://github.com/hiratazx)** for the **help** and **permission**!
- **[XDroidOss](https://github.com/xdroid-oss)** – For the amazing ROM project!
- **[phhusson](https://github.com/phhusson)** – For the help and **TrebleDroid**!
- **[3443](https://github.com/FlowerGEN)** – For **testing**!
- **[Lawnchair](https://github.com/LawnchairLauncher)** - For **pixel-like launcher and awesome iconpack** !
---

## **📋 • License**

- **Lawnchair/Lawnicons** - [Apache 2.0](https://choosealicense.com/licenses/apache-2.0/)
- **LiteGApps** - [MIT](https://choosealicense.com/licenses/mit/)

