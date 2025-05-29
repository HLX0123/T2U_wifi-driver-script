
Welcome to **hlx01's TechHub**! This repository hosts a professional-grade Bash script to effortlessly install and configure the TP-Link Archer T2U Plus (RTL8821AU chipset) Wi-Fi driver on Kali Linux. With *one simple command*, it automates the entire process—no complicated setup required.

## Download
**[Download complete_setup_with_driver_removal_and_hlx01_branding.sh](https://github.com/HLX0123/T2U_wifi-driver-script.git)**

### File Details
- **Version**: 1.0 (~1.2 KB)
- **Last Updated**: May 29, 2025
- **Compatibility**: Kali Linux (kernel 6.12.25-amd64), TP-Link Archer T2U Plus (RTL8821AU)
- **License**: MIT License (free for personal use)

## What This Script Does
- **Downloads**: Kernel headers (`linux-headers-6.12.25-*`) from Kali mirrors.
- **Clones**: The `morrownr/8821au-20210708` repository.
- **Optional Cleanup**: Removes old or corrupted drivers (e.g., `88XXau`) with a deep clean.
- **Installs**: Configures headers via `dpkg -i` and deploys the driver with `install-driver.sh`.
- **Features**: User-friendly prompts, error handling, and hlx01’s signature branding.

## How to Use
1. **Prerequisites**:
   - Kali Linux (amd64, kernel 6.12.25-amd64).
   - Internet connection and `sudo` privileges.
   - Install dependencies:
     ```bash
     sudo apt install wget git dkms
2.   **Download**:
   Use the link above or clone the repository:
   git clone https://github.com/hlx01/wifi-driver-script.git
cd wifi-driver-script
3. **Setup**
chmod +x complete_setup_with_driver_removal_and_hlx01_branding.sh
sudo ./complete_setup_with_driver_removal_and_hlx01_branding.sh
