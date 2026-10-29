# The-Rick-Game
For Friends

# How to Play Rickdiculous Adventure

Oct 29, 2026 · @Sir

## Before you start

The game runs on your own computer in your web browser. It takes about 5 minutes to set up the first time. You don't need a Claude account or a GitHub account.

You need:

- The zip file **rickdiculous-adventure-2026-10-29.zip** 
- Chrome, Edge or Safari
- Python 3 (free; the steps below show how to get it)
- An Xbox controller for two-player air support (optional for solo)

Don't double-click `index.html`. The game won't load that way. Follow the steps for your computer below instead.

Multiplayer online doesn't work in this version. Single-player runs normally.

## Mac

1. **Unzip the game.** Double-click **rickdiculous-adventure-2026-10-29.zip** in your Downloads folder. A folder called **rickdiculous-adventure** appears next to it.
2. **Open Terminal.** Press **Command + Space**, type `Terminal`, and press **Return**.
3. **Go to the game folder.** Type this and press **Return**:

   ```
   cd ~/Downloads/rickdiculous-adventure
   ```

   If you unzipped it somewhere else, type ` cd  ` (with a space after it), drag the folder into the Terminal window, and press **Return**.
4. **Start the game server.** Type this and press **Return**:

   ```
   python3 -m http.server 8000
   ```

   You'll see `Serving HTTP on :: port 8000`. If a pop-up asks to install developer tools, click **Install**, wait for it to finish, then run the command again.
5. **Play.** Open your browser and go to:

   ```
   http://localhost:8000
   ```
6. **Stop when you're done.** Click the Terminal window and press **Control + C**, or just close it.

Next time, repeat steps 2 to 5.

## Windows

1. **Install Python (first time only).** Go to [python.org/downloads](https://www.python.org/downloads/) and click the yellow **Download Python** button. Open the installer. On the first screen, **check the box "Add python.exe to PATH"**, then click **Install Now**.
2. **Unzip the game.** In your Downloads folder, right-click **rickdiculous-adventure-2026-10-29.zip** and choose **Extract All…**, then click **Extract**.
3. **Open the game folder.** In the folder that opens, keep double-clicking into **rickdiculous-adventure** until you see `index.html`, `sfa.js` and `sfd.js`.
4. **Open Command Prompt in that folder.** Click the address bar at the top of the File Explorer window (where the folder path shows), type `cmd`, and press **Enter**. A black window opens.
5. **Start the game server.** Type this and press **Enter**:

   ```
   python -m http.server 8000
   ```

   You'll see `Serving HTTP on :: port 8000`. If it says Python wasn't found, or the Microsoft Store opens, type this instead:

   ```
   py -m http.server 8000
   ```
6. **Play.** Open Chrome or Edge and go to:

   ```
   http://localhost:8000
   ```
7. **Stop when you're done.** Click the black window and press **Ctrl + C**, or just close it.

Next time, repeat steps 3 to 6.

## If something goes wrong

| What you see | Fix |
| --- | --- |
| Black or blank screen | Make sure the address is `http://localhost:8000`, not a file path. The Terminal or Command Prompt window must stay open while you play. |
| `No such file or directory` (Mac) | The folder isn't in Downloads. Use the drag-the-folder method in Mac step 3. |
| `Address already in use` | The game is already running in another window. Close that window, or change `8000` to `8001` in the command and the browser address. |
| Python not found (Windows) | Use the `py` command, or reinstall Python with "Add python.exe to PATH" checked. |
| A Windows Firewall pop-up | Click **Cancel**. The game still works because it only runs on your computer. |
| Controller doesn't respond | Plug it in, then refresh the browser page and press a button. |
| Game loads slowly | It's about 20 MB. The first load can take several seconds. |



## Credits

Rickdiculous Adventure is built on 3D models, code and art from over 25 other creators. Most models come from Sketchfab under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/), which allows reuse with credit. Every model was reduced, rescaled, re-rigged or re-textured for the game.

Some links are marked "search" because the game's code credits those models by name but doesn't record their page URLs. Those links open a Sketchfab search for the title.

