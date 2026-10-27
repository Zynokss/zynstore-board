# Product media

| File | Origin and purpose |
| --- | --- |
| `zynstore-cover.jpg` | AI-generated abstract product cover. Charcoal, lime and violet are based on the current storefront and dashboard styles. It depicts no application interface. |
| `storefront-demo.png` | Actual rendered storefront catalog using four sample products and neutral image placeholders. |
| `dashboard-demo.png` | Actual rendered dashboard home using a fictional Demo Operator, sample products and zero orders. |

## Screenshot method

A fresh desktop Chromium context loaded each hosted website. Before navigation, capture rules intercepted API requests and supplied isolated demo responses; non-GET requests were blocked. A synthetic session existed only in that disposable browser to render the dashboard. It did not authenticate to the live service. No personal browser profile, customer account, database seed or production record was used.

Product photography and avatar requests were replaced with neutral placeholders. The added bottom caption identifies the isolated demo. The layout and controls are rendered by the actual applications. Interface status text such as online/sync indicators is not an independent uptime or telemetry verification. Demo prices, quantities and products are not offers or evidence of real inventory. Screenshots do not establish that every visible control is finished.

## Cover generation

Generated with the built-in image-generation tool using the imagegen skill. The final image is optimized as a JPEG for repository use. No application source or private data was supplied as an image reference.

The complete generation prompt is in [cover-prompt.txt](cover-prompt.txt). Image alt text and demo disclosures appear beside the images in the main README. See [rights](../RIGHTS.md) and [notices](../THIRD_PARTY_NOTICES.md).
