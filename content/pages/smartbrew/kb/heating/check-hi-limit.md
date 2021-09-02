---
title: Check Hi-Limit Switch
date: Last Modified 
tags:
  - thermistor
problemCode: "Check Tank Temperature"
resolutionCode: 304
nextStepURL: "/heating/"
---
## Possible Issue(s)

- [Overheat Error](/smartbrew/kb/overheat-error/)

## What to Check - Field

- Check wires loose connections or burnt wires or sealant.
- Check reset button.

## Action Needed - Field

### I. Prerequisites

- If not already done, [open the SmartBrew top and trunk panels](/smartbrew/kb/open-machine/).
- [Check Thermistor](/smartbrew/kb/check-thermistor/)

### II. Check Wiring

- Check the wire connections to both sides of the heater element as well as the hi-limit switch, for loose connections or burnt wires.

### III. Check Reset Button

![Hi-Limit Switch](/images/hi-limit-switch-angle.jpg)
- Check to see if the “RED or BROWN” reset button on top of the hi- limit switch has been tripped (UP position). 
- If tripped, then attempt to reset it by firmly pushing the button down until a click sound is heard. 
- Now attempt to reheat the tank and check for a boiling water condition. 
- If the switch will not reset, then replace the defective hi-limit switch.

### IV. Check Voltages

- If the hi-limit switch is NOT tripped, then verify that there is 120VAC on BOTH sides of the limit switch as well as to the heater element.

- Step 1 - Turn ON power to the machine via the power switch in the rear of the unit.
- Step 2 - Turn Volt/Ohm meter dial to 200 ACV (A/C Voltage) setting (See Figure 2).
![Figure 2](/images/volt-meter-200.jpg)

- Step 3 - Verify 120VAC to the hi-limit switch by touching the tips of the test leads to the incoming power terminal (Violet w/Black striped wire) which comes from the ‘NO’ terminal on the heater relay and ground being the top of the tank (See Figure 3). 
![Figure 3](/images/red-probe-hi-limit.jpg)

If there is NO reading, then check the wire connections and goto Section “V” to check the voltages at the heater relay.
- Step 4 - Verify 120VAC through the hi-limit switch by moving the red test lead to the other (outgoing) side of the hi-limit switch and leaving the black lead touching the top of tank (ground) (See Figure 4). If there is voltage only on the incoming side of the switch then replace the defective hi-limit switch, else If there is voltage on BOTH sides of the switch, then continue.
- Step 5 - Check for voltage through the heater element. Touch the tips of the test leads to both the power and neutral terminals of the heater element (See Figure 5). The meter should read 120 Volts AC. If we do have 120VAC then [check heater relay](/smartbrew/kb/check-heater-relay/)
- Step 6 – If there is NO reading in Step 5, then there maybe a bad connection/wire between the hi-limit switch and the heater element. Check the connections by touching the test leads to the incoming side of the hi-limit switch (Note: we have already verified the switch is good) and the power terminal of the heater element. If no reading is found, then [check the continuity](/smartbrew/kb/check-continuity-heater-wiring/) of the connections at the hi-limit switch as well as the heater terminals and replace the wire/connections as necessary.


## ⚠️ Caution

::: callout

Before servicing the unit; be sure to disconnect the power supply completely (unplug or turn off circuit breaker). When it is advised to remove a wire to check for Voltage throughout these procedures, turn the power OFF to unit first; get yourself setup; then turn power back on to check for Voltage.

NEVER DISCONNECT LIVE WIRES FROM ANY DEVICE ON THE MACHINE. ALWAYS EXERCISE SAFETY FIRST!
:::

