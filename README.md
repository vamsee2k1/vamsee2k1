# Hi, I'm Vamsee Krishna A

Bioinformatics Engineer | Genomics Pipeline Developer | PRS/GWAS Workflow Builder

M.Sc. in Applied Bioinformatics (Cranfield University, UK) with hands-on experience building reproducible NGS pipelines, integrating DNA/RNA-seq workflows, and translating genomic data into biologically interpretable outputs.

I work at the intersection of:
- bioinformatics pipeline engineering (Snakemake / HPC / automation)
- variant + GWAS + PRS analysis
- data science and statistics for biological datasets
- web tools for scientific usability

Location: Milton Keynes, England, UK

---

## What I Build

I build analysis systems that are:
- reproducible: versioned configs, documented references, validated inputs
- practical: clear run commands, examples, runtime expectations, output manifests
- biologically useful: annotation, enrichment, disease-oriented interpretation, PRS context

### Areas I focus on
- DNA/RNA bioinformatics workflows
- Variant calling, filtering, and functional annotation
- GWAS summary interpretation and variant-to-gene mapping
- PRS scoring from genotype-bearing VCFs
- Bioinformatics automation on local/HPC environments
- Scientific data tools and analysis dashboards

---

## Flagship Project (Pinned)

### [`PRS_GWAS_SNP_PIPELINE`](https://github.com/vamsee2k1/PRS_GWAS_SNP_PIPELINE)
A reproducible Snakemake pipeline for variant interpretation, GWAS summary workflows, and PRS-ready analysis.

### Project Status
- AI integration is implemented (QC anomaly detection, variant prioritization, explainability reports).
- Pipeline is production-usable for current supported modes and test datasets.
- Development is active and ongoing for robustness, usability, and expanded disease/resource coverage.
- Current workflows are reproducible and publication-ready for documented runs.

### What it supports
- `variant_only` workflows from `VCF / VCF.GZ / CSV / TSV`
- GWAS summary interpretation (plots + downstream variant-centric interpretation)
- Optional PRS scoring from genotype-bearing VCFs
- Full-mode DNA/RNA branches (QC, alignment, calling, filtering, enrichment)
- Reproducible execution docs, validation checks, and runtime observations

### Why people find it useful
- Combines pipeline engineering + biological interpretation
- Documents real runs and examples
- Explicit about reference builds, resources, and reproducibility limits

