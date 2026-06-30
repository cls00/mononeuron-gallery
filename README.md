# Gallery

Generated progression galleries: one folder per task, each holding the
performance record of a selected set of checkpoints plus the static poster and
animated recording of every run. The page lets you filter and sort the
specimens by metric and play a checkpoint's recording on hover or touch.

This folder holds **generated output** (per-task `index.html`, `data.json`,
`cards/`, `gifs/`) plus a top-level `index.html` linking the tasks. The
generator lives in `tools/gallery.py`; rerun it to rebuild from `runs/` and
`checkpoints/`.

Build: `.venv\Scripts\python.exe -m tools.gallery <task>`
