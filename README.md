# Golden Spawner Overlay

Client-side Fabric mod for Minecraft 1.21.11 that adds HollyWorld Golden Spawner stats to the item's inventory tooltip.

**Open source:** the complete source code is available at https://github.com/ZZarxs/HollyWorld-gold-spawner-info.

## What the mod does

- Shows the current mob, inserted egg count, farmed count, and remaining kills.
- Shows the sword's full custom name and every enchantment, including HollyWorld custom enchantments.
- Displays the information only while hovering over the spawner item in an inventory.
- Reads only data already synchronized to the client and present on the hovered item.

This is an informational client-side overlay. It does not search the world or nearby chunks, send requests to the server, automate actions, modify gameplay, or reveal data that the server has not sent to your client. The source is public so anyone can inspect exactly what the mod does.

## Install

1. Install Fabric for Minecraft 1.21.11.
2. Install Fabric API for Minecraft 1.21.11.
3. Put the mod jar in the `mods` folder and launch the Fabric profile.

## Build from source

Requires Java 21. Run `./gradlew build` on Linux/macOS or `gradlew.bat build` on Windows. The remapped jar is written to `build/libs/`.

## License

Released into the public domain under [CC0 1.0](LICENSE).
