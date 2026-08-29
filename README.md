# 📦 PublicAssets

> **Centralized Distribution Hub for Open Datasets, Language Packs & Static Application Assets**

Welcome to the **PublicAssets** repository. This repository acts as an open, high-speed CDN and asset host for client applications across various projects. Large downloadable assets, binary database packs, and media files are published here and distributed globally via GitHub Releases and direct raw CDN links.

---

## 📂 Projects & Asset Directory

| Project | Category | Description | Primary Distribution |
| :--- | :--- | :--- | :--- |
| **[LexiCore](LexiCore/)** | Language Packs & Linguistic Databases | Offline SQLite language packs, translation matrices, and word corpora for the LexiCore Android vocabulary platform. | [Releases](https://github.com/ToukirMunna/PublicAssets/releases) |

---

## 🚀 How Releases Work

Large binary assets (such as `.db`, `.sqlite`, `.gz`, `.zip`, `.tflite`, etc.) are attached directly to tagged **GitHub Releases** for fast, high-bandwidth global downloads with direct HTTP resume support.

### Direct Download URL Pattern:
```
https://github.com/ToukirMunna/PublicAssets/releases/download/<tag>/<filename>
```

---

## 🛠️ Repository Layout

```
PublicAssets/
├── README.md
├── LexiCore/
│   ├── README.md
│   └── language_packs/
└── [Future Projects]/
```

---

## 📄 License & Attribution
Assets hosted in this repository are distributed for use with associated client applications. Individual datasets maintain their respective open-source and corpus licensing.
