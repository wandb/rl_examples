# Training LLMs using Reinforcement Learning

This repository contains examples that show how to train LLMs with reinforcement learning and how to build agents. In these examples, you will learn to:

- Trace rollouts with [Weave](https://docs.wandb.ai/weave), view prompts, outputs, rewards, etc. in one place
- Use `Weave` with popular frameworks like `TRL`, `verl`, `OpenPipe`, and `verifiers`
- Use the `OpenPipe` serverless API to train models calls without hosting your own stack
- Build and test agents with open models using RL, with repeatable logs and evals

---

## Examples

| Sno | Framework |                  Code                                                                    |            |
| ---:|-----------|------------------------------------------------------------------------------------------|------------|
| 1.   | TRL       | [Post-training Qwen2.5 On NuminaMath Dataset](./trl_examples/numinamath_grpo.ipynb)    | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/wandb/rl_examples/blob/main/trl_examples/numinamath_grpo.ipynb)       |
| 2.   | TRL       | [Post-training with GSPO algorithm](./trl_examples/numinamath_gspo.ipynb)              | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/wandb/rl_examples/blob/main/trl_examples/numinamath_gspo.ipynb)       |
