# Sam Powell

CEO @ [Vilano AI](https://vilano.ai)

> I build systems that stay legible under failure: when the worker dies, the network lies, or the interface fights back.
>
> Durable runtimes. Agent control planes. Retrieval and code intelligence. Browser and protocol sandboxes. Low-latency execution systems. Security work close to adversarial surfaces.

My GitHub history is less a single lane than a trail through hard constraints. The through-line is consistent: I care about durable state, explicit control, grounded answers, believable environments, and operators who can tell what happened without guessing.

## Current Focus

[Vilano Runtime](https://github.com/vilano-ai/runtime) is the clearest expression of how I think about software: a durable runtime for agent systems built around deterministic replay.

The code reruns. The state does not.

A BEAM kernel handles waits, signals, leases, supervision, passivation, and durable execution state. Disposable TypeScript workers sit on top. The point is not just to automate work, but to make execution inspectable, replayable, and governable once the system is under load.

## Vilano Stack

Runtime is the execution substrate.

A retrieval and code-intelligence layer sits next to it: polyglot analysis, knowledge graphs, semantic search, and grounded answers with citations instead of hand-wavy synthesis.

A durable work system sits on top: take a ticket, turn it into an explicit graph, execute it with specialized agent roles, review failures, replan when the shape of the work changes, and keep the whole process inspectable.

That same stack also underpins product-shaped surfaces: branchable synthetic systems, decision environments, and simulation tools built on the same durable foundations.

## Past Work

Before focusing this hard on durable agent runtimes, I spent years building across a much wider set of difficult surfaces: browser automation and anti-bot environments, protocol and sandbox work, smart contract and adversarial security systems, low-latency signal-to-action tooling, scraping and public-data pipelines, retrieval and code intelligence, and the infra required to keep those systems alive.

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
