# Showcase media

| File | Origin and purpose |
| --- | --- |
| `zynstore-cover.jpg` | AI-generated abstract cover using the existing charcoal, lime and violet palette. It is promotional artwork, not an interface screenshot. |
| `storefront-demo.png` | Actual storefront catalog rendered with four sample products and neutral image placeholders. |
| `dashboard-demo.png` | Actual dashboard home rendered with a fictional Demo Operator, sample products and zero orders. |

## Screenshot provenance

Each hosted website was loaded in a fresh desktop Chromium context. API requests were intercepted before navigation and answered with isolated demo data. Non-GET requests were blocked. A synthetic session existed only in the disposable capture browser to render the dashboard; no live account was authenticated.

No personal browser profile, customer records, production database seed or real order data was used. Photography and avatar requests were replaced with neutral placeholders. The added bottom caption identifies the isolated demo.

The layouts and controls are rendered by the actual websites. Visible sync indicators, stock quantities and version labels are interface content, not independently verified service or release claims. Sample products and prices are not offers for sale. Visible screens may contain unfinished or simulated workflows, as explained in the [showcase README](../README.md).

## Generated cover

The cover was made using the imagegen skill and built-in image-generation tool, then optimized as a JPEG. No application source or private data was supplied as an image reference. The original [generation prompt](cover-prompt.txt) is preserved for provenance; it describes the cover's visual direction, not a released product.

See [rights and credits](../RIGHTS.md) and [third-party notices](../THIRD_PARTY_NOTICES.md). Project enquiries: contact@zynoks.com.
