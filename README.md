# Pricing Tier Comparison Builder

This tool builds two to four pricing tiers, previews them as cards, and copies a markdown comparison table. The table lists every feature across all tiers as rows, with a check where a tier includes it, so the differences are easy to read.

**Live demo:** https://0xelitesystem.github.io/pricing-tier-comparison-builder/

## What it does

Edit each tier's name, price, billing period, and feature list, one feature per line, and mark one tier as featured. The preview renders the tiers as tags with the featured one raised. The copy button produces a markdown table whose rows are the union of all features, with a price row at the top and a check in each column where that tier has the feature.

This is for laying out and comparing tiers, not for collecting payment. Nothing is sent or saved.

## Aesthetic

Retail hang-tags: manila swing tags with a string hole, stamped prices, and a red featured marker on the highlighted tier.

## Privacy

Everything runs in your browser. Nothing you type is sent anywhere, stored, or saved. Closing the tab clears it.

## Use it

Open `index.html` in any modern browser, or host it as a static page. No build step, no dependencies, no network calls.

## More

Part of a catalog of single-file browser tools and plain-language references, all MIT licensed and dependency-free: [0xelitesystem.github.io](https://0xelitesystem.github.io/). Built by [elitesystem.ai](https://elitesystem.ai).

## License

MIT. Copyright (c) 2026 0xelitesystem.
