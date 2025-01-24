# SSM-Z (Super Sampling Manager)

## Overview
This program helps gamers keep their AI-enhanced graphics libraries (DLSS, FSR, XeSS) up-to-date for the best performance and visual quality. It scans user-selected directories for these libraries, compares them with the latest available versions, and provides options for manual or automatic updates.

## Key Features
- **Library Scanning**: Automatically detects DLSS, FSR, and XeSS libraries on user-selected or all drives.
- **Version Comparison**: Compares installed libraries against the latest versions from official repositories.
- **Automatic Updates**: Updates all libraries in a selected location with the latest versions.
- **Manual Updates**: Users can choose specific libraries to update.
- **Backup and Restore**: Creates backups of original files before updates and allows restoration if needed.
- **Dark/Light Theme Support**: Adapts to user preferences for a better UI experience.
- **System and Driver Compatibility Check**: Verifies that your system and graphics drivers meet the requirements for DLSS, FSR, and XeSS.
- **Multilingual Support**: Automatically adjusts to the system language (16 languages supported).
- **Refresh and Report Tools**: Options to refresh GPU detection and report unknown cards.
- **Background Mode**: Runs quietly in the background with taskbar integration.
- **Donation Support**: Includes a link for financial contributions to support further development.

## Requirements
- **Operating System**: Windows 10 version 2004 (10.0.19041) or newer.
- **Graphics Drivers**:
  - NVIDIA: 522.25 or newer.
  - AMD: Radeon Adrenalin 22.5 or newer.
  - Intel: 31.0.101.4090 or newer.

## Supported Libraries
### AMD FSR Libraries
- `amd_acs_x64.dll` (AMD CPU Services Library)
- `amd_ags_x64.dll` (AMD GPU Services Library)
- `amd_fidelityfx_dx12.dll` (AMD FidelityFX DX12 Library)
- `amd_fidelityfx_vk.dll` (AMD FidelityFX Vulcan Library)
- `ffx_backend_dx12_x64.dll` (AMD FidelityFX Backend DX12 Library)
- `ffx_frameinterpolation_x64.dll` (AMD FidelityFX Frame Interpolation DX12 Library)
- `ffx_fsr3_x64.dll` (AMD FidelityFX FSR3 Library)
- `ffx_fsr3upscaler_x64.dll` (AMD FidelityFX FSR3 Upscaler Library)
- `ffx_opticalflow_x64.dll` (AMD FidelityFX Optical Flow Library)

### Intel XeSS Libraries
- `libxell.dll` (XeLL Low Latency SDK)
- `libxess.dll` (XeSS Super Sampling SDK)
- `libxess_fg.dll` (XeSS Frame Generation SDK)

### NVIDIA DLSS Libraries
- `nvngx_dlss.dll` (NVIDIA Deep Learning Super Sampling)
- `nvngx_dlssd.dll` (NVIDIA DLSS 3 Ray Reconstruction)
- `nvngx_dlssg.dll` (NVIDIA DLSS Multi Frame Generation)
- `NRD.dll` (NVIDIA Real-time Denoising)
- `NvLowLatencyVk.dll` (NVIDIA Vulkan Reflex Support)
- Other NVIDIA SL plugins (`sl.common.dll`, `sl.reflex.dll`, etc.).

## Installation
### Portable Version
1. Download the portable version from the [releases page](#).
2. Extract the contents to a directory of your choice.
3. Run the executable.
4. (Optional) Enable autostart in the settings.

### Installer Version
1. Download the installer from the [releases page](#).
2. Run the installer and follow the on-screen instructions.
3. The program will autostart by default.

## Usage
1. Launch the program.
2. Select a drive or directory to scan.
3. Review the detected libraries and their versions.
4. Choose to update all libraries or manually select specific ones.
5. Use the "Restore" button to revert updates if necessary.

## Contribution
Contributions are welcome! Follow these steps:
1. Fork this repository.
2. Create a branch for your feature/fix.
3. Submit a pull request with a detailed explanation.

## Support
If you encounter issues or have suggestions, please open an issue or use the contact form in the "About" section of the program or the [project website](#).

## Donations
Support the project via [PayPal](#).

## License
This project is licensed under the [MIT License](LICENSE).

---

**Note:** This program does not distribute copyrighted libraries directly. It relies on official repositories for fetching the latest versions.

