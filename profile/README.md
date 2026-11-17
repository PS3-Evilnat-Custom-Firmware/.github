
# Evilnat Custom Firmware (CFW)

Evilnat Custom Firmware is a modified system firmware for compatible Sony PlayStation 3 consoles. It extends the original PS3 firmware with kernel-level modifications, COBRA functionality, additional system capabilities, and support for custom firmware plugins.

The project is distributed in multiple firmware configurations designed for different PS3 hardware and operating modes.

## Core Features

- COBRA 8.5 integration.
- Modified PS3 system firmware.
- CEX and PEX firmware configurations.
- D-PEX configuration for compatible DEX systems.
- NoBD firmware variants for consoles with Blu-ray drive or logic-board issues.
- NoBT firmware variants for consoles with Bluetooth hardware issues.
- Combined NoBD and NoBT configurations.
- Optional overclocked firmware builds.
- Compatibility with established PS3 homebrew applications and plugins.
- Support for additional system-level functionality through COBRA.

## Firmware Architecture

Evilnat CFW modifies the PS3 firmware environment and integrates additional components into the system software.

### Core Firmware

The base firmware provides the modified system environment and platform-specific configuration.

### COBRA Integration

COBRA provides additional kernel-level functionality and compatibility interfaces used by PS3 homebrew applications.

Its integration enables support for software and system extensions that depend on COBRA-compatible firmware.

### Kernel Modifications

Custom firmware includes modifications to the PS3 system environment, enabling additional functionality beyond standard retail firmware.

### Firmware Configuration

Different firmware variants are provided for retail and development-oriented configurations.

## Firmware Variants

Evilnat firmware is distributed in several configurations.

| Variant | Description |
|---|---|
| CEX | Retail firmware configuration |
| PEX | Retail-oriented configuration with additional firmware functionality |
| D-PEX | Configuration intended for DEX environments |
| DEX | Development-oriented firmware configuration |
| NoBD | Firmware variant for systems with a broken or missing Blu-ray logic board |
| NoBT | Firmware variant for systems with broken or missing Bluetooth hardware |
| NoBD + NoBT | Combined hardware compatibility variant |
| Overclocked | Optional performance-oriented firmware configuration |

Not every variant is available in every release. The latest documented 4.93 release includes PEX, D-PEX, and CEX variants.

Evilnat has warned that its DEX variants are unstable and are not recommended for installation. D-PEX is the documented alternative for compatible DEX configurations.

## COBRA 8.5

Evilnat 4.93 integrates COBRA 8.5.

COBRA provides an extended system interface used by compatible PS3 software.

Its functionality is relevant to:

- Kernel-level system extensions.
- Homebrew compatibility.
- Plugin loading.
- Additional storage and application interfaces.
- Integration with utilities such as webMAN MOD.

The availability of individual functions depends on the installed firmware configuration and compatible software versions.

## Hardware Compatibility

Evilnat CFW is intended for PS3 systems capable of running standard custom firmware.

Compatibility is determined by the console's hardware revision and minimum supported firmware version.

### Commonly Supported Hardware

| PS3 hardware | CFW compatibility |
|---|---|
| Original PS3 Fat | Supported on compatible revisions |
| PS3 Slim CECH-20xx | Supported |
| PS3 Slim CECH-21xx | Supported |
| PS3 Slim CECH-25xx | Conditional; depends on minimum firmware version |
| PS3 Slim CECH-30xx | Not compatible with standard CFW installation |
| PS3 Super Slim CECH-4xxx | Not compatible with standard CFW installation |

CECH-25xx systems require individual compatibility verification. A model number alone is insufficient to determine whether CFW can be installed.

PS3HEN is a separate homebrew-enabling environment for additional PS3 hardware revisions. It is not equivalent to Evilnat CFW.

## Firmware Version

The documented current release in this package is:

| Property | Value |
|---|---|
| Firmware | Evilnat 4.93 |
| COBRA version | 8.5 |
| Firmware package | PUP |
| Variants | CEX, PEX, D-PEX |
| Additional variants | NoBD, NoBT, NoBD + NoBT, Overclocked |

The release version and available configurations should be checked against the official developer release information before installation.

## Installation Environment

Evilnat CFW installation requires compatible hardware and an appropriate firmware installation path.

For the documented 4.93 installation workflow, the requirements include:

- A CFW-compatible PS3 console.
- Compatible HFW 4.93.1 environment where required.
- The corresponding 4.93 Flash Writer.
- A verified NAND or NOR flash dump.
- PyPS3tools for flash-dump validation.
- The correct Evilnat CFW PUP package.

The installation process differs depending on whether the console is already running CFW or requires flash preparation.

## Flash Storage

PS3 consoles use different flash architectures depending on their hardware revision.

| Flash type | Hardware examples |
|---|---|
| NAND | CECHA, CECHB, CECHC, CECHE, CECHG |
| NOR | Other supported PS3 revisions |

Flash operations must use the correct hardware-specific configuration.

A valid flash backup should be preserved before performing firmware-level modifications.

## Homebrew Compatibility

Evilnat CFW supports a broad ecosystem of PS3 homebrew software.

Examples include:

- webMAN MOD
- multiMAN
- IRISMAN
- ManaGunZ
- Apollo Save Tool
- PS3 system management utilities

Compatibility depends on the installed firmware version, COBRA configuration, and individual application requirements.

## Development and Related Projects

Evilnat's developer maintains several public PS3-related projects and components.

Related repositories include:

- Cobra-PS3
- Flash Writer
- erk_dumper
- xai_plugin

These projects are separate components and should not be treated as interchangeable with the complete Evilnat firmware package.

## Project Information

| Property | Value |
|---|---|
| Project | Evilnat Custom Firmware |
| Platform | Sony PlayStation 3 |
| Project type | Custom Firmware |
| Latest documented release | 4.93 |
| COBRA integration | 8.5 |
| Firmware format | PUP |
| Main configurations | CEX, PEX, D-PEX |
| Additional configurations | NoBD, NoBT, Overclocked |
| Developer | Evilnat |

## Official Resources

- Developer profile: https://github.com/xXEvilnatXx
- Developer projects: https://gitlab.com/Evilnat
- COBRA-PS3 source: https://github.com/xXEvilnatXx/Cobra-PS3
- Evilnat firmware release information: https://www.psx-place.com/
- Firmware compatibility reference: https://consolemods.org/wiki/PS3:Firmwares/en
- Installation guide: https://store.brewology.com/ps3/guides/cfw/

---

Evilnat CFW extends compatible PlayStation 3 systems through modified firmware components, COBRA integration, hardware-specific firmware variants, and compatibility with the PS3 homebrew ecosystem.

