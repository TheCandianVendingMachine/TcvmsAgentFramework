# TCVM's Agent Framework

This mod provides utilities for developers to create large scale agent behaviours.

This mod does **not** change any default AI behaviour, it is purely used as a dependency.

This project is on [GitHub](https://github.com/TheCandianVendingMachine/TcvmsAgentFramework).

## About

This mod provides tools to simulate agents more deeply than what ARMA allows by default. This includes path finding,
steering behaviours, and movement handling.

As a developer, you can use the public API to generate navigation meshes (navmesh) and flow-fields for areas, and then have agents use them
to navigate the world. Likewise, there ways to generate a navigation mesh for the entire map and use that.

This mod uses extensions. The extensions are the core of how the navmeshes and flow-fields are generated.

This mod will _not_ change any AI behaviour by default. You must register agents to the handler in order for them to be used.
Further documentation will be available at a later date.

## Requirements

- [HEMTT](https://github.com/BrettMayson/HEMTT/releases/latest) required for building and testing

## License

This mod is licensed under [GPL 3.0](LICENSE.md). Please report any violations to the mod author.





