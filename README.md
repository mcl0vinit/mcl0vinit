# Sam Powell

CEO @ [Vilano AI](https://vilano.ai)

> I build infrastructure for agent systems that have to survive contact with reality.

Vilano is the clearest expression of how I think about software: durable execution, grounded retrieval, explicit work graphs, and operator control.

If agents are going to matter, they cannot just be clever in the happy path. They need to be replayable, inspectable, governable, and resilient under load.

## Vilano Stack

- [Vilano Runtime](https://github.com/vilano-ai/runtime): the durable execution substrate. It is built around deterministic replay. The code reruns. The state does not. Underneath it is a BEAM kernel handling waits, signals, leases, supervision, passivation, and durable execution state, with disposable TypeScript workers on top.
- Corpus: the retrieval and code-intelligence layer. Polyglot analysis, knowledge graphs, semantic search, and grounded answers with citations instead of hand-wavy synthesis.
- Assembly: the durable work system. It turns tickets into explicit graphs, executes them with specialized agent roles, reviews failures, replans when the shape of the work changes, and keeps the whole process inspectable.
- On top of that foundation sit product-shaped surfaces: branchable synthetic systems, decision environments, and simulation tools.

## Past Work

Before Vilano, I spent years on harder and more adversarial surfaces: browser automation and anti-bot environments, protocol and sandbox work, smart contract security, low-latency execution systems, scraping and public-data pipelines, retrieval and code intelligence, and the infra required to keep those systems alive.

The common thread was never the market. It was the constraint. I kept choosing problems where the interface lies, the environment pushes back, timing matters, and you only get paid for what still works once reality hits.

## Language Footprint

```text
non-fork repo history

Rust         54  ##############
TypeScript   45  ############
Go           33  #########
JavaScript   27  #######
Solidity     27  #######
Other        37  ##########
```
