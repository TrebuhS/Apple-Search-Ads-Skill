# Apple Search Ads Skill

This [skill](https://docs.anthropic.com/en/docs/claude-code/skills) lets agents manage your Apple Search Ads campaigns, ad groups, keywords, and reports through the [asa-cli](https://github.com/TrebuhS/asa-cli) tool.

## What it does

Once installed, Claude Code can:

- Create and manage campaigns, ad groups, and keywords
- Add negative keywords to block wasted spend
- Pull performance reports (daily, weekly, monthly)
- Search for apps and geo targets
- Bulk operations — pause 50 keywords in one command
- Manage multiple ASA accounts

Just ask Claude things like:

- "Show me my active campaigns"
- "Pause all keywords with CPA over $5"
- "Pull a weekly report for January. List the suggestions on what can be improved"
- "Add keywords from my category, competition and brand campaigns as negative keywords to my discovery campaign"
- "Do a deep keywords research for my habit tracker. Look only into tier 1 countries. Choose 1 country that performs the best, plan the ads campaigns structure and create it. My daily budget is $100."

## Prerequisites

Install the `asa-cli` tool:

```bash
brew install TrebuhS/tap/asa-cli
```

Then configure your Apple Search Ads API credentials:

```bash
asa-cli configure
```

See the [asa-cli README](https://github.com/TrebuhS/asa-cli) for full setup instructions.

## Install the skill

```bash
npx skills add TrebuhS/apple-search-ads
```

## License

[MIT](LICENSE)
