# Peso Tracker

An offline weekly allowance, bills, and pay-later installment tracker. It's built for students who get a weekly allowance and pay bills like SPayLater, TikTok PayLater, and subscriptions.

- **Works offline.** It's a PWA: open it once, then add it to your home screen.
- **Private.** Your data stays in your browser's storage on your device. Nothing is uploaded.
- **Safe to spend.** It shows how much you can spend today without missing a future bill.
- Week-by-week running balance, monthly bill totals, and 0%-interest installment splitting (the last payment absorbs the rounding).
- Expense log, paid-tick per bill, and backup/restore via a JSON file or a data code.

## Use it
1. Open the site in Safari (iPhone) or Chrome (Android/desktop).
2. **iPhone:** Share → *Add to Home Screen*. **Android:** ⋮ → *Install app*.
3. Set it up in **Setup**, or import a backup (Setup → Backup).

Data codes and `#data=` links contain your numbers. Don't post them publicly.

## Run locally
Plain HTML/JS, no build step. Serve the folder over HTTP (service workers don't run from `file://`):
```
python3 -m http.server 8000
```

## License
MIT
