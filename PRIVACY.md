# Privacy Policy — PDF Editor

_Last updated: June 2026 · App owner: Majed Aljunaidy_

PDF Editor is a local application. It runs entirely on your computer.

## Your documents

- PDF files you open are processed **in memory on your own machine** by a
  local server bound to `127.0.0.1` (your computer only — not reachable
  from the network).
- Documents and edits are **never uploaded anywhere** and are discarded
  when the application closes.
- Exported PDFs are saved only where you choose to save them.

## Network access

The application accesses the internet for exactly one purpose: downloading
font files from the Google Fonts service (`fonts.googleapis.com` /
`fonts.gstatic.com`) when you explicitly choose a font that is not on your
system, plus two font families preloaded at startup. Requests to Google
Fonts are subject to
[Google's privacy policy](https://policies.google.com/privacy). No document
content is ever included in these requests. The app works offline; font
downloads simply fail gracefully.

If you connect an AI assistant via the local MCP endpoint and ask it to
insert an image from a web address, the app downloads that image from the
URL the assistant supplies. Like fonts, this only happens on request and
never includes document content.

## AI assistants (MCP)

The optional MCP endpoint is served on the same local-only address
(`127.0.0.1`). An AI client you connect (for example Claude) reads and
edits documents through it — that exchange happens between programs on
your computer. What an AI assistant itself does with content you share
with it is governed by that assistant's own privacy policy, not this one.

## Data collection

- No analytics, no telemetry, no accounts, no tracking.
- No personal data is collected, stored, or shared.

## Contact

Questions about this policy: open an issue at
[github.com/majedjun17/PDF-Editor](https://github.com/majedjun17/PDF-Editor/issues).
