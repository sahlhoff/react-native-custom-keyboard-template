# React-Native-Keyboard

## Steps I followed

1. `react-native init RNKeyboardText`
2. Added `RNKeyboard` custom keyboard extension target in obj-c
3. Added `App Transport Security Settings` in order to `Allow Arbitrary Loads` in the Info.plist file for 'RNKeyboard' target
4. Under __Build Phases__, add all React Native binary libraries in the __Link Binary with Libraries__ for the `RNKeyboard` target
5. Under __Build Settings__, add `-ObjC` and '-lc++' linker flag
6. Updated code in KeyboardViewController.m and index.ios.js
