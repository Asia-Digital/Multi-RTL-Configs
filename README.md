# Multi-RTL Community Configs

Community-maintained RTL configuration files for the [Multi-RTL](https://chromewebstore.google.com/detail/multi-rtl/nhajcafhnpnnfeniefjmaplmeodoffem) Chrome extension.

## Available Configs

| Site | File |
|------|------|
| ChatGPT | `multi-rtl_config_ChatGPT.json` |
| Claude | `multi-rtl_config_Claude.json` |
| Claude Code (Web) | `multi-rtl_config_ClaudeCode.json` |
| Gemini | `multi-rtl_config_Gemini.json` |
| Kimi | `multi-rtl_config_Kimi.json` |
| NotebookLM | `multi-rtl_config_NotebookLM.json` |
| Perplexity | `multi-rtl_config_Perplexity.json` |
| Slack | `multi-rtl_config_Slack.json` |
| WhatsApp | `multi-rtl_config_WhatsApp.json` |

## How to use

The easiest way: open the Multi-RTL extension popup, click **Import Config**, and choose any config from the list — it imports directly with one click.

You can also browse and download configs from the [Configuration Portal](https://multi-rtl.asia-digital.online/#portal) on the Multi-RTL website.

## Contributing

To add a config for a new site:

1. Export your config from the Multi-RTL extension (Export Config)
2. Add the JSON file to `configs/`
3. Update `configs/index.json` with the new entry
4. Submit a Pull Request
