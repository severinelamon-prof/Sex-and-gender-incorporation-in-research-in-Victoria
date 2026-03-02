Sex and Gender Inclusion Benchmarking Pipeline (Victoria, 2020–2025)
Overview

This repository contains the informatics pipeline used to assess baseline incorporation of sex and gender as determinants of health across Victorian health and medical research funding schemes, research organisation policies, and university health curricula (2020–2025).

Victoria was selected as an analytical lens to inform national benchmarking ahead of anticipated mandatory inclusion requirements.

The workflow integrates:

Public data mining

Manual and automated term-based analysis

Context extraction

AI-assisted contextual validation

Targeted survey data integration

The pipeline was designed to be scalable and extensible to other jurisdictions.

Study Objectives

Establish a pre-2026 baseline of sex and gender inclusion in:

Health and medical research funding guidelines and summaries

Research organisation policy documents

University health curricula

Compare manual and automated analytical approaches for:

Accuracy

Efficiency

Scalability

Develop a reproducible computational framework suitable for national rollout.

Informatics Workflow

The curriculum mining component consists of four phases:

University-specific data extraction

Custom Python web scraper (Python v3.11)

Retrieval of course descriptors and unit guides

University-agnostic content analysis

Application of expert-informed sex and gender search terms

Context extraction

Identification of surrounding semantic content

AI-driven contextual validation

Classification of substantive vs superficial inclusion

API-assisted contextual interrogation

Manual searches (Microsoft Word and Excel) were conducted in parallel and integrated through an iterative feedforward optimisation loop.

Repository Structure
/pipeline
│
├── scraper.py                  # University-specific data extraction
├── term_analysis.py            # Term-based matching and frequency analysis
├── context_extraction.py       # Extraction of surrounding textual context
├── ai_validation.py            # AI-based contextual classification
├── requirements.txt            # Python dependencies
├── LICENSE                     # MIT License
└── README.md
Requirements

Python 3.11

See requirements.txt for package dependencies

To install dependencies:

pip install -r requirements.txt
Reproducibility and Transparency

This repository supports reproducible analysis consistent with open research standards.

All scripts used for data extraction and analysis are provided.

Survey instruments are reported in the Supporting Information of the manuscript.

Outputs were integrated with publicly available funding, policy, and curriculum documents.

Note: This repository does not host proprietary or restricted data.

Citation

If using this pipeline, please cite:

Author(s).
Baseline assessment of sex and gender inclusion across Victorian research funding, organisational policy, and university curricula (2020–2025).
[Journal name, year – if published]

You may also cite the repository directly:

Author(s). Sex and Gender Inclusion Benchmarking Pipeline (Version X.X). GitHub. Year.

License

This project is licensed under the MIT License.

You are free to use, modify, and distribute this code, provided appropriate attribution is given.

Contact

For questions regarding implementation or adaptation of this framework: severine.lamon@deakin.edu.au
