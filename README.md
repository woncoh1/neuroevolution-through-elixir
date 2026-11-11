# Livebook of Neuroevolution through Elixir

> Remaster and interpretation of the classic [Handbook of Neuroevolution through Erlang](https://link.springer.com/book/10.1007/978-1-4614-4463-3)

## Thesis-Antithesis-Synthesis

> Each chapter consists of the following 3 types of implementation:

- Thesis: Pure Elixir translation and modernization of the original Erlang codebase
- Antithesis: Introduce Numerical Elixir (Nx), and convert the actor model to tensor parallelism
- Synthesis: Fuse the strengths of pure Elixir and Nx to enable neuroevolution that is both flexible and computationally efficient

## Generation-Evaluation-Selection

> This is a conceptual framework of evolution we use to organize source code:

- Generation: mutation, cross-over, and other mechanisms of creating diversity
- Evaluation: fitness, reward, energy cost, or other methods and indicators to measure value
- Selection: survival, reproduction, archiving, and other constraints
