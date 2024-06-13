# AVE Mixer User Control

## Overview

** AVE Mixer User Control is a versatile and user-friendly interface designed to manage and control audio mixer settings. It provides an intuitive graphical user interface (GUI) for configuring various parameters of your AVE mixer, enabling both novice and experienced users to optimize their audio setups with ease.

## Features

- **User-Friendly Interface:** Simplified and intuitive GUI for easy navigation and control.
- **Real-Time Adjustments:** Make real-time adjustments to audio and video settings without interrupting the ongoing stream or playback.
- **Custom Presets:** Save and load custom presets for different scenarios and environments.
- **Multi-Platform Support:** Compatible with Windows.
- **Extensive Control Options:** Full control over audio levels, input sources, and DSP effects.

## Installation

### Prerequisites

- Ensure your system meets the following requirements:
  - Windows 8 or higher
  - [.NET Framework 4.6.1 or higher](https://dotnet.microsoft.com/download/dotnet-framework)

### Steps

1. Download the AVE Mixer User Control zip file from the repository.
2. Unzip the zip file inside a temporary folder on your Windows PC.
3. Run the `setup.exe` file to start the AVE Mixer User Control software installation.
4. Check your email for the serial key sent to you.
5. When requested, type the given serial key.
6. Wait for the installation to complete.

## Usage

1. Launch the AVE Mixer User Control application from the Start menu or desktop shortcut.
2. Use the intuitive controls to adjust audio settings as needed.
3. Save your configurations as presets for future use.
4. Explore advanced settings to fine-tune your audio experience.

## Releases

### [v2.2.4.7](https://github.com/yourusername/AVE-Mixer-User-Control/releases/tag/v2.2.4.7) - 2024-06-14
- Fixed and improved the mixer type check to avoid using the software with a mixer different from the one set in the project.
- Modified the save preset command to force the updating of parameters in the DSP in MCU firmware version v1.7.6.
- Improved management of pop-up windows to inform the user. A new pop-up window automatically closes the previous ones and does not pause the communication between PC and mixer.
- Improved communication initialization when changing communication bus from SerialCOM to TCP/IP and vice versa even without closing the project.
- Added the message dispatcher for toast type messages.
- Improved management of toast messages to signal the connection or disconnection between PC and mixer.
- Improved the functionality of the Get Mixer Info command in the Info menu. The information pop-up closes any open pop-ups and does not pause communication. Also added the display of CPU load and refresh rate values ​​for Andante V2.0 mixers.

### [v2.2.4.6](https://github.com/yourusername/AVE-Mixer-User-Control/releases/tag/v2.2.4.6) - 2024-05-11
- Create the structures (model and viemodel) relating to the Andante V2.0 mixer.
- Added compressor gain value readout for input and output compressors.
- Fixed closing of the antifeedback and spectrum analysis windows, the dispatcher timer was not stopped when closing the window with the x at the top. In this way, reading the peak values soon became extremely slow due to all the reading commands present.
- The new digital mixers Andante 16 - v2.0 and Andante 8 - v2.0 have been introduced.
- Fixed command scheduler, applications are cloned when reinserted into the getting queue.
- Corrected the opening session function in subnet_model.vb when the fault condition occurs: in this event the time variables must not be reset.
- The main toolbar has been added for easy and quick access to the main functions of the software.
- The position of the layout blocks and the related dialogs are saved in the project file to restore the desired workspace.
- Created the "Import Project" tool in the "File" menu to import a project created for the Andante V1.0 mixers into the new Andante V2.0 family.
- Added the dockable panel for editing the main "display" properties (label, font, alignment, color...) of the layout DSP blocks.
- Added control for scaling the size of DSP blocks.
- Added communication pop-up to indicate mixer connection or disconnection.
- Extended context-menus of DSP blocks.
- Inserted the measurement of the refresh-rate of the controls during the mixer monitoring.

## Getting Help and Sharing Tips

We encourage users to share their experiences, tips, and suggestions. If you have any questions or run into any issues, please let us know!

- **Reporting Issues:** If you encounter any problems or have any suggestions, please open an issue in the [Issues](https://github.com/yourusername/AVE-Mixer-User-Control/issues) section.
- **Sharing Tips and Suggestions:** Share your tips, best practices, or feature requests in the [Discussions](https://github.com/yourusername/AVE-Mixer-User-Control/discussions) section.

## License

This application is the property of AVE GmbH and all rights are reserved. Unauthorized copying, modification, or distribution of this software is strictly prohibited.
Contact

For any questions or suggestions, please open an issue on GitHub or contact us at your-info@ave-stuttgart.de.

*Made with* 💛 *by DSPSoft - Romanin Matteo*


