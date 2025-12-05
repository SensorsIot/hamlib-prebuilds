# Hamlib Pre-builds

[![GitHub Actions](https://img.shields.io/badge/Built%20with-GitHub%20Actions-2088FF?logo=github-actions&logoColor=white)](https://github.com/SensorsIot/hamlib-prebuilds/actions)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Hamlib License: LGPL v2.1](https://img.shields.io/badge/Hamlib-LGPL%20v2.1-blue.svg)](https://www.gnu.org/licenses/lgpl-2.1)
[![Platform](https://img.shields.io/badge/Platform-Windows-0078D6?logo=windows)](https://github.com/SensorsIot/hamlib-prebuilds/releases)
[![Hamlib](https://img.shields.io/badge/Hamlib-4.6.5-green?logo=radio)](https://hamlib.github.io/)

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

## License

- **This repository** (build scripts, workflows): [MIT License](LICENSE)
- **Hamlib library** (pre-built binaries): [LGPL-2.1](https://www.gnu.org/licenses/lgpl-2.1) / [GPL-2.0](https://www.gnu.org/licenses/old-licenses/gpl-2.0)

Hamlib is free software released under a dual LGPL/GPL license. See the [Hamlib repository](https://github.com/Hamlib/Hamlib) for full licensing details.
