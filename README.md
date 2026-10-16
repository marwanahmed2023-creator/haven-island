# Haven Island

A browser-based, low-poly 3D island survival and exploration game.

## Play locally
Open `index.html` in a modern browser with internet access. The game loads Three.js from jsDelivr, so an internet connection is needed.

## Controls
- **WASD** to move (movement keys, speed, and mouse sensitivity are adjustable in **Settings**)
- **Mouse** to look around
- **Click** to gather/use items
- **E** to interact
- **C** to open the crafting table
- **J** to open the explorer journal
- **1–8** to select a tool
- **Esc** to release the mouse

On touch screens, use the on-screen movement controls and drag the world to look around.

## Publish with GitHub Pages
1. Make this repository public if you're using GitHub Free.
2. Open **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to **GitHub Actions**.
4. Open the **Actions** tab and run **Deploy Haven Island to GitHub Pages** if it doesn't start automatically.
5. The expected site URL is `https://marwanahmed2023-creator.github.io/haven-island/`.

## 3D asset credits
- Trees and rocks use models from **Kenney Nature Kit**, licensed CC0: https://kenney.nl/assets/nature-kit
- Wildlife visuals use the **Deer Grazing**, **Red Fox**, and **Tree Squirrel** GLB models from Innerscene's public-domain library, released under CC0: https://www.innerscene.com/tools/library/3d-parts/deer-grazing-f586dbe8 · https://www.innerscene.com/tools/library/3d-parts/red-fox-e5cb59a3 · https://www.innerscene.com/tools/library/3d-parts/tree-squirrel-6499352e
- The models load from Innerscene's public GLB endpoints at runtime. If an external model cannot load, the game keeps its built-in smooth procedural animal fallback.
- Three.js and its GLTFLoader are used under the Three.js MIT license: https://github.com/mrdoob/three.js/blob/dev/LICENSE

## Game notes
Haven Island is an original project inspired by the broad survival-crafting genre. It does not include Tribals.io proprietary code or assets. The current version is a playable foundation; the longer expedition and progression can be expanded in future updates.
