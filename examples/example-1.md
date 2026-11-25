# Example

## Input

Online store selling routers and mesh Wi-Fi. AOV $120. Klaviyo. Max discount 10%. Reorder cycle ~180 days.

## Output (abridged)

| Flow | Trigger | Emails | Exit |
|---|---|---|---|
| Abandoned cart | Started Checkout | 3 (1h, 24h, 72h) | Placed Order |
| Win-back | No order in 270 days | 3 | Placed Order |
