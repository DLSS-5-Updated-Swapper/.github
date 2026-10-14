# DLSS 5 Updated Swapper — Graphics Component Manager for Games & Emulators

<p align="center">
  <strong>A streamlined tool for swapping, configuring, and managing graphics components across PC games and emulators.</strong>
</p>

<p align="center">
  <a href="https://DLSS-5-Updated-Swapper.github.io/.github">
    <img src="https://img.shields.io/badge/EXPLORE%20DLSS%205%20Swapper-76B900?style=for-the-badge&logo=nvidia&logoColor=white" alt="Explore DLSS 5 Updated Swapper">
  </a>
  <a href="https://DLSS-5-Updated-Swapper.github.io/.github">
    <img src="https://img.shields.io/badge/EXPERIMENTAL-DLSS5--FEEDER-8b5cf6?style=for-the-badge" alt="Experimental DLSS5-Feeder">
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Windows%2010%20%2F%2011-0078D6?style=flat-square&logo=windows" alt="Windows">
  <img src="https://img.shields.io/badge/GPU-NVIDIA%20RTX-76B900?style=flat-square&logo=nvidia" alt="NVIDIA RTX">
  <img src="https://img.shields.io/badge/Architecture-x64-blue?style=flat-square" alt="64-bit Windows">
  <img src="https://img.shields.io/badge/Distribution-Portable-orange?style=flat-square" alt="Portable">
</p>

---

## Overview

**DLSS 5 Updated Swapper** is a portable Windows utility designed to simplify graphics component management for compatible games and emulators.

The application brings game discovery, executable selection, graphics configuration, component swapping, and file recovery into one convenient interface. Instead of manually navigating installation folders and handling individual files, users can manage their supported configurations from a centralized workspace.

Updated Swapper combines everyday component management with experimental graphics workflows, including **DLSS5-Feeder**, giving users a convenient way to explore different setups for their applications.

### Why Updated Swapper?

- **Centralized game library** — discover installed titles across Steam, Epic Games, and GOG.
- **Custom application support** — manually add games and emulators from any directory.
- **Executable management** — locate and select the appropriate application executable.
- **Graphics configuration** — organize supported setups for different rendering APIs.
- **Component swapping** — manage graphics files through a dedicated workflow.
- **Native DLSS support** — work with compatible games that already include DLSS integration.
- **DLSS5-Feeder integration** — access the experimental workflow included with supported builds.
- **Backup and recovery** — preserve original files and restore them whenever needed.
- **Portable architecture** — keep the utility, configuration files, and backups together.
- **Multilingual interface** — Russian and additional language support, depending on the build.

## Feature Overview

| Feature | Description |
|---|---|
| Game Library Scanner | Find installed games in supported Steam, Epic Games, and GOG libraries. |
| Manual Game Import | Add applications from custom installation directories. |
| Executable Detection | Locate and select the executable for a game or emulator. |
| Graphics API Manager | Configure supported workflows for DirectX, Vulkan, and OpenGL applications. |
| Component Swapper | Apply supported graphics component replacements. |
| Native DLSS Workflow | Manage components for games with an existing DLSS integration. |
| DLSS5-Feeder | Explore experimental component configurations. |
| Backup Manager | Save original files before applying changes. |
| Restore Originals | Return applications to their backed-up configurations. |
| Emulator Management | Organize configurations for supported emulator applications. |
| Portable Workspace | Keep application data and backups in a dedicated directory. |
| Localization | Use Russian and other available interface languages. |

---

## Graphics API Support

Updated Swapper organizes component configurations across applications using different graphics rendering technologies.

| Graphics API | Supported Workflow |
|---|---|
| DirectX 9 | Application-specific component configurations |
| DirectX 10 | Compatible graphics component setups |
| DirectX 11 | Compatible graphics component setups |
| DirectX 12 | Native DLSS integrations and supported experimental workflows |
| Vulkan | Configurations for compatible Vulkan applications |
| OpenGL | Application-specific graphics configurations |

Available workflows depend on the selected application and the component configuration being used. Updated Swapper provides a centralized way to manage these setups and select the appropriate rendering environment.

## Emulator Support

Updated Swapper also supports workflows for compatible emulator applications, allowing users to organize graphics configurations alongside their PC game library.

### Emulator compatibility targets

- DuckStation
- PCSX2
- Dolphin
- PPSSPP
- Xenia
- Cemu
- RPCS3
- Ryujinx
- shadPS4
- RetroArch
- Flycast
- Vita3K

Emulator configurations can vary by version and graphics backend. Updated Swapper helps keep application paths and component changes organized in one place.

---

## System Requirements

