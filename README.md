# Combo

A lightweight Minecraft plugin for **1.21+** that registers the custom **Combo Momentum** enchantment (`comboweapon:combo_momentum`) for melee weapons, rewarding consecutive hits on the same target with scaling bonus damage.

[![Modrinth](https://img.shields.io/badge/Modrinth-Download-00AF5C?style=for-the-badge&logo=modrinth&logoColor=white)](https://modrinth.com/plugin/chatblock-why_luca/)
[![Discord](https://img.shields.io/badge/Discord-Join%20Server-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.com/invite/D8DtJF2Jye)
[![Ko-fi](https://img.shields.io/badge/Ko--fi-Support-FF5E5B?style=for-the-badge&logo=ko-fi&logoColor=white)](https://ko-fi.com/why_luca)

---

## Features
* **Custom Registered Enchantment:** Adds **Combo Momentum** (up to Level 3) directly into the Minecraft enchantment registry for melee weapons.
* **Scaling Combo Damage:**
  * Every consecutive hit on the same target increases your combo by `+1`.
  * Bonus damage scales with enchantment level: up to **+100%** at Level 1, **+200%** at Level 2, and **+300%** at Level 3.
  * Displays your live combo counter, current damage bonus, and enchantment level in the action bar.
* **Balanced Combat Mechanics:**
  * Switching targets halves your current combo.
  * Taking damage or going 5 seconds without dealing damage resets your combo.
* **Natural Progression:** Obtainable through the Enchanting Table or as a rare enchanted book trade from Librarian villagers.

## Commands

| Command | Description | Permission |
| :--- | :--- | :--- |
| `/comboweapon` | Applies Combo Momentum (Lv. 1) to the item in your main hand. | `combo.comboweapon` |
| `/combobook [1-3]` | Gives an enchanted book with Combo Momentum (Level 1–3). | `combo.comboweapon` |

## Permissions

| Permission | Description | Default |
| :--- | :--- | :--- |
| `combo.comboweapon` | Allows using `/comboweapon` and `/combobook`. | `op` |

## Installation
1. Download the latest `.jar` file from Modrinth.
2. Place the file into your server's `plugins` folder (requires **Paper 1.21+**).
3. Restart your server so the custom enchantment registers cleanly during bootstrap.

## Links & Support
* 🌐 **Website:** [why-luca.bot-keep.xyz](https://why-luca.bot-keep.xyz/)
* 💬 **Discord:** [Join the Discord Server](https://discord.com/invite/D8DtJF2Jye)
* ☕ **Support:** [Buy me a coffee on Ko-fi](https://ko-fi.com/why_luca)

## License
This project is licensed under the **Combo License** – see the [License file](https://github.com/Thor-48/Combo-License-Mc-Plugin/blob/main/license.md) for details.

*Copyright © 2026 Thor_48, Why_Luca, and Luca The Fox*
