
# DataPrep AI Assistant (LangGraph-style)

## Overview
This repository contains a LangGraph-style AI agent that helps with basic data preprocessing tasks:
- CSV loading
- Data cleaning (missing detection & simple imputation)
- File conversion (CSV, JSON, Parquet)
- Quick insight generation (summary stats & basic plots)

## How to run
See the attached Colab notebook cells. Example dataset and outputs are included.

## Files
- Notebook: Colab cells (copy/paste)
- Assignment PDF (requirements): /mnt/data/Assignment 2_ASE.pdf

## Notes
- LLM used: google/flan-t5-small (lightweight HF model; free to use)
- Tools are implemented as Python classes in `src/tools` (or notebook cells).
