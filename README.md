# LaClawClaw · Open Source Production

> The open source community has given us so much.
> We're open-sourcing our factory production steps from 0 → 1.

[LaClawClaw](https://laclawclaw.com) is the first agent-only Shopify store.
The products we sell are designer collectibles manufactured in Zhongshan,
China. This repo is the glass wall — every spec, workflow phase, mold
drawing, and factory question, published as we ship.

**No NDA. No PR gloss. No retconned timelines.**

## Links

- **Store:** [laclawclaw.com](https://laclawclaw.com) — pitch + $1 Founders pre-order
- **Live build log:** [laclawclaw.com/build](https://laclawclaw.com/build) — chronological updates
- **Agent protocols:** [laclawclaw.com/how-it-works](https://laclawclaw.com/how-it-works) — A2A, MCP, AWP explainer
- **Agent manifest:** [laclawclaw.com/.well-known/agent.json](https://laclawclaw.com/.well-known/agent.json)

## Products in production

| Product | Status | Ship target |
|---|---|---|
| [**Glytch: Nemo Edition**](./products/glytch-nemo-edition/) — 7" (17.8cm) designer figure | CAD handoff | Q3 2026 |
| Klaw · variant TBD | Concept | TBD |
| Jynx · variant TBD | Concept | TBD |

## Why this repo exists

Open source gave us every tool we needed to build an agent-native commerce
platform — the Linux kernel our servers run on, the compilers our code hits,
the protocols (A2A, MCP, AWP) that let agents discover us. We can't
open-source Shopify. We can't open-source Stripe. But we can open-source how
we make a physical product: what we asked the factory, what they pushed back
on, what broke, what shipped.

If you're making a designer toy, a collectible, or any small-run physical
good — fork what's useful. That's the contract.

## How this repo is structured

```
products/<slug>/
├── README.md              ← index for this product
├── parts-breakdown.svg    ← exploded component diagram
├── mold-specs.md          ← dimensions, tolerances, finishes
├── workflow.md            ← 5 phases: Design → CAD → Sign-off → T1 → Production
├── factory-questions.md   ← open questions for the manufacturer
└── photos/                ← reference images
```

## Contributing / learning from this

This is a write-ahead log of our manufacturing process — not a typical OSS
project accepting PRs. But:

- **Fork it** — if you're shipping a collectible of your own, clone the
  structure. The workflow phases are what our factory agreed to.
- **Open an issue** — if you spot something we got wrong (a mold tolerance
  that won't survive T1, a material choice that'll warp), we want to hear.
  This is why we're publishing.
- **Cite it** — if you write about open-source hardware workflows, a
  pointer back helps spread the practice.

## License

- **Documentation (Markdown, SVGs, photos):** [CC-BY-4.0](./LICENSE)
- **CAD files** (when published): CERN-OHL-S-2.0

You can reuse any of this commercially as long as you attribute LaClawClaw
and preserve the license.

---

_Built by [Injester](https://injester.com). Questions: founders@injester.com._
