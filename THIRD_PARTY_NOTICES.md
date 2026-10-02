# Third-party notices and attribution

## Scope

This file covers third-party material in this package. `LICENSE` (MIT) covers
**the authors' original code only**. It does not grant, extend, or imply any
right to third-party data.

## Statistics and derived content

Statistics underlying this study originate from **NBA.com**.

The per-game evaluation tables and the forecasts in them are *derived research
artifacts*, not raw provider data. They are included here because they are the
minimum input needed to independently recompute the reported statistics. Their
inclusion is **attribution, not a licence**; the redistribution question is
recorded as unresolved in `RIGHTS.md`.

Nothing in this package should be read as a claim of permission to redistribute
NBA.com content or content derived from it.

## Upstream source data

Raw play-by-play, box scores, rotations and player-level provider tables are
**not** part of this package and are not redistributed here.

A broken placeholder submodule pointer previously existed at `source_data/`: an
empty gitlink whose remote pointed at a nonexistent placeholder repository, not
at any real data source. It has been **removed**. `source_data/README.md`
now documents what upstream categories were used privately, why they are not
bundled, and which reproduction level this package actually supports. There is no
submodule here.

## Methodological precedents

Ridge RAPM and out-of-sample testing precede this work (Sill, 2010). L-RAPM uses
weekly expanding-window prediction (Petridis and Pelechrinis, 2026). See
`PRIOR_WORK.md` for the closest-primary-work comparison and the permitted
novelty wording. These are cited precedents, not redistributed material.

## Not evaluated

Betting-market data and operational decision benefits were **not** evaluated.
No market-comparison implication is made or implied.

## Standing rights question

The redistribution status of the derived evaluation tables is unresolved. Either
obtain permission, or distribute only what a permitted derived-evaluation release
allows, with the reproduction limit stated. The NBA.com attribution above should
be preserved wherever the tables are redistributed.
