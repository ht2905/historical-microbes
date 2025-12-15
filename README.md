# 🦠 Microbes as Agents of Change: Historical, Cultural, and Astrobiological Perspectives

This repository contains the **Quarto** source code and supporting files for an academic paper submitted for the **Microbiology (BT321IU)** course. The manuscript was prepared using the **Elsevier Quarto template** for journal-ready formatting, references, and figures.

> **PDF Preview:** A rendered PDF version of the manuscript is included in this repository for quick viewing without rendering the source files.

---

## 🎯 Project Overview

This paper explores the multifaceted role of **microorganisms** throughout history, culture, and science. Microbes are presented not just as pathogens but as active agents shaping societies, inspiring art, and influencing life beyond Earth.

* **Topic:** Microbes as Agents of Change
* **Course:** Microbiology (BT321IU)
* **Authors:** Tran Quoc Hoang, Nguyen Hoang Tuong Vy, Nguyen Vy Van, Nguyen Le Ngoc Vy, Nguyen Hoang Quynh Anh
* **Submission Date:** 12 December 2025

**Abstract Highlights:**

* Historical pandemics like the Black Death and smallpox
* Key microbiologists: Pasteur, Koch, Fleming
* Microbial influence in art, textiles, and pigment production
* Microbial survival in space and extremophilic adaptations

---

## 💻 Technical Environment

This project uses **Quarto** and **R (RStudio)** to dynamically generate the manuscript, including figures and tables. The **Elsevier Quarto template** ensures formatting meets journal requirements.

### Main Files

* **Manuscript Source:** `historical_microbes.qmd`
* **Bibliography:** `bibliography.bib`
* **Figures:** `/photos/` folder
* **LaTeX Header:** `preamble.tex`

### Development Environment

* **OS:** Windows 11 + WSL2 / Ubuntu 22.04 LTS
* **R Version:** ≥ 4.2
* **Key R Packages:** `knitr`, `rmarkdown`, `tinytex`, `ragg`, `yaml`

---

## ⚠️ Disclaimer

This README intentionally omits an explicit list of system-level packages and platform-specific build commands. Collaborators are expected to manage any required system dependencies appropriate to their environment. The project is reproducible at the R/Quarto level via `renv` and the steps below; however, rendering advanced outputs (e.g., PDF) can require additional system libraries or LaTeX, which are not documented here.

---

## 🛠 Installation Instructions

### 1️⃣ Install R Packages

Open R or RStudio, then install `renv` if not already present:

```r
install.packages("renv")
```

Restore the project environment to install all packages at their exact versions:

```r
renv::restore()
```

This will install all necessary packages, including `tinytex` for PDF rendering.

---

### 2️⃣ Install Quarto & Elsevier Template

1. Install **Quarto** from [https://quarto.org/docs/get-started/](https://quarto.org/docs/get-started/). Verify installation:

```bash
quarto check install
```

2. Install the **Elsevier Quarto template** (not included in this repo):

```bash
quarto add quarto-journals/elsevier
```

---

### 3️⃣ Render the Manuscript

Once all dependencies are installed, run:

```bash
quarto render historical_microbes.qmd
```

Outputs will be in PDF format, with figures, tables, and references automatically handled via the **Elsevier template**.

---

## 📚 Key Sections

1. **Introduction:** Microbes as foundational drivers of ecosystems and human history
2. **Microbes that Changed History:** Black Death, Smallpox, and social transformations
3. **Famous Microbiologists:** Pasteur, Fleming, Koch, and their discoveries
4. **Microbes in Art & Culture:** Bacterial art and fungal pigments in textiles
5. **Bacteria in Space:** Extremophiles, ISS experiments, and panspermia
6. **Conclusion:** Microbes as active agents shaping Earth and beyond

---

## 👥 Author Contributions

* **Tran Quoc Hoang:** Conceptualization, methodology, Sections 2 & 3, manuscript compilation
* **Nguyen Hoang Tuong Vy:** Section 5, Conclusion
* **Nguyen Vy Van:** Section 4, Introduction
* **Nguyen Le Ngoc Vy & Nguyen Hoang Quynh Anh:** Abstract co-authors, visualization, slides
* All authors contributed to reviewing and editing

---

## ⚖️ Declaration of Competing Interest

The authors declare no competing interests.

---

## 📂 Data & Code Availability

The full Quarto project (manuscript, figures, and bibliography) is available at:
[https://github.com/ht2905/historical-microbes](https://github.com/ht2905/historical-microbes)

> **PDF Preview:** A rendered PDF version of the manuscript is included in the repository for quick reference.