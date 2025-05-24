# greenCCD
A theoretical implementation of the SuzyQable as a USBC-USBC dongle.

## Why?

- The original SuzyQable was discontinued.
- Most implimentations on the market forgo the internal USB hub.
- Most implimentations on the market also suck.

## Internal USB hub??? Why?

The original SuzyQable, manufactured by sparkfun, contained a USB hub in order to mount a target CrOS device twice on the host machine:

1. As a TTL interface to the Cr50 or Ti50
2. As a target _android_ device for usage with ADB.

The ADB system is also used to (debug android apps on ChromeOS)[https://chromeos.dev/en/android-environment/deploying-apps], hence its neccesity. 

