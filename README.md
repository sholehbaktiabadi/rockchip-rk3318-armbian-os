# How to Create a Bootable Armbian Image for Rockchip RK3318

This guide explains how to prepare and flash an **Armbian image** to a Rockchip RK3318/RK3358 TV Box using **Multitool**.

---

## 🧰 Requirements

- A **USB flash drive** (at least 4 GB)
- A **computer** with Windows, Linux, or macOS
- Tools for flashing images, such as:
  - [Balena Etcher](https://etcher.balena.io/)
  - [Rufus](https://rufus.ie/)
  - [Win32 Disk Imager](https://sourceforge.net/projects/win32diskimager/)
- Files to download:
  - `multitool.xz`
  - The **Armbian image** for Rockchip RK3318 (e.g., `Armbian_XX.xx_Rk3318.img.xz`)

---

## ⚙️ Steps

### 1. Download the Required Files
Download both:
- `multitool.xz`
- Your preferred **Armbian** image for **Rockchip RK3318**.

---

### 2. Create a Bootable Multitool USB Drive
1. Open **Balena Etcher**, **Rufus**, or **Disk Imager**.
2. Select the downloaded file `multitool.xz` as the source.
3. Choose your **USB flash drive** as the target.
4. Start the flashing process.
5. Once the process is complete, a new partition called **MULTITOOL** should appear on your computer.

---

### 3. Copy the Armbian Image
1. Open the **MULTITOOL** partition.
2. Inside, you’ll find a folder named `images`.
3. Copy the downloaded **Armbian image file** (e.g., `Armbian_XX.xx_Rk3318.img.xz`) into the `images` folder.

---

### 4. Safely Eject the Flash Drive
After the copy process finishes:
- Eject the USB flash drive safely from your computer.

---

### 5. Boot the TV Box
1. Insert the prepared USB flash drive into your **RK3318 TV Box**.
2. Power on the TV Box.
3. The **Multitool** menu should appear, allowing you to:
   - Choose backup flash (if need)
   - Choose Erase flash (if need)
   - Choose Burn Image to flash
   - Choose previouse image you copy like Armbian_XX.xx_Rk3318.img.xz then OK
   - Wait until proccess complete the OK
   - You will see main menu then Shutdown
   - Eject USB flash drive
   - Power on the TV Box
   - Setup your username, password etc

---

<img width="432" height="396" alt="image" src="https://github.com/user-attachments/assets/8316e5fc-6fb1-48d7-a9c1-4b768ae00d70" />

## ✅ Done!
You’ve successfully created a **bootable Armbian image** for your **Rockchip RK3318 TV Box** using **Multitool**.  
You can now proceed with installing or testing Armbian on your device.

---

### 🔗 Useful Links
- [Armbian Official Website](https://www.armbian.com/)
- [Armbian Forum (TV Box Section)](https://forum.armbian.com/forum/24-tv-box/)
- [Balena Etcher Download](https://etcher.balena.io/)

---
