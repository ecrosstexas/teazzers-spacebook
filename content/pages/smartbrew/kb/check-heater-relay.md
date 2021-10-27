---
title: Check Heater Relay
date: Last Modified 
tags:
  - 
problemCode: 
resolutionCode: 
nextStepURL: "/heating/"
---
## Action - Field 🛻

### I. Prerequisites

- If not already open, [open the SmartBrew top and trunk panels](/smartbrew/kb/open-smartbrew/).
- [Check Thermistor](/smartbrew/kb/check-thermistor/)
- [Check Hi-Limit Switch](/smartbrew/kb/check-hi-limit/)

### II. Check Heater Relay

If there is no voltage reading at the hi-limit switch then test the connections at the heater relay.

1. Disconnect the violet w/black stripe wire from the Common (COM) terminal of the heater relay (See Figure 6).
2. Place one test lead from the meter to the disconnected violet/black wire terminal (See Figure 8). Place the other lead on the neutral side of terminal block or ground (See Figure 9 or Figure 10). It should read 120VAC. If not, then [check for continuity](/smartbrew/kb/check-continuity-heater-wiring/).
3. If we do read 120VAC, then reconnect the violet w/black stripe wire to the COM terminal of the heater relay.
4. Remove the violet w/black wire going from the heater relay to the hi-limit switch.
5. Place one test lead from the meter to the disconnected violet/black wire terminal. Place the other lead on the neutral side of terminal block or ground (See Figure 9 or Figure 10). It should read 120VAC. If not, then [check for continuity](/smartbrew/kb/check-continuity-heater-wiring/).
6. Then disconnect the red and blue 12VDC wires from the heater relay (See Figure 6). 
7. Set the meter to 200DCV as in Figure 12.
8. Connect the test leads to these 12VDC relay connectors (See Figure 11).
9. If there is a 12-17VDC reading on the red and blue wires and there is 120VAC reading on the violet w/black wire from the terminal block to the Common (COM) terminal on the heater relay, but no voltage from the Normally Open (NO) terminal to the hi-limit thermostat switch, then replace the defective heater relay. [Resolved](/smartbrew/kb/resolutions#303) ☺️?
10. If not, then [check for continuity](/smartbrew/kb/check-continuity-heater-wiring/).
11. If the continuity of the wires is ok, then the main system board maybe defective.

##  Caution ⚠️

::: callout

Before servicing the unit; be sure to disconnect the power supply completely (unplug or turn off circuit breaker). When it is advised to remove a wire to check for Voltage throughout these procedures, turn the power OFF to unit first; get yourself setup; then turn power back on to check for Voltage.

NEVER DISCONNECT LIVE WIRES FROM ANY DEVICE ON THE MACHINE. ALWAYS EXERCISE SAFETY FIRST!
:::
