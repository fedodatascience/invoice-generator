# Changelog

## v1.3.1 — 2026-10-31

- Fixed profile selection not applying fields — JSON with double quotes inside onclick attributes was breaking HTML; switched to index-based lookup

## v1.3.0 — 2026-10-31

- Added multi-client profile system: "Profily" dropdown on both Dodávateľ and Odberateľ section headers
- Built-in customer profile: o.z.Dúhovka-DTH (Ševčenkova 33, Bratislava)
- User-saved profiles persist in localStorage; deletable via × button
- "Uložiť aktuálne ako profil" saves current fields as a named profile
- No second HTML file needed for different clients

## v1.2.0 — 2026-10-31

- Fixed empty form on fresh load (new browser, incognito, different machine)
- Form now pre-fills with sample/placeholder data when localStorage is empty
- Defaults match invoice_data_sample.json

## v1.1.0 — 2026-04-24

- Added localStorage autosave — form data persists across page refreshes and browser restarts
- Imported JSON data is also persisted automatically

## v1.0.0 — 2026-03-20

- Initial release
- Single-file HTML invoice generator
- JSON import/export support
- Native date pickers with DD.MM.YYYY formatting
- Multiple line items with auto-calculated totals
- Print-optimized A4 layout for PDF export