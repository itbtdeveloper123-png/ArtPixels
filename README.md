# ArtPixels Launcher

<p align="center">
  <b>One place to install, update and open the ArtPixels Creative Suite, rebuilt in pure Rust.</b><br>
  AngkorPix (Pro Image Editor) & AngkorVector (Vector Illustration): the right build for your computer, kept up to date.
</p>

<p align="center">
  <img alt="100% Rust" src="https://img.shields.io/badge/100%25-Rust-b7410e?style=flat-square&logo=rust">
  <img alt="macOS · Windows · Linux · Web" src="https://img.shields.io/badge/macOS%20%C2%B7%20Windows%20%C2%B7%20Linux%20%C2%B7%20Web-native-26282e?style=flat-square">
  <img alt="License: MIT OR Apache-2.0" src="https://img.shields.io/badge/license-MIT%20%2F%20Apache--2.0-3a3a3a?style=flat-square">
  <a href="https://github.com/itbtdeveloper123-png/ArtPixels"><img alt="GitHub Repo" src="https://img.shields.io/badge/GitHub-ArtPixels-181717?style=flat-square&logo=github"></a>
  <img alt="Status: alpha" src="https://img.shields.io/badge/status-alpha-d69e2e?style=flat-square">
</p>

<p align="center">
  <a href="https://github.com/itbtdeveloper123-png/ArtPixels/releases"><b>Download ArtPixels Launcher</b></a> ·
  <a href="https://github.com/itbtdeveloper123-png/AngkorPix">AngkorPix</a> ·
  <a href="https://github.com/itbtdeveloper123-png/AngkorVector">AngkorVector</a>
</p>

---

## What it does

ArtPixels Launcher brings together the **ArtPixels Creative Suite**:
- **AngkorPix**: Professional image editor with full Photoshop PSD compatibility, layers, masks, adjustments, filters, and high-performance GPU rendering.
- **AngkorVector**: Modern vector illustration tool with Bézier paths, shapes, typography, and SVG/PDF support.

The launcher gives you:
- **One-click Launch & Updates**: Checks GitHub releases for new versions and lets you open or update your apps effortlessly.
- **Pure Native Rust & egui**: Fast, responsive, minimal memory usage, zero Electron, zero webview bloat.
- **Tray & Background Operation**: Stays out of your way until you need it.

---

## Features

<table>
  <tr>
    <td width="33%" valign="top">
      <h3>📦 Fast Setup</h3>
      Detects installed versions automatically, configures portable and installed environments, and opens your creative apps instantly.
    </td>
    <td width="33%" valign="top">
      <h3>🔄 Direct GitHub Updates</h3>
      Checks your repository releases directly on GitHub and alerts you when fresh features and fixes are published.
    </td>
    <td width="33%" valign="top">
      <h3>🧭 Native & Lightweight</h3>
      Built with egui and wgpu in pure safe Rust. Instant startup, silky smooth 60+ FPS UI.
    </td>
  </tr>
</table>

---

## The ArtPixels Creative Suite

| App | What it's for | Repository |
|---|---|---|
| **AngkorPix** | Professional image editing: layers, masks, filters, text and native PSD support | [GitHub](https://github.com/itbtdeveloper123-png/AngkorPix) |
| **AngkorVector** | Vector art and illustration: paths, shapes, gradients, and vector assets | [GitHub](https://github.com/itbtdeveloper123-png/AngkorVector) |

---

## Build from Source

You need a recent stable Rust toolchain (1.85+):

```sh
git clone https://github.com/itbtdeveloper123-png/ArtPixels.git
cd ArtPixels
cargo run --release -p artpixels
```

---

## License

ArtPixels Launcher is open source and dual-licensed under [MIT](LICENSE-MIT) or [Apache-2.0](LICENSE-APACHE).
Developed and maintained by **ArtPixels / IT BT**.
