# Golden View Financial — A2P Compliance Website

Static site for **goldenviewfinancial.uk** built to satisfy A2P 10DLC campaign
registration requirements (public opt-in flow, consent language, SMS-specific
Privacy Policy, Terms, and contact info). US-based business; domain is `.uk`.

## Pages
- `index.html` — Home / services overview
- `optin.html` — SMS opt-in form with CTIA-compliant consent checkbox
- `privacy.html` — Privacy Policy (includes required "no mobile info shared with third parties" clause)
- `terms.html` — Terms & Conditions (SMS program terms)
- `contact.html` — Contact details
- `styles.css` — Shared styles

The LeadConnector chat widget is embedded site-wide (before `</body>`).

## Before submitting for A2P — remaining placeholder
Business phone (+1 909-647-6478) and address (1783 Long Dr, Beaumont, CA 92223)
are filled in. Still to confirm:
- `support@goldenviewfinancial.uk` — support email (confirm it's a live inbox)

The consent language, opt-out (STOP/HELP) instructions, and Privacy Policy SMS
clause are written to match carrier/TCR requirements — keep them consistent with
your campaign registration use case.

## Hosting
No build step. Deploy the folder to any static host (Vercel, Netlify, GitHub
Pages) and point goldenviewfinancial.uk at it.
