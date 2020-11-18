# -public-A10-PRIMER-BT_TEST_ON_EHS
ACCESSING BT SETTINGS ON A10 + EHS IN USER MODE

Licensed under MIT license, no warranty, you accept A10-PRIMER-BT_TEST_ON_EHS,v1.x.apk as-is.

- "NFC-BT" button lets you access the BT settings through the NFC / SEE MORE menu
- "BT PICKER" is a slightly differet BT menu

enterprisehomescreen.xml must contain:

```xml
<apps_enabled>
  <application package="com.android.settings"/>
  <application package="com.android.settings.bluetooth.BluetoothSettings"/>
  <application package="android.provider.Settings.ACTION_BLUETOOTH_SETTINGS"/>
  <application package="android.bluetooth.devicepicker.action.LAUNCH"/>
</apps_enabled>
