# project-12-voice-of-workers
# Project 12 — Worker Voice in Cloudwork Platform Governance

This project analyzes the 2023 and 2025 Fairwork Cloudwork Ratings reports.
It examines documented appeal procedures, barriers described in worker
accounts, and public recognition of workers’ organizing rights.

## Files

- [Executed notebook](project-12-voice-of-workers.ipynb) — Python code and saved outputs.
- [Submission ZIP](project-12-voice-of-workers-submission.zip) — Executed notebook,
  results archive, and target journal file. The results archive contains the
  CSV data, figures, tables, source manifest, and evidence audit.

## How to reproduce the results

1. Open `project-12-voice-of-workers.ipynb` in Kaggle or Jupyter.
2. Enable internet access so the notebook can download the two Fairwork PDFs.
   For an offline run, supply the original PDFs and set `FAIRWORK_INPUT_DIR`
   to their folder. Use the dependencies listed in `provenance/requirements.txt`
   inside the results archive.
3. Run all cells. The notebook verifies the source PDFs and generates
   `project12_fairwork_results.zip`.

## Verification and scope

All 10 code cells were rerun successfully, and the 29-file results archive
passed its integrity check. The findings describe evidence documented in
the Fairwork reports. The manual coding has been source-audited, and
independent recoding is pending.

**Target journal:** Journal of Business Research
