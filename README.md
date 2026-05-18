# Spiffy for Claude Code

Talk to the Spiffy checkout platform from Claude Code. Customer lookup, MRR / affiliate / churn reports, customer notes, and one-off promo code generation. Works with any Spiffy account - supply your own API key.

## Install

```
/plugin marketplace add juliandickie/spiffy-plugin
/plugin install spiffy
```

Or via the outfit catalog -

```
/plugin marketplace add juliandickie/outfit
/plugin install spiffy
```

## Configure

Set your Spiffy API key. Two options -

1. The `SPIFFY_API_KEY` environment variable (a literal 64-character hex key, or a 1Password `op://` reference)

2. A TOML file at `~/.config/spiffy-plugin/config.toml` containing `api_key = "your_key"` (TOML syntax, not dotenv `SPIFFY_API_KEY=`)

There is no repo-root `.env` option, the plugin has no dotenv loader. Get your key from the Spiffy dashboard under Settings - API.

## Source and development

This is the lean published plugin - generated, not hand-edited. Development happens at [juliandickie/spiffy-dev](https://github.com/juliandickie/spiffy-dev) (full source, build tooling, history). File issues there.

## License

MIT.
