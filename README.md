# nuki_ble
This lib is made for communicating directly to a Nuki smart lock via BLE without the need of a Nuki Bridge.
Implementation is according to [Nuki Smart Lock BLE API](https://developer.nuki.io/page/nuki-smart-lock-api-2/2/) 
(kudo's to the Nuki developers for providing such an accurate and well made documentation!)

## Tested Hardware
- ESP32 wroom
- Nuki smart lock v2
- Nuki smart lock v3

## V0.0.3
- Cleanup and refactor
- Fixed loosing pincode on re-pairing
- Updated scanning intervals according to recommendations Nuki dev
- Made BLE scanner injectable

## V0.0.2
- Added eventhandler

## V0.0.1
lib is ready for beta testing, most if not all Nuki lock v2 functionality is implemented.
Most of the basic methods have been tested, some of the more advanced (mostly settings related) methods still need to be tested
There can still be braking changes....!
Implementation is according to Nuki Smart Lock API V2.2.1 (22.06.2021)

## Wip
- Add documentation to the readme and classes

## Todo
- Some data integrity could be checked
