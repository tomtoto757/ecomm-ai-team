# Awesome Ecomm Skills

Curated ecommerce skill files collected into one repository for easier browsing, reuse, and future curation.

## What Is In This Repo

- `skills/` is organized by ecommerce category first, then by source namespace.
- `skills/<category>/finsilabs/` contains the imported `finsilabs/awesome-ecommerce-skills` skills mapped into that category.
- `skills/<category>/openclaw/` contains the active ecommerce-relevant `openclaw/skills` imports mapped into that category.
- `licenses/` keeps the upstream MIT licenses with the imported content.
- `upstream/` keeps useful upstream docs copied from the main ecommerce source.
- `docs/source-notes.md` explains what was imported from each link you shared.
- `data/source-manifest.json` provides a machine-readable inventory of sources and imported subsets.

## Categories

- `storefront-shopping-experience`
- `catalog-inventory`
- `pricing-promotions-loyalty`
- `checkout-payments-tax`
- `orders-shipping-returns`
- `customer-support-crm`
- `marketing-growth`
- `analytics-reporting`
- `platform-integrations-infrastructure`

## Imported Sources

### `finsilabs/awesome-ecommerce-skills`

- Imported: 178 skill folders
- Location: distributed under `skills/<category>/finsilabs/`
- Why: this is the strongest dedicated ecommerce skill library in your source list

### `openclaw/skills`

- Imported: 5 ecommerce-relevant skill folders
- Location: distributed under `skills/<category>/openclaw/`
- Included:
  - `customer-support-crm/openclaw/52yuanchangxing/ecommerce-customer-service-pro`
  - `orders-shipping-returns/openclaw/52yuanchangxing/ecommerce-return-intelligence`
  - `checkout-payments-tax/openclaw/a5huynh/universal-checkout`
  - `storefront-shopping-experience/openclaw/dejimarquis/groupon-skill`
  - `catalog-inventory/openclaw/denicmic-chung/amazon-product-scraper`
- Why: these were the clearly ecommerce, Shopify, checkout, ordering, deal-finding, or marketplace-adjacent skills with concrete reusable files

### Removed After Security Review

- Removed: 3 `openclaw` skill folders
- Removed:
  - `abhishekj9621/ecom-manager-d2c`
  - `abuiles/shopify-directory`
  - `asenwang/shopify-manager-cli`
- Why:
  - `shopify-directory` delegated trust to mutable third-party remote `skill.md` files
  - `shopify-manager-cli` exposed live destructive store mutations with no runtime confirmation guard
  - `ecom-manager-d2c` granted overly broad autonomous control over financially impactful operations

## Structure

```text
skills/
  analytics-reporting/
    finsilabs/
  catalog-inventory/
    finsilabs/
    openclaw/
  checkout-payments-tax/
    finsilabs/
    openclaw/
  customer-support-crm/
    finsilabs/
    openclaw/
  marketing-growth/
    finsilabs/
  orders-shipping-returns/
    finsilabs/
    openclaw/
  platform-integrations-infrastructure/
    finsilabs/
  pricing-promotions-loyalty/
    finsilabs/
  storefront-shopping-experience/
    finsilabs/
    openclaw/
```

Source attribution is preserved in the path. For example, a Shopify skill now lives under a category path such as `skills/platform-integrations-infrastructure/finsilabs/platform-shopify/...`.

## Attribution

Upstream licensing is preserved under `licenses/`. Please keep the original copyright and license notices if you redistribute or remix the imported material.
