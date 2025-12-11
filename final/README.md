# Smart Incident Detection from IT Logs

This project implements an end-to-end anomaly detection pipeline for 
large-scale system logs using the BlueGene/L (BGL) dataset. The workflow 
includes data download, log parsing, template extraction, baseline anomaly 
detection, n-gram sequence modeling, and visual analysis. All results are 
reproducible through a single Jupyter notebook and a Sphinx-generated HTML 
report.

---

## 📁 Project Structure
project/
│
├── data/
│ ├── raw/ # BGL.zip and BGL.log (downloaded automatically at runtime)
│ └── processed/ # Parsed logs, templates, and intermediate CSVs
│
├── notebook/
│ └── project.ipynb # Main end-to-end notebook (runs with one click)
│
├── sphinx/
│ ├── source/ # Sphinx source (.rst) files and notebook symlink
│ ├── build/ # Generated HTML documentation
│ └── Makefile # Build script for Sphinx (make html)
│
└── README.md # This file

---

## 📝 Running the Jupyter Notebook

The full pipeline is implemented in: notebook/project.ipynb

To run everything:

1. Open the notebook.  
2. Select **Kernel → Restart & Run All**.  

---

## 📘 Building the Sphinx HTML Report

This project includes a full HTML report generated via Sphinx.

To build it:

```bash
cd sphinx 
make clean
make html
open build/html/index.html

