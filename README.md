# ender_recipe_mod
A simple Minecraft mod that adds logical vanilla crafting recipes for Blaze Rods and Ender Pearls.

---

## 📌 Repository Structure
This repository acts as a multi-version source hub. Inside each folder, you can inspect the exact recipe JSON syntax and mod metadata configurations for different generations of Minecraft:
* `Fabric;Forge_1.17~1.20.5,NeoForge1.20.2~1.20.5/` -> Legacy syntax (`recipes` plural folder / `item` result format)
* `Fabric;Forge_1.20.6~1.21.1,NeoForge1.20.6~1.21.1/` -> Transition syntax (`recipe` singular folder / `id` result format)
* `Fabric;Forge_1.21.2~26.2,NeoForge1.21.2~26.2/` -> Latest syntax (`recipe` singular folder / simpler ingredients format)
* `ender_recipe_addon-bedrockedition/` -> Bedrock Edition Addon (`recipes` plural folder / classic components format)

---

## 🛠️ Added Recipes

### 1. Blaze Rod
**Crafting Table Grid:**

`[Gold Nugget]` `[Glowstone Dust]` `[Gold Nugget]`

`[Glowstone Dust]` `[Stick]` `[Glowstone Dust]`

`[Crimson Roots]` `[Crimson Roots]` `[Crimson Roots]`

### 2. Ender Pearl (Yields x2)
**Crafting Table Grid:**

`[Flint]` `[Black Dye]` `[Flint]`

`[Black Dye]` `[Emerald]` `[Black Dye]`

`[Warped Roots]` `[Warped Roots]` `[Warped Roots]`

### 3. Black Dye (Yields x2)

* `[Black Wool]` x1 ➔ `[Black Dye]` x2

---

## ⚠️ Notes & Policies
* **Installation**: 
  * **Java Edition**: For multiplayer, this mod must be installed on **both the Client and Server sides** to ensure your in-game recipe book displays the textures correctly.
  * **Bedrock Edition**: Simply import the `.mcaddon` file into your game and activate it under the Behavior Packs section of your world settings.
* **License & Anti-Plagiarism Policy**: 
  This project is licensed under **CC-BY-NC-SA-4.0**. You are free to include this mod in any modpack or addon list, provided it is for non-commercial use and clearly credits the author (**Runo98112 or runo-98112**).
  However, **impersonating the author, re-uploading this source code under a false identity, or falsely claiming ownership of this project is strictly prohibited under any circumstances.** Any copyright infringement or unauthorized re-distribution without proper attribution will be reported immediately to GitHub and Modrinth for permanent removal.
