# 8 GHz SIW Slot Antenna — HFSS Models

Saved Ansys HFSS project files for a substrate integrated waveguide (SIW) slot-antenna design study targeting 8 GHz.

## Contents

The `models/` directory preserves the original filenames of seven saved project revisions:

| File | Description |
| --- | --- |
| `project1(finish2).aedt` | Candidate model to inspect first; saved with a solved-state flag. |
| `project1(finish).aedt` | Same saved geometry and solution settings as the candidate above, with different solution/display state. |
| `project1.aedt` | Earlier project revision. |
| `tryout.aedt` | Trial project revision. |
| `tryout1.aedt` | Trial project revision. |
| `tryout2.aedt` | Trial project revision. |
| `tryout3.aedt` | Trial project revision. |

These are saved model revisions; a verified final model has not yet been selected.

## Saved setup in the candidate model

- Project header: Ansys Electronics Desktop Student 2025 R2.
- Design: `HFSSDesign1`.
- Solution type: HFSS Terminal Network.
- Adaptive solution frequency: 8 GHz.
- Frequency sweep: 6–12 GHz, 121 points, Fast sweep.
- Port boundary: Wave Port.
- Maximum adaptive passes: 20.
- Maximum delta S: 0.02.

## Opening and solving

1. Open `models/project1(finish2).aedt` in a compatible version of Ansys Electronics Desktop / HFSS.
2. Inspect the geometry, materials, port, boundaries, and `Setup1` before solving.
3. Validate the model, then solve `Setup1` and its frequency sweep.
4. Regenerate the required S-parameter and radiation reports from the resulting solution.

The `.aedtresults` directories are not included. The saved solved-state flag does not mean cached solution data is included; a fresh solve may be required. This repository snapshot has not been re-solved or independently validated.

## Repository scope

This initial snapshot contains model files only, together with repository documentation. It excludes generated solver data, autosave files, presentation templates, and report drafts. Original model files are preserved without modification.
