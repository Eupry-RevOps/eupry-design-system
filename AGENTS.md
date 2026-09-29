# Agent instructions — Eupry Design System

Before any task, including after a fresh clone or pull, read [WORKFLOW.md](WORKFLOW.md) and [memory-bank/toc.md](memory-bank/toc.md). Load active context and the latest monthly task summary before changing files. Reconcile notes against current source.

For every change, update `memory-bank/activeContext.md` and a dated final task document in the same branch. Document each new file's path and reuse analysis in that task document. The GitHub memory-bank check enforces these updates on pull requests and main pushes.

Project boundary: Keep the squid as the sole custom UI brand icon; use actual Lucide icon names as documented.

Repository facts start at README.md; DESIGN.md; tokens.json. Do not commit credentials or production data. A Git pull cannot automatically run checked-in hooks; start this sequence when beginning work in the checkout.
