# StoreRocket Store Locator

StoreRocket runs the store locator on your website: the map and list where customers find your nearest store, dealer or stockist. This plugin connects Claude to your StoreRocket account, so you can go from an empty account to a live store locator in one conversation, and keep it working for you after that.

## What it does

- **Connects Claude to StoreRocket.** Claude can find, add and update your locations (addresses, opening hours, categories, custom fields and buttons), create and change the custom fields and buttons themselves (a "Book a visit" button on every store in one ask), get the code that puts the locator on your website, and read how visitors use it: views, searches, clicks, leads, and the places people searched without finding a store.
- **Sets you up, step by step.** The `get-started` skill finds your store locator, adds your stores if it is empty, gives you the install code for your website platform, and checks that the locator is live once you publish.
- **Reports what visitors want.** The `performance-report` skill shows how your locator did against the period before, what visitors searched for, where they found no store nearby, and the few actions worth taking.

Claude asks before every change, and each deletion removes one location, field or button at a time. The connection cannot see your billing or change your plan, password or team.

## Try asking

- "Set up my StoreRocket store locator."
- "Add these stores to my store locator" (paste a list or attach a spreadsheet).
- "Give me the code to put my store locator on my Shopify store."
- "How did my store locator do last month?"
- "Where did visitors search without finding a store?"

## Install

In Claude, add **StoreRocket Store Locator** from the plugin directory. In Claude Code:

```
/plugin install storerocket --marketplace storerocket/agent-plugins
```

The first time Claude uses StoreRocket, sign in with your StoreRocket login and choose what to allow. New to StoreRocket? [Start a free trial](https://storerocket.io/get-started?utm_source=claude&utm_medium=plugin&utm_campaign=agent-plugins) or create your account while you connect. Every plan and free trial can connect. Visitor statistics follow your plan's Analytics.

## How it connects

The plugin adds one remote MCP server, `https://storerocket.io/mcp`, with OAuth sign-in. It runs no code on your computer.

## Data

Everything the plugin reads or changes goes between Claude and StoreRocket only, and nothing is sent anywhere else. See StoreRocket's [privacy policy](https://storerocket.io/privacy) and [terms](https://storerocket.io/terms).

## Help

[Documentation](https://docs.storerocket.io/api/mcp) · [Support](https://storerocket.io/contact) · [StoreRocket for AI assistants](https://storerocket.io/ai-agents?utm_source=claude&utm_medium=plugin&utm_campaign=agent-plugins)
