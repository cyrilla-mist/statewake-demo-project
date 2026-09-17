# STATEWAKE Demo Evidence Project

> **Supporting repository — not the STATEWAKE source code.**
>
> This deliberately small project exists as external project evidence for the STATEWAKE demo. The main product repository is [`cyrilla-mist/statewake`](https://github.com/cyrilla-mist/statewake).

## Repository Role

STATEWAKE is designed to verify whether a previously trusted working state is still safe to continue from. This repository provides a controlled project history that STATEWAKE can inspect during that demonstration.

It is intentionally separate from the product source so the demo can distinguish:

- the recovery agent itself;
- the external project being observed;
- historical implementation evidence;
- the currently trusted continuation path.

## Current Demo State

- Current implementation path: **Feature B**
- Primary demo route: **Feature B**
- Feature A has been removed from the active demo flow.
- Feature A remains part of project history.

## Demo Flow

The demo uses changes in this repository to show how STATEWAKE handles an interrupted project:

1. STATEWAKE compares the previously trusted state with current evidence.
2. A direction conflict can require explicit human authorization.
3. After authorization, the trusted continuation state moves to Feature B.
4. Later evidence is evaluated against that updated trusted state rather than the original baseline.

See the main [`STATEWAKE`](https://github.com/cyrilla-mist/statewake) repository for product architecture, recovery rules, testing, and deployment information.

## Status

This repository is maintained as a **demo/evidence fixture**. It is not intended to evolve into an independent product.
