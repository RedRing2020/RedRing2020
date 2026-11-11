<div align="center">

# ⭕ RedRing

**CAD/CAM kernel developer from Tokyo, building a modeling & machining platform in Rust.**<br>
東京を拠点に、Rust で CAD/CAM カーネルとソフトウェアを開発しています。

[![Website](https://img.shields.io/badge/redring.jp-0A0A0A?style=flat-square&logo=googlechrome&logoColor=white)](https://redring.jp/)
[![Docs](https://img.shields.io/badge/Docs-GitHub_Pages-B7410E?style=flat-square&logo=mdbook&logoColor=white)](https://redring2020.github.io/RedRing/)
[![X](https://img.shields.io/badge/@redring2020-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/redring2020)
[![Qiita](https://img.shields.io/badge/Qiita-redring-55C500?style=flat-square&logo=qiita&logoColor=white)](https://qiita.com/redring)
[![Sponsor](https://img.shields.io/badge/Sponsor-❤-EA4AAA?style=flat-square&logo=githubsponsors&logoColor=white)](https://github.com/sponsors/RedRing2020)

</div>

---

## 🔴 RedRing — Rust CAD/CAM research platform

[**RedRing2020/RedRing**](https://github.com/RedRing2020/RedRing) is a standalone CAD/CAM environment built with **Rust + wgpu**.

**v0.1.0 (preview)** — import an STL, generate a 3-axis scanline toolpath, and verify it with a cutting simulation.

| | Status |
|---|---|
| 🎨 GPU rendering (wgpu / winit) | ✅ |
| 📐 Foundation geometry & in-house NURBS curves / surfaces | ✅ |
| 🔪 3-axis scanline toolpath — ball / flat end mill, inverse offset method | 🧪 preview |
| ⚡ Cutting simulation — tri-dexel stock with animation | 🧪 preview |
| 🗂️ Machining management (operations, jobs, tool library) | 🔜 v0.2.0 |
| 🧾 Connecting moves & NC output | 🔜 v0.3.0 |
| 💾 STEP / IGES, WebAssembly, SpaceMouse | 🗺️ planned |

**Design principles:** type safety through ownership and traits · layered architecture (`foundation` → `model` → `viewmodel` → `view`) · modular crates for incremental growth.

👉 [Issues](https://github.com/RedRing2020/RedRing/issues) · [Projects](https://github.com/RedRing2020/RedRing/projects) · [Design philosophy](https://github.com/RedRing2020/RedRing/blob/develop/manual/philosophy.md) · [日本語 README](https://github.com/RedRing2020/RedRing/blob/develop/README.jp.md)

---

## 🛠️ Tech

**Main:**
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![wgpu](https://img.shields.io/badge/wgpu-WebGPU-005A9C?style=flat-square&logo=webgpu&logoColor=white)
![nalgebra](https://img.shields.io/badge/nalgebra-linear_algebra-4B8BBE?style=flat-square)
![mdBook](https://img.shields.io/badge/mdBook-docs-B7410E?style=flat-square&logo=mdbook&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

**Also:**
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=flat-square&logo=jquery&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![OpenGL](https://img.shields.io/badge/OpenGL-5586A4?style=flat-square&logo=opengl&logoColor=white)
![WordPress](https://img.shields.io/badge/WordPress-21759B?style=flat-square&logo=wordpress&logoColor=white)

---

## 📈 Activity

<p>
  <img src="https://raw.githubusercontent.com/RedRing2020/RedRing2020/main/profile-summary-card-output/default/0-profile-details.svg" alt="Profile details" width="100%">
</p>
<p>
  <img src="https://raw.githubusercontent.com/RedRing2020/RedRing2020/main/profile-summary-card-output/default/3-stats.svg" alt="Stats" width="49%">
  <img src="https://raw.githubusercontent.com/RedRing2020/RedRing2020/main/profile-summary-card-output/default/2-most-commit-language.svg" alt="Most commit language" width="49%">
</p>

---

## 🌿 Elsewhere

- 🖥️ **[redring.jp](https://redring.jp/)** — project site
- 🐠 **[oriva.jp](https://oriva.jp/)** — hobby site on aquariums & paludariums (field guide, layout gallery, blog) *— coming soon*
- ✍️ [Qiita](https://qiita.com/redring) · [Stack Overflow (ja)](https://ja.stackoverflow.com/users/51688/redring) · [Reddit](https://www.reddit.com/user/RedRing2020) · [Instagram](https://www.instagram.com/redringram/) · [Facebook](https://www.facebook.com/redring2020/)

<div align="center"><sub>Building CAD/CAM, one crate at a time. 🦀</sub></div>
