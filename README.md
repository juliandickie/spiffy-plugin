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

Set your Spiffy API key. Three options -

1. `SPIFFY_API_KEY` env var (a literal 64-char hex key, or a 1Password `op://` reference)

2. `~/.config/spiffy-plugin/config.toml` with `api_key = "..."`

3. A repo-root `.env` with `SPIFFY_API_KEY=...`

Get your key from the Spiffy dashboard under Settings - API.

## Source and development

This is the lean published plugin - generated, not hand-edited. Development happens at [juliandickie/spiffy-dev](https://github.com/juliandickie/spiffy-dev) (full source, build tooling, history). File issues there.

## License

MIT.
