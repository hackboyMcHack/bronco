
# DISCLAIMER

**YOU ARE USING THIS APP AT YOUR OWN RISK.** I'm not repsonsible for any damage that may result from you interacting with this software in any way.

## What?

This Android app that lets you set custom max speed on a CBY 3 bike. Tested on firmware `4.10.0`.

## Where?

[Download app](./files/Bronco.apk)

---

## How?

### App installation

You probably know that but just in case:

1. Open Settings in your Android phone
2. Tap `Security`
3. Check the `Unknown Sources` option
4. You can now open the `.apk` and install it

### Usage

1. Make sure your bike is paired with the CBY app. 
2. Open the app, tap "Connect to bike"
3. Choose your new speed and tap "Apply".
4. Done, you can close the app.

---

## Why?

For the lulz. It was a fun challenge.

---

## HELP

#### "Could not find any bikes"

Make sure Bluetooth is on and the bike can be unlocked from the CBY app. Bike doesn't have to be unlocked to make changes but it has to be bonded with your device.

#### "BluetoothAdapter not initialized"

Make sure Bluetooth is on. Try turning it off and on again.

#### "service not found"
#### "Could not find activity or service"

Make sure you are actually connecting to a CBY 3 bike and not something with a similar name. In theory this shouldn't happen because the app checks for necessay service before letting you past the first step, but you never know. The app will breifly show your bike's MAC address when connecting so you can use this to check.

#### Write failed. Check logcat.

Restart the app and trying again. You may find extra information by reading logcat with your standard `adb logcat`.
