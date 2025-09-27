# Modern Manchu Text Font

## ✨ Project Goals

Building upon the traditional text font *Ginggulere Hergen*, this project aims to develop a new typeface for the Manchu script. The glyphs will be adjusted for improved appearance in various formal contexts, including printing and PDF rendering. Additionally, a **bold** version and an *italic* version of the typeface will be developed.

The **bold** style has been particularly designed rather than being automatically generated.

## 📜 License

This project operates under the [SIL Open Font License](https://openfontlicense.org/). This means all source files, documentation, and outputs are open source.

## 🚀 Quick Start: Installation

For the easiest start, follow these three steps:

1.  **Download:** Get the compiled font files (.ttf or .otf) from the [Release folder](https://github.com/Hasutai/ManchuTextFont/tree/main/Release).
2.  **Install:** Choose **either** the **TrueType (.ttf)** or **OpenType (.otf)** version. You must install both the regular and bold styles (e.g., `Sungar Folon-regular.otf` and `Sungar Folon-bold.otf`). **Do not install both the .ttf and .otf versions** as they can conflict and overwrite each other, causing confusion. For details on which version is best for your needs, see [Font File Versions](#font-file-versions).
3.  **Keyboard (Optional but Recommended):** Download and install the custom [keyboard layout(s)](https://github.com/Hasutai/ManchuTextFont/tree/main/Release/Keyboard%20Layouts) to unlock all special characters and features of the font.

---

## 🛠️ Detailed Installation & Usage Notes

### Font File Versions

The font has been compiled into two versions: an [OpenType version](https://github.com/Hasutai/ManchuTextFont/tree/main/Release/OpenType) and a [TrueType version](https://github.com/Hasutai/ManchuTextFont/tree/main/Release/TrueType).

While the **OpenType** version offers better performance for screen display (e.g., in Microsoft Word), its embedding in PDFs generated via some software, such as Microsoft Word's "Save As" option, is not well supported. (However, using the "Print to PDF" option in Microsoft Word still allows for proper embedding of the OpenType version.) Therefore, users should choose the version that best suits their specific usage.

### Encoding Notes

This font uses an amended encoding based on the conventional Unicode for Manchu.

* **Encoding of `k`, `g`, and`h`:** The consonants for `ᡴᡝ/ke`, `ᡤᡝ/ge`, and `ᡥᡝ/he` have been separated from `ᡴᠠ/ka`, `ᡤᠠ/ga`, and `ᡥᠠ/ha`. Instead, they have been merged into the group of `ᠺᠠ/k'a`, `ᡬᠠ/g'a`, and `ᡭᠠ/h'a`. This means that when typing with this font, users will need to use the keyboard keys corresponding to `ᠺ/k'`, `ᡬ/g'`, and `ᡭ/h'` for characters like `ke`, `ki`, `ku`, and so on. There are no changes for `ka`, `ko`, `kv`, and `k'a`, `k'o`, etc.

* **Encoding of `ᡷᡳ/jy` and `ᡱᡳ/c'y`:** For more linguistic property, the new approach suggests the vowel is a new letter (see the [keyboard layouts](https://github.com/Hasutai/ManchuTextFont/tree/main/Release/Keyboard%20Layouts)), while the consonants are left to the common `ᡷ/j` and `ᡱ/c`. **The font still supports the old conventional encoding** of `ᡷᡳ/jy` and `ᡱᡳ/c'y` for backward compatibility.

* **Umlaut Vowels:** An innovation is an umlaut mark upon the vowels (you can type them by **Shift+A/E/O/U** with the new keyboard layout) to denote `[æ]`, `[e]`, `[œ]`, and `[y]`. Although not an element of the traditional Manchu alphabet, this is designed to be useful for the extension of the Manchu alphabet to other Tungusic languages and for handling loan words.

### Keyboard Layouts

I have made two keyboard layouts: one for the Manchu character subset and one for the Sibe character subset.

By using either of them, the user could type all special characters belonging to the other subset (see the layout image), the only difference being that the most commonly used keys are primarily designated for the corresponding language. Importantly, there is no functional problem with installing both keyboard layouts simultaneously, **despite a potential glitch** in their display name in the language bar.

---

## 🤝 Contributing & Technical Details

We welcome your contributions to help make this font better! You can make your own changes based on the provided source files. Please refer to the [Contributinon Folder](https://github.com/Hasutai/ManchuTextFont/tree/main/Contribution) for detailed instructions.

The glyphs for this typeface are built with **FontLab 8** software, as well as the transformation scripts, or the OpenType features, which are essential for the Manchu script, are now coded directly within the FontLab project file [Sungar Folon.vfc](https://github.com/Hasutai/ManchuTextFont/blob/main/Contribution/SungarFolon/Sungar%20Folon.vfc).

The source files for the keyboard layouts are also included in the **[Contribution folder](https://github.com/Hasutai/ManchuTextFont/tree/main/Contribution/KeyboardLayout)**. These layouts were built with **Microsoft Keyboard Layout Creator 1.4**.
