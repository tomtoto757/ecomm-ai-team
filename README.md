# Awesome Ecomm Skills

Curated ecommerce skill files collected into one repository for easier browsing, reuse, and future curation.

## What Is In This Repo

- `skills/finsilabs/` contains the full `finsilabs/awesome-ecommerce-skills` library.
- `skills/openclaw/` contains the active ecommerce-relevant skill folders I pulled from `openclaw/skills`.
- `licenses/` keeps the upstream MIT licenses with the imported content.
- `upstream/` keeps useful upstream docs copied from the main ecommerce source.
- `docs/source-notes.md` explains what was imported from each link you shared.
- `data/source-manifest.json` provides a machine-readable inventory of sources and imported subsets.

## Imported Sources

### `finsilabs/awesome-ecommerce-skills`

- Imported: 178 skill folders
- Location: `skills/finsilabs/`
- Why: this is the strongest dedicated ecommerce skill library in your source list

### `openclaw/skills`

- Imported: 8 ecommerce-relevant skill folders
- Location: `skills/openclaw/`
- Included:
  - `52yuanchangxing/ecommerce-customer-service-pro`
  - `52yuanchangxing/ecommerce-return-intelligence`
  - `a5huynh/universal-checkout`
  - `dejimarquis/groupon-skill`
  - `denicmic-chung/amazon-product-scraper`
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
  finsilabs/
    business-operations/
    catalog-inventory/
    customer-crm/
    data-analytics/
    fulfillment-shipping/
    headless-modern/
    infrastructure-performance/
    integrations-apis/
    marketing-growth/
    payments-checkout/
    platform-magento/
    platform-salesforce-cc/
    platform-shopify/
    platform-woocommerce/
    pricing-promotions/
    security-compliance/
    storefront-ui/
  openclaw/
    52yuanchangxing/
    a5huynh/
    dejimarquis/
    denicmic-chung/
```

## Attribution

Upstream licensing is preserved under `licenses/`. Please keep the original copyright and license notices if you redistribute or remix the imported material.
