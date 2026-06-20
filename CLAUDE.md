# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Status

This repository is newly initialized and currently contains no application code — only
`README.md` (a title) and a `.gitignore`. There is no build, lint, test, or run tooling yet.
As real code lands, update this file with the actual commands and architecture.

## Project intent

`nat-gas-overview` — a natural gas overview project. The `.gitignore` is the standard GitHub
Python template and includes entries for **Streamlit**, **Marimo**, and **Jupyter**, indicating
the intended stack is Python, likely with a data/notebook or Streamlit-based UI component.

## Conventions for bootstrapping

- This is a Python project. When introducing dependencies and tooling, record the chosen
  package manager (uv / poetry / pip) and the build/lint/test/run commands here.
- Lock files (`uv.lock`, `poetry.lock`, `Pipfile.lock`) are currently NOT ignored by
  `.gitignore` and should be committed.
