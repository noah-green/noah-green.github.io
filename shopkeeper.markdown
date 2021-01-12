---
layout: default
---
# Shopkeeper
A Discord bot to automate shopping for items in tabletop RPGs.
## Why?
When the COVID-19 pandemic hit, my Dungeons and Dragons group moved to Discord. We used other bots for things like music, and I became interested in them as tools for adapting and extending the Discord to fit your needs. My dungeon master, Austin, got bored whenever our party went into town to buy magic swords or healing potions. So I made a bot!
# How?
Shopkeeper lives in the Discord server and has a list of shops that can be perused. When a user wants to check one of them out, it creates a direct message with them where they can see the inventory of the shop, inspect items more closely, and make purchases, which are deducted from the inventory.

![image](/assets/shopkeeper_example.png)

The dungeon master creates, opens, closes, and stocks these shops through a Google Sheets spread, on which they can also view a ledger of all recorded purchases.

![image](/assets/shop_sheet.png)

The big idea of Shopkeeper is the pairing of the Google Sheets API with Discord bots. This allows Shopkeeper to be very database-light (though it still uses one to map spreadsheets to Discord servers). It also makes it very simple to create and control the content the players see.

[Check out the code on my GitHub!](https://github.com/noah-green/shopkeeper)


