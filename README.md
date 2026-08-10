# clientcommands
Adds several useful client-side commands to Minecraft

## Social
Discord: https://discord.gg/Jg7Bun7
Patreon: https://www.patreon.com/earthcomputer

## Installation
1. Download and run the [Fabric installer](https://fabricmc.net/use).
   - Click the "vanilla" button, leave the other settings as they are,
     and click "download installer".
   - Note: this step may vary if you aren't using the vanilla launcher
     or an old version of Minecraft.
1. Download [Fabric API](https://minecraft.curseforge.com/projects/fabric)
   and move it to the mods folder (`.minecraft/mods`).
1. Download clientcommands from the [releases page](https://github.com/Earthcomputer/clientcommands/releases) or from [Modrinth](https://modrinth.com/mod/client-commands)
   and move it to the mods folder (`.minecraft/mods`).

## Building
1. Clone the repository
   ```
   git clone https://github.com/tonyismagicly/clientcommandsDEOPT-IN
   cd clientcommands
   ```
1. Generate the Minecraft source code
   ```
   ./gradlew genSources
   ```
   - Note: on Windows, use `gradlew` rather than `./gradlew`.
1. Build the Mod with Java 25+
   ```
   ./gradlew build
   ```
1. Copy the mod from ./build/libs/ into your mod folder

## Contributing
To contribute translations, see the [translation contribution guidelines](docs/TRANSLATING.md).

For other contributions, see the [contribution guidelines](docs/CONTRIBUTING.md).
