# R36S Clone – GA36-MB V1.1–20251025 · EmuELEC (30GB SD Card Backup)

This repository holds a full backup of the original SD card for the **GA36-MB V1.1-20251025** motherboard running **EmuELEC 4.7**, designed to help restore devices with corrupted storage.
- This is **NOT a modified firmware**
- This is an **exact image of the original SD card**
- Compatible **ONLY** with:
  - **R36S Clone**
  - **Motherboard: GA36-MB V1.1**
  - **EmuELEC 4.7**

If your console uses a different board or firmware version, **do NOT use this image**.

## 📷 System Preview
Here is the verified working setup, motherboard model, and storage configuration used to create this backup:

### 🧩 Motherboard & Hardware Identification
<img src="New%20folder%20(2)/board.jpg" width="40%" alt="GA36-MB V1.1 Motherboard" />

### 💾 Verified MicroSD Card
<img src="New%20folder%20(2)/sd_card.jpg" width="40%" alt="SanDisk Ultra 64GB Card" />

### 🚀 Console in Working Condition
<p align="center">
  <img src="New%20folder%20(2)/console_1.jpg" width="30%" alt="R36S Working Console View 1" />
  <img src="New%20folder%20(2)/console_2.jpg" width="30%" alt="R36S Working Console View 2" />
  <img src="New%20folder%20(2)/console_3.jpg" width="30%" alt="R36S Working Console View 3" />
</p>
<p align="center">
  <img src="New%20folder%20(2)/console_4.jpg" width="45%" alt="R36S Working Console View 4" />
  <img src="New%20folder%20(2)/console_5.jpg" width="45%" alt="R36S Working Console View 5" />
</p>

## 📥 Download Links
The backup image is split into **8 compressed parts**. You must download all 8 parts from TeraBox into the same folder before extracting:

*⚠️ **Note for TeraBox Downloads:** Because these files are large, TeraBox will ask you to log into a free account to download them. If you want to bypass the login completely, you can copy the link and use an online bypass tool like **[Terabox Downloader](https://teradownloader.com/)**

* 👉Part 1 (.zip.001) **[Download Part 1](https://1024terabox.com/s/1KiqWE2mU8916v4FIycQRFw)**
* 👉Part 2 (.zip.002) **[Download Part 2](https://1024terabox.com/s/15NLKU3ix0Qn5zvGqTTy6Bg)**
* 👉Part 3 (.zip.003) **[Download Part 3](https://1024terabox.com/s/1EACxGs4qO0pm6PqCwWJxjw)**
* 👉Part 4 (.zip.004) **[Download Part 4](https://1024terabox.com/s/12aKcSEDgRuCP6TsupOACMg)**
* 👉Part 5 (.zip.005) **[Download Part 5](https://1024terabox.com/s/1RHggpkPcjEh-gWIBiHFoGg)**
* 👉Part 6 (.zip.006) **[Download Part 6](https://1024terabox.com/s/18cdWtFSbQkw7e8dDmoQ5Rg)**
* 👉Part 7 (.zip.007) **[Download Part 7](https://1024terabox.com/s/1cyW7_hoSvYzI2v4UpwVYrA)**
* 👉Part 8 (.zip.008) **[Download Part 8](https://1024terabox.com/s/1Rti1jMUyxKtJzlHb3kxflw)**

## 📋 Image & Hardware Specifications
* **Motherboard:** GA36-MB V1.1 20251025
* **OS:** EmuELEC 4.7
* **Content:** Around **20,000 games** pre-installed across **20 emulated platforms** (including PlayStation, PSP, Capcom 1/2/3, MAME, PC Engine, Famicom/Nintendo, Game Boy, Super Famicom/SNES, Nintendo 64, GBC, GBA, Nintendo DS, Game Gear, Sega Mega Drive, Dreamcast, and Neo-Geo).
* **Actual Image Size:** Under 32 GB (Fits cleanly onto a standard **32 GB card**).
* **Card Used for Backup:** SanDisk Ultra microSDXC UHS-I card 64GB (used simply because it was available at the time of creation).

### ⚠️ IMPORTANT HARDWARE LIMITATION (TF2 Slot)
This specific motherboard revision **only supports a single SD card setup**. For unknown hardware or firmware reasons, this board **does not recognise secondary SD cards placed in the TF2 slot** for extra space. You must flash everything (OS and ROMs) onto your primary card in the TF1 slot.

## 🧰 Restoration Guide

### Step 1: Extract the Multi-Part Archive
1. Download **all 8 files** and place them inside the **exact same folder** on your PC.
2. Ensure the files are named sequentially (e.g., `.zip.001`, `.zip.002`, up to `.zip.008`).
3. Right-click on **Part 1 (`.zip.001`)** using **7-Zip or WinRAR** (Windows) or **Keka** (Mac).
4. Select **"Extract Here"** or **"Extract to..."**. The software will automatically read all 8 parts and merge them into a single 30GB `.img` file.

### Step 2: Flash the SD Card
1. Open **Rufus** or **DiskGenius** (Tools > Write Image To Disk)
2. Select your target MicroSD card (Minimum 32GB, must go into the **TF1 slot**).
3. Choose the newly extracted `.img` file.
4. Click **Start** and wait for the process to complete.

### Step 3: First Boot
1. Insert the card into your R36S Clone console's **TF1 slot**.
2. Power it on. The system will take longer than usual to boot as it resizes partitions. **Do not power off the console during this process.**

## 🛑 Troubleshooting
* **Extraction Error:** If 7-Zip throws a "data error" or "CRC failed", one of your downloaded parts is incomplete or corrupted. Redownload that specific part.
* **Black Screen:** Double-check your motherboard. This image only works on `GA36-MB V1.1 20251025`.

---
*For personal backup and recovery purposes.*
