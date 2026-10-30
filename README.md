# Golden Spawner Overlay

Client-side Fabric mod for Minecraft 1.21.11 that adds HollyWorld Golden Spawner stats to the item's inventory tooltip.

## Features

- Shows the current mob, inserted egg count, farmed count, and remaining kills.
- Shows the sword's full custom name and every enchantment, including HollyWorld custom enchantments.
- Displays the information only while hovering over the spawner item.

The mod reads the `minecraft:custom_data` already present on the item. It does not scan nearby chunks or send requests to the server. Values missing from the item data cannot be displayed.

## Install

1. Install Fabric for Minecraft 1.21.11.
2. Install Fabric API for Minecraft 1.21.11.
3. Put the mod jar in the `mods` folder and launch the Fabric profile.

## Build from source

Requires Java 21. Run `./gradlew build` on Linux/macOS or `gradlew.bat build` on Windows. The remapped jar is written to `build/libs/`.

## License

Released into the public domain under [CC0 1.0](LICENSE).

