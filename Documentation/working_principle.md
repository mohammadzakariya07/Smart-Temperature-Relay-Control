# Working Principle

The Smart Temperature Relay Control System continuously monitors temperature using a thermocouple sensor. The microcontroller processes this data and compares it with predefined temperature thresholds.

Each relay is controlled using hysteresis logic to avoid rapid ON/OFF switching. When the temperature crosses a defined upper or lower threshold, the corresponding relay state changes.

EEPROM memory is used to store relay states whenever a change occurs. On system startup, the relay states are restored, ensuring continuity even after power failure.

The system provides real-time feedback via serial communication for monitoring and debugging.
