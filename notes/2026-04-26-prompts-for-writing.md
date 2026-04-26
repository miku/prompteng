# Prompts for writing

* no more than 50% context usage, [context rot](https://www.trychroma.com/research/context-rot)
* less test-time bugdet, "thinking mode", for summarization, style contraints writing, or factual recall from documents
* thinking for analytical texts, advanced arguments and the like

Avoid SLOP:

* LLM indicators, e.g. em-dash, *that's not X, that's Y*, and more; cf. [The Last Fingerprint: How Markdown Training Shapes LLM Prose](https://arxiv.org/pdf/2603.27006)
* typical markers: three-part enumeration, "not just ..., but", adjective before nouns
* prompt to write like a "journalist", short main clauses, mention numbers at the start, ...
* use blacklists in system prompt, but also positive instructions, cf [pink elephant paradox](https://en.wikipedia.org/wiki/Ironic_process_theory)

Agent Skills:

* [Spec](https://agentskills.io/home)

> A standardized way to give AI agents new capabilities and expertise.

Workspace may include:

* styleguide (up to 5K words)
* glossary
* 3-5 example texts (in target style)
* 1-2 counterexamples
* target audience
* format constraints

