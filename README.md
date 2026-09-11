# ⚔️ Sons Of Odin — Valheim Mod Pack

Everything you need to play on the **Sons Of Odin** dedicated server, in one download.

This pack is for **Valheim 1.0 "Deep North"** and bundles the exact mods (and versions) the server runs, so you can install once and join. No mod manager required.

---

## 🌐 Server Info

| | |
|---|---|
| **Server name** | `Sons Of Odin` |
| **Password** | `Valhalla` |
| **Crossplay** | Off (Steam) |

**To join:** in Valheim, go to **Start → Join Game → Community**, search **`Sons Of Odin`**, and enter the password `Valhalla`. (You can also use **Join by IP** if the server owner has shared the address.)

---

## 📦 What's in the box

- `SonsOfOdin-ModPack.zip` — all the mods (extract into your `BepInEx\plugins` folder).
- `BepInExPack_Valheim-5.4.2350.zip` — the BepInEx mod loader (one-time setup, only if you don't already have it).

---

## 🛠️ Installation (5 minutes)

> You need the PC (Steam) version of Valheim. These files go inside your Valheim install folder:
> `...\Steam\steamapps\common\Valheim`
> (In Steam: right-click **Valheim → Manage → Browse local files**.)

### Step 1 — Install BepInEx (one time only)
Skip this if you already run BepInEx mods.
1. Open `BepInExPack_Valheim-5.4.2350.zip`.
2. Inside, open the `BepInExPack_Valheim` folder.
3. Copy **everything inside it** (`BepInEx`, `doorstop_libs`, `winhttp.dll`, `doorstop_config.ini`, etc.) into your **Valheim** folder.
4. Launch the game once, then quit — this creates the `BepInEx\plugins` folder.

### Step 2 — Install the mod pack
1. Open `SonsOfOdin-ModPack.zip`.
2. Extract **all the mod folders inside it** into:
   `...\Steam\steamapps\common\Valheim\BepInEx\plugins`
3. That's it — your `plugins` folder should now contain `Thor`, `Odin`, `Loki`, `Jotunn`, and the rest.

### Step 3 — Play
Launch Valheim, join **Sons Of Odin**, and you're in. Press **F1** in-game to open the mod config menu.

---

## 🧩 Included mods

| Mod | Version | Author |
|---|---|---|
| Thor | 1.0.2 | MrBumChinz |
| Odin | 1.2.7 | MrBumChinz |
| Loki — Auto Map Pins | 1.4.2 | MrBumChinz |
| Jötunn (The Valheim Library) | 2.30.0 | Jötunn Team |
| ConditionalConfigSync | 1.0.5 | shudnal |
| YamlDotNet | 16.3.1 | ValheimModding |
| Longship Upgrades | 1.0.18 | shudnal |
| Extra Slots | 1.2.1 | shudnal |
| Extra Slots Custom Slots | 1.0.22 | shudnal |
| Hip Lantern | 1.1.6 | shudnal |
| Configuration Manager (Official BepInEx) | 18.4.1 | BepInEx Team |
| Better Ladders | 0.2.0 | see CREDITS |
| Speedy Paths | 1.0.8 | see CREDITS |
| Minimal Status Effects | 1.0.7 | see CREDITS |

Requires **BepInExPack Valheim 5.4.2350** (included).

Full author and source links are in [CREDITS.md](CREDITS.md).

---

## 🔄 Updating

When the server updates, re-download this pack, delete the old mod folders from `BepInEx\plugins`, and extract the new `SonsOfOdin-ModPack.zip` again. Your config files in `BepInEx\config` are kept.

---

## ❓ Troubleshooting

- **Game crashes on launch / mods don't load** — make sure BepInEx (Step 1) was installed correctly; you should see a `BepInEx\plugins` folder.
- **"Incompatible version" when joining** — your pack is out of date; re-download and reinstall.
- **No F1 menu** — confirm the `ConfigurationManager` folder is inside `BepInEx\plugins`.
- **Want a clean start** — delete the `BepInEx\plugins` folder contents and redo Step 2.

---

## 📜 Legal / License

This is a **free, non-commercial community mod pack** created so players can easily join the Sons Of Odin server. It is **never sold**. All third-party mods remain the property of their respective authors and are redistributed here for convenience with credit and source links — see [CREDITS.md](CREDITS.md). If you are a mod author and would prefer your mod not be bundled here, open an issue and it will be removed promptly.
