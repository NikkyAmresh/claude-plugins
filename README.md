# Claude Code plugins by Nikky Amresh

A Claude Code plugin marketplace. Add it once, then install any plugin listed below.

```
/plugin marketplace add NikkyAmresh/claude-plugins
/plugin install <plugin>@nikkyamresh
```

## Plugins

| Plugin | What it does | Install |
| --- | --- | --- |
| [Redline](https://github.com/NikkyAmresh/redline) | Review Claude Code plans like a doc and playable prototypes like a design: inline comments, suggested edits and component pins in the browser that land back in the session. [redline.algofunds.in](https://redline.algofunds.in) | `/plugin install redline@nikkyamresh` |

Update with `/plugin marketplace update nikkyamresh`, then `/plugin update <plugin>`.

## Adding a plugin

Each plugin lives in its own repository with a `.claude-plugin/plugin.json`. To list one here, add an entry to `.claude-plugin/marketplace.json` pointing at that repository and a row to the table above, then check it with `claude plugin validate .`.
