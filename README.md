# TWRP for Xiaomi 13T Pro Corot

This repository contains the TWRP recovery build environment for Xiaomi 13T Pro (code-named "Corot").

## About TWRP

Team Win Recovery Project (TWRP) is an open-source software custom recovery image for Android-based devices. It provides a touchscreen-enabled interface that allows users to install third-party firmware and back up the current system, functions often unsupported by stock recovery images.

## Pre-requisites

- Basic knowledge of Android build environment.
- Installed JDK 8 or newer.
- A Linux environment or macOS.

## How to Build

1. **Set up your build environment**: 
   Make sure you have a proper Android build environment set up. You can follow the [Android source guide](https://source.android.com/setup/build/initializing).

2. **Clone this repository**:
git clone https://github.com/Scav-engeR/13T_Pro_Corot_Twrp.git


3. **Prepare the build environment**:
Navigate to the root of the source code and prepare the environment.
cd 13T_Pro_Corot_Twrp
source build/envsetup.sh


4. **Build the recovery image**:
lunch omni_corot-eng
mka recoveryimage


The resulting image (`recovery.img`) will be in the `out/target/product/corot` directory.

## Contributing

Contributions to the project are welcome! Please fork the repository, make your changes, and open a pull request to contribute.

## License

This project is licensed under the [MIT License](LICENSE) - see the LICENSE file for details.

## Acknowledgments

- Thanks to all the contributors who have helped to build and maintain the TWRP for Xiaomi 13T Pro Corot.