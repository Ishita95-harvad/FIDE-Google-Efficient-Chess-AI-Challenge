# Efficient Chess AI Agents

This repository contains optimized chess agents for the FIDE & Google Efficient Chess AI Challenge on Kaggle. The goal is to build CPU-efficient chess bots under strict memory constraints.

## Files

- `agent.py`: Main Alpha-Beta pruning agent.
- `submission.py`: Wrapper required by the Kaggle competition.
- `zip_submission.sh`: Compresses the submission below 64KiB.
- `evaluate.py`: Test agent locally using FENs.

## How to Submit

1. Ensure `agent.py` and `submission.py` are under 64KiB zipped.
2. Run:
```bash
bash zip_submission.sh
