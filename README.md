# react-native-nordic-dfu

This library allows you to do a Device Firmware Update (DFU) of your nrf51 or
nrf52 chip from Nordic Semiconductor. It works for both iOS and Android.

For more info about the DFU process, see: [Resources](#resources)

### This is a fork from the original library!

- Original repository: https://github.com/Pilloxa/react-native-nordic-dfu
  - Forked by: https://github.com/Salt-PepperEngineering/react-native-nordic-dfu
    - Forked by: https://github.com/circularing/react-native-nordic-dfu
      - Forked by us (current repository)
- This fork contains the latest verisons of [`iOSDFULibrary`](https://github.com/NordicSemiconductor/IOS-DFU-Library) & [`Android-DFU-Library`](https://github.com/NordicSemiconductor/Android-DFU-Library).

### Installation

Install and link the NPM package per usual with

```bash
npm install --save waylenAllen/react-native-nordic-dfu
```

or

```bash
yarn add waylenAllen/react-native-nordic-dfu
```

### Resources

- [DFU Introduction](http://infocenter.nordicsemi.com/topic/com.nordic.infocenter.sdk5.v11.0.0/examples_ble_dfu.html?cp=6_0_0_4_3_1 "BLE Bootloader/DFU")
- [Secure DFU Introduction](http://infocenter.nordicsemi.com/topic/com.nordic.infocenter.sdk5.v12.0.0/ble_sdk_app_dfu_bootloader.html?cp=4_0_0_4_3_1 "BLE Secure DFU Bootloader")
- [How to create init packet](https://github.com/NordicSemiconductor/Android-nRF-Connect/tree/master/init%20packet%20handling "Init packet handling")
- [nRF51 Development Kit (DK)](http://www.nordicsemi.com/eng/Products/nRF51-DK "nRF51 DK") (compatible with Arduino Uno Revision 3)
- [nRF52 Development Kit (DK)](http://www.nordicsemi.com/eng/Products/Bluetooth-Smart-Bluetooth-low-energy/nRF52-DK "nRF52 DK") (compatible with Arduino Uno Revision 3)
