# Homarr Custom CSS Collection

A centralized collection of production-ready, custom CSS stylesheets designed to customize and enhance your [Homarr](https://homarr.dev/) dashboard. From cinematic and glassmorphic designs to ultra-minimalist and high-contrast palettes, this repository hosts modular themes ready for drop-in deployment.

---

## Available Themes

| Theme Name | Style / Aesthetic | Primary Accent | File Link |
| :--- | :--- | :--- | :--- |
| **The Batman (2022)** | Smoky Glass, Noir, Distressed Gotham | Flare Crimson (`#e61919`) | [`TheBatman.css`](.Themes/TheBatman.css) |
| *More coming soon* | Minimalist Slate, Cyberpunk Neon, OLED | Various | *TBD* |

---

## Quick Installation

1. Browse the `themes/` directory and open the `.css` file you want to use.
2. Copy the entire contents of the raw CSS file.
3. Open your Homarr dashboard and navigate to **Settings** > **Customization** > **Custom CSS**.
4. Paste the stylesheet into the custom CSS field and click **Save**.

> **Wallpaper Note:** For themes utilizing an external background image, check the `body` selector inside the stylesheet. Replace the placeholder URL in `url('...')` with your own hosted or local image address.

---

## Design Principles

- **True Glassmorphism:** Utilizes hardware-accelerated `backdrop-filter` blur and fine-tuned semi-transparency for depth without sacrificing legibility.
- **Component Integrity:** Explicitly targets Mantine UI primitives and Homarr dashboard elements without breaking forms, navigation headers, or third-party widgets.
- **Dynamic Interaction:** Custom hover transitions, illuminated border glows, custom scrollbars, and focused input states.
