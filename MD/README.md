# Espressif ZeroCode

Your device is now flashed and you are ready to go.

This firmware has test certificates, which cannot be used for production device. When you place an order, the ZeroCode modules will have the production certificates.

## Setup code

Scan the below QR Code from any of the Matter supported phone apps to setup the device. You can also use the manual setup code.

<img src="https://esp-ezc-launchpad-246098634217-prod.s3.us-east-1.amazonaws.com/companies/5UA72W8OFAVQBR6YE7C8QF/products/THMA9ANQMOT3GGMLSKDAY7/732811583_1691599239/qrcode.png" alt="qr_code" width="30%" />

## Device setup

Here's how you can get started with using this device with any of your favourite Ecosystems:

<details>
<summary>Amazon</summary>

* Requirements:
    * Latest Amazon Alexa app on an Android Device.
    * One of these <a href="https://www.amazon.com/b?ie=UTF8&node=37490568011#:~:text=Echo%20Dot%20(5th%20Gen)%2C,(v3)%2C%20Echo%20Dot%20Gen" target="_blank">devices</a> already setup in your network:
        * Echo (at least 4th gen)
        * Echo Dot (at least 3rd gen)
        * Echo Show (at least 5)
        * Echo Flex
        * Echo Input
        * Echo Plus
        * Echo Pop
        * Echo Studio
* Setup:
    * In the Alexa app, go to devices.
    * Click the `+` icon on the top right, and select `Add Device`.
    * Then scroll to the bottom and select `Other`. Then select `Matter`.
    * You will be asked if your device has a Matter logo. Select `Yes`.
    * Scan the QR code or enter the setup code manually.
    * The device setup should start.
    * You will be prompted to enter your network credentials.
    * In about a minute, you will be prompted to add your device to any room/group and change the device name to what you want.
    * The app should show that the device has been added successfully.
* Control:
    * You should be able to control the device using the Alexa app.
    * You can also use `Alexa` and use voice to control your device.

</details>

<details>
<summary>Apple</summary>

* Requirements:
    * Latest Apple Home app on an Apple device (running at least iOS/iPadOS 16.1).
    * One of these <a href="https://github.com/espressif/connectedhomeip/blob/master/docs/guides/darwin.md#setup-requirements-for-application-development" target="_blank">devices</a> already setup in your network:
        * Apple Homepod (running at least tvOS 16.1)
        * Apple TV (running at least tvOS 16.1)
* Setup:
    * Open the Apple Home app.
    * Click the `+` icon on the top right, and select `Add Accessory`.
    * Scan the QR code or enter the setup code manually.
    * The device setup should start.
    * You might get a prompt that you are adding an `uncertified accessory`, click on `add anyway`.
    * In about a minute, you will be prompted to add your device to any room and change the device name to what you want.
    * You might be asked for some additional device setup, which you can `skip` or do them `later`.
    * The app should show that the device has been added successfully.
* Control:
    * You should be able to control the device using the Apple Home app.
    * You can also use `Siri` and use voice to control your device.

</details>

<details>
<summary>Google</summary>

* Requirements:
    * Latest Google Home app on an Android Device (running at least Android 8.1).
    * One of these <a href="https://support.google.com/googlenest/answer/12391458" target="_blank">devices</a> already setup in your network:
        * Google Home (does not have Thread support)
        * Google Home Mini (does not have Thread support)
        * Google Nest Audio (does not have Thread support)
        * Google Nest Hub (does not have Thread support)
        * Google Nest Hub (2nd gen)
        * Google Nest Hub Max
        * Google Nest Mini (does not have Thread support)
        * Nest WiFi Pro
    * Since the device has test certificates, your Google account needs to be registered to be able to setup the device. You can share your Google email ID with us, and we can enable your account.
* Setup:
    * In the Google Home app, go to devices.
    * Click the `+ Add` button, and select `New device`.
    * Select your home then the app will start looking for nearby devices.
    * Select your device from the list, then scan the QR code or enter the setup code manually.
    * The device setup should start.
    * In about a minute, the app should show that the device has been added successfully.
    * You can now add your device to any room and change the device name to what you want.
* Control:
    * You should be able to control the device using the Google Home app.
    * You can also use `Google Assistant` and use voice to control your device.

</details>

<details>
<summary>ESP RainMaker</summary>

* Requirements:
    * Latest ESP RainMaker app on an Apple Device (running at least iOS/iPadOS 16.4).
* Setup:
    * Open the ESP RainMaker app and select/create a group.
    * Click the `+` icon on top right.
    * Scan the QR code.
    * You might be asked to scan the QR code again or enter the setup code manually.
    * The device setup should start.
    * You might get a prompt that you are adding an `uncertified accessory`, click on `add anyway`.
    * In about 2 minutes, the app should show that the device has been added successfully.
* Control:
    * You should be able to control the device using the ESP RainMaker app.

</details>

<details>
<summary>Samsung</summary>

* Requirements:
    * Latest SmartThings app on an Android Device.
    * One of these <a href="https://support.smartthings.com/hc/en-us/articles/11219700390804-SmartThings-x-Matter-Integration-#" target="_blank">devices</a> already setup in your network:
        * Aeotec Smart Home Hub
        * SmartThings 2015 Hub (does not have Thread support)
        * SmartThings 2018 Hub
* Setup:
    * In the SmartThings app, go to devices.
    * Click the `+` icon, and select `QR code`.
    * Scan the QR code or enter the setup code manually.
    * The device setup should start.
    * You might get a prompt that this isn't a Matter certified device, click on `continue`.
    * You might also be prompted to enter your network credentials.
    * In about a minute, you will be prompted to add your device to any room and change the device name to what you want.
    * The app should show that the device has been added successfully.
* Control:
    * You should be able to control the device using the SmartThings app.

</details>

## Device Functionality

### Indicators

* **Setup mode**: LED blinks continuously, about 4 seconds per cycle, with white color.
* **Setup started**: LED blinks continuously, about 1 second per cycle, with white color.
* **Setup complete**: LED shows the default state of the device and stops any ongoing patterns.
* **Setup failed**: LED shows the default state of the device and stops any ongoing patterns.
* **Device ready**: LED shows the default state of the device and stops any ongoing patterns.
* **Factory reset triggered**: LED blinks continuously, about 0.4 seconds per cycle, with white color.
* **Forced rollback triggered**: LED blinks continuously, about 0.4 seconds per cycle, with white color.
* **Test mode start**: LED blinks for 1.5 seconds, about 0.5 seconds per cycle, with white color.
* **Test mode complete**: LED blinks for 3 seconds, about 0.5 seconds per cycle, with white color.

### Factory Reset

* Press and hold the input button for about 5000 milliseconds. Then release the button to factory reset the device.
* The device will then reboot and enter setup mode.

### Test Mode

* **Test complete**: Mark test mode as complete. The device will not enter test mode ever again.
    * ssid: test_complete
* **BLE MAC**: Broadcast the MAC address over BLE.
    * ssid: test_ble_mac
* **Socket 1**: All sockets turn on and off, 3 times.
    * ssid: test_socket_1