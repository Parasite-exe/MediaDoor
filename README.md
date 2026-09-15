## MediaDoor v1.1 - The Foundation Update

MediaDoor v1.1 introduces major improvements to high-resolution video handling, application stability, and update mechanics.

### 🚀 What's New
* **High-Resolution Support:** Expanded format parsing to automatically detect and pull pristine 2K and 4K video streams.
* **Automatic Format Standardization:** Embedded FFmpeg post-processing now forces automatic container remuxing into standard `.mp4` format for maximum compatibility.
* **Overhauled Auto-Updater:** The internal update engine has been rewritten to safely bypass SSL certificate blocks on clean Windows installations, ensuring you never miss a future patch.
* **Dynamic Font Rendering:** Custom application fonts are now loaded dynamically from the local Assets folder, guaranteeing the UI looks perfectly sharp on any PC.

### ⚙️ Installation
1. Download `MediaDoor_setup.exe` from the Assets section below.
2. Run the installer (it will cleanly install to your local AppData to allow seamless future updates).
3. Launch MediaDoor from your Start Menu or Desktop.
