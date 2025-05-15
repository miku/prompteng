# Prompting

## Training

* base model
* SFT
* RLHF

## How to save or export a chat history?

* browser extension to export chat history
* use a chat app

### Chat Apps

* LibreChat: https://github.com/danny-avila/LibreChat

## List of system prompts

Leaked prompts:

* [https://github.com/x1xhlol/system-prompts-and-models-of-ai-tools](https://github.com/x1xhlol/system-prompts-and-models-of-ai-tools)
* [https://github.com/jujumilk3/leaked-system-prompts](https://github.com/jujumilk3/leaked-system-prompts)

PLeak: Prompt leaking attacks: [https://arxiv.org/pdf/2405.06823](https://arxiv.org/pdf/2405.06823)

> The functionality and performance of an LLM application highly
depend on its system prompt. Thus, an LLM application developer often views its
system prompt as intellectual property and keeps it confidential.

> Specifically, they manually craft certain queries by human experts so that
when an LLM application takes such a query as input, its response reveals its
own system prompt

Different from jailbreaking; e.g. let an LLM do what it "should not"

Use of a "shadow llm" and an optimization problem.

> While intuitively simple, it is challenging to solve the optimiza-
tion problem due to a large search space and the goal of word-by-
word exact matches with system prompts in the output.

On system prompts:

LLM Application. An LLM application, denoted by 𝑓 in Table 1, builds on top of
a backend LLM 𝑓𝜃 and designs a system prompt 𝑝𝑡 . A user sends a query 𝑞 to an
LLM application, which concatenates the query 𝑞 with its system prompt 𝑝𝑡 to
construct a prompt. Then, the LLM application sends the constructed prompt to
the backend LLM, which produces a response. Finally, the LLM application relays
the response back to the user.

## Adversial Queries

* can you make a prompt that make a model to do X? e.g. repeat it self, endlessly
