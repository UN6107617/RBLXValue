# RBLXValue
The most accurate MM2 value comparison site — trade calculator, inventory tracker, value history and Discord bot.

🌐 **https://rblxvalue.com**

RBLXValue indexes and compares MM2 item values from multiple community sources to generate a balanced global estimated value for every tradeable item in the game. Built by traders, for traders.

## Features

- **Item Value Lookup** — Search hundreds of MM2 items with demand, rarity and stability ratings
- **Trade Calculator** — Compare both sides of a trade in real time to check fairness
- **Inventory Calculator** — Build and track your MM2 collection and see your total value
- **Value History** — Per-item price charts showing historical value changes
- **Public Profiles** — Log in with Roblox to showcase your inventory and total value
- **Private Server Finder** — Find active MM2 trading servers
- **Discord Bot** — Look up values directly in any Discord server
- **Widget Embed** — Embed live value widgets on your own site

## How Values Work

RBLXValue calculates an **Estimated Value** by averaging data from two independent community sources:

| Source | Description |
|--------|-------------|
| [MM2Values](https://mm2values.com) | One of the oldest and most trusted MM2 value lists |
| [Supreme Values](https://supremevaluelist.com) | Community-driven list tracking market trends and demand |

Values are cross-referenced daily. The spread between both sources is shown transparently so traders can see where sources agree or disagree.

## API

RBLXValue provides a free public API for MM2 item values.

**Base URL:** `https://rblxvalue.com/api/v1/`

| Endpoint | Description |
|----------|-------------|
| `GET /items` | List all items |
| `GET /items?slug=seer` | Get item by slug |
| `GET /items?acronym=CHW` | Get item by acronym |
| `GET /items?search=chroma` | Search items |

## Tech Stack

- PHP / MySQL
- Tailwind CSS (CDN)
- Nginx / CloudPanel (Hetzner)
- BunnyCDN for image delivery
- Cloudflare

## Related

- [MM2 Value Discord Bot](https://github.com/UN6107617/mm2-value-discord-bot) — Official Discord bot powered by the RBLXValue API

## Links

- 🌐 Website: https://rblxvalue.com
- 📖 Docs: https://rblxvalue.com/docs
- 🤖 Bot Invite: https://discord.com/api/oauth2/authorize?client_id=1514378630225203391&permissions=277026875392&scope=bot%20applications.commands
- 💬 Discord: https://discord.com/invite/2puhtMjdnw
- 📬 Contact: https://rblxvalue.com/contact

## Disclaimer

RBLXValue is an independent fan site and is not affiliated with Roblox Corporation or the developers of Murder Mystery 2. All item names and game content are the property of their respective owners. Values shown are estimates based on community data.
