
# Lung Cancer Multimodal Scraper

Automated pipeline for collecting and screening multimodal deep learning research from **PubMed** and **DBLP**.

## Quick Start
1. **Setup:** `pip install pandas openpyxl`
2. **Run:** `python scrape.py`

## Features
* **Strict Filtering:** Targets Lung Cancer + AI + Fusion terms.
* **Auto-Scoring:** Prioritizes papers based on modality variety (CT, PET, Omics, etc.).
* **Output:** Saves results to `data/` in CSV and Excel formats.
