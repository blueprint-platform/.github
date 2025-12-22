# Blueprint Platform — Branding Assets

This directory contains the **official branding assets** for the **Blueprint Platform** organization.

These assets are intended for:

* GitHub organization and repository pages
* Documentation and README files
* Generated project attribution (non-intrusive branding)
* Future UI, portal, and diagram usage

All assets here are **canonical** and should be referenced directly (not copied) by other repositories.

---

## 📁 Available Assets

### `blueprint-platform-avatar-1024.png`

* **Purpose:** GitHub organization avatar
* **Usage:** GitHub org settings (`Change your organization’s avatar`)
* **Notes:** Optimized for circular cropping

---

### `blueprint-platform-logo-light.png`

* **Purpose:** Official wordmark (icon + name)
* **Usage:**

    * README files
    * Documentation
    * Blog posts or presentations
* **Background:** Light / neutral backgrounds

---

### `blueprint-platform-icon.png`

* **Purpose:** Icon-only variant (no text)
* **Usage:**

    * UI components
    * Diagrams
    * Favicons or small visual markers

---

## 🔗 Recommended Usage Pattern

When referencing these assets from other repositories (including generated projects), use the **raw GitHub URL** instead of copying files:

```html
<img src="https://raw.githubusercontent.com/blueprint-platform/.github/main/branding/blueprint-platform-logo-light.png"
     width="120"
     alt="Blueprint Platform" />
```

This ensures:

* A single source of truth
* Consistent branding across the ecosystem
* Easy updates without touching downstream repositories

---

## 🧭 Branding Philosophy

Blueprint Platform branding is intentionally **minimal and non-intrusive**.

* Branding acts as an **architectural signature**, not marketing
* Generated projects remain fully owned by their teams
* Visual identity reinforces trust without creating vendor lock-in

> Architecture as a Product — not Branding as a Product.
