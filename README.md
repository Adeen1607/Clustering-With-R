# Milk and Frozen Spending Clusters

Coursework R script and original Clustering Documentation.docx; Dataset.txt is absent.



## Rebuild the reading edition

```bash
python -m pip install -r requirements-research.txt
python scripts/build_research_site.py
```

This renders saved notebook outputs without rerunning model training or external APIs. To refresh findings, run the analysis commands above first, update `reports/research-findings.md`, and rebuild.

<!-- research-edition:start -->
## Research edition

[Research report and final visual results](research/report.md) · [Browser-ready notebook catalogue](research/notebooks.html)

The original report selected **four milk/frozen spending clusters** after inspecting k=3, 4 and 5. This is a documented interpretability choice. The source Dataset.txt is missing, so no refreshed inertia, silhouette score or customer counts are claimed.


The `research/` folder contains a professional static reading edition. The Pages workflow deploys it after GitHub Pages is enabled with **GitHub Actions** as the publishing source. Intended URL: `https://adeen1607.github.io/Clustering-With-R/`. Deployment status must be checked in Actions before treating that address as live.

<!-- research-edition:end -->
