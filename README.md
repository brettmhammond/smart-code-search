# smart-search

**OpenClaw skill for semantic code & docs search powered by ColGREP/NextPlaid.**

\#1 on MTEB Code. Local, fast, private — search by meaning, not keywords.

## Install

```bash
npx clawhub@latest install smart-search
```

Or manually: copy the `SKILL.md` and `references/` folder into your OpenClaw skills directory.

## What It Does

Gives your OpenClaw agent semantic search across codebases, documentation, and knowledge bases using [ColGREP](https://github.com/lightonai/next-plaid) — a 17M parameter model that runs locally on CPU and outperforms 8B parameter embedding models on every benchmark.

- **MTEB Code**: #1 code retrieval
- **BrowseComp-Plus**: 87.59% accuracy (beating all models up to 8B params)
- **Sub-second queries** on CPU, zero API cost, 100% private
- **Auto-updating indexes** — no maintenance

## Quick Start

```bash
# Install ColGREP
brew install lightonai/tap/colgrep

# Index your project
cd /path/to/project && colgrep init

# Search by meaning
colgrep "payment capture retry logic"
```

## Links

- [ColGREP + NextPlaid](https://github.com/lightonai/next-plaid)
- [The Bloated Retriever Era Is Over](https://lighton.ai/lighton-blogs/the-bloated-retriever-era-is-over)
- [LateOn-Code: #1 on MTEB Code](https://lighton.ai/lighton-blogs/lateon-code-colgrep-lighton)
- [ClawHub](https://clawhub.ai)
- [OpenClaw](https://openclaw.ai)

## License

MIT
