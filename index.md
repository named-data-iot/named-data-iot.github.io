---
layout: home
title: Home
landing-title: 'Hi, this is NDN-Lite'
description: null
image: null
author: null
show_tile: false
---

<img src="https://zhiyi-zhang.com/images/ndn-lite-logo.jpg" alt="logo" width="500"/>

The network stack can be applied to any platforms that support C, requiring a minimum version of C11 (ISO/IEC 9899:2011).
To work with the network interfaces (e.g., Bluetooth, Bluetooth Low Energy, IEEE 802.15.4, etc.) and hardware crypto interfaces (e.g., hardware ECC support, hardware pseudo random generator, etc.), proper adaptation work is required.

So far, we have developed ndn-lite based IoT packages (with platform adaptation ready) for POSIX platforms (Linux, MacOS, Raspberry Pi), [RIOT OS](https://www.riot-os.org/) and [Nordic NRF52840 Development Kit](https://www.nordicsemi.com/eng/Products/nRF52840-DK).
Developers can directly develop IoT applications based on these packages without worrying about the adaptation.

Check the ndn-lite based packages in the following list (more to be added in the future):

* [NDN-Lite Unit Tests over RIOT OS](https://github.com/named-data-iot/ndn-lite-test-over-riot) \
Maintainer: Edward Lu, Zhiyi Zhang, Tianyuan Yu

* [NDN IoT Package for Nordic SDK using Segger IDE and Android Phone](https://github.com/named-data-iot/ndn-iot-package-over-nordic-sdk) \
Maintainer: Edward Lu, Bo Chen

* [NDN IoT Package for Nordic SDK using GCC](https://github.com/named-data-iot/ndn-iot-package-over-nordic-sdk-gcc) \
Maintainer: Tianyuan Yu

* [NDN IoT Package for POSIX using CMake](https://github.com/named-data-iot/ndn-iot-package-over-posix) \
Maintainer: Xinyu Ma

* [NDN-Lite Doxygen Documentation](https://zjkmxy.github.io/ndn-lite-docs/index.html) \
Maintainer: Xinyu Ma
