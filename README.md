# The Receipt Eater

One HTML file that turns a folder of receipt files — phone scans saved as text, e-receipts,
invoice emails — into a clean expense log your bookkeeper can import. Built live on
**Build It With AI, Episode 13**.

- **[Open the tool](https://jonathangeorgegatz.github.io/receipt-eater/)** — it runs entirely
  in your browser; nothing is uploaded anywhere.
- **[Download the bundle](https://jonathangeorgegatz.github.io/receipt-eater/Receipt_Eater_BUNDLE.zip)** —
  the tool, the 75-receipt sample folder (Saltgrass Coffee Roasters — fictional), and the exact
  three prompts from the episode.

What it promises: labeled-line totals (never "the biggest number"), card EXP lines never read
as dates, same-day twins merged with their sources listed, near repeats flagged and kept,
signed refunds, arithmetic refusals with reasons, and a to-the-cent self-audit that prints
**DO NOT TRUST THIS LOG** when it fails.

Checks behind the build: 207 cross-implementation runs vs an independent Python checker
(0 disagreements) · 24 functional checks in a real browser with the network blocked.
