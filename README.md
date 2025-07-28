<h1 align="center"> 
  Modular
  <img src="https://raw.githack.com/mxi-git-repo/modular-cube-doc/refs/heads/main/static/images/ModularCube.ico" width="50px"> 
  Cube.js 
</h1>

<p align="center">
  <img src="https://img.shields.io/badge/status-production--ready-brightgreen?style=for-the-badge" alt="Status">
  <img src="https://img.shields.io/badge/web-standards--based-blue?style=for-the-badge" alt="Web Standards">
  <img src="https://img.shields.io/badge/javascript-vanilla-f7df1e?style=for-the-badge&logo=javascript&logoColor=black" alt="Vanilla JS">
  <img src="https://img.shields.io/badge/license-FULL%20v1.0.0-lightgrey?style=for-the-badge" alt="License">
</p>

<br>

<p align="justify">
  <strong>ModularCube</strong> is a lightweight, standards-first front-end framework for building modular, maintainable, and performant web applications. 
  It leverages <strong>Web Components, ES Modules, Shadow DOM, and HTML Templates</strong> to reduce complexity while prioritizing reliability and long-term maintainability.
</p>

**No transpilation, No virtual DOM, No framework lock-in.**

<br>

<div align="center">
  
  [🚀 Quick Start](#quick-start) •
  [💎 Sponsorship](#sponsorship) •
  [📘 Documentation](#documentation)
  
</div>

---

## 🔍 Overview

- **Minimal Setup:** Include the framework in HTML with a single script
- **Standards-First:** Built on native browser APIs,future-proof by design
- **Modular Architecture:** Self-contained, reusable components
- **Performance-Oriented:** Tiny runtime (~30kb) for fast loading
- **Long-Term Focus:** Maintainable, clear, and predictable

> A frontend framework built entirely on web standards.

<br>

## ❓ Why ModularCube.js?

Modern frontend frameworks introduce **overhead, complexity, and large dependency trees**. ModularCube focuses on **browser-native capabilities**.

- **Zero Build Step:** No bundlers, compilers, or preprocessing
- **Native APIs:** ES Modules, Custom Elements, Shadow DOM
- **Ultra-Lightweight:** Minimal runtime footprint
- **Predictable & Maintainable:** Encapsulation reduces technical debt
- **Hot Swapping:** Update modules without refreshing the page

> Focus on building features, not managing tooling.

<br>

## ⚙️ Core Features

| Feature | Description |
| :--- | :--- |
| **Reactive State** | Efficient state management without Virtual DOM overhead |
| **Native Components** | Real Web Components with Shadow DOM encapsulation |
| **Scoped Styles** | Isolated styling for maintainability |
| **Vanilla Routing** | Simple, URL-first SPA routing |
| **Hot Swapping** | Edit components without full reload |
| **ES Module Based** | Direct import and modular architecture |

<br>

## 💡 What Makes ModularCube.js Different

- **No build step:** Runs directly in the browser
- **No virtual DOM:** Explicit, scoped DOM updates
- **Web standards first:** Native Custom Elements with Shadow DOM
- **Minimal abstraction:** Code executes as written
- **Long-term maintainability:** Fewer layers, easier debugging

Suitable for projects where **clarity, stability, and control** are essential.

<br>

## 📊 Comparison: ModularCube vs Traditional Approaches

| Feature | ModularCube | Typical Frontend Frameworks |
| :--- | :--- | :--- |
| **Build Step** | None | Required (Webpack, Babel, Vite, etc.) |
| **Installation** | Single `<script>` tag | NPM packages + dependency trees |
| **Learning Curve** | Low (Plain JS/HTML/CSS) | Medium to High (JSX, Hooks, Directives) |
| **Long-Term Stability** | High (Standards-based) | Moderate (Version churn) |
| **Bundle Size** | ~30kb | 100kb–500kb+ |
| **Runtime Model** | Direct DOM updates | Virtual DOM abstraction |

> Comparison values are indicative.

<br>

<a id="quick-start"></a>

## 🚀 Quick Start

<details open>
  <summary>index.html</summary>
  
  ```html
  <script type="importmap">
  {
    "imports": {
      "@modular-cube": "https://cdn.jsdelivr.net/gh/mxi-git-repo/modular-cube-release@main/main.js"
    }
  }
  </script>
  ```
</details>

> That’s all you need to include ModularCube in your project.  
> For more details, refer to the [Documentation](#documentation).

<br>

## 📌 Project Status

- Release series: 1.0.0
- Public API: stable
- Breaking changes: avoided whenever possible
- Focus: stability, performance, long-term maintenance, documentation

> ModularCube is intended for **real-world usage**, not experimentation only.

<br>

## 🌍 Real-World Usage

ModularCube is used and tested in production by developers and teams.  
Organizations using it are encouraged to **reach out or open an issue** to be listed.

Visibility supports **long-term sustainability**.

<br>

<a id="sponsorshipt"></a>

## 💎 Sponsorship

ModularCube is free and open-source. Maintaining a framework requires ongoing work:

- Compatibility updates
- Bug fixes
- Documentation improvements
- Long-term API stability

Sponsorship ensures ModularCube remains **actively maintained, reliable, and free**.  
It helps keep the project **simple, stable, and independent**.

👉 [Sponsor ModularCube on GitHub]()

<br>

<a id="documentation"></a>

## 📘 Documentation

Full reference, lifecycle guides, and examples.

> [ModularCube Reference Manual](https://raw.githack.com/mxi-git-repo/modular-cube-doc/refs/heads/main/index.html)

<br>

---

## 📄 License

ModularCube.js  
Copyright (c) 2025 MXI.Studio  

This project is licensed under the **MIT License**.

> For more details, refer to the [License](https://github.com/mxi-git-repo/modular-cube-release/blob/main/LICENSE).

<br>

## 👤 Maintainer

<p align="justify"> 
  ModularCube is designed, developed, and maintained by <a href="">MXI.Studio</a>, which specializes in turning complex technological challenges into reliable, scalable, and well-structured solutions that strengthen foundations and ensure long-term stability and efficiency.
</p>

> The framework was originally created by the studio and is exclusively maintained by the same team. 
> All core architectural decisions, implementations, and releases are handled internally to ensure consistency, quality, and long-term stability.

As the sole maintainer, the studio is responsible for:
- Core framework architecture and development  
- API stability and backward compatibility  
- Bug fixes, performance improvements, and compatibility updates  
- Documentation, examples, and reference materials  
- Reviewing issues, feedback, and community contributions  

<p align="justify"> 
  ModularCube is independently developed and maintained by our studio. 
  This independent structure allows the project to evolve in a deliberate and sustainable way, prioritizing clarity, long-term maintainability, and standards-based design over short-term trends or ecosystem-driven constraints.
</p>

> If your team relies on ModularCube for real-world projects, sponsorship helps ensure continued maintenance, stability, and long-term sustainability.
