# Archived Arduino/ESP32 firmware

This folder preserves the two original source sketches available from the project team's public code snapshot:

- `input/InputGame.ino`: input station, display, ESP-NOW commands.
- `robot/RobotGame.ino`: two-motor drive, reflectance sensor, stop/pause logic, ESP-NOW receive.

The physical hopper control board is part of the completed prototype, but the corresponding original hopper sketch was not present in the available code snapshot. It is not included here.

The sketches contain the original GPIO assignments, calibration values, and ESP-NOW peer MAC addresses, which may need modification for different hardware. The included source has not been independently compiled or hardware-tested in preparing this portfolio archive.
