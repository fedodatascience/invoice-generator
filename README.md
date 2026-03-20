# Invoice Generator

A lightweight, single-file HTML invoice generator designed for Slovak businesses. No server, no dependencies, no installs — just open the file in your browser, fill in the details, and print to PDF.

![License](https://img.shields.io/badge/license-MIT-green)

## Features

- **Single HTML file** — no build tools, no frameworks, no backend
- **Live preview** — switch between form and invoice preview instantly
- **PDF export** — uses the browser's native Print → Save as PDF
- **Multiple line items** — add/remove rows with auto-calculated totals
- **JSON import/export** — save your invoice data for reuse, or load previous invoices
- **Date pickers** — native date selectors with automatic `DD.MM.YYYY` formatting
- **Print-optimized** — clean A4 layout with proper `@page` rules
- **Responsive** — works on desktop and mobile
- **Slovak locale** — labels, formatting, and DPH note in Slovak

## Quick Start

1. Download or clone this repository
2. Open `invoice_generator.html` in any modern browser
3. Fill in your company details, customer info, dates, and line items
4. Click **Náhľad & PDF** to preview
5. Click **Uložiť ako PDF** to save

## JSON Workflow

You can save and reload invoice data as JSON files — useful for recurring invoices where only dates and amounts change.

**Export:** Click `Exportuj JSON` to download the current form data as a `.json` file.

**Import:** Click `Načítaj JSON` to load a previously saved file. The form auto-populates.

A sample file is included — see [`invoice_data_sample.json`](invoice_data_sample.json) for the expected format.

## Keeping Your Data Private

If you fork or clone this repo, **do not commit JSON files with your real company data** (bank account, IČO, personal info). The `.gitignore` is already configured to ignore `invoice_data_*.json` files — only the sample is tracked.

## Tech Stack

- Pure HTML / CSS / JavaScript (no dependencies)
- [DM Sans](https://fonts.google.com/specimen/DM+Sans) + [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) (loaded from Google Fonts)
- CSS Grid layout, CSS custom properties for theming

## License

MIT — free to use, modify, and distribute.

---

<details>
<summary>🇸🇰 Slovenská verzia</summary>

# Generátor faktúr

Jednoduchý generátor faktúr v jednom HTML súbore, navrhnutý pre slovenské firmy a SZČO. Žiadny server, žiadne závislosti — stačí otvoriť súbor v prehliadači, vyplniť údaje a uložiť ako PDF.

## Ako použiť

1. Stiahnite alebo naklonujte tento repozitár
2. Otvorte `invoice_generator.html` v prehliadači
3. Vyplňte údaje dodávateľa, odberateľa, dátumy a položky
4. Kliknite na **Náhľad & PDF** pre zobrazenie náhľadu
5. Kliknite na **Uložiť ako PDF** pre uloženie

## JSON súbory

Údaje faktúry je možné exportovať a importovať ako JSON súbory — ideálne pre opakujúce sa faktúry, kde sa menia iba dátumy a sumy.

Vzorový súbor: [`invoice_data_sample.json`](invoice_data_sample.json)

## Súkromie

Necommitujte JSON súbory s reálnymi firemnými údajmi. Súbor `.gitignore` je nastavený tak, aby ignoroval `invoice_data_*.json` — sledovaný je len vzorový súbor.

</details>
