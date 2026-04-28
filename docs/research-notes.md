# tmux for Aguvis: Multimodal Evaluation Protocol

## Purpose

This document records the research framing behind the static GitHub Pages site. The project studies how tmux can be adapted for Aguvis as a durable terminal substrate for agentic work.

## Research Question

What evaluation design captures the joint contribution of visual grounding and terminal-state memory for Aguvis?

## Working Thesis

Aguvis should be evaluated on multimodal coherence: visual pane boundaries, text events, and task-level intentions must agree over time.

## Design Claims

- Benchmark cases include split panes, noisy output, and task interruptions.
- Metrics compare visual-only, text-only, and fused observation modes.
- Human review focuses on interpretable trace evidence.

## Evaluation Lens

- Multimodal consistency
- Error localization in fused traces
- Task recovery after visual ambiguity


## Threats to Validity

- Terminal state can be over-instrumented, causing an adapter to measure artifacts of the harness rather than real agent behavior.
- A final successful artifact may hide poor recovery behavior, repeated command attempts, or fragile focus management.
- Agent-specific adapters can become difficult to compare unless trace schemas remain explicit and documented.

## Hero Image Prompt Summary

A 700x500 academic technical illustration for tmux adaptation research with Aguvis, emphasizing terminal panes, agent traces, reproducible evaluation, and a serious research discussion style. The generated image was copied into `docs/assets/hero.png` and normalized to 700x500 pixels.
