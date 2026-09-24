# RBLXValue

RBLXValue is an MM2 value comparison platform for Murder Mystery 2 traders, developers and communities.

🌐 **https://rblxvalue.com**

RBLXValue compares MM2 item data from multiple community value sources and provides tools for checking item values, sets, trading data, value history and Roblox profiles.

## Features

- **Item Value Lookup** — Search hundreds of MM2 items with values, demand, rarity, stability and source data
- **Set Values** — View complete MM2 sets, included items and combined set values
- **Trade Calculator** — Compare both sides of a trade in real time
- **Inventory Calculator** — Build and track an MM2 collection and calculate its total value
- **Value History** — View historical value changes for supported items
- **Public Profiles** — Connect a Roblox account and showcase inventory information
- **Private Server Finder** — Find active MM2 trading servers
- **Discord Bot** — Look up MM2 items, sets and Roblox profiles directly from Discord
- **Widget Embed** — Embed live RBLXValue data on your own website
- **Developer API** — Build your own MM2 tools and applications using the RBLXValue API

## How Values Work

RBLXValue compares data from multiple community sources and provides an estimated value for supported MM2 items.

The platform currently references:

| Source | Description |
|--------|-------------|
| [MM2Values](https://mm2values.com) | Community MM2 value list |
| [Supreme Values](https://supremevaluelist.com) | Community value list tracking MM2 market data |

Source values are displayed transparently so users can compare the different values instead of relying on a single number.

## API

RBLXValue provides a public REST API for developers building MM2 tools, Discord bots, websites and applications.

**Base URL:**

```text
https://api.rblxvalue.com/v2
```

### Authentication

Authenticated requests use the `X-Api-Key` header:

```http
X-Api-Key: YOUR_API_KEY
```

### Available Endpoints

| Endpoint | Description |
|----------|-------------|
| `GET /items/{slug}` | Get an MM2 item and its value data |
| `GET /sets` | Search and retrieve MM2 set data |
| `GET /history/{slug}` | Get value history for an item |
| `GET /profile/{username_or_id}` | Get Roblox profile data |
| `GET /inventory/{username_or_id}` | Get Roblox inventory data |
| `GET /meta` | Get API and data metadata |

Example:

```bash
curl https://api.rblxvalue.com/v2/items/corrupt \
  -H "X-Api-Key: YOUR_API_KEY"
```

For complete API documentation, visit:

**https://docs.rblxvalue.com**

## Discord Bot

RBLXValue provides a ready-to-use Discord bot built with **discord.js v14**.

The bot currently supports commands such as:

- `/item`
- `/set`
- `/profile`

The bot uses the RBLXValue API and can be installed on your own Discord server.

**Repository:**  
https://github.com/UN6107617/mm2-value-discord-bot

## Tech Stack

- PHP / MySQL
- Tailwind CSS
- Nginx / CloudPanel
- Hetzner
- BunnyCDN
- Cloudflare

## Related Projects

- **MM2 Value Discord Bot** — https://github.com/UN6107617/mm2-value-discord-bot
- **API Documentation** — https://docs.rblxvalue.com
- **RBLXValue Website** — https://rblxvalue.com

## Links

- 🌐 Website: https://rblxvalue.com
- 📖 API Documentation: https://docs.rblxvalue.com
- 🤖 Discord Bot: https://github.com/UN6107617/mm2-value-discord-bot
- 💬 Discord: https://discord.com/invite/2puhtMjdnw
- 📬 Contact: https://rblxvalue.com/contact

## Disclaimer

RBLXValue is an independent fan site and is not affiliated with Roblox Corporation or the developers of Murder Mystery 2.

All item names, game content and trademarks are the property of their respective owners. Values shown on RBLXValue are estimates based on community data and should not be treated as guaranteed market prices or financial advice.
