# Example 3 — Order Holder Validation

**Customer:** Where is my order 1?

**Assistant:** I can check it. For security, I need the full name of the account holder.

**Customer:** Pedro Henrique Oliveira.

**Internal action:** `get_order_status(order_id=1, customer_name="Pedro Henrique Oliveira")`

**Assistant:** I found your order. It is marked as delivered. The order date was 2025-10-15 and the tracking code is BRAB1234567BR. If you did not receive it, I can refer the case to our team.

> This example uses fictional data. The real lookup validates the name before returning details.
