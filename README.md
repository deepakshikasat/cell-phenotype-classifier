# Cell Phenotype Classifier

    Transfer-learning project scaffold for fluorescence cell phenotype classification.

    ## Dataset

    Public-data-ready structure for BBBC image datasets with synthetic manifest and demo metrics.

    ## Methods

    - Image manifest
- ResNet18 training scaffold
- Confusion matrix
- GradCAM interpretation placeholders

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

    Open `reports/analysis_report.html` for the full hypothesis, data provenance,
    process, outputs, and interpretation narrative.

    ## Portfolio Note

    This repository uses public or synthetic demonstration data only. It is
    intended to show reproducible computational biology and AI/ML workflow
    design without relying on confidential or employer-owned material.
