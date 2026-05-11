# kov2025-radio-mentions

Analysis of how often the top-20 most-voted candidates from Estonia's 2025 KOV elections were mentioned on Vikerraadio.

Candidates are fetched from the official ```opendata.valimised.ee``` portal. Vikerraadio audio files were transcribed using faster-whisper on Kaggle (GPU T4 x2). Mentions are counted with fuzzy name matching to account for transcription errors.

## Output

| File | Contents |
|------|----------|
| `top20.csv` | Top-20 candidates by personal votes |
| `mentions.csv` | Mention count per candidate |
