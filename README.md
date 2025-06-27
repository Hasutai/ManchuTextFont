# Modern Manchu Text Font

## ✨ Project Goals

Building upon the traditional text font "Ginggulere Hergen", this project aims to develop a new typeface for the Manchu script. The glyphs will be adjusted for improved appearance in various formal contexts, including printing and PDF rendering. Additionally, a **bold** version and an *italic* version of the typeface will be developed.

## 📜 License

This project operates under the [SIL Open Font License](https://openfontlicense.org/). This means all source files, documentation, and outputs are open source.

## 🚀 Getting Started

### ⬇️ Installation

You can download and directly install the compiled font files (.ttf or .otf) without any building requirements.

The font has been compiled into two versions: an [OpenType version](https://github.com/Hasutai/ManchuTextFont/tree/main/Release/OpenType) and a [TrueType version](https://github.com/Hasutai/ManchuTextFont/tree/main/Release/TrueType). Both have their pros and cons. While the OpenType version offers better performance for screen display (e.g., in Microsoft Word), its embedding in PDFs generated via some softwares, such as Microsoft Word's "Save As" option, is not well supported. (However, using the "Print to PDF" option in Microsoft Word still allows for proper embedding of the OpenType version.) Therefore, users should choose the version that best suits their specific usage.

**Important Note on Encoding:** This font uses an amended encoding based on the conventional Unicode for Manchu. Specifically, the consonants for `ᡴᡝ/ke`, `ᡤᡝ/ge`, and `ᡥᡝ/he` have been separated from `ᡴᠠ/ka`, `ᡤᠠ/ga`, and `ᡥᠠ/ha`. Instead, they have been merged into the group of `ᠺᠠ/k'a`, `ᡬᠠ/g'a`, and `ᡭᠠ/h'a`. This means that when typing with this font, users will need to use the keyboard keys corresponding to `ᠺ/k'`, `ᡬ/g'`, and `ᡭ/h'` for characters like `ke`, `ki`, `ku`, and so on. There are no changes for `ka`, `ko`, `kv`, and `k'a`, `k'o`, etc.

### 🤝 Contributing

We welcome your contributions to help make this font better! You can make your own changes based on the provided source files. Seeking for your help to make it better.

## 🛠️ Technical Details

The glyphs for this typeface are built with FontLab VI software. The transformation scripts, or the OpenType features, which are essential for the Manchu script, are edited with Microsoft VOLT.

Accordingly, the project's source files contain a FontLab project file (.vfc) and a MS VOLT project file (.vtp).

**Note for Contributors:** Despite the OpenType features will be ultimately encoded in, and could be directly edited within the FontLab project file, we require summiteers include a MS VOLT project file whenever update a open-type feature, together with a correspondingly updated FontLab project file.
