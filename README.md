# NextGenEE Practicum 2

This folder contains the student version of practicum 2: analyzing power flow
with realistic time series load data.

## Prerequisites

1. Install Python 3.13 or newer.
2. Install `uv`: <https://docs.astral.sh/uv/getting-started/installation/>
3. Open this folder in VS Code, PyCharm, or another editor that can run
   Jupyter notebooks.

## Setup

From this folder, install the Python environment:

```bash
uv sync
```

Then select the Python interpreter from `.venv` in your editor.

## Running the Practicum

Open and work through:

```text
practicum_2_time_series_calculation.ipynb
```

The notebook is a student exercise. Some code cells contain incomplete lines
marked with `TODO`, such as blank assignments. These are intentional; complete
them before running the later cells that depend on them.

The provided data files are under `data/`, and the plotting helper is under
`plot_utils/`.

## Expected Work

In this practicum, you will:

1. Load grid and time series load data.
2. Convert the load profile into PowerGridModel batch update data.
3. Run batched power flow calculations.
4. Plot node voltages and line loadings over time.
5. Visualize selected time steps on the grid graph.
