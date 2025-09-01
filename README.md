# shopify-app-notes



Shopify evaluates apps based on four core principles:

| Principle      | What It Means                                                    |
|----------------|------------------------------------------------------------------|
| **Usefulness** | App delivers clear value, reflected in installs and positive reviews. |
| **User Experience** | Easy to use, intuitive, and accessible for all merchants.         |
| **Performance** | Runs efficiently for merchants and their customers.             |
| **Integration** | Meets category-specific standards so data flows to the right places.

# App Surfaces in Shopify

Apps can extend Shopify in different areas, called **app surfaces**. Each surface defines *where* and *how* an app interacts with the platform.

| Surface          | Description                                                                 |
|------------------|-----------------------------------------------------------------------------|
| **Shopify Admin** | Back-office apps that help merchants manage operations (inventory, orders, reporting). |
| **Online Store** | Customer-facing apps that enhance shopping (navigation, recommendations, checkout, upsells, loyalty). |
| **Shopify POS**  | Apps that extend the Point of Sale system for in-person sales.              |


# Shopify App Surfaces (Simplified Reference)

| Surface       | Extension Type           | Notes                                                                 |
|---------------|--------------------------|----------------------------------------------------------------------|
| **Admin**     | Embedded app             | App UI inside Shopify Admin (iframe, Polaris). Useful for app settings/config. |
|               | Admin app extensions     | Extend existing Admin pages (smaller surface).                       |
|               | Shopify Flow             | Add triggers/actions to workflows.                                   |
| **Online Store** | Theme app extensions  | Add blocks/snippets to storefront (filters, swatches, badges). ✅ Core for your project. |
|               | Checkout UI extensions   | Customize checkout (Shopify Plus only).                              |
|               | Post-purchase extensions | Upsells after checkout (requires approval).                          |
|               | Web pixels               | Add tracking/analytics scripts.                                      |
| **Customer Accounts** | Inline/order/full-page extensions | Extend customer portal (less relevant for your project). |
| **Server-only** | Backend apps           | Logic-only, no UI. Good for integrations/data sync.                   |
| **POS (Point of Sale)** | POS UI extensions | Shopify Plus only.                                                   |

---

### ✅ Most Relevant for a Filter/Swatch Builder
- **Admin → Embedded app** → Merchant-friendly UI for configuring filters/swatches.  
- **Online Store → Theme app extension** → Render those filters/swatches directly on collection/product pages.
