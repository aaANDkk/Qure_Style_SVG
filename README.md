# Qure-Style-SVG

[English](README_en.md) · [简体中文](README.md)

Qure 风格的 SVG 图标集，包含 **2012 个 SVG**：**1742 个通用图标**、**270 个地区与组织旗帜**，统一为 **144 × 144** 画布，其中旗帜 SVG 均采用**贝塞尔丝滑曲率绘制圆角**。可按 icon 设计规范提交 **PR** 补全缺失图标。

[通用图标索引](icon/svg/common/README.md) · [旗帜图标索引](icon/svg/flag/README.md) · [图标包 JSON](Other/Qure-Style-SVG.json)

---

## 🔮 图标包订阅

<img src="https://avatars.githubusercontent.com/u/149130188?v=4" width="60" height="60" alt="aaANDkk 的 GitHub 头像" style="border-radius: 80%;">

**Qure-Style-SVG** · 2012 个图标 · 作者：[aaANDkk](https://github.com/aaANDkk)

复制下方订阅链接，添加到支持 JSON 图标集和 SVG 图片的客户端（如 FlClash 和 Bettbox ）：

```text
https://raw.githubusercontent.com/aaANDkk/Qure_Style_SVG/main/Other/Qure-Style-SVG.json
```

> [!NOTE]
> 清单中的图片为 SVG 矢量格式；客户端需同时支持 JSON 图标集和 SVG 格式。仅支持 PNG 的客户端不能直接使用此图标包。客户端如 **Bettbox** 已内置此图标包。

---

## 🎨 图标预览

### 通用图标 · 1742 个

业务分流、品牌服务、流媒体、AI、网络工具与策略图标。

[逐项浏览与下载](icon/svg/common/README.md) · [可缩放 SVG 总览](docs/assets/common-overview.svg) · [PNG 大图](docs/assets/common-overview.png)

[![1742 个 Qure 风格通用图标](docs/assets/common-overview.png)](docs/assets/common-overview.png)

### 地区与组织旗帜 · 270 个

按英文文件名排序，索引附中文名称。

[逐项浏览与下载](icon/svg/flag/README.md) · [可缩放 SVG 总览](docs/assets/flags-overview.svg?v=6fe731a3dfef) · [PNG 大图](docs/assets/flags-overview.png?v=7269aea08043)

[![270 个地区与组织旗帜](docs/assets/flags-overview.png?v=7269aea08043)](docs/assets/flags-overview.png?v=7269aea08043)

---

## 🔗 单个图标使用

在图标索引中找到文件名，使用对应的原始文件链接（文件名区分大小写）：

- **通用图标示例**：
  ```text
  https://raw.githubusercontent.com/aaANDkk/Qure_Style_SVG/main/icon/svg/common/ChatGPT.svg
  ```

- **旗帜图标示例**：
  ```text
  https://raw.githubusercontent.com/aaANDkk/Qure_Style_SVG/main/icon/svg/flag/Japan.svg
  ```

- **Mihomo / Clash 配置示例**：
  ```yaml
  icon: "https://raw.githubusercontent.com/aaANDkk/Qure_Style_SVG/main/icon/svg/flag/Japan.svg"
  ```

---

## 📁 目录结构

| 目录 / 文件 | 说明 |
| :--- | :--- |
| [`icon/svg/common/`](icon/svg/common/) | 通用 SVG 图标与逐项索引 |
| [`icon/svg/flag/`](icon/svg/flag/) | 地区与组织旗帜及逐项索引 |
| [`docs/assets/`](docs/assets/) | SVG / PNG 总览展示图 |
| [`Other/Qure-Style-SVG.json`](Other/Qure-Style-SVG.json) | 图标包清单 |
| [`licenses/`](licenses/) | 第三方许可文本 |

> [!TIP]
> PNG 文件仅用于总览展示，所有图标源文件统一使用 SVG 格式。

---

## 💕 鸣谢与使用说明

- [Koolson / Qure](https://github.com/Koolson/Qure)：图标风格与部分图标重绘参考。
- [flag-icons](https://github.com/lipis/flag-icons)、[circle-flags](https://github.com/HatScripts/circle-flags)、[LobeHub Icons](https://github.com/lobehub/lobe-icons)、[Bettbox](https://github.com/appshubcc/Bettbox)、[Simple Icons](https://github.com/simple-icons/simple-icons) 等：部分几何轮廓与品牌素材来源。

本项目为非官方整理与风格化 SVG 图标集，与 Qure 官方项目无隶属关系。品牌名称与标志归各自权利人所有；相关素材请遵循其原有许可及使用要求。Qure 参考与重绘部分保留原作者署名，按原项目要求用于学习交流，不用于商业盈利。详细来源和许可见 [第三方说明](THIRD_PARTY_NOTICES.md)。
