# Analysis code for "A dataset-dependent falsifiability analysis of the Afshordi–Magueijo critical-geometry varying-speed-of-light cosmology"

This repository holds the project-written analysis scripts behind the paper's headline numerical results. Download `vsl-falsifiability-code.zip` (also attached to the v1.0 release) for the full bundle. The scripts reproduce:

- the Planck PR3 null test of the n_s = 0.96478 prediction (free fit n_s = 0.964777; fixing n_s = 0.96478 costs Δχ² = 0.001, ~0.03σ),
- the Planck PR3 + BK18 r null test (free r = 0.0105; fixing r = 0 costs Δχ² = 0.856, ~0.9σ),
- the ACT DR6 null tests (free n_s = 0.968018; fixing 0.96478 costs Δχ² = 3.63, ~1.9σ; the reheating variant 0.96838 costs Δχ² = 2.08, ~1.4σ),
- the (ε, F) knob-grid scan and inversion against published constraints,
- the SPHEREx flattened-bispectrum Fisher forecast and its independent tightening redo.

See the full README inside the zip for the per-script guide, dependencies, data sources (likelihood data are NOT bundled; fetch from the Planck Legacy Archive, bicepkeck.org, and the ACT DR6 likelihood repo), and reproduction notes.

**Caveat:** the ACT DR6 result is a likelihood reproduction, not the collaboration's own chains; see the paper's methods section.

## Suggested citation

Schaefer, J. R. (2026). Analysis code for "A dataset-dependent falsifiability analysis of the Afshordi–Magueijo critical-geometry varying-speed-of-light cosmology". GitHub. https://github.com/janet-pm/vsl-falsifiability-code
