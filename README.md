# Explicit Derivation of Duality Between a Free Dirac Cone and QED3

This repository is the publication layer for the pedagogical monograph. It receives material only after the corresponding derivations have been developed and verified in the sibling `qed3-duality-workplace` repository.

## Current state

The repository is presently a book scaffold. The chapter directories and baseline table of contents are in place, but no workplace module has yet completed the migration gate.

Part 0, Chapters A–G, is being developed in the workplace to provide the mathematical and physical toolkit needed by the main argument. The baseline plan for Chapters 1–9 remains available in [`doc/TOC_1.0.0.md`](doc/TOC_1.0.0.md); it will be revised here when verified Part 0 material is ready to migrate.

## Repository layout

| Path | Purpose |
|---|---|
| `.agents/` | Book-synthesis instructions as they are added. |
| `doc/` | Versioned publication plans and tables of contents. |
| `src/ch01/` … `src/ch09/` | Destination directories for verified chapter narratives and calculation appendices. |
| `infra/` | Future book-class, preamble, bibliography, and build infrastructure. |
| `fig/` | Final publication figures. |

## Migration gate

Material enters this repository only after it has:

1. been derived in a module under `workplace/src/`;
2. used the reference digests in the sibling `references/` repository and audited any necessary source equations;
3. passed the applicable mathematical, symbolic, numerical, and LaTeX checks;
4. reached `VERIFIED` status in the workplace; and
5. been rewritten as a continuous pedagogical chapter rather than copied as research notes.

This separation keeps exploratory calculations and generated artifacts out of the publication history while preserving their evidence in the workplace repository.
