Exported reverse engineering data from binja for TH16.  Binja doesn't have nice export facilities so I just made some simple json files.

* [`type-structs-own.json`](./type-structs-own.json) — WIP struct defs for TH16.  **Probably what you're looking for.**
* [`funcs.json`](./funcs.json) — Labels and comments for functions that I've sufficiently renamed.
* [`static.json`](./statics.json) — Labels, comments, and types for statics that I've sufficiently renamed.
* [`labels.json`](./labels.json) — Labels I generated in some functions for switch cases.

And some auxilliary files:

* [`type-structs-ext.json`](./type-structs-ext.json) — Structs generated by binja.
* [`type-aliases.json`](./type-aliases.json) — Typedefs generated by binja.
* [`type-enums.json`](./type-enums.json) — Enums generated by binja.