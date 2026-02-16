# Overheid Claude Plugins

[![EUPL-1.2](https://img.shields.io/badge/licentie-EUPL--1.2-blue.svg)](LICENSE)

Centrale catalogus van [Claude Code](https://docs.anthropic.com/en/docs/claude-code) plugins voor de Nederlandse overheid. Via deze marketplace kunnen overheidsteams hun Claude Code plugins publiceren en ontdekken.

## Installatie

Voeg de marketplace toe aan Claude Code:

```bash
claude plugin marketplace add MinBZK/overheid-claude-plugins
```

Bekijk beschikbare plugins:

```bash
claude plugin list --marketplace overheid-plugins
```

Installeer een plugin:

```bash
claude plugin install logius-standaarden@overheid-plugins
```

## Beschikbare plugins

| Plugin | Beschrijving | Maintainer |
|--------|-------------|------------|
| [logius-standaarden](https://github.com/MinBZK/logius-standaarden-plugin) | 10 skills voor 88 Logius standaarden repositories (API Design Rules, Digikoppeling, OAuth NL, FSC, CloudEvents, BOMOS, en meer) | Logius |

## Plugin toevoegen

Wil je een plugin toevoegen aan deze marketplace? Zie [docs/plugin-toevoegen.md](docs/plugin-toevoegen.md) voor de stappen.

Wil je eerst een plugin bouwen? Zie [docs/plugin-maken.md](docs/plugin-maken.md) voor een handleiding.

## Kwaliteitseisen

Plugins in deze marketplace moeten voldoen aan:

- Open-source licentie (EUPL-1.2, Apache-2.0, MIT, of vergelijkbaar)
- Publieke GitHub repository
- Geldige `.claude-plugin/plugin.json`
- Minimaal 1 werkende skill, command of agent
- Nederlandse of tweetalige documentatie

Zie [CONTRIBUTING.md](CONTRIBUTING.md) voor het volledige review-proces.

## Licentie

[EUPL-1.2](LICENSE) - European Union Public Licence
