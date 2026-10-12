# Codiac K4 development

This is David Jordan's development fork of [Colin Patrick's KryptosBot](https://github.com/jcolinpatrick/kryptos). Upstream history, authorship and research records are preserved. This document describes planned work, not a K4 solution or validated capability.

## Starting point

Fork development started on 13 October 2026 from upstream commit b5dfbe54aa0c52782894ac876363774f7a894096. The upstream README describes the public release as open-source and a gift to the Kryptos community. No new licence is assigned to upstream material by this fork.

## First comparisons

- Independently check alphabet coordinates, permutation direction, inverse/composition and irregular-grid coverage before adopting route implementations.
- Reproduce Bean constraints only under their stated additive, positional and layer assumptions; do not apply those eliminations to arbitrary layered or Hill constructions.
- Use public synthetic challenges as exposed regression fixtures, separately from fresh blind controls and real K4 evidence.
- Retain scoring-resource identities, score units, raw results, model assumptions, search bounds and reconstruction checks. Codiac's pinned UCS nats model remains separate from proposal and crib scores.

## Development boundaries

Work takes place on the codiac/k4-development branch. Upstream main is preserved for comparison. Private Codiac application source, case evidence, credentials, signing keys and installed engine snapshots are not included in this public fork. External scripts and agent instructions are reviewed as source material before execution. Crib matches, replay and high scores are consistency checks; intended plaintext requires independent evidence.
