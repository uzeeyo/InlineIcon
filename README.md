# 🧩 InlineIcon for Adobe InDesign

### Automate your card design workflow

InlineIcon is a free InDesign plugin that replaces placeholder text with icons automatically.  
I built it for my own  workflow but am releasing it for free to help others in the community.

If there’s enough interest, I may release a paid version with additional features or support for older InDesign versions.

---

## ✨ Features

- Automatically replaces text like `Lose 1 <Heart>` with an inline icon — e.g. `Lose 1 ❤️`
- Processes every text frame in the active document
- Links imported SVGs, so updates in Illustrator are instantly reflected in InDesign
- Works seamlessly within your existing InDesign workflow

---

## 💡 Why It’s Useful

- InDesign doesn’t natively support replacing text with images  
- Font-based icon methods require custom (and to my knowledge, paid) multicolor fonts  
- Iteration can clutter your installed fonts
- InlineIcon imports your SVG icons directly — no font conversion needed  
- *Nandeck* exists, but I didn't find it intuitive and didn't want to spend the time learning it so I spent even more time writing my own plugin  
- This plugin lets you stay inside InDesign with all its features while simplifying icon management

---

## 🧰 How to Use

-  **New Icons...** — Import multiple standalone icons, each with their own size and vertical offset  
-  **New Group...** — Import a set of icons that share the same size and vertical offset  
-  Use the **X** button to remove icons

---

## ⚠️ Limitations

- Icon definitions are **not saved** between sessions — they’ll need to be recreated when InDesign restarts
- Indesign's API doesn't provide a way to read a text frame's content if the content is overset so make sure your frame is large enough
- Currently supports **SVG files only**  
- Requires **Adobe InDesign 20.5.0** (or newer) and likely **Creative Cloud** for installation

---

## 📦 Installation

1. Download the latest release from the **Releases** panel on the right  
2. Open the `.ccx` file and allow **Creative Cloud** to install it  
3. In InDesign, go to **Plugins → InlineIcon → InlineIcon** from the top menu bar

---

## 💬 Support

- 📧 Email: [jordan@minott.dev](mailto:jordan@minott.dev)  
- 🐞 Report bugs or suggest features: [Create an Issue](../../issues)

---