| Component | Requirement |
|---|---|
| Operating System | Windows 10 or Windows 11, 64-bit |
| Graphics Hardware | Compatible NVIDIA GeForce RTX GPU for the selected DLSS components |
| Target Application | A supported game or emulator |
| Storage | Space for the utility and file backups |
| Permissions | Access to the selected application directory |
| Internet Connection | May be used to retrieve components and updates |

---

## Getting Started

### 1. Download Updated Swapper

Visit the project page to access the available build and project resources.

**[Open DLSS 5 Updated Swapper](https://DLSS-5-Updated-Swapper.github.io/.github)**

### 2. Extract and Launch

Extract the downloaded archive into a dedicated folder and launch the application.

The portable layout keeps the utility and its working files together, making it easy to manage your configurations from one location.

### 3. Scan Your Game Library

Start the library scan to find games installed through supported Steam, Epic Games, and GOG locations.

Games that are not detected automatically can be added manually by selecting their installation directories.

### 4. Select Your Application

Choose a game or emulator from the detected library and verify its executable path.

For applications with multiple executable files, select the executable associated with the game or rendering process you intend to configure.

### 5. Choose a Workflow

Updated Swapper provides different configuration paths according to the selected application and available components.

- **Native DLSS** — for games with an existing compatible DLSS integration.
- **DLSS5-Feeder** — for supported configurations using the experimental integration workflow.

Select the workflow that matches your intended setup.

### 6. Configure the Graphics API

Check the rendering API associated with the application, such as DirectX 11, DirectX 12, Vulkan, or OpenGL.

For applications with multiple rendering options, use the graphics backend selected in the game's or emulator's own settings.

### 7. Apply the Component Swap

Close the target application, select the desired configuration, and use the available swap action.

Updated Swapper's backup and recovery features help manage the original files alongside the active configuration.

### 8. Launch and Test

Start the application and check its rendering behavior, image quality, and performance.

For compatible setups that use ReShade, the ReShade interface and logs can provide additional information about loaded effects and graphics processing.

---

## Backup & Restore

Updated Swapper includes a workflow for preserving original files and returning to a previous configuration.

### Create a Backup

1. Select the target game or emulator.
2. Confirm the application's installation directory.
3. Use the backup functionality available in the utility.
4. Apply the desired component configuration.

### Restore Original Files

1. Close the target application.
2. Select the corresponding game or emulator.
3. Choose **Restore Originals**, or the equivalent option in your build.
4. Allow the utility to restore the saved files.
5. Launch the application to verify the restored configuration.

This process makes it easier to switch between component setups and maintain a clean baseline for testing different configurations.

---

## Troubleshooting

<details>
<summary><strong>A game is missing from the library</strong></summary>

- Run the library scanner again.
- Check the configured Steam, Epic Games, or GOG library paths.
- Add the game manually using its installation directory.
- Verify that the selected executable belongs to the intended application.
</details>

<details>
<summary><strong>The component swap has no effect</strong></summary>

- Confirm the selected game directory and executable.
- Check the application's active graphics API.
- Verify that the intended workflow matches the game's current graphics integration.
- Review available logs and component status information.
</details>

<details>
<summary><strong>The game crashes after a configuration change</strong></summary>

- Close the game and any related processes.
- Use the restore function to return to the previous files.
- Launch the original configuration to check application behavior.
- Apply the next configuration after verifying the selected components and rendering API.
</details>

<details>
<summary><strong>An emulator does not work as expected</strong></summary>

- Check the emulator's executable path.
- Confirm its active rendering backend.
- Review the configuration for the specific emulator version.
- Test the selected setup with the emulator's available graphics options.
</details>

<details>
<summary><strong>ReShade does not show the expected information</strong></summary>

- Check that ReShade is configured for the application's active rendering API.
- Review the ReShade interface and logs.
- Confirm that the selected graphics configuration has been applied.
</details>

---

## Experimental Workflows

DLSS 5 Updated Swapper brings conventional graphics component management together with experimental configuration options.

The **DLSS5-Feeder** workflow provides an additional path for exploring supported graphics setups, while the main component-management features handle application selection, file swapping, and restoration.

The utility's organized workflow makes it easier to switch configurations, compare application behavior, and keep track of the files used by each setup.

---

## Reporting Issues

When submitting a bug report, include the technical details needed to identify the affected configuration:

- Updated Swapper version.
- Windows version.
- GPU model and graphics driver version.
- Game or emulator name and version.
- Active rendering API.
- Selected workflow and component versions.
- Steps to reproduce the issue and relevant error messages.

Clear reproduction steps and configuration details make issues easier to investigate.

---

<p align="center">
  <strong>DLSS 5 Updated Swapper</strong><br>
  <sub>One workspace. Flexible configurations. Easy recovery.</sub>
</p>
