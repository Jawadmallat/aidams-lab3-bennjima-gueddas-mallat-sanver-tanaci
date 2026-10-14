# aidams-lab3-bennjima-gueddas-mallat-sanver-tanaci

Lab 3 for research class AIDAMS: bottom-up steel emissions with uncertainty (`lab3.ipynb`).

## Data

The notebook uses the Global Energy Monitor *Global Iron and Steel Tracker* (GIST), **September 2026 (V1)** release.
The September 2025 release named in the lab text was not available to us, so numbers may differ slightly from that version.

The Excel files are not committed (see `.gitignore`). Download the release from
<https://globalenergymonitor.org/projects/global-iron-and-steel-tracker/> and put the plant-level file at:

```
data/Plant-level data - Global Iron and Steel Tracker - September 2026 (V1).xlsx
```

To use another location or file, set the `GIST_PATH` environment variable.

## How to run

Requires [uv](https://docs.astral.sh/uv/) (Python 3.13).

```bash
uv sync
# open lab3.ipynb in VS Code and select the .venv kernel, or: uv run --with jupyter jupyter lab lab3.ipynb
```

Then run **Kernel -> Restart & Run All**.
