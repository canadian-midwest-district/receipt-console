# receipt-console

The **receipt reconciliation console** for the Canadian Midwest District — served at
**expenses.canadianmidwest.ca** (GitHub Pages). This is the *same* app as
[`mileage-expense-app`](https://github.com/canadian-midwest-district/mileage-expense-app)
running in **console mode**: `index.html` keys off the hostname, so on `expenses.*`
it shows only Emmanuel's reconciliation dashboard, while `travel.*` runs the capture app.

**Keep `index.html` in sync with `mileage-expense-app`.** It is the same file; edits to the
shared app must be copied to both repos (or merged from the `console-split` branch there).

Access is gated by the `ReceiptAccountant` Entra group; this separate, unshared subdomain
is an additional obscurity layer, not the primary control.
