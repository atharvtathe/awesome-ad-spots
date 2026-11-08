# Contributing

Thanks for helping keep this list useful. Two kinds of contributions are welcome:

1. **Add a site** that sells ad spots on its own website.
2. **Update an entry** whose price, placements or traffic have changed, or whose ad page is gone.

Don't want to open a pull request? [Open an issue](../../issues/new/choose) and fill in the form instead.

## What qualifies

- The site has its **own audience**: a community, tool, web app, blog or docs site that people actually use.
- It sells **on-site placements**: banners, sidebars, sponsored posts, in-feed ads, logo placements.
- It has a **public advertise / sponsor page** or a clear way to book.

Not accepted:

- Directories, listing sites and "submit your startup" sites whose main product is the listing.
- Newsletter-only or podcast-only sponsorships.
- Ad networks (these go under **Related**, not in the tables).
- Affiliate or tracking links. Link straight to the site's ad page.

Running the site yourself is fine. Just say so in the pull request.

## Adding an entry

Add one row to the table for the section that fits best:

| Column                 | What to write                                                                                     |
| ---------------------- | ------------------------------------------------------------------------------------------------- |
| **Site**               | `[Site name](link to the advertise page)`                                                         |
| **Audience**           | Who reads or uses the site, in a few words. Use the site's own breakdown if it gives one.         |
| **Website placements** | The on-site ad formats on offer. Leave out newsletter and podcast slots.                          |
| **Starting price**     | The cheapest website placement with its unit (`/wk`, `/mo`, per post). `On request` if not shown. |
| **Traffic (claimed)**  | The site's own number, as stated. `Not published` if there isn't one.                             |
| **Verified**           | The month you checked the ad page, e.g. `Nov 2026`.                                               |

Style:

- Keep each cell short. Use `;` to separate multiple prices.
- Use the currency the site uses (`$`, `€`).
- Don't add your own opinions or estimates. Only what the site publishes.
- If a price under $100 is the cheapest option, also add the site to **Budget Picks**.
- Update the count next to the section in **Contents**, and the total in the description at the top.
- Tables don't need aligned columns. Unaligned rows render fine on GitHub.

## Updating an entry

Change the cells that are out of date and set **Verified** to the current month. If the ad page no longer exists and there's no replacement, remove the row (and its Budget Picks row, if any) and lower the counts.

## Pull request checklist

- [ ] One site (or one fix) per pull request.
- [ ] Link goes to the site's advertise / sponsor page.
- [ ] Every number comes from the site's own page.
- [ ] **Verified** set to the month you checked.
- [ ] Section count and total updated (new or removed sites only).

By contributing, you agree to release your contribution under the [CC0 license](LICENSE) and to follow the [Code of Conduct](code-of-conduct.md).
