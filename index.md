⠀

# DISCLAIMER

**YOU ARE USING THIS APP AT YOUR OWN RISK.** I'm not repsonsible for any damage that may result from you interacting with this software in any way.

⠀

---

⠀

## New in 4.0

⠀


New features:

- **Auto lock** setting
- **Fault reader** mode to help debug issues with the bike's controller
- **ASI register reader** available after unlocking developer mode by tapping "App version" 7 times. 
  - This feature lets you read configuration parameters of the bike's controller. 
  - The source has enough groundwork for experienced modders to build their own *arbitrary configuration writer*.
- Option to **adjust initial torque** when accelerating. 
  - If you're on older firmwares, the "soft" setting implements the official fix for motor "brrr" sound and unwanted vibrations when accelerating from a stop.

Improvements:

- Streamlined user experience when performing long lasting Bluetooth operations

⠀

---

⠀

## What?

This Android app lets you set custom max speed on a CBY bike (all models) or remove speed restriction completely. Tested on firmwares `4.10.0` to `4.10.9` but should work on all of them.

## Where?

[Download Bronco Unleashed](https://github.com/hackboyMcHack/bronco/releases/download/3.5/BroncoUnleashed35.apk)

⠀

---
⠀

![Dashboard](./files/30-dashboard.png) ![Speed setting](./files/30-speedsetting.png) ![Field weakening](./files/30-fieldweakening.png) ![Settings](./files/30-settings.png) ![Bike details](./files/30-details.png) ![Fault diagnostics](./files/40-faults.png)

⠀

---

⠀

## How?

### App installation

You probably know that but just in case:

1. Open Settings in your Android phone
2. Tap `Security`
3. Check the `Unknown Sources` option
4. You can now open the `.apk` and install it

⠀

### Usage

1. Make sure your bike is paired with the CBY app and Bluetooth is on. 
2. Open ***Bronco Unleashed*** app.
3. Choose the bike you want to connect to.
4. You can now control the bike, change its options etc.

⠀

---

⠀

## Why?

I was bored and I like poking around.

⠀

---

⠀

## FAQ

#### Is this change permanent?

If you only choose to change the speed limit, the official app *will* overwrite it to 32 (V1, V2) or 28 (V3). You can also remove the limit completely which can only be reverted with Bronco _version Unleashed_. Or you can just ditch the official app completely.

#### How do I revert this?

Default values are: speed limit enabled, 25km/h, field weakening 0%. You can set all these values back to default using this app.

#### Can I use this instead of the official app?

Bronco Unleashed features a rudimentary dashboard which provides all the information the official app does, except the map. You will probably want to use a standalone navigation app anyway, because the official one sucks. Right? 

#### Notification? why?

Due to how the dashboard works, the app requires a background service. At this point I may as well show the info as a notification. If you don't like it, you can deny the app from pushing notifications in Android settings.

#### Who is responsible if this f\*cks my bike up?

You. I don't give you any guarantee that this app will even work so use it at your own risk.

#### I liked the previous version more.

[You can still get them](https://github.com/hackboyMcHack/bronco/releases).


⠀

⠀

