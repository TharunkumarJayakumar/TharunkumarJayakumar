<div align="center">

<img src="assets/profile-banner.svg" alt="Blue DNA double helix banner" width="100%">

# Tharun Kumar J

**Computational Biology · Bioinformatics Pipelines · Long-read Genomics**

[![profile views](https://komarev.com/ghpvc/?username=TharunkumarJayakumar&label=profile%20views&color=1d4ed8&style=flat-square)](https://github.com/TharunkumarJayakumar)
[![GitHub stats](https://github-readme-stats.vercel.app/api?username=TharunkumarJayakumar&show_icons=true&title_color=1d4ed8&icon_color=0891b2&text_color=0f2540&bg_color=f2f7fd&border_color=c9dcf5&hide_border=false&include_all_commits=true)](https://github.com/TharunkumarJayakumar)
[![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=TharunkumarJayakumar&layout=compact&title_color=1d4ed8&text_color=0f2540&bg_color=f2f7fd&border_color=c9dcf5)](https://github.com/TharunkumarJayakumar)

📍 Hosur, Tamil Nadu, India · ✉️ [tharunjayy@gmail.com](mailto:tharunjayy@gmail.com) · [LinkedIn](https://www.linkedin.com/in/tharunjay)

</div>

---

## 👋 What I do

M.Tech Biotechnology graduate building **reproducible, containerised NGS workflows** and asking careful questions of biological data. My work spans long-read variant calling, repeat-expansion genotyping, TB AMR detection, single-cell marker audits and applied machine learning.

I care about the part many pipelines skip: **can someone else rerun this, and do the numbers actually mean what we claim?**

> *"Life, uh, finds a base."* — from my browser tool, [Genome Analytics](#-repositories)

---

## 🧬 Featured result — one marker, two failure modes

A zero count for a cell-surface marker can be technical dropout **or** a real biological state. I audited CD20 (MS4A1) in 700 single immune cells and showed that the CD20-zero B cells are mostly **CD20-low plasmablasts**, not merely dropped-out reads.

<table>
  <tr>
    <td width="50%" align="center"><b>The evidence</b><br><img src="https://raw.githubusercontent.com/TharunkumarJayakumar/computational-immunology/main/figures/03_cd20_dropout.png" alt="CD20 dropout audit figure" width="100%"></td>
    <td width="50%" align="center"><b>The atlas</b><br><img src="https://raw.githubusercontent.com/TharunkumarJayakumar/computational-immunology/main/figures/01_atlas_umap.png" alt="UMAP of the 700-cell atlas" width="100%"></td>
  </tr>
</table>

[Read the full analysis →](https://github.com/TharunkumarJayakumar/computational-immunology) · [Executed notebook](https://github.com/TharunkumarJayakumar/computational-immunology/blob/main/notebooks/cd20_analysis.ipynb)

*34 of 95 B cells read zero for MS4A1. They keep CD79A (33/34), have higher UMI counts (4210 vs 3482), and are enriched for the plasmablast marker MZB1 (30/34 vs 21/61).*

---

## 📦 Repositories

| Project | What it is |
|---|---|
| [computational-immunology](https://github.com/TharunkumarJayakumar/computational-immunology) | Single-cell CD20 marker audit. Pinned environment, dataset SHA-256, 5 tests, executed notebook and CI. |
| [vcf-annotate-smk](https://github.com/TharunkumarJayakumar/vcf-annotate-smk) | Snakemake GRCh38 VCF filtering and Ensembl VEP annotation with per-rule Conda envs and CI. |
| [My_resume](https://github.com/TharunkumarJayakumar/My_resume) | Portfolio site — light-blue, evidence-led, with embedded figures and a tiny theme toggle. [Live site ↗](https://tharunkumarjayakumar.github.io/My_resume/) |

---

## 🛠 Toolkit

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![Nextflow](https://img.shields.io/badge/Nextflow-0B7D95?style=for-the-badge)
![Snakemake](https://img.shields.io/badge/Snakemake-0E7C86?style=for-the-badge)
![Scanpy](https://img.shields.io/badge/Scanpy-7C3AED?style=for-the-badge)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Conda](https://img.shields.io/badge/Conda-342B2E?style=for-the-badge)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

## 🔭 Currently

- Extending the annotation workflow into an end-to-end **FASTQ → filtered VCF** germline pipeline
- Building a **bulk RNA-seq differential expression** project on public GEO data
- Publishing **Genome Analytics**, a browser tool for FASTQ stats, BAM conversion and VCF inspection

<div align="center">

[⬆ Back to top](#-what-i-do)

</div>
