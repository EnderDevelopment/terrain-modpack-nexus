# Minecraft NeoForge Modpack Specification

Terrain Modpack Nexus is a Minecraft modpack specification for a NeoForge modpack that includes the Create mod and Integrated Dungeons and Structures, with a documented setup for adding a separately developed terrain-generation mod. It targets Minecraft 1.21.1, NeoForge 21.1.172, and Java 21.

## Install

1. Install Java 21.
2. Install NeoForge 21.1.172 for Minecraft 1.21.1.
3. Download Minecraft 1.21.1 NeoForge-compatible files for Create and Integrated Dungeons and Structures.
4. Download any additional dependencies listed by those mods.
5. Place the downloaded `.jar` files in the Minecraft instance's `mods` folder.
6. Launch Minecraft with the NeoForge profile.
7. Add your own terrain-generation mod separately, using a build compatible with Minecraft 1.21.1 and NeoForge.

The included `modpack.json` provides the machine-readable pack definition, including the required mods, Minecraft version, loader version, and excluded terrain-generation category.

## Use

1. Create or select a Minecraft 1.21.1 NeoForge instance.
2. Install the required Create and Integrated Dungeons and Structures files.
3. Start the instance and confirm that both mods load successfully.
4. Add a compatible terrain-generation mod to the same `mods` folder if required.
5. Create a new world to use the configured mod combination.

This project is a modpack specification. It does not contain a custom terrain-generation implementation or bundled mod files.

---

More Minecraft mod projects by EnderDevelopment: https://github.com/EnderDevelopment

Project page: https://dash.enderdevelopment.com/community/4552a71c-0a88-4b5a-927f-37d22515ab94?utm_source=github&utm_medium=readme&utm_campaign=auto_publish&utm_content=4552a71c-0a88-4b5a-927f-37d22515ab94
