# LLM Architecture and Training

## Key Concepts (Understand)
- Training data shapes capabilities; quality and domain specificity matter.
- Transformers replaced RNN-based seq2seq models by processing tokens in parallel.
- Attention mechanism lets the model focus on relevant words for each output token.
- Post-training aligns models with human preferences through supervised data and reinforcement learning.
- Sampling strategies (temperature, top-k/p) balance creativity and consistency.

## Deep Learning Technique (Absorb)
**Mind map:** Sketch the path from raw text → tokens → transformer layers → sampled output to visualize data flow.

## Practical Application (Apply)
- Adjust sampling temperature in a small text-generation script and observe output differences.
- Compare a seq2seq translation example with a transformer-based translation.

## Reflection (Integrate)
- What trade-offs arise between enlarging model size and ensuring high-quality training data?

## Connections (Expand)
- [[02 How LLMs Work]]
- [[15 Fine-Tuning]]
- External: [Attention Is All You Need](https://arxiv.org/abs/1706.03762)

## Memory Hooks (Remember)
- Attention acts like a spotlight highlighting important words.
- Think of sampling as rolling weighted dice for each new token.
- Transformer = parallel in, sequential out.

## Backlinks
- [[02 How LLMs Work]]
- [[15 Fine-Tuning]]
