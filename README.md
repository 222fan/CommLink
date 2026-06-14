# CommLink


## Goal

Create a real communcation link for transmitting data between two devices.

Current focus:
- Laptop to latop communcation using audio
- Real time
- No encryption
- No hardware
- QAM modulation

## Milestone
### Version 1
- Send a text string
- Record microhpone audio
- Get the correct bitstirng
- Use upsampling methods

### Version 2
- Add packet numbers
- Handle packet loss
- Change to radio waves

### Version 3
- Add encryption
- OFDM

## Current Task
Implememnting basic functions of receiver and transmitter

## Current Problem
None.

## Notes
- Keep files small.
- One file should have one responsibility.
- Avoid putting everything in main.py.
- Use functions unless state needs to be stored.
- Use classes for devices and connections.
- Test each component separately.
