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

Before pulling those threads together into the Vilano stack, I spent years building across a much wider set of difficult surfaces: browser automation and anti-bot environments, protocol and sandbox work, smart contract and adversarial security systems, low-latency signal-to-action tooling, scraping and public-data pipelines, retrieval and code intelligence, and the infra required to keep those systems alive.

The repo history is broad because the work has been broad. What makes it coherent is taste. I keep ending up in places where the interface lies, the environment pushes back, timing matters, and the operator still needs a clear picture of what happened after the fact.

## Build Surface

- Durable execution, orchestration, and stateful runtime systems.
- Agent infrastructure with review loops, governance, escalation, and real authority boundaries.
- Retrieval and code intelligence built around grounding, citations, and confidence instead of guesswork.
- Browser, protocol, and anti-bot work where "the script ran" is not the same thing as "the environment was believable."
- Low-latency systems that move from live input to ranking, filtering, and action.
- Data acquisition and integration work against brittle, ugly, or openly hostile interfaces.
- Security work close to smart contracts, transport quirks, and adversarial environments.

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
