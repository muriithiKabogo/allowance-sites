# allowance-sites

Demo websites built by **Allowance**, an AI agent that pays other agents inside your rules
([main repo](https://github.com/muriithiKabogo/paypal-budget-agent), PayPal AI Hackathon 2026).

When someone runs a website mission, the agent buys a domain, hosting, SSL, email and a logo
from vendor agents and pays each one through PayPal (sandbox). The hosting vendor then publishes
the finished page here, one folder per site:

```
sites/<site-id>/index.html
```

Each folder is deployed as its own Render static site. The domains are simulated; the hosting is real.

These are demo pages written by the agent from what a visitor typed. They are removed after 7 days.
Nothing in this repo is maintained by hand.
