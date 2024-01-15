## Pi PICO Bad USB

## Description

The Pi PICO Bad USB project allows you to convert a Raspberry Pi PICO into a Human Interface Device (HID), such as a keyboard or mouse, for educational purposes.
This project is intended for learning and pranking friends and colleagues, not for any malicious activities.

## Features

- Converts the Raspberry Pi PICO into an HID (Human Interface Device).
- Prank friends by using the Pi PICO as a keyboard or mouse.


## Installation

1. Put Pi PICO in Boot Mode:
    - Hold the reset button on the Pi PICO.
    - Connect the Pi PICO to your computer using a USB cable.
    - A new storage unit named "RPI-Rp2" will appear.
  
2. Flash CircuitPython:
    - Copy and paste the file **`adafruit-circuitpython-raspberry_pi_pico-en_US-8.2.9 (1).uf2`** provided in the repository.
    - The storage device will be converted and renamed as "CIRCUITPYTHON".

3. Copy Files:
    - Copy the files inside the "copy" folder to the "lib" folder present in the root of the CircuitPython.
  
4. Add Extra Libraries (Optional):
    - If needed, copy the contents of the "extra_lib" folder to the "lib" folder.
  
5. Convert Pi PICO to HID:
    - Copy all the `.py` files from the "pico_ducky_main" folder to the root folder of the CircuitPython.
    - Alternatively, copy and paste the "ROOT" folder from the repository to the root folder of CircuitPython.
  
6. Edit Payload:
    - Open `payload.dd` in Notepad mode and copy-paste the provided code from the "script" folder.
  

## Usage

- Reboot the Pi PICO by pressing the reset button and connecting it again.
- The "RPI-RP2" storage unit will appear again.
- Copy and paste the file present in the "reset" folder to restore the Pi PICO to its original state.

## Contributing

Feel free to contribute by updating the script folder as you create new payloads. However, be cautious, as updating the payload folder will run the payload on your device.
