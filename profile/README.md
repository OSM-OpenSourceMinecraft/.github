# RPG Open World Server

This is an ambitious project for an RPG-style Open World server inspired by games like Genshin Impact. We are building a unique, custom-made experience that moves away from traditional Minecraft mechanics to create a rich, persistent world for players to explore.

> **⚠️ Warning:** This project is currently in its very early stages. The concepts and technical details outlined here are subject to change. This is a concept-in-progress, and we'll be sharing more concrete details soon.

## Core Concepts

The server is designed from the ground up to provide a dynamic and personal player experience. Here are some of the key ideas that define this project:

* **Custom-Built World:** The world will not be destructible. Instead, it is a handcrafted Open World, allowing for detailed environments and unique locations.
* **Player Instancing:** All players exist on the same server (or multiple servers depending on scale) but cannot see each other by default. Each player has their own "world instance" containing unique elements like loot chests and mobs.
* **Synchronized Co-op:** Players can invite others into their personal world. When an invitation is accepted, the "world packages" of both players are synchronized, and the guest is teleported to the owner's location.
* **Database-Driven Progression:** All player data, including items, progress, and stats, is stored in a central database. This allows players to have a consistent experience across multiple servers without a traditional Minecraft inventory.

## Open Source & Contribution

This is a completely **open-source project**, and we welcome contributions from everyone. Whether you're a developer, a designer, or just passionate about the concept, you can get involved. We believe that by building this project together, we can create an amazing experience for players.

## Licensing

For this repository, we will be using the **MIT License**.

We've chosen this permissive license because it offers maximum flexibility for all potential contributors and users. It allows for free use, modification, and distribution of the code, even in commercial and proprietary projects, as long as the original copyright notice and license are included. Our goal is to encourage widespread use and collaboration without placing restrictive conditions on how the code can be utilized.

## External Plugins

In addition to our custom-written plugins, we will be utilizing the following third-party plugins to create the core server experience. The use of these tools is fundamental to the project's vision.

* **CraftEngine:** This plugin is a resource pack manager that allows us to dynamically add custom items, blocks, and other assets to the game. It is a cornerstone of our project for creating a unique, non-vanilla experience.
    * [https://github.com/Xiao-MoMi/craft-engine](https://github.com/Xiao-MoMi/craft-engine)
* **MythicMobs:** A powerful mob creator that allows us to design custom monsters, bosses, and advanced AI.
    * [https://mythiccraft.io/index.php?resources/mythicmobs.1/](https://mythiccraft.io/index.php?resources/mythicmobs.1/)
* **ModelEngine 4:** An entity model manager to create and implement custom 3D models for mobs and other entities.
    * [https://mythiccraft.io/index.php?resources/model-engine%E2%80%94ultimate-entity-model-manager-1-19-4-1-21-4.1213/](https://mythiccraft.io/index.php?resources/model-engine%E2%80%94ultimate-entity-model-manager-1-19-4-1-21-4.1213/)

## Coming Soon

* **Project Structure:** Details on how the project is organized will be provided once the architecture is finalized.
* **Storyline:** The main plot and lore for the world are currently in development.
* **Item Concepts:** A detailed look at the custom items and their functions will be shared soon.

## Socials

* **Discord:** [Join our community!](https://discord.gg/WBC8jBhZyr)
