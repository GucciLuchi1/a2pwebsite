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

## Before submitting for A2P — replace placeholders
Search the repo for these and swap in real details:
- `+1 (000) 000-0000` — phone number
- `support@goldenviewfinancial.uk` — support email (confirm it's live)
- `[Business address line 1]` / `[City, State ZIP]` — registered business address

The consent language, opt-out (STOP/HELP) instructions, and Privacy Policy SMS
clause are written to match carrier/TCR requirements — keep them consistent with
your campaign registration use case.

## Hosting
No build step. Deploy the folder to any static host (Vercel, Netlify, GitHub
Pages) and point goldenviewfinancial.uk at it.
