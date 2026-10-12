# Build Verification

- Dataset verified: 50,000 rows, 2 columns (`review`, `sentiment`), 25,000 positive and 25,000 negative, no null values, 418 exact duplicate rows.
- Task 1 preprocessing was independently checked against the supplied dataset. After duplicate removal: 49,582 rows; mean cleaned length about 229.96 words; median 172; 95th percentile 587; chosen `MAXLEN` = 590.
- The notebook contains all seven required tasks and 110 cells (74 Markdown, 36 code).
- All notebook code cells pass Python AST syntax validation.
- HTML export was generated successfully.
- Full TensorFlow training was not executed in this build environment because TensorFlow is not installed and this environment cannot download packages from the internet. No model metrics were fabricated.
