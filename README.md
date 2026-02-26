# Hi, I'm Vamsee Krishna A 👋

🧬 **Bioinformatics Engineer | Genomics Pipeline Developer | PRS/GWAS Workflow Builder**

M.Sc. in **Applied Bioinformatics (Cranfield University, UK)** with hands-on experience building reproducible NGS pipelines, integrating DNA/RNA-seq workflows, and translating genomic data into biologically interpretable outputs.

I work at the intersection of:
- **bioinformatics pipeline engineering** (Snakemake / HPC / automation)
- **variant + GWAS + PRS analysis**
- **data science / statistics for biological datasets**
- **web tools for scientific usability**

📍 Milton Keynes, England, UK

---

## 🔬 What I Build

I build analysis systems that are:
- **reproducible** → versioned configs, documented references, validated inputs
- **practical** → clear run commands, examples, runtime expectations, output manifests
- **biologically useful** → annotation, enrichment, disease-oriented interpretation, PRS context

### Areas I focus on
- DNA/RNA bioinformatics workflows
- Variant calling, filtering, and functional annotation
- GWAS summary interpretation and variant-to-gene mapping
- PRS scoring from genotype-bearing VCFs
- Bioinformatics automation on local/HPC environments
- Scientific data tools and analysis dashboards

---

## 🚩 Flagship Project (Pinned)

### [`PRS_GWAS_SNP_PIPELINE`](https://github.com/vamsee2k1/PRS_GWAS_SNP_PIPELINE)
A reproducible Snakemake pipeline for **variant interpretation, GWAS summary workflows, and PRS-ready analysis**.

### What it supports
- ✅ `variant_only` workflows from `VCF / VCF.GZ / CSV / TSV`
- ✅ GWAS summary interpretation (plots + downstream variant-centric interpretation)
- ✅ optional PRS scoring from genotype-bearing VCFs
- ✅ full-mode DNA/RNA branches (QC, alignment, calling, filtering, enrichment)
- ✅ reproducible execution docs, validation checks, and runtime observations

### Why people usually find it interesting
- It combines **pipeline engineering + biological interpretation**
- It documents **real runtimes** and **example outputs** (not just commands)
- It is explicit about **reference builds/resources** and reproducibility limits

### Recent observed runtimes (documented in repo)
- `variant_only + gwas_summary` → ~`22 sec`
- `variant_only + vcf_interpretation` → ~`8 min 58 sec`
- `full` DNA long-read test → ~`12 min 43 sec`
- `full` DNA short-read (GIAB HG002 practical-depth) → ~`37 min 10 sec` wall span

