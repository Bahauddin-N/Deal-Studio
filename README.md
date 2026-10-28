# Deal Studio

Funding calculator, product guide, bank-statement analyzer and lender-matching tool.

Everything runs in the browser from a single file, `index.html`. There is nothing to install or build.

## Use it
- Locally: download `index.html` and open it in Chrome, Edge or Safari.
- Online: enable GitHub Pages (Settings → Pages → Deploy from branch → `main` / root) and open the link it gives you.

## Statement Analyzer
Reading PDF statements needs your own Anthropic API key, entered in the app. It is stored only in your browser, and only if you tick "Remember key". It is never part of this repository.

Statement PDFs are sent to Anthropic's API to be read. Make sure your agreements allow sharing client bank data this way.

## Notes
- Lender guidelines in the app are internal and not for public distribution. Keep this repository private.
- Lender tiers 2, 5 and Reverse use estimated limits until their guidelines are added.
