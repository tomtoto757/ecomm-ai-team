# Source Notes

## Imported

### `https://github.com/finsilabs/awesome-ecommerce-skills`

- Status: imported
- Result: copied the full `skills/` tree into `skills/finsilabs/`
- Count: 178 `SKILL.md` files
- Extras copied:
  - `upstream/finsilabs-README.md`
  - `upstream/finsilabs-CATALOG.md`
  - `licenses/finsilabs-MIT.txt`

### `https://github.com/openclaw/skills/tree/main`

- Status: partially imported after filtering for direct ecommerce relevance
- Result: 5 active skill folders remain in `skills/openclaw/`; 3 imported skill folders were later quarantined
- Selection rule: only folders with clearly ecommerce, Shopify, checkout, deal, or product-ordering relevance and usable source files

Active folders:

- `52yuanchangxing/ecommerce-customer-service-pro`
- `52yuanchangxing/ecommerce-return-intelligence`
- `a5huynh/universal-checkout`
- `dejimarquis/groupon-skill`
- `denicmic-chung/amazon-product-scraper`

Quarantined after security review:

- `abhishekj9621/ecom-manager-d2c`
- `abuiles/shopify-directory`
- `asenwang/shopify-manager-cli`

Reasons:

- `shopify-directory` relied on mutable third-party remote `skill.md` instructions
- `shopify-manager-cli` exposed live destructive Shopify mutations without runtime confirmation flags
- `ecom-manager-d2c` was too broadly autonomous for pricing, ad spend, and operational changes

## Researched But Not Added As Separate Imports

### `https://awesome-ecommerce-skills.com/library`

- Status: researched
- Finding: the site is a JS-driven public catalog for the same `finsilabs/awesome-ecommerce-skills` project
- Decision: not imported separately to avoid duplicate content

### `https://www.reddit.com/r/ClaudeAI/comments/1rp52eq/these_are_the_claude_skills_we_use_everyday_to/`

- Status: researched
- Finding: the thread mentions skill names like `/frontend-design`, `/case-study-writing`, `/linkedin-post`, `/humanize-text`, and `/outreach-campaigns`, but does not include downloadable files or canonical repo links in the visible post content
- Decision: not imported because there were no verifiable raw skill files to fetch
