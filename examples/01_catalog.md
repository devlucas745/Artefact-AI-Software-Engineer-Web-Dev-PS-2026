# Example 1 — Catalog and Inventory

**Customer:** Which guitars are available for up to R$ 1,000?

**Assistant:** I will check the catalog and current inventory for options within that budget.

**Internal action:** `search_products(query="guitar", max_price=1000, only_available=true)`

**Assistant:** I found these available options in the catalog:

- Tagima Memphis AC-39 Nylon Natural — R$ 429.90
- Rozini RC-104 Nylon Student — R$ 459.90
- Shelby SN-100 Folk Steel Black — R$ 549.00
- Giannini GF-1R Folk Steel Sunburst — R$ 579.90
- Yamaha C40 Nylon Natural — R$ 599.90

Would you like me to compare these models?

> The list is based on the supplied CSV records; display order may vary.
