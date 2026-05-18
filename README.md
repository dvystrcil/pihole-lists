# pihole-lists

Personal [Pi-hole](https://pi-hole.net/) blocklist configuration — a curated
mix of manually-added host entries and subscribed community blocklists.

## Contents

- **`ad-list.txt`** — combined blocklist file:
  - **Inline `0.0.0.0 host.example` entries** at the top — manually added
    blocks for site analytics, tag managers, and comment platforms that
    Pi-hole's defaults miss
  - **Subscribed-feed URLs** at the bottom — community-maintained blocklists
    to be imported into Pi-hole's *Group Management → Adlists*

## Use

Two ways to consume the contents:

1. **Manual entries** — copy individual `0.0.0.0 host` lines into your
   Pi-hole's custom blocklist via *Group Management → Domains → Add
   exact block*.
2. **Subscribed feeds** — paste the raw URLs into *Group Management →
   Adlists*. Pi-hole will pull and refresh them on its normal schedule.

## License

[MIT](LICENSE).
