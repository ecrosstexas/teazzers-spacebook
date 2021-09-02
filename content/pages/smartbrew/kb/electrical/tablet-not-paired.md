---
title: Tablet Bluetooth not Paired / App in Demo Mode
description: Tablet is not paired with SmartBrew machine via Bluetooth.
date: 2020-09-15
tags:
  - "demo mode"
  - tablet
  - brewing
problemCode:
resolutionCode: 113
nextStepURL: "/power/"
---
## Issue

The NEWCO Touch app is designed to run in "Demo Mode" when the tablet is not paired with the SmartBrew machine via Bluetooth.

![App Protected Access - No Bluetooth Paired](/images/app-protected-access-keypad-no-bluetooth.png)

## Action Needed - Phone

1) Turn SmartBrew machine off for 10 seconds.
2) After turning it back on, DO NOT TOUCH tablet for 30 seconds.
3) Brew Screen with 3 urns should appear when the tablet is paired.
4) If it fails, try two more times before moving on.

![App Brew Screen](/images/app-brew-screen-updated-urns.png)

## Action Needed - Field

1) [Exit Pro-Kiosk Mode](/power/exit-pro-kiosk-mode/)
2) [Access Android Settings](/power/access-android-settings/)
3) Choose Bluetooth Settings
4) Select device named RNBT-XXXX where XXXX is the last 4 characters of the MAC address of the Bluetooth board found in the SmartBrew machine.

![Android Bluetooth Settings](/images/android-settings-bluetooth.png)
