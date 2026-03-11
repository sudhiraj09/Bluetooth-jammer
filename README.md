# Bluetooth Jammer

## Project Overview
This Bluetooth Jammer project aims to disrupt Bluetooth communication in a specified area by emitting signals on the Bluetooth spectrum. It is intended for educational and testing purposes only.

## Features
- **Channel Flooding:** The jammer utilizes various channels to evade detection.
- Simple command structure for easy operation.

## Hardware Requirements
- Microcontroller (e.g., esp 32 wroom32)
- Bluetooth Module
- Power Supply (Battery or AC Adapter)
- Connecting Wires
- Breadboard (for prototyping)
- Antina (Nrf24 L01)
- Optional: Enclosure for temporary or permanent setup

## Installation
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/sudhiraj09/Bluetooth-jammer.git
   ```
2. **Install Dependencies:** 
   Ensure all necessary libraries for your microcontroller are installed.

## Usage
1. Connect the hardware according to the configuration guide.
2. Power on the device.
3. Use the following command to initiate the jamming:
   ```bash
   python jammer.py
   ```

## Configuration
Adjust configuration parameters in the `config.json` as per your requirements. Ensure to set the correct frequency ranges and power levels.

## Hardware Setup
Schematic diagrams and pin connections should be referenced in the `hardware_setup.py` file.
connected the pins upload the code and power up to work this device.

## Channel flooding Modes
The Bluetooth Jammer supports several channel flooding modes which can be configured in the settings. 
## Troubleshooting
- **Device Not Powering On:** Check your power supply connections.
- **Incomplete Jamming:** Ensure that you're within range of your target devices.
- **Connection Issues:** Verify that the Bluetooth module is properly connected and configured.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing
Contributions are welcome! Please read `CONTRIBUTING.md` for guidelines on how to contribute to this project.
