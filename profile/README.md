<p align="center">
  <img src="sheetlink-logo-github-banner.png" alt="SheetLink Banner">
</p>

> Your bank data, in your control — synced to Google Sheets, Excel, Postgres, and more, or queried by Claude.

SheetLink connects your financial accounts through Plaid and syncs balances and transactions into the tools you already use. Privacy-first: your data is never stored on our servers, and it only syncs when you trigger it. Built for people who want full control over their financial data.

---

## Products

- **[Chrome Extension](https://chromewebstore.google.com/detail/sheetlink-sync-bank-trans/niehncndbonfankgokhandgbaebdbpch)** — Plaid → Google Sheets, one click
- **[Excel Add-in](https://marketplace.microsoft.com/en-us/product/office/WA200010463)** — Plaid → Excel (Microsoft AppSource)
- **[CLI](https://github.com/sheetlink/cli)** — `sheetlink sync` to JSON, CSV, Postgres, or SQLite
- **[MCP Server](https://github.com/sheetlink/mcp)** — ask Claude questions about your spending with live bank data
- **[Dashboard](https://sheetlink.app/dashboard)** — manage banks, billing, and API keys

---

## Repositories

### [sheetlink/extension](https://github.com/sheetlink/extension)
The Chrome extension. Connects Plaid to Google Sheets. Release builds are the exact packages published to the Chrome Web Store, so anyone can inspect what ships.

### [sheetlink/cli](https://github.com/sheetlink/cli)
The `sheetlink` npm package. Sync transactions from the terminal to any destination, on your own schedule.

```bash
npm install -g sheetlink
sheetlink sync --output postgres://localhost/mydb
```

### [sheetlink/mcp](https://github.com/sheetlink/mcp)
The SheetLink MCP server — connect your bank data to Claude and other MCP-compatible AI tools.

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
