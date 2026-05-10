# ltbl-experiment
aka the-fourth-man: a controlled experiment in agentic development methodology using three parallel implementations

## The Experiment
 
ltbl — Let There Be Light — is a WebGPU wavefront path-traced
pinball game built in Rust/WASM. A pinball machine reimagined
as a fully 3D playing field enclosed inside a glass egg,
floating in space.
 
The game is also a laboratory.
 
Three parallel implementations of ltbl are being developed
simultaneously, each driven by a different methodology for
providing context to an AI coding agent. The experiment
generates empirical data on a question that matters more as
agents take on more implementation work: does the quality and
structure of design context change what agents build, and how?
 
## The Three Twins
 
**Force** —
[`ltbl-force`](https://github.com/bdeansrowe/ltbl-force)
Full parley methodology.
 
**Brute** —
[`ltbl-brute`](https://github.com/bdeansrowe/ltbl-brute)
Good documentation, minimal methodology. Solid reference
material, no structured design reasoning.
 
**Ignorance** —
[`ltbl-ignorance`](https://github.com/bdeansrowe/ltbl-ignorance)
Thin documentation, no methodology. The control group.
 
## What Is Being Measured
 
Divergence between implementations over time. Where the three
twins make different choices given the same problem, and
whether those differences correlate with context quality.
 
## Stack
 
Rust, wgpu 27, WebGPU, winit 0.30, wasm-pack,
wasm32-unknown-unknown target.
