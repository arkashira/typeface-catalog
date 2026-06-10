<h3 align="center">🛠️ typeface-catalog</h3>

<div align="center">
  <a href="https://github.com/your-org/typeface-catalog/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-green.svg" alt="License: MIT"></a>
  <img src="https://img.shields.io/badge/language-JavaScript-ff69b4.svg" alt="Language">
  <img src="https://img.shields.io/badge/build-passing-success.svg" alt="Build Status">
  <img src="https://img.shields.io/github/stars/your-org/typeface-catalog?style=social" alt="Stars">
</div>

---

# 🚀 typeface-catalog
**Power designers & developers with a unified schema & tooling for typeface families, font metadata, and license lifecycles.**  
A domain‑specific schema system tightly integrated with Sanity CMS that makes managing fonts as easy as managing content.

## Why typeface-catalog?
- **Single source of truth** – All font files, metadata, and licensing info live in one Sanity dataset, eliminating version drift.  
- **Built for type designers** – Tailored fields for weight, style, OpenType features, and licensing terms.  
- **Instant validation** – Schema‑level constraints catch missing or inconsistent font data before publishing.  
- **License lifecycle automation** – Track expirations, renewals, and usage rights with built‑in status flags.  
- **CMS‑first workflow** – Designers edit fonts directly in Sanity, developers fetch ready‑to‑use JSON via GROQ.  
- **Scalable & extensible** – Add custom fields or plug‑ins without touching core code.  
- **Open & MIT‑licensed** – Free for commercial and personal projects.

## Feature Overview

| Feature | Description |
|---------|-------------|
| **Sanity schema** | Pre‑defined document types for families, variants, and licenses. |
| **Metadata enrichment** | Auto‑populate common font metrics (ascender, descender, etc.) from uploaded files. |
| **License tracking** | Status flags (`active`, `expired`, `renewal_pending`) with date alerts. |
| **CLI utilities** | Commands to import/export font bundles and sync with Sanity. |
| **Webhooks** | Trigger CI pipelines when a font is added or its license changes. |
| **Type safety** | Generated TypeScript typings from the Sanity schema. |
| **Documentation generator** | Auto‑create a searchable catalog page from the CMS data. |

## Tech Stack
*The technology decisions are not yet locked in the `decisions/tech-stack.md` file.*  
When the stack is defined, this section will be updated to list the exact languages, frameworks, and tools used (e.g., Node.js, TypeScript, Sanity.io, etc.).

## Project Structure
```
typeface-catalog/
├─ business/          # Core business logic (schema definitions, validation, license handling)
│   └─ ...            # Files inside this folder
├─ README.md          # This document
```

## Getting Started
> **Note:** The exact install/run commands depend on the final tech‑stack. Below are generic steps that work for most JavaScript/Node.js projects. Replace placeholders once the stack is locked.

```bash
# 1️⃣ Clone the repository
git clone https://github.com/your-org/typeface-catalog.git
cd typeface-catalog

# 2️⃣ Install dependencies (npm or yarn)
npm install   # or: yarn install

# 3️⃣ Set up Sanity credentials
# Create a .env file (example)
cat <<EOF > .env
SANITY_PROJECT_ID=your_project_id
SANITY_DATASET=production
SANITY_TOKEN=your_sanity_token
EOF

# 4️⃣ Run the development server (if applicable)
npm run dev   # or: yarn dev

# 5️⃣ Run tests
npm test      # or: yarn test
```

## Deploy
Deployment instructions will be added once the stack (e.g., Vercel, Netlify, Docker) is finalized in `decisions/tech-stack.md`.

## Status
🟢 **Active** – Initial commit `9e0da11` (Initial commit) is the latest change.

## Contributing
We welcome contributions! Please read our [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on how to propose enhancements, report bugs, and submit pull requests.

## License
This project is licensed under the **MIT License**.