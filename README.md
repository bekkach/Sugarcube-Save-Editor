# 🧠 SuaveSave – SugarCube Save Editor

**SuaveSave** is a lightweight, web-based tool for decompressing, editing, and re-saving encrypted SugarCube save files. It allows Twine/SugarCube players and developers to inspect and modify save states directly through the browser — no installation needed!

---

## 🚀 Features

- 🧩 **Decompress & View** SugarCube saves (Base64 + LZ-string encoded)
- ✏️ **Edit** your game progress directly
- 🔐 **Recompress** and download your modified file
- 🌐 100% browser-based, no data ever leaves your device
- 🎨 Sleek, responsive user interface

---

## 📸 Screenshot

![SuaveSave Editor Screenshot](https://your-screenshot-url.com)

---

## 🛠️ How to Use

1. **Export your save file** from a SugarCube game (usually via the "Save to Disk" or "Download Save" option).
2. Open [`index.html`](./index.html) in your browser.
3. Click `📂 Select a save file` and choose your `.save` file.
4. The decrypted save contents will appear in the text area.
5. Make any changes you want.
6. Set a filename (or keep the suggested one).
7. Click `📥 Save File (Encrypted)` to download your updated save.

---

## 📦 Local Usage

You can run it directly on your machine:

```bash
git clone https://github.com/yourusername/suavesave.git
cd suavesave
open index.html
