---
name: get-started
description: Set up StoreRocket after connecting it. Finds the person's store locator, adds their stores if it is empty, gives them the code that puts it on their website, and checks that it is live. Use when someone has just connected StoreRocket or asks to set up their store locator, dealer locator or stockist map.
---

# Get started with StoreRocket

The person just connected StoreRocket. Help them reach a working store locator on their website in as few steps as possible.

1. Call `list-store-locators`. If there is more than one, ask which one to set up; if there is one, use it without asking.
2. If it has no locations (its `next_step` says so), ask for their stores in one short question. They can paste a list, attach a spreadsheet, or give the page on their website that lists their stores. Add them with `create-locations`, up to 50 per call, and say how many were added. Ask before adding anything.
3. Call `get-install-code`. Ask what their website runs on if they have not said, then give the code and its steps for that platform. Shopify and WordPress have free StoreRocket apps that need no code.
4. When they say the page is published, call `get-install-code` again. If `live` is true, tell them the store locator is live and on which page.
5. If the store locator already had locations and is already live, skip to a short summary instead: how many locations, the page it is live on, and the places visitors searched without finding a store (`get-searches-with-no-results`).

Keep each reply short. Never invent stores, addresses or numbers.
