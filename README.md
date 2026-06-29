<p align="center">
  <img src="logo.png" alt="GIFSlicer Logo" width="120" height="120">
</p>

<h1 align="center">GIFSlicer</h1>

<p align="center">
  <strong>A lightweight, efficient Android application to slice and extract frames from animated GIFs.</strong>
</p>

---

**GIFSlicer** is a clean and practical Android tool designed to extract and slice animated GIF files into individual high-quality image frames. Whether you are a game developer handling pixel art sprite sheets, an animator, or just looking to extract a specific frame from a GIF, GIFSlicer makes the process seamless and instant.

---

## ✨ Features

* **Easy Import:** Quick file picker to load any GIF directly from your device storage.
* **Frame Breakdown:** Decodes and displays all frames with precise frame-delay information (e.g., `80ms`).
* **Interactive Preview:** Built-in animated preview player with an adjustable FPS (Frames Per Second) slider to inspect animations frame-by-frame.
* **Selective Export:** Choose to export all frames or manually select/deselect specific frames (`ALL` / `NONE` controls).
* **Multiple Formats:** Export extracted frames as high-quality **PNG** or **JPEG** formats.
* **Quality Control:** Adjustable quality slider for fine-tuning compression before exporting.
* **Modern UI:** Clean, minimalist flat-design user interface with a dark mode aesthetic built for efficiency.

---

## 📸 Screenshots

| Welcome Screen | Decoded Frames & Options | Animation Preview |
|---|---|---|
| <img src="629317.jpg" width="250"> | <img src="629318.jpg" width="250"> | <img src="629319.jpg" width="250"> |

> *Note: If you move your screenshots to a specific folder (e.g., `assets/`), make sure to update the image paths in the table above.*

---

## ⚙️ How It Works

1. **Choose a GIF:** Tap the `CHOOSE GIF` button on the main screen to select your file.
2. **Review & Filter:** Look through the decoded grid of individual frames. Tap the checkboxes to select only the ones you need.
3. **Preview (Optional):** Hit the Play button in the top bar to open the preview dialog, adjust the playback FPS, and see the loop in action.
4. **Configure & Export:** Select your preferred format (**PNG** or **JPEG**), tweak the quality slider, and tap `EXPORT FRAMES` to save them directly to your device storage.

---

## 🛠️ Technical Details & Stack

* **Platform:** Android
* **Language:** Java / Kotlin
* **UI Layouts:** XML Layouts (Material Design)
* **Features:** Custom GIF decoding logic, dynamic frame rendering, and background thread image exporting.
