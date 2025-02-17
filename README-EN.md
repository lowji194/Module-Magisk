[![🇻🇳 Tiếng Việt](https://img.shields.io/badge/Ngôn_ngữ-Tiếng_Việt-red?style=for-the-badge&logo=Google%20Translate)](README.md)
---
# Magisk Module Installation Guide

Magisk is a powerful tool for rooting Android devices without changing the system. You can install Magisk modules to add new features to your device. Here are instructions for installing two prominent Magisk modules.

## Module Introduction

### 1. [AutoTCP](https://github.com/lowji194/Module-Magisk/raw/refs/heads/main/AutoTCP.zip)

The **AutoTCP** module automatically opens a TCP connection over port **5555**. This is useful if you want to set up a wireless ADB connection or for other development purposes without having to manually open the connection each time.

- **Features**:
- Automatically opens port **TCP 5555**.
- Convenient for developing and testing ADB connections over the network.

- **Download**: [Download AutoTCP.zip](https://github.com/lowji194/Module-Magisk/raw/refs/heads/main/AutoTCP.zip)

### 2. [Auto ADB Enable](https://github.com/lowji194/Module-Magisk/raw/refs/heads/main/Auto_ADB_Enable.zip)

The **Auto ADB Enable** module automatically confirms and enables ADB connection when the device boots. This saves time as you do not need to manually enable ADB every time you reboot the device.

- **Features**:
- Automatically enable ADB mode when the device boots.

- Convenient for developers or those who frequently use ADB.

- **Download**: [Download Auto ADB Enable.zip](https://github.com/lowji194/Module-Magisk/raw/refs/heads/main/Auto_ADB_Enable.zip)

## Installation Steps

### Requirements
- The device is **rooted** with **Magisk**.

- **Magisk Manager** is installed on the device.

### 1. **Install Magisk** (if not already installed)
- Download **Magisk Manager** from [Magisk GitHub](https://github.com/topjohnwu/Magisk).

- Install **Magisk** via **Magisk Manager**.

- Make sure the device is **rooted** successfully.

### 2. **Download Magisk Module**
- Download the **module file** you want to install from the link above (AutoTCP or Auto ADB Enable).

### 3. **Install Modules via Magisk Manager**
1. Open **Magisk Manager**.
2. Go to the **Modules** tab.
3. Tap the **+** icon to add the module.
4. Select the **.zip`** file you downloaded.
5. Tap **Install** and wait for the installation to complete.

### 4. **Reboot Device**
After successful installation, **reboot device** to enable the module.

### 5. **Check Module**
Back to **Magisk Manager**, in the **Modules** tab, you can check if the module is installed and working.

## Uninstall Module

If you want to uninstall the module, follow these steps:
1. Open **Magisk Manager**.
2. Go to the **Modules** tab.

3. Select the module you want to remove.

4. Tap the **trash** icon and confirm.

## Note
- Please **backup** important data before making any changes.

- Read the module documentation carefully if any additional configuration is required.

- If your device crashes after installing the module, you can **disable** or **remove** the module via Magisk Manager.

## References
- [Magisk GitHub Page](https://github.com/topjohnwu/Magisk)
- [XDA Magisk Forum](https://forum.xda-developers.com/f/magisk.6100/)

---

Thank you for using our Magisk modules! If you have any questions or encounter problems during installation, please create an issue on our GitHub page or contact us via our support channels.
