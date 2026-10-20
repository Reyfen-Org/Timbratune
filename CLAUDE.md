# Timbratune website

The public pages of Timbratune (home, support, privacy policy, terms), served by GitHub Pages from `main` at https://reyfen-org.github.io/Timbratune/. Each page has an English and a Polish version; change both together.

## Ground rules

- **Update the "last updated" date with every change.** Whenever a page's content changes, set its date to the day of the change, in both languages, in the same `DD-Mon-YYYY` format (e.g. `20-Oct-2026`). The dates are in:
  - `privacy.html`: `Last updated: …` (English) and `Ostatnia aktualizacja: …` (Polish), each in the `<p class="updated">` under the page heading.
  - `terms.html`: the same two lines.
  - `index.html` and `support.html` have no date.
- **The privacy policy and terms must match the app and the stores.** If the app starts collecting data, adds analytics or purchases, or the App Store age rating changes (now 13+), update the policy first. App Store Connect's privacy answers ("Data Not Collected") must say the same.
- **Commit only when asked.** Work happens directly on `main`; a push to it updates the live site.
