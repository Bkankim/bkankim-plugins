# bkankim-plugins

Claude Code plugin marketplace maintained by [Bkankim](https://github.com/Bkankim).

## Plugins

| Plugin | What it does | Status |
|---|---|---|
| [smartthink](https://github.com/Bkankim/smartthink) | Context arming engine. Routes your task through Cynefin diagnosis, loads only the mental-model references it needs, synthesizes task-specific research into an armory pack, and primes the session before you start working. | v3 in development (pinned to the `v3` branch) |

## Install

```bash
claude plugin marketplace add Bkankim/bkankim-plugins
claude plugin install smartthink@bkankim-plugins
```

Start a new Claude Code session afterwards.

## How this marketplace works

Each plugin lives in its own repository. `.claude-plugin/marketplace.json` references it by git URL pinned to a commit sha, so what you install is exactly what was released. The sha moves only when a plugin ships a release.

## License

Marketplace metadata: MIT. Each plugin carries its own license.