📎 Useful entry points:
- [Pipeline README](https://github.com/vamsee2k1/PRS_GWAS_SNP_PIPELINE)
- [Install / run on a new PC](https://github.com/vamsee2k1/PRS_GWAS_SNP_PIPELINE#install-and-run-on-a-new-pc-verified)
- [Input format docs](https://github.com/vamsee2k1/PRS_GWAS_SNP_PIPELINE/blob/main/docs/USER_INPUT_FORMATS.md)
- [Reproducible execution notes](https://github.com/vamsee2k1/PRS_GWAS_SNP_PIPELINE/blob/main/docs/REPRODUCIBLE_EXECUTION.md)
- [CITATION.cff](https://github.com/vamsee2k1/PRS_GWAS_SNP_PIPELINE/blob/main/CITATION.cff)

---

## 📊 Example Outputs (from the pipeline)

> I prefer showing real outputs and documented runs over generic portfolio claims.

<table>
  <tr>
    <td align="center"><b>QC Before/After (Full Mode)</b></td>
    <td align="center"><b>Variant Type Counts</b></td>
  </tr>
  <tr>
    <td><img src="https://raw.githubusercontent.com/vamsee2k1/PRS_GWAS_SNP_PIPELINE/main/docs/assets/readme/full/qc_before_after.png" width="420" alt="QC before after plot" /></td>
    <td><img src="https://raw.githubusercontent.com/vamsee2k1/PRS_GWAS_SNP_PIPELINE/main/docs/assets/readme/full/variant_type_counts.png" width="420" alt="Variant type counts plot" /></td>
  </tr>
  <tr>
    <td align="center"><b>Variant Enrichment (Full Mode)</b></td>
    <td align="center"><b>PRS Distribution (Variant-Only Example)</b></td>
  </tr>
  <tr>
    <td><img src="https://raw.githubusercontent.com/vamsee2k1/PRS_GWAS_SNP_PIPELINE/main/docs/assets/readme/full/variant_enrichment_dotplot.png" width="420" alt="Variant enrichment dotplot" /></td>
    <td><img src="https://raw.githubusercontent.com/vamsee2k1/PRS_GWAS_SNP_PIPELINE/main/docs/assets/readme/variant_only/prs_distribution.png" width="420" alt="PRS distribution plot" /></td>
  </tr>
</table>

---

## 🧠 Selected Experience Highlights

### 🧪 Unified NGS Pipeline Development — Cranfield University, UK
**Nov 2023 – Sep 2024**

- Consolidated **20+ independent DNA/RNA-seq workflows** into a single automated pipeline, reducing analysis time by **~50%**
- Built an end-to-end workflow from raw sequencing data to variant calling/annotation and PRS-oriented analysis
- Optimized NGS / variant-calling performance on **HPC** using **Bash, Python, R, Galaxy, snpEff, and SQL**

### 🌐 Full Stack Web Developer (Freelance), UK
**Oct 2024 – Present**

- Built and maintained interactive web applications for clients (including AI-driven experiences)
- Improved web performance / user experience outcomes for client projects (CV includes measured improvement metrics)
- This experience strongly influences how I design bioinformatics tools for usability, not just correctness

### 📈 Data Analyst Intern — South Central Railway Medical Dept, India
**May 2021 – Aug 2021**

- Improved healthcare data accuracy and operational efficiency through data-cleaning and epidemiological analytics
- Built **SQL + R** scripts for outbreak tracking and reporting workflows
- Applied statistics to real-world public health datasets

---

## 🧪 Projects (Beyond the Flagship Repo)

### 🎓 M.Sc. Thesis (Cranfield University)
**Unified NGS Pipeline for FUT3 SNP-based HMO Analysis**

- Developed an automated pipeline integrating DNA/RNA workflow components for SNP detection and downstream analysis
- Applied multivariate statistics / differential-expression-style methods (transferable to metabolomics contexts)
- Designed for real clinical-style datasets using **Python, Bash, R, Galaxy, SQL, HPC**

### 🍃 Group Project: TeaGen — RNA-seq Analysis Web Application
**Cranfield University**

- Led backend development for an **R Shiny** app enabling real-time RNA expression analysis, PCA, heatmaps, and interactive visualizations
- Focused on scientific usability and interpretable outputs
- **Awarded Best Group Project** for technical innovation and usability

### 🧬 Personal Project (Independent) — Completed
**PRS / GWAS / SNP Pipeline for Genomic Risk & Variant Interpretation**

- Built and published a reproducible Snakemake pipeline for variant-centric interpretation, GWAS summary workflows, and PRS-ready analysis
- Implemented `variant_only` workflows for `VCF / VCF.GZ / CSV / TSV` inputs with QC metrics, annotation, visualization, and enrichment outputs
- Added documented install/run steps, mode-specific runtime observations, example test inputs, and local resource requirements for reproducible use on other systems
- Designed a phase-2 web-platform architecture blueprint (API + worker + database) for future deployment without changing the core pipeline engine

---

## 🛠️ Technical Stack

### Bioinformatics / Genomics
- Snakemake
- `bcftools`, `samtools`, `mosdepth`, `snpEff`
- `bwa`, `bwa-mem2`, `minimap2`, `STAR` (workflow-dependent)
- GATK, BLAST
- Bioconductor
- HPC-based workflow execution

### Data / Statistics / Analysis
- Python
- R
- Bash
- SQL (PostgreSQL / MySQL)
- Multivariate statistics
- Pathway analysis
- GWAS/PRS-related data handling and QC

### Web / App Development
- JavaScript / TypeScript (project-dependent)
- R Shiny
- Full-stack web development experience (freelance)
- UI/UX awareness for scientific tools

### Cloud / Infra (working knowledge)
- AWS (exposure / learning path)
- Reproducible environment setup with Conda / Mamba

---

## 🏫 Education

### Cranfield University, UK
**M.Sc. in Applied Bioinformatics (Merit)**

Relevant training includes:
- NGS Informatics
- Pipeline Automation
- Machine Learning for Genomics
- Data Integration & Visualization
- HPC and Bash Scripting
- Advanced NGS
- Python / SQL / Statistics

### SRM Institute of Science & Technology, India
**B.Sc. in Biotechnology (First Class with Distinction)**

Foundation in:
- Molecular Biology
- Microbial Genomics
- Genetics
- Immunology
- Computational Biology
- Cancer Biology

---

## 🏅 Certifications / Recognition

- 🏆 **Best Group Project** — Cranfield University (TeaGen RNA-seq web app)
- Google — Crash Course on Python
- University of North Texas — Contemporary Biology
- NPTEL — Functional Genomics
- NPTEL — Molecular Genetics

---

## 🌍 Current Focus (What I’m Building Next)

- Expanding PRS workflows beyond Alzheimer disease to major complex diseases
  - CAD, T2D, hypertension, AF, asthma, CKD, schizophrenia, etc.
- Curating build-aware PRS/GWAS resource packs and disease presets
- Designing a future web + local-worker architecture for pipeline execution (without compromising reproducibility)

---

## 🤝 Collaboration Interests

I’m especially interested in collaborating on:
- reproducible genomics pipeline engineering
- variant interpretation / annotation workflows
- GWAS + PRS analysis pipelines (research use)
- scientific visualization and report generation
- bioinformatics tools that are usable by non-programmer scientists

---

## 📬 Connect

- GitHub: [@vamsee2k1](https://github.com/vamsee2k1)
- Email: [vamsee.akkaraju@gmail.com](mailto:vamsee.akkaraju@gmail.com)
- LinkedIn: [a-vamsee](https://www.linkedin.com/in/a-vamsee)

> I intentionally left out phone numbers from this public profile README for privacy.

---

<details>
<summary><b>⚙️ Quick run (from my flagship pipeline repo)</b></summary>

```bash
git clone https://github.com/vamsee2k1/PRS_GWAS_SNP_PIPELINE.git
cd PRS_GWAS_SNP_PIPELINE
conda env create -f envs/workflow.yaml
conda activate bioinfo-workflow
./run_pipeline.sh --use-conda --conda-frontend mamba --cores 1 --until preflight_resources
```

The repository README documents required local reference/resource downloads and exact run examples.
</details>

---

⭐ If you’re visiting from LinkedIn, start with **`PRS_GWAS_SNP_PIPELINE`** and the pinned repositories on my profile.
