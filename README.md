# Our Team — Website

A static site built with Jekyll, same setup as the UEFA B portfolio site. GitHub Pages builds it automatically on push — no local install needed.

## Privacy note

This site is public. By design, it contains **no player names and no photos** — keep it that way when adding content. If you ever want to post something that would identify a specific player (a name, a photo, a squad list), that's a sign it belongs somewhere private (a team WhatsApp/app), not on this public site.

## How to add or edit a page

Same pattern as the portfolio site:

```
---
layout: default
title: Your Page Title
eyebrow: Optional label
lede: Optional intro line
permalink: /your-page-url/
---
```

Write the content below in markdown. Add it to `_data/nav.yml` if it should appear in the top menu.

## Updating "Matchday — One Thing" weekly

Edit `matchday.md` — replace the sentence inside the quote box with this week's message, commit, push. That's the whole workflow; nothing else needs to change.

## Deploying for the first time

1. Create a new **public** repository on GitHub (e.g. `our-team-site`) — separate from the portfolio repo.
2. Push everything in this folder to `main`.
3. **Settings → Pages → Deploy from a branch → main / (root)**.
4. GitHub gives you a live URL. Every push after that updates it automatically.
