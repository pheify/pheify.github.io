# Pheify PS5 Controller Skin

A custom Gamepad Viewer skin for PS5 (DualSense) controllers.

## Setup

### 1. Host on GitHub Pages

1. Create a new GitHub repository (e.g. `pheify-skin`)
2. Upload all files from this folder into the repo root
3. Go to **Settings → Pages** and enable GitHub Pages from the `main` branch
4. Your skin URL will be:
   ```
   https://YOUR_USERNAME.github.io/pheify-skin/skin.css
   ```

### 2. Use with Gamepad Viewer

1. Go to [gamepadviewer.com](https://gamepadviewer.com)
2. Click the **Settings** gear icon
3. Set **Controller Type** to `PS4/PS5`
4. Paste your CSS URL into the **Custom CSS** field:
   ```
   https://YOUR_USERNAME.github.io/pheify-skin/skin.css
   ```
5. Hit **Apply** — the Pheify skin should load immediately.

### 3. Add to OBS / Streamlabs

Add a **Browser Source** in OBS with the Gamepad Viewer URL (copy it from the gamepadviewer.com address bar after applying your skin).

---

## Files

| File | Description |
|------|-------------|
| `skin.css` | Main stylesheet — point Gamepad Viewer here |
| `Base.svg` | Controller body (white + orange accents) |
| `Touchpad.svg` | Touchpad with Pheify logo |
| `Face.svg` | △ □ ○ × buttons |
| `Stick.svg` | Analog sticks (L3 / R3) |
| `Trigger.svg` | L2 / R2 triggers |
| `Bumper.svg` | L1 / R1 bumpers |
| `Dpad.svg` | Directional pad |
| `Meta.svg` | PS button |
| `Start.svg` | Options / Share buttons |
| `Disconnected.svg` | Disconnected state |
