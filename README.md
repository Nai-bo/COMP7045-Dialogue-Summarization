# Dialogue Summarization on SAMSum

COMP7045 Natural Language Processing & Large Language Model project.

This project investigates dialogue summarization on the SAMSum dataset using:
- Extractive baseline: TextRank
- Abstractive model: fine-tuned `facebook/bart-large-cnn`

## Results

| Model | ROUGE-1 | ROUGE-2 | ROUGE-L |
|---|---:|---:|---:|
| TextRank baseline | 28.72 | 7.94 | 22.20 |
| BART fine-tuned | 51.03 | 25.80 | 41.04 |

## Files
- `COMP7045_Mini_Project.ipynb` — dataset exploration, TextRank baseline, BART fine-tuning, ROUGE evaluation
- `COMP7045_report.pdf` — project report
- `COMP7045_presentation.pdf` — presentation slides

## Setup
```bash
pip install -r requirements.txt
