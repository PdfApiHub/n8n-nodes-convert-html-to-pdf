# n8n-nodes-convert-html-to-pdf

[![NPM Version](https://img.shields.io/npm/v/n8n-nodes-convert-html-to-pdf.svg)](https://www.npmjs.com/package/n8n-nodes-convert-html-to-pdf)
[![License](https://img.shields.io/npm/l/n8n-nodes-convert-html-to-pdf.svg)](LICENSE.md)

> Convert HTML content or any website URL to a pixel-perfect PDF — with full control over paper size, margins, fonts, and dynamic data.

This is an [n8n](https://n8n.io/) community node powered by **[PDF API Hub](https://pdfapihub.com)**.

---

## 🚀 Install

1. Go to **Settings → Community Nodes** in n8n
2. Enter `n8n-nodes-convert-html-to-pdf`
3. Click **Install**

## 🔑 Setup

1. Sign up at [pdfapihub.com](https://pdfapihub.com) (free tier available)
2. Copy your API key
3. In n8n → **Credentials → New → PDF API Hub API** → paste your key

---

## ✨ Operations

### HTML to PDF
Render your own HTML/CSS template as a polished PDF document.

| Parameter | Description |
|-----------|-------------|
| **HTML Content** | Your HTML template — supports `{{placeholder}}` syntax |
| **CSS Content** | Optional CSS injected before rendering |
| **Load Google Fonts** | Pipe-separated font names (e.g. `Roboto|Inter`) |
| **Dynamic Params** | Key/value pairs that replace `{{placeholders}}` in your HTML |
| **Starter Templates** | Pick from ready-made samples to pre-fill HTML, CSS, and params |

### URL to PDF
Capture any webpage as a PDF — great for reports, receipts, and archiving.

| Parameter | Description |
|-----------|-------------|
| **URL** | Any public webpage (`https://` added automatically) |
| **Full Page** | Capture the full scrollable page or just the viewport |
| **Cookie Accept Text** | Auto-click cookie consent buttons before capture |
| **Wait Until** | Fully Loaded, DOM Ready, Network Quiet, or First Response |

### Common Options (both operations)

| Parameter | Description |
|-----------|-------------|
| **Paper Size** | A0–A6, Letter, Legal, Tabloid, Ledger |
| **Orientation** | Portrait or Landscape |
| **Margins** | None, Small, Medium, Large, or Custom (px/mm/cm/in) |
| **Viewport** | Standard, Laptop, Desktop, Mobile, Tablet, or Custom dimensions |
| **Output Format** | **URL** (hosted 30 days), **Base64**, or **Binary File** |
| **Output Filename** | Custom filename for the generated PDF |

### Advanced Options

| Option | Description |
|--------|-------------|
| Print Background | Render CSS background colors and images |
| Header & Footer | Show default browser header/footer |
| Max Pages | Limit the number of pages returned |
| CSS Page Size | Honor `@page` size declarations |
| Navigation Timeout | Max seconds to wait for page load |

---

## 💡 Use Cases

- **Invoice generation** — merge customer data into an HTML template
- **Report automation** — capture dashboards as PDF snapshots
- **Contract creation** — fill placeholders with CRM data
- **Website archiving** — save webpages for compliance records

## 📚 Resources

- [PDF API Hub Docs](https://pdfapihub.com/docs)
- [n8n Community Nodes](https://docs.n8n.io/integrations/community-nodes/)

## License

[MIT](LICENSE.md)
