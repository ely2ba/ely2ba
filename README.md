I'm interested in continual learning and the dynamics of post-training: what fine-tuning and
reinforcement learning leave in a model beyond its score, and how a skill holds up under the training
that comes after it.

**Latest:** [Fine Until Fine-Tuned: Repeated Solutions Make Reasoning
Fragile](https://arxiv.org/abs/2609.33559) (arXiv, 2026). A model trained on a
few hundred solutions repeated many times scores as well as one trained on many solutions seen once, but
its reasoning breaks when it is fine-tuned again, even on something unrelated.
[Code, data and results](https://github.com/ely2ba/reasoning-durability).
