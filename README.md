# LuckyBlockExpansionWithDefaultBlocks
Expands Lucky Block with SkyBlock-friendly drops, mini islands, starter kits, and progression resources for Minecraft Fabric 1.20.2.

# Lucky SkyBlock Expansion

> **Lucky Block addon** for Minecraft 1.20.2 Fabric  
> Eliminates SkyBlock softlocks without replacing the default Lucky Block events.

---

## 📦 Installation

1. Make sure the **Lucky Block** mod is installed in your `.minecraft/mods/` folder.
2. Launch Minecraft at least once so the mod can generate its required directories.
3. **Copy the entire `LuckyBlockExpansionWithDefaultBlocks` folder** into:
   ```
   .minecraft/addons/lucky/LuckyBlockExpansionWithDefaultBlocks/
   ```
4. Launch the game and enjoy!

### Final directory structure:

```
.minecraft/
└── addons/
    └── lucky/
        └── LuckyBlockExpansionWithDefaultBlocks/
            ├── pack.mcmeta
            ├── properties.txt
            ├── drops.txt
            ├── structures.txt
            └── structures/
                ├── oak_island.luckystruct
                ├── cherry_island.luckystruct
                ├── snow_island.luckystruct
                ├── jungle_island.luckystruct
                ├── desert_island.luckystruct
                ├── mushroom_island.luckystruct
                ├── crimson_island.luckystruct
                ├── warped_island.luckystruct
                ├── ocean_island.luckystruct
                ├── mangrove_island.luckystruct
                ├── lush_island.luckystruct
                ├── savanna_island.luckystruct
                └── dark_forest_island.luckystruct
```

---

## 🎲 Features

### 🌱 Phase 1 — Resource Drops

Essential resources for SkyBlock progression without softlocks.

| Item | Amount | Chance |
|---|---|---|
| Dirt | ×16 | ⭐⭐⭐⭐⭐ |
| Oak Log | ×8 | ⭐⭐⭐⭐⭐ |
| Oak Sapling | ×2 | ⭐⭐⭐⭐ |
| Gravel | ×16 | ⭐⭐⭐⭐ |
| Sand | ×16 | ⭐⭐⭐⭐ |
| Bone Meal | ×16 | ⭐⭐⭐ |
| Sugar Cane | ×8 | ⭐⭐⭐ |
| Water Bucket | ×1 | ⭐⭐ |
| Lava Bucket | ×1 | ⭐⭐ |
| ...and 50+ additional items | | |

### 🎒 Starter Kits (Group Drops)

- **Builder Kit:** Dirt + Logs + Sapling + Cobblestone
- **Farmer Kit:** Seeds + Bone Meal + Pumpkin/Melon Seeds + Water
- **Forest Kit:** 32 Oak Logs + Moss + Saplings
- **Lumberjack Kit:** Oak, Spruce, Birch and Cherry Logs
- **Desert Kit:** Sand + Cactus + Dead Bush
- **Ocean Kit:** Kelp + Sea Pickle + Lily Pad + Water
- **Coral Reef Kit:** Corals, Coral Fans, and Coral Blocks
- **Nether Builder Kit:** Blackstone + Polished Blackstone Bricks + Basalt
- **Nether Flora Kit:** Nylium + Crimson & Warped Fungi + Nether Wart
- **Nether Starter Kit:** Flint + Iron + Lava + Obsidian *(rare)*

### 🏝 Phase 2 — Mini Islands (Structures)

Lucky Blocks can generate a small **7×7 island** next to the player.

| Island | Contents |
|---|---|
| 🌳 Oak Island | Grass platform + Oak tree |
| 🌸 Cherry Island | Cherry tree + Pink Petals |
| ❄️ Snow Island | Snow platform + Ice + Spruce tree |
| 🌴 Jungle Island | Jungle tree + Cocoa + Ferns |
| 🌵 Desert Island | Solid Sandstone base + Sand + Cacti + Dead Bushes |
| 🍄 Mushroom Island | Mycelium + Giant Mushroom + Small Mushrooms |
| 🔥 Crimson Island | Crimson Nylium + Crimson Fungus Tree + Shroomlight |
| 🔵 Warped Island | Warped Nylium + Warped Fungus Tree + Shroomlight |
| 🪸 Ocean Island | Prismarine base + Water pool + Corals + Sea Pickles |
| 🐊 Mangrove Island | Mud + Mangrove Tree with roots + Propagules |
| 🌺 Lush Island | Moss platform + Azalea Tree + Spore Blossom |
| 🌾 Savanna Island | Coarse Dirt + Acacia Tree + Dry Bushes |
| 🌲 Dark Forest Island | Podzol + 2×2 Dark Oak Tree + Mushrooms |

### 🦋 Phase 3 — Rare SkyBlock Unlocks

Very rare items that unlock new progression paths:

- Turtle Egg
- Bee Nest
- Sniffer Egg
- Frogspawn
- Mob Spawn Eggs (Cow, Pig, Chicken, Sheep, Horse, Camel)
- Coral Fan
- Glow Berries
- Sea Pickle

### 💎 Phase 4 — Jackpots

Rare "Wow!" moments:

- Diamond Block
- Netherite Scrap
- Enchanted Golden Apple
- Totem of Undying
- Trident
- Elytra
- Beacon
- Heart of the Sea
- Loot-filled Shulker Box

---

## 🔧 Testing

### Quick Creative Test

```
/give @p lucky:lucky_block 64
```

Place 10 or more Lucky Blocks in a row and break them to verify the new drops.

### Checking Logs

If the addon fails to load, check:

```
.minecraft/logs/latest.log
```

Search for entries containing:

```
LuckyBlockExpansionWithDefaultBlocks
```

---

## ⚖️ Balance

This addon **does not replace** the default Lucky Block event pool—it only **adds** new events.

The new content makes up approximately **20–25%** of the total event pool.

| Category | Approximate Chance |
|---|---|
| Default Lucky Block Events | ~75% |
| Resource Drops (Phase 1) | ~18% |
| Mini Islands (Phase 2) | ~4% |
| Rare Unlocks (Phase 3) | ~2% |
| Jackpots (Phase 4) | ~1% |

---

## 📝 Version Information

- **1.0** — Resource Drops + Starter Kits + Mini Islands + Rare Unlocks + Jackpots
- **Minecraft:** 1.20.2
- **Loader:** Fabric
- **Lucky Block:** Compatible with any Fabric version for Minecraft 1.20.2

## Contributing

Contributions are welcome!

Feel free to:

- Fork the project
- Add new Lucky Block events
- Improve balance
- Fix bugs
- Create pull requests
- Share your own ideas

This project is intended to be a community-driven SkyBlock expansion for Lucky Block.


MIT License

Copyright (c) 2026 ayarem

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND.