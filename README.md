# R2CASS 2025 Workshop: Interactive Reproducibility Demos

## Social Science Meets Web Data: Reproducible and Reusable Computational Approaches

This repository serves as the central hub for the interactive demonstrations presented at the "Interactive Replicability Session" of the R2CASS 2025 Workshop, held in conjunction with ICWSM 2025.

Our goal is to showcase how computational social science research, specifically the **analysis of politician claims from the LIAR dataset**, can be made **fully reproducible** and **easily shareable** using platforms like [MyBinder.org](https://mybinder.org/). We demonstrate that with proper code organization and environment configuration, anyone can launch and run this very same analysis in a pre-configured environment, directly from a web browser, **without any local setup headaches**, regardless of whether it's implemented in Python or R.

## Explore the Demos

Click on the badges below to launch the interactive environments directly in your browser. These demos will guide you through practical examples of reproducible data analysis for the LIAR dataset in both Python and R.

### 🐍 Python Demo: Politician Claims Analysis (LIAR Dataset)

This demonstration showcases an analysis of politician claims and their fact-checking truth ratings from the LIAR dataset using **Python**. It walks you through data loading, truth rating distribution, and visualizing claims by party affiliation.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/lorraine-dev/ICWSM-Reproducibility-Python-Demo/main)

**GitHub Repository:** [ICWSM-Reproducibility-Python-Demo](https://github.com/lorraine-dev/ICWSM-Reproducibility-Python-Demo/tree/main)

### 📊 R Demo: Politician Claims Analysis (LIAR Dataset)

This demonstration provides an example of the **same politician claims analysis from the LIAR dataset**, implemented in **R** and executed within an RStudio environment. It illustrates how to set up an R environment with necessary packages and run an R Markdown notebook directly in your browser, mirroring the Python analysis.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/lorraine-dev/ICWSM-Reproducibility-R-Demo/main)

**GitHub Repository:** [ICWSM-Reproducibility-R-Demo](https://github.com/lorraine-dev/ICWSM-Reproducibility-R-Demo)

---

### Why Binder?

* **Zero Setup:** No need to install software, libraries, or dependencies locally.
* **Interactive:** Users can run, modify, and explore your code live.
* **Reproducible:** Ensures consistent results across different environments.
* **Shareable:** A single URL is all it takes to share your executable research.

---

### Get Started With Your Own Project!

Want to make your own research reproducible with Binder? Check out our workshop slides (link coming soon!) or follow these quick steps:

1.  **Organize your code** in a clean GitHub repository (use relative paths!).
2.  **Define your environment** (e.g., `requirements.txt` for Python, `install.R` for R).
3.  **Push to GitHub** (make sure your repo is public!).
4.  Go to [mybinder.org](https://mybinder.org/), paste your repo URL, and launch!
5.  Copy the generated **Binder badge** to your `README.md`.
