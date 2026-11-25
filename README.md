# Block Yard 3D

A cozy 3D village builder that runs in your browser. Build a house, grow crops, keep animals, and keep your villagers happy.

**No install, no build step.** Everything is one HTML file plus [Three.js](https://threejs.org) loaded from a CDN.

## How to play

- Pick a material and tap or drag to place blocks exactly where you tap. Tapping an existing block **replaces** it with your material. **Erase** removes anything, even the ground and trees.
- Chop the **forest** (logs give wood), or switch the background forest off with **Forest**.
- Sell eggs, milk, wood and spare wheat with **Sell goods**, and spend coins on chickens, cows and horses.
- Build a sealed room with a **2-tall door** and put **Beds** inside. Tom and Mira move in, work by day and sleep at night.
- Plant **Wheat** and **Cotton** on grass or dirt. Tap ripe crops to harvest them.
- Add **chickens, cows and horses**. Tap an animal to feed it one wheat. Fed chickens lay eggs and fed cows give milk.
- Villagers have five needs: home, food, clothes, company and light. Use **Sew outfit** (3 cotton) for clothes.
- Tap a villager, or press **Ask villager**, for compliments and hints.
- Use **View** and **Tilt** to rotate the 3D camera. Water flows downhill, rain helps crops grow.
- Your progress is saved in the browser.

## Run locally

Open `index.html` in a modern browser (internet needed once for the Three.js CDN).

`classic.html` is the earlier 2.5D canvas version, with no WebGL needed.

## Publish with GitHub Pages

1. Create a new repository on GitHub, for example `block-yard`.
2. Push these files (see below).
3. In the repository go to **Settings > Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
4. Your game will be live at `https://<your-username>.github.io/block-yard/`.

## Push to GitHub

```bash
cd block-yard
git init
git add .
git commit -m "Block Yard 3D: village builder"
git branch -M main
git remote add origin https://github.com/<your-username>/block-yard.git
git push -u origin main
```

With the GitHub CLI: `gh repo create block-yard --public --source=. --push`

## Credits

Built with [Three.js](https://threejs.org) (MIT). Game code is MIT licensed, see `LICENSE`.
