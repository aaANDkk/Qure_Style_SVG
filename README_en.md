# Qure-Style-SVG

[English](README_en.md) · [简体中文](README.md)

A Qure-style SVG icon pack containing **2,012 SVGs**: **1,742 common icons** and **270 regional & organization flags**, standardized to a **144 × 144** canvas. All flag SVGs feature **continuous Bézier curvature rounded corners**. Pull requests (**PRs**) following the icon design specifications are welcome to add missing icons.

[Common Icons Index](icon/svg/common/README_en.md) · [Flag Icons Index](icon/svg/flag/README_en.md) · [Icon Pack JSON](Other/Qure-Style-SVG.json)

---

## 🔮 Icon Pack Subscription

<img src="https://avatars.githubusercontent.com/u/149130188?v=4" width="60" height="60" alt="aaANDkk's GitHub Avatar" style="border-radius: 80%;">

**Qure-Style-SVG** · 2,012 icons · Author: [aaANDkk](https://github.com/aaANDkk)

Copy the subscription link below and add it to clients supporting JSON icon collections and SVG images (such as FlClash and Bettbox):

```text
https://raw.githubusercontent.com/aaANDkk/Qure_Style_SVG/main/Other/Qure-Style-SVG.json
```

> [!NOTE]
> All images in the manifest are in SVG vector format; the client must support both JSON icon collections and SVG images. Clients that only support PNG cannot use this icon pack directly. Clients such as **Bettbox** already have this icon pack built-in.

---

## 🎨 Icon Preview

### Common Icons · 1,742 Icons

Traffic routing, brand services, streaming media, AI, network tools, and proxy policy icons.

[Browse & Download](icon/svg/common/README_en.md) · [Scalable SVG Overview](docs/assets/common-overview.svg) · [Full-size PNG](docs/assets/common-overview.png)

[![1,742 Qure-style Common Icons](docs/assets/common-overview.png)](docs/assets/common-overview.png)

### Regional & Organization Flags · 270 Flags

Sorted alphabetically by English filename, with index showing region/country names.

[Browse & Download](icon/svg/flag/README_en.md) · [Scalable SVG Overview](docs/assets/flags-overview.svg?v=6fe731a3dfef) · [Full-size PNG](docs/assets/flags-overview.png?v=7269aea08043)

[![270 Regional & Organization Flags](docs/assets/flags-overview.png?v=7269aea08043)](docs/assets/flags-overview.png?v=7269aea08043)

---

## 🔗 Using Individual Icons

Find the filename in the icon index, then use the corresponding raw file URL (filenames are case-sensitive):

- **Common Icon Example**:
  ```text
  https://raw.githubusercontent.com/aaANDkk/Qure_Style_SVG/main/icon/svg/common/ChatGPT.svg
  ```

- **Flag Icon Example**:
  ```text
  https://raw.githubusercontent.com/aaANDkk/Qure_Style_SVG/main/icon/svg/flag/Japan.svg
  ```

- **Mihomo / Clash Configuration Example**:
  ```yaml
  icon: "https://raw.githubusercontent.com/aaANDkk/Qure_Style_SVG/main/icon/svg/flag/Japan.svg"
  ```

---

## 📁 Directory Structure

| Directory / File | Description |
| :--- | :--- |
| [`icon/svg/common/`](icon/svg/common/) | Common SVG icons and item-by-item index |
| [`icon/svg/flag/`](icon/svg/flag/) | Regional & organization flags and item-by-item index |
| [`docs/assets/`](docs/assets/) | SVG / PNG overview images |
| [`Other/Qure-Style-SVG.json`](Other/Qure-Style-SVG.json) | Icon pack manifest |
| [`licenses/`](licenses/) | Third-party license texts |

> [!TIP]
> PNG files are only used for overview display; all icon source files are standardized in SVG format.

---

## 💕 Acknowledgements & Usage Notes

- [Koolson / Qure](https://github.com/Koolson/Qure): Icon style and vector redraw references for parts of icons.
- [flag-icons](https://github.com/lipis/flag-icons), [circle-flags](https://github.com/HatScripts/circle-flags), [LobeHub Icons](https://github.com/lobehub/lobe-icons), [Bettbox](https://github.com/appshubcc/Bettbox), [Simple Icons](https://github.com/simple-icons/simple-icons), etc.: Sources for certain geometric silhouettes and brand materials.

This project is an unofficial curated and stylized SVG icon set and is not affiliated with the official Qure project. Brand names and logos belong to their respective owners; please follow their original licenses and usage requirements. The Qure reference and redrawn portions retain the original author's attribution and are intended for study and exchange as requested by the original project, not for commercial profit. For detailed sources and licenses, see [Third-Party Notices](THIRD_PARTY_NOTICES.md).
