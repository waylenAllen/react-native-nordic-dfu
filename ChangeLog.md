# 1.0.0
- import native library with modules on iOS to fix compiling error
- remove CBCentralManager getter on iOS, init an instance of CBCentralManager interanally, which makes the library independent of react-native-ble-manager

# 1.0.1
- Remove maxMtu opiton on Android, it slows down the firmware transfering