# WinBluetoothDevices

A Windows desktop application that displays all connected Bluetooth devices with detailed information.

## Features

- 🔍 **Real-time Bluetooth Device Detection**: Automatically detects and displays all connected Bluetooth devices
- 📊 **Device Information**: Shows device name, address, connection status, signal strength, and battery level
- 🔄 **Auto-refresh**: Automatically updates the device list
- 🎨 **Modern UI**: Clean and intuitive Windows Presentation Foundation (WPF) interface
- 💡 **Lightweight**: Minimal system resource consumption

## Requirements

- Windows 10 or later
- .NET Framework 4.8 or later
- Bluetooth adapter

## Installation

### From Release
Download the latest release from the [Releases](https://github.com/jonezybri/WinBluetoothDevices/releases) page and run the installer.

### From Source
1. Clone the repository:
   ```bash
   git clone https://github.com/jonezybri/WinBluetoothDevices.git
   ```
2. Open `WinBluetoothDevices.sln` in Visual Studio
3. Build the solution (Ctrl+Shift+B)
4. Run the application (F5)

## Usage

1. Launch the application
2. The app will automatically scan for connected Bluetooth devices
3. View device details in the list
4. Click the "Refresh" button to manually update the device list

## Technology Stack

- **Language**: C#
- **Framework**: .NET Framework / .NET Core
- **UI Framework**: Windows Presentation Foundation (WPF)
- **Bluetooth API**: Windows.Devices.Bluetooth (UWP APIs)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Support

If you encounter any issues or have suggestions, please open an [Issue](https://github.com/jonezybri/WinBluetoothDevices/issues).