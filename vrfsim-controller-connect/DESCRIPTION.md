---
name: VrFsim Controller Connect
type: software
version: 0.2.1
platform: Windows
developer: guyka2212
released: 2026-10-09
tags: VR, FTC, controller, Quest, VrFsim, low-spec
summary: Drive VrFsim on your Quest with a controller plugged into a low-spec laptop.
file: VrFsimControllerConnect.exe
website: https://github.com/guyka2212/controller-connect
---
**Only for laptops that can't run Quest Link.** If your PC can run Link or SteamVR, play the **Windows version** of VrFsim instead.

The game runs on the headset (install **VrFsim (Meta Quest)** first). Plug your controller into the laptop, and Controller Connect sends it to the headset over the headset's USB-C cable, instead of an adapter on the headset. The cable also charges the headset while you play.

## How to use
1. Connect the headset with a USB-C cable (developer mode on) and accept **Allow USB debugging** in the headset
2. The first time only, click **Download Android tools from Google** (about 7 MB)
3. Click **Start VrFsim on the headset**
4. Plug a controller into this PC and pick it in the list. The **Link** line turns green

> Keep the window open while you play.

## Controllers
- Xbox controllers (XInput)
- PlayStation, Logitech (D mode), Switch Pro and other pads that Windows lists under Game controllers
- Buttons that land wrong can be rebound in the game's Menu → Controls

## System requirements
- Windows 10 or 11
- A Meta Quest with VrFsim installed and developer mode on

## What's new in 0.2.1
1. Only Meta Quest headsets are used: Android phones and emulators connected to the PC are ignored
