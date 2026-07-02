# Fable 5 vs Opus 4.8 — Physics Simulation Benchmark

A head-to-head comparison of two Claude models given an identical, frozen prompt:
build a self-contained HTML physics simulation (a rotating hexagon with 10 balls
bouncing inside it, with gravity, wall-motion-aware bounces, inter-ball momentum
transfer, and energy loss).

Both models received the **same prompt**, under the **same conditions**, with no
follow-up messages. This repo publishes the prompt, the run conditions, and each
model's deliverable untouched, so the comparison can be inspected and reproduced.

## Contents

| Path | What it is |
|------|------------|
| [`frozen-prompt.md`](frozen-prompt.md) | The exact prompt, v1.0, pasted verbatim into both sessions |
| [`run-conditions.md`](run-conditions.md) | Model versions, thinking mode, timestamps, environment — the controlled variables |
| `outputs/fable/` | Run A deliverable (claude-fable-5), committed untouched |
| `outputs/opus/` | Run B deliverable (claude-opus-4-8), committed untouched |

## Status

🚧 Scaffold published. Benchmark outputs land in `outputs/` after the runs complete.

## How to view a result

Each output is a single self-contained HTML file. Open it directly in any modern
browser — no build step, no dependencies.

## Method notes

- Identical frozen prompt, sent to both models within a target 30-second window.
- Extended thinking ON for both — how each model reasons is part of what's evaluated.
- No clarifying answers given; models made and stated their own assumptions.
- Outputs are committed exactly as produced. See `run-conditions.md` for the full protocol.
