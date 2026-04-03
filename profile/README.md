<p align="center">
  <img src="sheetlink-logo-github-banner.png" alt="SheetLink Banner">
</p>

> Sync your bank transactions anywhere — Google Sheets, Excel, CSV, Postgres, SQLite.

SheetLink connects your financial accounts through Plaid and syncs balances and transactions into the tools you already use. Built for people who want full control over their financial data.

---

## Products

- **[Chrome Extension](https://chromewebstore.google.com/detail/sheetlink/niehncndbonfankgokhandgbaebdbpch)** — Plaid → Google Sheets, one click
- **Excel Add-in** — Plaid → Excel (available on AppSource)
- **[CLI](https://github.com/sheetlink/cli)** — `sheetlink sync` to JSON, CSV, Postgres, or SQLite
- **[Dashboard](https://sheetlink.app/dashboard)** — Manage banks, billing, and API keys

---

## Repositories

### [sheetlink/extension](https://github.com/sheetlink/extension)
The Chrome extension source. Connects Plaid to Google Sheets.

### [sheetlink/cli](https://github.com/sheetlink/cli)
The `sheetlink` npm package. Sync transactions from the terminal to any destination.

```bash
npm install -g sheetlink
sheetlink sync --output postgres://localhost/mydb
```

### [sheetlink/sheetlink-recipes](https://github.com/sheetlink/sheetlink-recipes)
Open-source Google Apps Script recipes — budget trackers, cash flow forecasts, and business reporting tools you can install directly into your spreadsheet.

### Internal
The web client, API, and operational tooling are maintained privately.

---

## Links

- **Website:** [sheetlink.app](https://sheetlink.app)
- **Pricing:** [sheetlink.app/pricing](https://sheetlink.app/pricing)
- **Support:** support@sheetlink.app

---

<p align="center">
  © 2026 SheetLink · Built in Austin, TX
</p>
