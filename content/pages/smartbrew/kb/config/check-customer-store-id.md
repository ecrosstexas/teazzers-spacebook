---
title: Check Customer / Store ID
description:
date: 2020-10-01
tags:
  - TeaWorld
  - tablet
  - communication
problemCode: 
resolutionCode: 504
nextStepURL: "/config/"
---
## Possible Cause

- Customer and/or Store ID

## What to Check - Field

- Store ID should match data from TeaWorld. This is the unit number of a [Location](https://teazzers.azurewebsites.net/Locations).
- Customer ID should match the account number of the [Parent Company](https://teazzers.azurewebsites.net/Customers/Index) record from TeaWorld.

![App Network Screen - TeaWorld Primary Server](/images/app-network-setup-primary-server-tea-world.png)

## Action Needed - Field

1) Enter App Network Setup Screen (13375)
2) Update Store ID and/or Customer ID so that it matches data provided.
3) Exit Network Setup
4) Return to Network Setup screen
5) Poll Server for latest updates.
6) Verify communication with TEAZZERS.

## Caution