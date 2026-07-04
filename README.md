# 🎨 tasteskills: The Anti-Slop Visual Framework for Antigravity

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Antigravity](https://img.shields.io/badge/Agent-Antigravity-blue)](https://gemini.google.com/)
[![Aesthetic: Premium](https://img.shields.io/badge/Aesthetic-Anti--Slop-green)](https://github.com/Leonxlnx/taste-skill)

Standard AI coding agents generate boring, generic visual layouts (the standard Inter font, centered heroes with glowing purple mesh gradients, repetitive layout rows, and lazy placeholder comments). 

**tasteskills** is a curated library of visual and layout skills ported specifically for the **Antigravity AI Agent**. It enforces premium spacing, layout variance, spring physics, and high-end typography rules, and hooks natively into Antigravity's tool stack.

---

## ⚡ Key Features

*   **Integrated Visual Mockups:** Image generation skills (`brandkit`, `imagegen-frontend-web`, `imagegen-frontend-mobile`) hook directly into Antigravity's native `generate_image` tool to draft wireframes and app screens in the chat, then implement the code to match them.
*   **Prompt-Driven Dials:** Control the agent's behavior dynamically using three numeric parameters (`DESIGN_VARIANCE`, `MOTION_INTENSITY`, `VISUAL_DENSITY`).
*   **Aesthetic Presets:** Dynamically load tailored guidelines like Notion-style (`minimalist-skill`), Swiss Grid (`brutalist-skill`), or smooth depth (`soft-skill`).
*   **Anti-Lazy Code Completion:** The `full-output-enforcement` skill overrides standard truncation boundaries and bans lazy placeholder comments (`// ... rest of code`).

---

## ⚙️ How it Works: The Dial Configurations

You can adjust three dials (scaled 1-10) directly inside your prompting sessions:

| Dial | Purpose | Low Value (1-3) | Mid Value (4-6) | High Value (7-10) |
| :--- | :--- | :--- | :--- | :--- |
| **`DESIGN_VARIANCE`** | Layout asymmetry & complexity. | Symmetrical grids, trust-first | Modern, clean balance | High asymmetry, Awwwards-style |
| **`MOTION_INTENSITY`** | Animation physics and scrub triggers. | Static, basic hovers | Smooth entry transitions | Physics-based sticky scroll stacks |
| **`VISUAL_DENSITY`** | Spacing and information layout. | Large whitespace, luxury DTC | Developer portfolio | Dense dashboard panels |

### Use-Case Presets

| Use Case | VARIANCE | MOTION | DENSITY | Recommended Trigger Keywords |
| :--- | :---: | :---: | :---: | :--- |
| **Mainstream SaaS Landing** | `7` | `6` | `4` | `design-taste-frontend`, `gpt-taste`, `modern SaaS` |
| **Luxury DTC / Product** | `7` | `6` | `3` | `soft-skill`, `forest theme`, `luxury craft` |
| **Creative Agency Landing** | `9` | `8` | `3` | `gpt-taste`, `brutalist-skill`, `horizontal scroll` |
| **Developer Portfolio** | `6` | `5` | `4` | `minimalist-skill`, `editorial layout`, `monochrome` |
| **Trust-First / Public-Sector**| `3` | `2` | `5` | `design-taste-frontend`, `trust-first` |

---

## 🛠️ Quick Installation Guide

To make these skills globally discoverable by your Antigravity agent:

### 1. Link to Your Global Configuration
Add the path of the cloned repository to your global `skills.json` file inside the Antigravity directory:

```json
{
  "entries": [
    { "path": "C:/path/to/cloned/tasteskills/skills" }
  ]
}
```

*Note: The global configuration folder is typically found at `C:\Users\<username>\.gemini\config\`.*

### 2. Auto-Discovery & Implicit Triggering
Once registered, the skills will load **implicitly** based on matching keywords in your conversation:
*   *e.g.,* Asking: *"Design an editorial, notion-style landing page"* will trigger **`minimalist-skill`**.
*   *e.g.,* Asking: *"Audit and redesign this button component styling"* will trigger **`redesign-skill`**.

---

## 🎨 Social Media & Writing Tips: Anti-Slop Dictionary

To get the absolute best visual outcomes, steer clear of generic AI instructions and use precise engineering terms:

| Avoid these generic terms (Produces Slop) | Use these precise terms (Produces Premium Layouts) |
| :--- | :--- |
| ❌ *"Make it clean and professional"* | ✅ *"Use asymmetrical white-space layouts and custom typography pairings"* |
| ❌ *"Make a modern dark mode dashboard"* | ✅ *"Set a cold luxury theme: slate and chrome grays with a sharp emerald green accent"* |
| ❌ *"Add cool micro-animations"* | ✅ *"Apply spring physics motion and GSAP scroll-triggered sticky card stacks"* |
| ❌ *"Make it look expensive"* | ✅ *"Group elements using generous negative space and thin borders instead of boxed cards"* |

---

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
