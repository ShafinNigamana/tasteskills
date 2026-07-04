# tasteskills: The Anti-Slop Visual Framework for Antigravity

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Antigravity](https://img.shields.io/badge/Agent-Antigravity-blue)](https://gemini.google.com/)
[![Aesthetic: Premium](https://img.shields.io/badge/Aesthetic-Anti--Slop-green)](https://github.com/Leonxlnx/taste-skill)

Standard AI coding agents suffer from strong default biases: they output narrow column layouts, generic Inter-based grids, AI-purple gradient bubbles, and lazy placeholder comments (`// ... rest of code`).

**tasteskills** is a curated layout and visual design framework ported specifically for the **Antigravity AI Agent**. It enforces premium spacing, layout asymmetry, spring physics, and high-end typography rules while hooking natively into the IDE's tool stack.

---

### The Dials System

Adjust the visual output dynamically inside your prompting sessions by setting numeric dials (scaled 1-10):

```text
[ DESIGN_VARIANCE ]  Symmetrical  [----|-----]  Artsy Chaos   (Dial 1-10)
[ MOTION_INTENSITY ]  Static       [------|---]  Cinematic     (Dial 1-10)
[ VISUAL_DENSITY   ]  Airy Space   [---|------]  Dense Cockpit (Dial 1-10)
```

#### Preset Configurations
You can instruct Antigravity to use these default presets depending on the project vibe:

*   **SaaS Landing Page** `7 / 6 / 4` (Clean asymmetry, responsive spring entry animations, balanced margins).
*   **Luxury DTC / Product Page** `7 / 6 / 3` (Spacious grids, off-white/bone color themes, custom spec blocks).
*   **Creative Agency Landing** `9 / 8 / 3` (Highly asymmetrical, custom typography, GSAP horizontal scroll).
*   **Developer Portfolio** `6 / 5 / 4` (Monochrome, editorial sans display type, minimal borders).
*   **Trust-First / Public-Sector** `3 / 2 / 5` (Perfect grid symmetry, zero animations, high readability contrast).

---

### Custom Skills Map

The 13 triggerable skills inside the library are grouped by functional categories:

```text
+--------------------------------------------------------------------------------+
|  I. THE DESIGN FOUNDATIONS                                                     |
|  - design-taste-frontend   Default visual system. Dynamic dial configuration.  |
|  - taste-skill-v1          Legacy frontend design rules.                       |
|  - gpt-taste               Advanced Awwwards-level GSAP motion templates.      |
+--------------------------------------------------------------------------------+
|  II. AESTHETIC DIRECTIVES                                                      |
|  - minimalist-skill        Clean, editorial-style interfaces (Notion/Linear).  |
|  - brutalist-skill         Swiss typographic grids, raw monospace terminals.   |
|  - soft-skill              Whitespace, soft elevations, premium fonts.         |
|  - stitch-skill            Google Stitch semantic design parameters.           |
+--------------------------------------------------------------------------------+
|  III. UTILITY & INTEGRATIONS                                                   |
|  - image-to-code-skill     Reference translation: image -> audit -> code.      |
|  - redesign-skill          Upgrades existing projects using visual audits.     |
|  - output-skill            Forces complete code output, banning placeholders.  |
+--------------------------------------------------------------------------------+
|  IV. VISUAL ASSET DESIGN (Hooks natively into generate_image tool)             |
|  - imagegen-frontend-web   Web layouts, hero assets, sections wireframing.     |
|  - imagegen-frontend-mobile Mobile screen flows and mockup framing.            |
|  - brandkit                Logo concept systems, identity presentations.       |
+--------------------------------------------------------------------------------+
```

---

### Quick Installation Guide

To make these skills globally discoverable by your Antigravity agent:

#### 1. Link to Your Global Config
Add the path of the cloned repository to your global `skills.json` file inside the Antigravity directory:

```json
{
  "entries": [
    { "path": "C:/path/to/cloned/tasteskills/skills" }
  ]
}
```
*Note: The global configuration folder is typically found at `C:\Users\<username>\.gemini\config\`.*

#### 2. Auto-Discovery & Contextual Triggering
Once registered, the skills load **implicitly** based on keywords in your conversation:
*   *e.g.,* Asking: *"Design an editorial, notion-style landing page"* triggers **`minimalist-skill`**.
*   *e.g.,* Asking: *"Audit and redesign this button component styling"* triggers **`redesign-skill`**.

---

### Anti-Slop Dictionary

To get the absolute best visual outcomes, steer clear of generic AI instructions and use precise engineering terms:

| Avoid these generic terms (Produces Slop) | Use these precise terms (Produces Premium Layouts) |
| :--- | :--- |
| ❌ *"Make it clean and professional"* | ✅ *"Use asymmetrical white-space layouts and custom typography pairings"* |
| ❌ *"Make a modern dark mode dashboard"* | ✅ *"Set a cold luxury theme: slate and chrome grays with a sharp emerald green accent"* |
| ❌ *"Add cool micro-animations"* | ✅ *"Apply spring physics motion and GSAP scroll-triggered sticky card stacks"* |
| ❌ *"Make it look expensive"* | ✅ *"Group elements using generous negative space and thin borders instead of boxed cards"* |

---

### License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
