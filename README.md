# Multi-RTL Community Configs

Community-maintained RTL configuration files for the [Multi-RTL](https://chromewebstore.google.com/detail/multi-rtl/nhajcafhnpnnfeniefjmaplmeodoffem) Chrome extension.

## Available Configs

| Site | File |
|------|------|
| ChatGPT | `multi-rtl_config_ChatGPT.json` |
| Claude | `multi-rtl_config_Claude.json` |
| Gemini | `multi-rtl_config_Gemini.json` |
| Kimi | `multi-rtl_config_Kimi.json` |
| NotebookLM | `multi-rtl_config_NotebookLM.json` |
| Slack | `multi-rtl_config_Slack.json` |
| WhatsApp | `multi-rtl_config_WhatsApp.json` |

## How to use

1. Download a config JSON file
2. Open the Multi-RTL extension popup
3. Click **Import Config** and select the file

Or use the **Import Config** button in the extension — it lists all available community configs for one-click import.

## Contributing

To add a config for a new site:

1. Export your config from the Multi-RTL extension (Export Config)
2. Add the JSON file to `configs/`
3. Update `configs/index.json` with the new entry
4. Submit a Pull Request
