# Tarot-Transformer

A deterministic, symbol-weighted tarot interpretation engine inspired by transformer attention.

This project treats tarot as a structured symbolic language composed of interacting entities (numbers, elements, suits, planets, archetypes, and positional context). The engine is designed to analyze tarot spreads using symbolic weighting, narrative collapse logic, and multi-mode tarot-based numerology without relying on probabilistic language models or hallucination-prone output.

# Purpose

Most tarot applications rely on random card generation, keyword lookups, static text, or LLM-based readings that introduce misattribution and contextual drift.
This project aims to create a transparent, explainable, and consistent interpretation engine using:

## defined symbolic modules

- deterministic reading logic

- narrative synthesis inspired by attention mechanisms

- tarot-specific multi-mode numerology

# Core Concepts
- Tarot-Based Numerology

- Each number (0–10) is defined through:

- essence

- tarot-specific modes

- shadow expressions

- narrative function

- embodied experiential states

- collapse behavior (math-informed, context-decided)

- guided questions

- JSON specification

## Symbol Modules

- numbers

- elements

- suits

- courts

- major arcana archetypes

- planets / correspondences

- positional spread meanings

### Each module includes:

- a specification document (/spec)

- a machine-readable JSON file (/data)

## Pattern Recognition

The engine evaluates:

- number clustering and repetition

- elemental and suit distribution

- archetypal reinforcement

- planetary correspondences

- major/minor arcana dynamics

- narrative tension

- collapse events (e.g., multiple 1s → 2-energy depending on context)

## Deterministic Narrative Synthesis

The system constructs a reading using:

- weighted symbol interactions

- narrative arcs across spread positions

- dominant vs secondary themes

- collapse logic

- interpretive constraints

Optional: stylistic formatting from an LLM without allowing hallucinated content.

## Status

Work in progress.

Current focus:

- numerology specification
- symbolic schema design

Planned work:

- complete numerology set
- define elements, suits, planets
- implement deterministic reading engine
- prepare examples and tests

## License

MIT License. See `LICENSE` for details.
