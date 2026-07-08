# Cell Phenotype Classifier

This repo is now explicitly framed as a **BBBC-ready transfer-learning scaffold**, not a completed image model. It includes a manifest, expected outputs, confusion-matrix format, and GradCAM reporting placeholders. A real upgrade would download BBBC021/BBBC038 images and train ResNet18 or a smaller CNN locally.

## Reproduce

```bash
python scripts/run_pipeline.py
```

## Outputs

- `data/image_manifest.csv`
- `outputs/model_metrics.csv`
- `outputs/confusion_matrix.csv`
- `figures/model_summary.svg`

## Analysis Report

Open `reports/analysis_report.html` for the hypothesis, public data provenance, process, outputs, and interpretation.

## Portfolio Note

This repository uses public data sources or clearly labelled synthetic demonstration data only. No employer-owned or confidential data are included.
