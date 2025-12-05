# Hamlib Pre-builds

[![GitHub Actions](https://img.shields.io/badge/Built%20with-GitHub%20Actions-2088FF?logo=github-actions&logoColor=white)](https://github.com/SensorsIot/hamlib-prebuilds/actions)
[![License: LGPL v2.1](https://img.shields.io/badge/License-LGPL%20v2.1-blue.svg)](https://www.gnu.org/licenses/lgpl-2.1)
[![Platform](https://img.shields.io/badge/Platform-Windows-0078D6?logo=windows)](https://github.com/SensorsIot/hamlib-prebuilds/releases)

Pre-built Hamlib libraries for MinGW64/MSYS2, used for building WSJT-X and WSJT-SWISS on Windows.

## Downloads

| Version | Description |
|---------|-------------|
| [hamlib-4.6.5](https://github.com/SensorsIot/hamlib-prebuilds/releases/tag/hamlib-4.6.5) | Latest, includes FlexRadio slice support |
| [hamlib-4.5.5](https://github.com/SensorsIot/hamlib-prebuilds/releases/tag/hamlib-4.5.5) | Previous stable version |

## Build Configuration

Libraries are built with:
- MSYS2 MINGW64 toolchain
- Shared library (DLL)
- No language bindings (Perl, Python, Tcl, Lua)

## Building

Builds are triggered manually via GitHub Actions:

1. Go to [Actions](https://github.com/SensorsIot/hamlib-prebuilds/actions)
2. Select **Build Hamlib**
3. Click **Run workflow**
4. Enter the Hamlib version tag (e.g., `4.6.5`)
5. Click **Run workflow**

The build will create a release with the zip file automatically.

## Usage

These pre-built libraries are used by [WSJT-SWISS](https://github.com/SensorsIot/wsjtx) Windows builds.
