# SAM9X60 MGS Quickstart for VS Code with MPLAB Extensions

Welcome to the SAM9X60 MGS Quickstart project! This example demonstrates a basic graphics application for the Microchip SAM9X60 Curiosity development board with WVGA display using Visual Studio Code with MPLAB extensions.

---

**Repository:**  
[mgsh_sam9x6_vs (master branch)](https://github.com/mchpgfx/mgsh_sam9x6_vs/tree/master "mgsh_sam9x6_vs GitHub")

---

## Features

- Quickstart example for SAM9X60 MGS applications
- WVGA display support (800x480)
- Integration with VS Code and MPLAB extensions
- CMake-based build system

---

## Getting Started

### 1. Prerequisites

- Visual Studio Code (latest version)
- MPLAB Extensions for VS Code
- Microchip SAM9X60 Curiosity development board
- PDA TM5000 WVGA display (or compatible)

### 2. Installation

- Clone the parent repository:
  
```bash
git clone https://github.com/mchpgfx/mgsh_sam9x6_vs.git
```

- Switch to the `master` branch:
```bash
git checkout master
```

- Open this project folder in VS Code.
- Install MPLAB extensions if not already installed.

### 3. Building and Running

- Open the project in VS Code.
- Use the MPLAB extension commands to build the application.
- Flash the application to your SAM9X60 Curiosity board.

---

## Project Structure

| Path                                          | Purpose                                                                                                                             |
|-----------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------|
| _build                                        | The [CMake build tree](https://cmake.org/cmake/help/latest/manual/cmake.1.html#introduction-to-cmake-buildsystems), can be deleted. |
| cmake                                         | Generated [CMake](https://cmake.org/) files. May be deleted if user.cmake has not been added                                        |
| .vscode                                       | See [VSCode](https://code.visualstudio.com/docs/getstarted/settings)                                                                |
| .vscode\settings.json                         | Workspace specific settings                                                                                                         |
| .vscode\mgs_qs_9x60_curiosity_wvga.mplab.json | The MPLAB project file, should not be deleted                                                                                       |
| out                                           | Final build artifacts                                                                                                               |

---

## Documentation & Developer Help

For detailed guides, troubleshooting, and API references, visit the  
[Microchip Developer Help Page for SAM9X60 MGS Dev Kits](https://developerhelp.microchip.com/xwiki/bin/view/software-tools/mgs/dev-kits/ "SAM9X60 MGS Dev Kits Help").

---

## License

See the LICENSE file for details.

---

## Contact

For questions or support, open an issue in this repository.
