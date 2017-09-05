# Aqara Motion Sensor Alpha
code looking at lux in the Xiaomi Aquara Motion Sensor
This handler is not stable so use at your own risk.

New Device Handler\n
Xiaomi Aquara Motion Sensor with lux. This reports lux but only on a motion event. It appears that this device does not support
the zigbee configureReporting command on cluster 400 so unable to have it reporting lux on a regular basis or on reportable change.
However it may still be of use as illuminance should now be exposed to smart apps e.g webCoRE where it could be used to determine motion events at nighttime (dark) as opposed to daylight.