### Useful entry points
- [Pipeline README](https://github.com/vamsee2k1/PRS_GWAS_SNP_PIPELINE)
- [Input format docs](https://github.com/vamsee2k1/PRS_GWAS_SNP_PIPELINE/blob/main/docs/USER_INPUT_FORMATS.md)
- [AI integration docs](https://github.com/vamsee2k1/PRS_GWAS_SNP_PIPELINE/blob/main/docs/AI_INTEGRATION.md)
- [Reproducible execution notes](https://github.com/vamsee2k1/PRS_GWAS_SNP_PIPELINE/blob/main/docs/REPRODUCIBLE_EXECUTION.md)
- [CITATION.cff](https://github.com/vamsee2k1/PRS_GWAS_SNP_PIPELINE/blob/main/CITATION.cff)

---

## Example Outputs (from the pipeline)

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

## Selected Experience Highlights

### Unified NGS Pipeline Development — Cranfield University, UK
Nov 2023 – Sep 2024

- Consolidated 20+ independent DNA/RNA-seq workflows into a single automated pipeline, reducing analysis time by ~50%
- Built end-to-end workflow from raw sequencing data to variant calling/annotation and PRS-oriented analysis
- Optimized NGS and variant-calling performance on HPC using Bash, Python, R, Galaxy, snpEff, and SQL

### Full Stack Web Developer (Freelance), UK
Oct 2024 – Present

- Built and maintained interactive web applications for clients (including AI-driven experiences)
- Improved web performance and usability outcomes for client projects
- Applied usability-first thinking to scientific tools

### Data Analyst Intern — South Central Railway Medical Dept, India
May 2021 – Aug 2021

- Improved healthcare data accuracy and operational efficiency through data cleaning and epidemiological analytics
- Built SQL + R scripts for outbreak tracking and reporting workflows
- Applied statistics to real-world public health datasets

---

## Projects (Beyond the Flagship Repo)

### M.Sc. Thesis (Cranfield University)
Unified NGS Pipeline for FUT3 SNP-based HMO Analysis

- Developed an automated pipeline integrating DNA/RNA workflow components for SNP detection and downstream analysis
- Applied multivariate statistics and differential-expression-style methods
- Designed for real clinical-style datasets using Python, Bash, R, Galaxy, SQL, and HPC

### Group Project: TeaGen — RNA-seq Analysis Web Application
Cranfield University

- Led backend development for an R Shiny app enabling real-time RNA expression analysis, PCA, heatmaps, and interactive visualizations
- Focused on scientific usability and interpretable outputs
- Awarded Best Group Project for technical innovation and usability

### Personal Project (Independent) — Active and Ongoing
PRS / GWAS / SNP Pipeline for Genomic Risk and Variant Interpretation

- Built and published a reproducible Snakemake pipeline for variant-centric interpretation, GWAS summary workflows, and PRS-ready analysis
- Implemented `variant_only` workflows for `VCF / VCF.GZ / CSV / TSV` inputs with QC metrics, annotation, visualization, and enrichment outputs
- Added AI-assisted modules for QC anomaly detection, variant prioritization, and explainability reports
- Continuously improving roadmap toward web-platform execution architecture and broader disease presets

---

## Technical Stack

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
- Full-stack web development experience
- UI/UX awareness for scientific tools

### Cloud / Infra (working knowledge)
- AWS (learning and implementation exposure)
- Reproducible environments with Conda / Mamba

---

## Education

### Cranfield University, UK
M.Sc. in Applied Bioinformatics (Merit)

Relevant training includes:
- NGS Informatics
- Pipeline Automation
- Machine Learning for Genomics
- Data Integration and Visualization
- HPC and Bash Scripting
- Advanced NGS
- Python / SQL / Statistics

### SRM Institute of Science & Technology, India
B.Sc. in Biotechnology (First Class with Distinction)

Foundation in:
- Molecular Biology
- Microbial Genomics
- Genetics
- Immunology
- Computational Biology
- Cancer Biology

---

## Certifications and Recognition

- Best Group Project — Cranfield University (TeaGen RNA-seq web app)
- Google — Crash Course on Python
- University of North Texas — Contemporary Biology
- NPTEL — Functional Genomics
- NPTEL — Molecular Genetics

---

## Current Focus

- Expanding PRS workflows beyond Alzheimer disease to additional complex diseases
- Curating build-aware PRS/GWAS resource packs and disease presets
- Improving robustness and usability of reproducible genomics workflows
- Building toward future web and local-worker execution architecture

---

## Collaboration Interests

I am especially interested in collaborating on:
- reproducible genomics pipeline engineering
- variant interpretation and annotation workflows
- GWAS + PRS analysis pipelines (research use)
- scientific visualization and report generation
- bioinformatics tools usable by non-programmer scientists

---

## Connect

- GitHub: [@vamsee2k1](https://github.com/vamsee2k1)
- Email: [vamsee.akkaraju@gmail.com](mailto:vamsee.akkaraju@gmail.com)
- LinkedIn: [a-vamsee](https://www.linkedin.com/in/a-vamsee)

---

<details>
<summary><b>Quick Run (Flagship Pipeline)</b></summary>

```bash
git clone https://github.com/vamsee2k1/PRS_GWAS_SNP_PIPELINE.git
cd PRS_GWAS_SNP_PIPELINE
conda env create -f envs/workflow.yaml
conda activate bioinfo-workflow
./run_pipeline.sh --use-conda --cores 4 --configfile config/test_data/test_niagads_advp_ad_gwas_hg38.yaml
