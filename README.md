# Guhs Pack: de officiële Guhs-server

Een [packwiz](https://packwiz.infra.link/)-pack voor de officiële **Guhs**-server (**guhs.nl**, Minecraft 26.1.2 + NeoForge 26.1.2.112).
De server en de Prism-instance halen hun mods allebei uit dit pack, dus je hebt altijd precies de goede mods.

## 🇳🇱 Spelen in 3 stappen (Prism Launcher)
1. Installeer [Prism Launcher](https://prismlauncher.org/) en log in met je Microsoft-account.
2. **Add Instance → Import** en plak deze URL:
   `https://pack.guhs.nl/prism/guhs-server-instance.zip`
3. Start **Guhs Server**. De eerste keer worden alle mods gedownload (even geduld). Kies **Multiplayer → Guhs Server** (`guhs.nl`). Vahoeg!

Bij elke start kijkt de instance of er nieuwe mods of updates zijn en haalt die vanzelf binnen.

## Mods
| Mod | Side |
|---|---|
| Guhs (nieuwste versie) | both |
| GeckoLib, JEI, Jade, JourneyMap, AppleSkin, Lootr, Architectury API, ModernFix, FerriteCore, spark | both |
| FTB Library, FTB Teams, FTB Filter System, FTB Quests, FTB Essentials | both |
| Sodium, Mouse Tweaks | client |
| Chunky, BlueMap | server |

## Maintainers
Edit with `packwiz` in this folder (e.g. `packwiz modrinth add <slug>`, `packwiz update --all`, `packwiz refresh`), then commit and push.
GitHub Pages publishes it, the server picks it up on its next (nightly) restart, and players pick it up on their next launch.
New Guhs version: `packwiz url add guhs https://github.com/coecomber/guhs/releases/download/vX.Y.Z/guhs-X.Y.Z.jar --meta-folder mods --force`.
Bump `version` in `pack.toml`.
