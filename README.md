# JC Ghiringhelli

I build tools and methodologies for AI-assisted software engineering. Independent researcher. Based in the US, originally from Uruguay.

In 2026 I published **Generative Specification** — a programming discipline for the stateless reader. The core argument: the dominant failure mode of AI-assisted development is not incorrect code, it is architectural drift. The fix is a discipline that constrains what a stateless reader can derive from the artifacts alone, across sessions that share no persistent context. I built and tested it across six production projects before writing the paper.

→ **Paper (Zenodo):** [doi.org/10.5281/zenodo.19073543](https://doi.org/10.5281/zenodo.19073543)
→ **Methodology hub:** [genspec.dev](https://genspec.dev)
→ **Experiments + quality gates:** [github.com/jghiringhelli/generative-specification](https://github.com/jghiringhelli/generative-specification)

---

## Projects

### [Generative Specification](https://github.com/jghiringhelli/generative-specification)

The methodology, reproducible experiments, and a community quality gate library — 17 gates mapped to the seven GS properties, open for contribution. If you want to challenge a claim, reproduce an experiment, or propose a gate, this is the place.

### [ForgeCraft](https://github.com/jghiringhelli/forgecraft-mcp)

Production-grade engineering standards for AI coding assistants. Generates tailored instruction files (CLAUDE.md, .cursor/rules/, Copilot instructions) from curated template blocks matched to your stack. Supports Claude, Cursor, Copilot, Windsurf, Cline, and Aider.

[![npm](https://img.shields.io/npm/v/forgecraft-mcp?label=npm&color=blue)](https://www.npmjs.com/package/forgecraft-mcp)

```bash
npx forgecraft-mcp setup .
```

### [CodeSeeker](https://github.com/jghiringhelli/codeseeker)

Graph-powered code intelligence for AI assistants. Builds a knowledge graph of your codebase — imports, calls, class hierarchies — so Claude, Copilot, and Cursor understand how your code actually connects, not just what files contain.

[![npm](https://img.shields.io/npm/v/codeseeker?label=npm&color=blue)](https://www.npmjs.com/package/codeseeker)

---

**Tech:** TypeScript · Node.js · MCP · PostgreSQL · Knowledge Graphs · LLMs