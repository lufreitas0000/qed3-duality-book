# Explicit Derivation of Duality Between a Free Dirac Cone and QED3

This repository is the publication layer for the pedagogical monograph. It receives material only after the corresponding derivations have been developed and verified in the sibling `qed3-duality-workplace` repository.

## Current state

The repository is presently a book scaffold. The chapter directories and baseline table of contents are in place, but no workplace module has yet completed the migration gate.

Part 0, Chapters A–G, is being developed in the workplace to provide the mathematical and physical toolkit needed by the main argument. The baseline plan for Chapters 1–9 remains available in [`doc/TOC_1.0.0.md`](doc/TOC_1.0.0.md); it will be revised here when verified Part 0 material is ready to migrate.

## Reference library

The project keeps reference material in two sibling locations:

- `../references-lightweight/` contains the version-controlled `ref_*.md` digests that agents should read first.
- `../reference-source/books/` contains the local full-book source PDFs kept outside Git.
- `../reference-source/_slices/` contains generated front matter, chapter PDFs, and focused section PDFs. Long-form Markdown transcriptions live in the sibling `../references-transcripts/` repository.

The workplace [Chapter Slices Index](https://github.com/lufreitas0000/qed3-duality-workplace/blob/dev/refs/CHAPTER_SLICES_INDEX.md) is the main catalog for the full-book library. It records each book's contents, printed and physical PDF page coordinates, source metadata, and the relative path of every generated chapter PDF. The catalog currently covers 28 source PDFs, 16 chapter-indexed works, and 202 chapter, appendix, supplement, or solution units. The detailed transcript/status audit is [`../references-transcripts/TRANSCRIPT_TOC_STATUS.md`](../references-transcripts/TRANSCRIPT_TOC_STATUS.md).

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
2. used the reference digests in the sibling `references-lightweight/` repository and audited any necessary source equations;
3. passed the applicable mathematical, symbolic, numerical, and LaTeX checks;
4. reached `VERIFIED` status in the workplace; and
5. been rewritten as a continuous pedagogical chapter rather than copied as research notes.

This separation keeps exploratory calculations and generated artifacts out of the publication history while preserving their evidence in the workplace repository.