### Characters and Rick and Morty props

All are from Sketchfab under CC BY 4.0.

| Model | Creator | Used as | Link |
| --- | --- | --- | --- |
| Rick T-Pose | CzernO | Rick, playable character | [search](https://sketchfab.com/search?q=Rick+T-Pose&type=models) |
| Rick and Morty Morty Smith | zairiq-123 | Morty, companion | [search](https://sketchfab.com/search?q=Rick+and+Morty+Morty+Smith&type=models) |
| Mr Meeseks | ElSalawwy | Mr. Meeseeks | [search](https://sketchfab.com/search?q=Mr+Meeseks&type=models) |
| Butter Robot Rick and Morty | Dylan Spin | Butter Robot enemies | [search](https://sketchfab.com/search?q=Butter+Robot+Rick+and+Morty&type=models) |
| Portal gun (Rick and Morty) | kreems | Portal gun | [search](https://sketchfab.com/search?q=Portal+gun+Rick+and+Morty&type=models) |
| Rick And Morty - Laser Pistol | nickscheetz | Laser pistol | [search](https://sketchfab.com/search?q=Rick+And+Morty+Laser+Pistol&type=models) |
| Rick's ship from Rick and Morty | Micheal-Holloway | Rick's ship | [model](https://sketchfab.com/3d-models/ricks-ship-from-rick-and-morty-71dce3dd627146e9a1e4776a490e786b) |
| Meeseeks Box | pythagean | Meeseeks Box | [model](https://sketchfab.com/3d-models/meeseeks-box-88525f59bb974271a0933fc7608672c2) |
| Realistic Plumbus | jason.lp.davis | Plumbus | [model](https://sketchfab.com/3d-models/realistic-plumbus-acf9a9b71fed417f8bfb9302cd65440f) |
| Smith House - Rick and Morty house full | Creator not recorded | Smith house | [search](https://sketchfab.com/search?q=Smith+House+Rick+and+Morty&type=models) |

The rider and bots in Free Skate and Waves use "Male Human Low-Poly Base" by [Fhraze](https://sketchfab.com/Fhraze), which is under the Sketchfab Standard license rather than CC BY.

### Weapons, vehicles, buildings and props

All are from Sketchfab under CC BY 4.0 unless the License column says otherwise.

| Model | Creator | License | Link |
| --- | --- | --- | --- |
| Low-Poly G17 | TastyTony | CC BY 4.0 | [model](https://sketchfab.com/3d-models/low-poly-g17-60efc54ac59e47d18bdff94b2f5144ff) |
| Low-Poly HK MP5 | TastyTony | CC BY 4.0 | [model](https://sketchfab.com/3d-models/low-poly-hk-mp5-80980f757c2c463ebc73460a31611652) |
| Low-Poly AKM | TastyTony | CC BY 4.0 | [model](https://sketchfab.com/3d-models/low-poly-akm-849b7cdf8622487485febc40db89e734) |
| Low-Poly Remington 870 | TastyTony | CC BY 4.0 | [model](https://sketchfab.com/3d-models/low-poly-remington-870-8766498ce778479aa03c3b6078937510) |
| Low-Poly L115A3 | TastyTony | CC BY 4.0 | [model](https://sketchfab.com/3d-models/low-poly-l115a3-a795adf5f8dd4a2294210d427cbb0e58) |
| Low-Poly RPG-7 | TastyTony | CC BY 4.0 | [model](https://sketchfab.com/3d-models/low-poly-rpg-7-5243ac034391491f9a47f797ea212afe) |
| Low-Poly M67 | TastyTony | CC BY 4.0 | [model](https://sketchfab.com/3d-models/low-poly-m67-c233d27d001d4d19aab9f35bf171f1a5) |
| Stylized AA12 (Slug) | TemmieTim | CC BY 4.0 | [search](https://sketchfab.com/search?q=Stylized+AA12+Slug&type=models) |
| Sniper Rifle HPSR9 Rig | TemmieTim | CC BY 4.0 | [search](https://sketchfab.com/search?q=Sniper+Rifle+HPSR9+Rig&type=models) |
| AR-15 style rifle | Creator not recorded | Not recorded | [search](https://sketchfab.com/search?q=AR-15+style+rifle&type=models) |
| Desert Eagle | Creator not recorded | Not recorded | [search](https://sketchfab.com/search?q=Desert+Eagle&type=models) |
| P90 | Creator not recorded | Not recorded | [search](https://sketchfab.com/search?q=P90&type=models) |
| Lockheed Martin F-22 Raptor | andertan | CC BY 4.0 | [search](https://sketchfab.com/search?q=Lockheed+Martin+F-22+Raptor&type=models) |
| Pan Am Airbus A310-324 (drop plane) | OUTPISTON | **CC BY-NC-SA 4.0** | [search](https://sketchfab.com/search?q=Pan+Am+Airbus+A310-324&type=models) |
| Dji FPV by SDC - High performance drone | SDC PERFORMANCE (@Lambo_SC04) | CC BY 4.0 | [model](https://sketchfab.com/3d-models/dji-fpv-by-sdc-high-performance-drone-d471ea8c6235457b8e131842e2cf3783) |
| Nevada Special '92 - Retro Styled Model | Daniel Zhabotinsky | CC BY 4.0 | [model](https://sketchfab.com/3d-models/nevada-special-92-retro-styled-model-f4ef1099f7de41d2a9867c6eae5d5275) |
| Vaquero '80 - Retro Style Model | Daniel Zhabotinsky | CC BY 4.0 | [model](https://sketchfab.com/3d-models/vaquero-80-retro-style-model-39b926a032364d4da170a1bd0deb7fb9) |
| Thunderbolt '96 - Retro Styled Model | Daniel Zhabotinsky | CC BY 4.0 | [model](https://sketchfab.com/3d-models/thunderbolt-96-retro-styled-model-b99b7f2db19f49638302f4181f06b64a) |
| Casini '75 - Retro Styled Model | Daniel Zhabotinsky | CC BY 4.0 | [model](https://sketchfab.com/3d-models/casini-75-retro-styled-model-52d1fddd66ce4edfb360b09aa0a1b039) |
| El Triello '70 - Retro Styled Model | Daniel Zhabotinsky | CC BY 4.0 | [model](https://sketchfab.com/3d-models/el-triello-70-retro-styled-model-fefa94b06cce47ab8ce4d96b973336dd) |
| Slater MK1 '93 - Retro Style model | Daniel Zhabotinsky | CC BY 4.0 | [model](https://sketchfab.com/3d-models/slater-mk1-93-retro-style-model-8b0db2a59de243dab175090e3c9c98a7) |
| French delivery van - Low poly model | Daniel Zhabotinsky | CC BY 4.0 | [model](https://sketchfab.com/3d-models/french-delivery-van-low-poly-model-a350a422d200485ea57778dc42139edc) |
| Chapman '73 Cop cruiser - Low poly model | Daniel Zhabotinsky | CC BY 4.0 | [model](https://sketchfab.com/3d-models/chapman-73-cop-cruiser-low-poly-model-b71558486d024ecc8dc4abbb1263f022) |
| Fairheaven LT '80 Taxi - Low poly model | Daniel Zhabotinsky | CC BY 4.0 | [model](https://sketchfab.com/3d-models/fairheaven-lt-80-taxi-low-poly-model-7da68ec2677f4abd8e31e9998b497a67) |
| Downtown Buildings Set - Low Poly model | Daniel Zhabotinsky | CC BY 4.0 | [model](https://sketchfab.com/3d-models/downtown-buildings-set-low-poly-model-7378e7fb9c914c39880d9913a6f4e1d6) |
| Midcity Buildings Set - Low Poly model | Daniel Zhabotinsky | CC BY 4.0 | [model](https://sketchfab.com/3d-models/midcity-buildings-set-low-poly-model-d5cbc471d20c4c9da31c3df656648916) |
| Industrial Buildings Set - Low poly models | Daniel Zhabotinsky | CC BY 4.0 | [model](https://sketchfab.com/3d-models/industrial-buildings-set-low-poly-models-e0b0d0342be24e6c923319991a2a4d3d) |
| Rural Buildings Set - Low Poly models | Daniel Zhabotinsky | CC BY 4.0 | [model](https://sketchfab.com/3d-models/rural-buildings-set-low-poly-models-51ab7e74bac347a89725f1d22b928edf) |
| Brownstone Building Set - Low poly model | Daniel Zhabotinsky | CC BY 4.0 | [model](https://sketchfab.com/3d-models/brownstone-building-set-low-poly-model-b15e6344acd844eabc823e1cc8332574) |
| Future City | Creator not recorded | Not recorded | [search](https://sketchfab.com/search?q=Future+City&type=models) |
| Low-poly Urban Street Props Pack (PS1 Style) | S1lMoon | CC BY 4.0 | [model](https://sketchfab.com/3d-models/low-poly-urban-street-props-pack-ps1-style-381b65d98a5b4e3886ac2acace7e5c74) |
| Low Poly Construction Assets | 99.Miles | CC BY 4.0 | [model](https://sketchfab.com/3d-models/low-poly-construction-assets-5c134526af464b5389f6c8a29fddeaff) |
| Low Poly Kids Playground | 99.Miles | CC BY 4.0 | [model](https://sketchfab.com/3d-models/low-poly-kids-playground-61c6f6f70db14bbb89ecdfa04b99bbc6) |
| Low Poly Road Closed Barrier - Game Ready | Rashad Ibrahimli | CC BY 4.0 | [model](https://sketchfab.com/3d-models/low-poly-road-closed-barrier-game-ready-af50e8d36c7e481c8ddc375ce751c1d6) |
| Petron Gas Station | imin96 | CC BY 4.0 | [model](https://sketchfab.com/3d-models/petron-gas-station-f4971d0f40c14d4c926216413a4f6d29) |
| Arcade Machine | Bruno Macena | CC BY 4.0 | [model](https://sketchfab.com/3d-models/arcade-machine-e9f530f79c674880ad48ff23b5cf5ed1) |

### Code, fonts and lighting

| Work | Creator | License | Used for | Link |
| --- | --- | --- | --- | --- |
| three.js r128 (core, GLTFLoader, RGBELoader, meshopt decoder, bloom post-processing) | mrdoob and three.js contributors | MIT | 3D rendering engine | [github.com/mrdoob/three.js](https://github.com/mrdoob/three.js) |
| rotorift | szabolevi98 | **AGPL-3.0** | FPV drone flight model | [github.com/szabolevi98/rotorift](https://github.com/szabolevi98/rotorift) |
| Sky HDRI | Poly Haven, via the pmndrs/assets pack | CC0 | Sky and scene lighting | [polyhaven.com](https://polyhaven.com) · [pmndrs/assets](https://github.com/pmndrs/assets) |
| Anton | Vernon Adams | SIL Open Font License | Display font | [Google Fonts](https://fonts.google.com/specimen/Anton) |
| Barlow Condensed | Jeremy Tribby | SIL Open Font License | Interface font | [Google Fonts](https://fonts.google.com/specimen/Barlow+Condensed) |

## Rights and license notes

Rick and Morty, its characters and its designs belong to Adult Swim and Warner Bros. Discovery. This is an unofficial, non-commercial fan project with no affiliation or endorsement. The fan-made models above are credited to their modelers, but their licenses cover only the modelers' own work, not the characters themselves.

- **CC BY 4.0:** reuse and modification are allowed with credit to the creator ([license](https://creativecommons.org/licenses/by/4.0/)).
- **CC BY-NC-SA 4.0** (Airbus drop plane): no commercial use, and adaptations must keep the same license ([license](https://creativecommons.org/licenses/by-nc-sa/4.0/)).
- **AGPL-3.0** (rotorift flight model): anyone who publishes a modified version must share its source under AGPL-3.0 ([license](https://www.gnu.org/licenses/agpl-3.0.html)).
- **Sketchfab Standard** (Fhraze's base body): Sketchfab's store license, not a Creative Commons license.

