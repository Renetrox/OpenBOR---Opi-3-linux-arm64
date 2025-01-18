# OpenBOR for ARM64 and Orange Pi 3B

This repository contains a modified version of OpenBOR (Open Beats of Rage) compatible with ARM64 devices, specifically optimized for the Orange Pi 3B.

## Key Features

- **ARM64 Compatibility**: Modifications made to compile and run OpenBOR on ARM64 devices.
- **Optimized for Orange Pi 3B**: Specific adjustments for the hardware and operating system of the Orange Pi 3B.
- **Extended Compatibility**: Tested on Debian- and Ubuntu-based distributions.

## System Requirements

- **Device**: Orange Pi 3B or any ARM64 device.
- **Operating System**: Debian 11/12, Ubuntu 20.04/22.04, or compatible systems.
- **Dependencies**:
  - SDL2
  - GCC/G++
  - Make
  - Git

## Installation Instructions

1. Clone this repository:

   ```bash
  git clone https://github.com/Renetrox/OpenBOR-Opi-3-linux-arm64.git
   cd OpenBOR-Opi-3-linux-arm64
   ```

2. Install the required dependencies:

   ```bash
   sudo apt update
   sudo apt install -y libsdl2-dev build-essential git
   ```

3. Compile OpenBOR:

   ```bash
   make
   ```

4. Run OpenBOR:

   ```bash
   ./OpenBOR
   ```

## Specific Notes for Orange Pi 3B

- **Hardware**: This project leverages the capabilities of the Rockchip RK3566 processor and ARM Mali G52 2EE GPU.
- **System**: Using Orange Pi OS (Debian-based) is recommended for an optimized experience.
- **Additional Configurations**:
  - Adjust scaling and resolution in the configuration file for optimal performance.

## Customization

You can add your own OpenBOR games to the `Paks` directory. Simply place the `.pak` files inside this folder.

## Credits

- **OpenBOR**: Original project developed by the Beats of Rage community.
- **ARM64 Adaptations**: Implemented by @Renetrox.
- **Contributions**: Thanks to everyone who helped with development and testing.

## License

This project uses the same license as OpenBOR. See the `LICENSE` file for more details.

---

Enjoy your games on your Orange Pi 3B!
