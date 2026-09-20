# Design Concepts

The novel-concepts laboratory of the Historiotheque: one file per novel design concept.

## What a design concept is

A design concept is a novel concept for a novel — not a plot, not a character, but the
conceptual machinery a novel runs on: the systems it simulates, the philosophical engine
underneath it, the problem it was built to solve. Design concepts are where the novels
are designed before they are written.

## One file per concept

Each concept lives in `design-concepts/YYYY-MM-DD-slug.md` and carries a stable ID:
`DC-YYYY-NNN` (e.g. `DC-2026-001`). IDs never change; titles may.

## Versions are new files, not edits

A design concept is never rewritten in place. When a concept evolves, write a new dated
file and link it from the old one (`superseded_by:` in the frontmatter). The history of
a concept's thinking is part of the concept.

## The five sections

1. **The concept whole** — the concept in one grasp: what it is, in full.
2. **Systems and simulations** — the systems the novel simulates, and how.
3. **Philosophical machinery** — the philosophical engine underneath.
4. **Bottleneck note** — how the concept survives the 1D bottleneck of words: what is
   lost in linearization, and the strategy for losing as little as possible.
5. **Open questions** — what the concept hasn't solved yet.

## Relation to the rest of the operation

- Concepts are *designed* here, *written* in the novels repo, *atomized* as Refcards.
- A concept may cite Refcards (`RC-YYYY-NNNN`) and studio logs; novels cite concepts
  (`DC-YYYY-NNN`).
