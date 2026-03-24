# Logitropic Plugins Directory

**Repository:** [logitropic/conductor](https://github.com/logitropic/conductor)

A curated directory of plugins for Claude Code.

> **Important:** Make sure to trust a plugin before installing, updating, or using it. Review the plugin source code and understand what permissions it requires.

## Structure

- **`.claude-plugin/`** - Plugin marketplace manifest
  - `marketplace.json` - Plugin registry defining available plugins and their sources

## Available Plugins

### Conductor

**Category:** Development

Conductor is a Claude Code plugin that allows you to specify, plan, and implement software features.

- **Source:** [logitropic/conductor](https://github.com/logitropic/conductor)
- **Path:** `plugins/conductor`
- **Homepage:** [https://github.com/logitropic/conductor](https://github.com/logitropic/conductor)

## Installation

First, add this marketplace to Claude Code:

```
claude plugin marketplace add https://github.com/logitropic/claude-plugins.git
```

Plugins can then be installed directly from this marketplace via Claude Code's plugin system.

To install, run:
```
/plugin install conductor@logitropic-plugins
```

Or browse for the plugin in `/plugin > Discover`

## License

Please see each linked plugin repository for the relevant LICENSE file.

## Documentation

For more information on developing Claude Code plugins, see the [official documentation](https://code.claude.com/docs/en/plugins).
