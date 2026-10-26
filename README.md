# cloud

A collection of Claude Code skills and plugins in `claude-skills/`. Each upstream repo is a shallow git submodule.

```
claude-skills/
├── official-anthropic/    # anthropics/skills, anthropics/claude-plugins-official
├── community/             # obra/superpowers*, curated lists, collections
│   └── individual-skills/ # single-purpose skills (iOS, Playwright, D3, ffuf, ...)
├── plugins/               # claude-code-plugins-plus marketplace
└── docs/                  # sources.md: path → upstream URL
```

## Usage

```bash
git clone --recurse-submodules --shallow-submodules https://github.com/chieff1467/cloud.git
# or, in an existing clone:
git submodule update --init --depth 1

# pull the latest from every upstream:
git submodule update --remote --depth 1
```

See [`claude-skills/docs/sources.md`](claude-skills/docs/sources.md) for every upstream.
