# toolchain-flexprop
PlatformIO toolchain for FlexProp build tools. Can be used to build software for the Parallax Propeller 1 and 2

Build server for flexprop used by platform-propeller in PlatformIO:
https://github.com/RileyMcCarthy/platform-propeller

## Building with Custom Forks

The workflow supports building from custom forks of the spin2cpp repository. When manually triggering the "toolchain-flexprop" workflow, you can specify:

- **Version**: The version tag to build (e.g., "1.0.0")
- **Repository**: The repository to build from (defaults to "totalspectrum/spin2cpp", but can be changed to any fork like "RileyMcCarthy/spin2cpp")

This allows for testing and releasing builds from custom modifications or forks of the FlexProp toolchain.
