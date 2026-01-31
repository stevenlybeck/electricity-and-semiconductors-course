# Claude Code Notes

## Python

Always use `uv` for Python interactions:
- `uv run python ...` to execute Python scripts
- `uv run jupyter lab` to launch Jupyter
- `uv run jupyter execute ...` to run notebooks
- `uv add <package>` to add dependencies
- `uv sync` to install/sync dependencies
- Never use bare `python`, `pip`, or `jupyter` commands

## Jupyter notebook validation

When verifying notebooks with `uv run jupyter execute`, judge success by **exit code**, not by log output. Stderr messages like `KeyboardInterrupt caught in kernel` or `ERROR |` lines are often benign — they come from normal kernel lifecycle events (e.g., widget cells in headless mode, kernel shutdown cleanup) and do not indicate notebook failure.

More generally: tools often emit warnings, deprecation notices, and log-level "ERROR" messages to stderr that are **informational, not failures**. Always check the actual exit code and/or structured output before concluding something is broken. A noisy stderr with exit code 0 is a success.

## Editing notebooks

Use the `NotebookEdit` tool (not `Edit`) to modify `.ipynb` files. `Edit` will refuse to operate on Jupyter notebooks. `NotebookEdit` works by cell ID — read the notebook first to find the target cell, then pass the cell ID and full replacement source to `NotebookEdit`.

## Generated artifacts

Notebooks should not write files into their own directories. Any `savefig()` or similar output should go into `_output/` (gitignored). A `matplotlibrc` in the repo root sets `savefig.directory: _output` to enforce this when Jupyter is launched from the repo root via `MATPLOTLIBRC=. uv run jupyter lab`.

Prefer `plt.show()` over `plt.savefig()` — notebook cell outputs already capture the figure. Only use `savefig` when you explicitly need a standalone file.
