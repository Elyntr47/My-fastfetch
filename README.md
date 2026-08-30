# CachyOS Fastfetch Configuration

A clean, modern, and vibrant Fastfetch configuration tailored for CachyOS and KDE Konsole. Features customized Nerd Font icons, detailed hardware/network metrics, and a multi-colored ASCII logo setup.

## Features
* **Multi-Colored Logo:** Customized built-in ASCII logo with neon colors.
* **Detailed System Info:** OS, Kernel, Uptime, Packages, Shell, WM, and Terminal.
* **Hardware Metrics:** CPU, GPU, Memory, and Btrfs Disk usage.
* **Network Metrics:** Local and Public IP details.

## Quick Installation

<img width="1236" height="584" alt="Ekran Görüntüsü_20260830_142216" src="https://github.com/user-attachments/assets/2a9dfbdf-5f2e-40e9-86bb-b2dc7788c1e5" />

Run the following commands in your terminal to clone the repository and apply the configuration directly:

```bash
# Clone the repository
git clone [https://github.com/Elyntr47/My-fastfetch.git] https://github.com/Elyntr47/My-fastfetch.git

# Create the fastfetch config directory if it doesn't exist
mkdir -p ~/.config/fastfetch

# Copy the configuration file
cp My-fastfetch/my-fastfetch.json ~/.config/fastfetch/config.jsonc

# Run fastfetch
fastfetch

