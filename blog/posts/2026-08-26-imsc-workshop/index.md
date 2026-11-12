---
title: "IMSC 2026 workshop: Is our proteomics data ready for AI?"
subtitle: "A recap of the PSI-AI workshop at IMSC 2026"
description: "Recap of the PSI-AI workshop at the 2026 International Mass Spectrometry Conference, covering what AI is, why it matters for proteomics, and the three PSI-AI tracks: standards, benchmarking, and responsible reuse."
author:
- name: Ralf Gabriels
  orcid: 0000-0002-1679-1711
  affiliations:
    - VIB-UGent Center for Medical Biotechnology, VIB, Belgium
    - Department of Biomolecular Medicine, Ghent University, Belgium
- name: Magnus Palmblad
  orcid: 0000-0002-5865-8994
  affiliations:
    - Leiden University Medical Center, Netherlands
- name: Robbe Devreese
  orcid: 0000-0002-3432-1502
  affiliations:
    - VIB-UGent Center for Medical Biotechnology, VIB, Belgium
    - Department of Biomolecular Medicine, Ghent University, Belgium
date: "2026-08-26"
categories: [community, workshop]
image: "featured.jpg"
draft: false
bibliography: references.bib
citation: true

---

## Introduction

At the 2026 International Mass Spectrometry Conference (IMSC) in Lyon (France), Ralf Gabriels (VIB-UGent), Magnus Palmblad (LUMC), and Robbe Devreese (VIB-UGent) ran a workshop titled *"Is our proteomics data ready for AI? A PSI-AI workshop"*, on behalf of the HUPO-PSI [@Deutsch2023] AI-readiness Working Group (PSI-AI). About 60 participants attended.

A digital poll opened the session by asking what participants expected to get out of it: 87% came to learn, 11% to discuss, and 2% to contribute. Given this near-unanimous appetite for learning, we pivoted the workshop toward education rather than open discussion. A second poll mapped the group's experience with AI in proteomics: 42% reported close to no experience, 23% used proteomics software that embeds AI models without building or training them, 25% had applied existing AI models to their own data, 6% had trained their own models, and 4% worked mainly on developing AI models for proteomics. The audience therefore consisted mostly of newcomers and consumers of existing models, with very few producers. About 20% of participants were already familiar with HUPO-PSI, which made the workshop a useful outreach opportunity for the initiative as a whole.

The following sections of this blog post cover the topics that were discussed during the workshop.

## What AI is, and what it is not

The terms AI, ML, DL, and generative AI (or genAI) are often used interchangeably, but they describe nested scopes. Artificial intelligence (AI) is the broadest category: any computational method that performs tasks normally associated with human intelligence. Machine learning (ML) is the subset of AI where a model learns patterns from data rather than following hand-coded rules. Deep learning (DL) is the subset of ML built on multi-layer neural networks. Generative AI (genAI), including large language models (LLMs) and image generators, is a further subset of DL that produces new content rather than a prediction or a label. In proteomics, AI is not only genAI: most established applications, such as retention time or fragmentation prediction, rely on earlier ML and DL approaches rather than generative models.

## AI in proteomics

> AI in proteomics broadly splits into two categories: Analytical AI and biological AI

AI excels at recognizing patterns, much like humans, but with the speed and reproducibility of a computer. This capability translates directly into pattern recognition at scale: mining large volumes of proteomics data for biological insight that would be impractical to extract manually, moving from data and information toward knowledge. The current moment favors this shift more than any before it, since large volumes of public proteomics data are now available and compute has become considerably cheaper, the same two conditions that have driven AI adoption across science in general.

Applications in proteomics broadly split into two categories. Analytical applications predict how peptides behave in the mass spectrometer, for example retention time or fragmentation. Biological applications extract meaning from the resulting measurements, for example biomarker predictors, tissue classification from protein quantification, and proteome foundation models.

## Why PSI-AI?

> PSI-AI's mission is to get the most out of AI for proteomics, responsibly and effectively

Ideally, most effort in an AI project goes into building the model itself. In practice, a large share of that effort goes into finding suitable training data, filtering it, downloading it, and parsing it with custom, often slow, parsers. PSI-AI exists to close that gap through standardized file formats, community-curated resources, and shared conventions for data sharing, while also ensuring that AI models already in use are used optimally. In short: get the most out of AI for proteomics, responsibly and effectively. PSI-AI pursues two goals: making public proteomics data suitable for AI applications, and supporting and standardizing the use of AI in workflows that generate new data. These goals are organized into three tracks: standards and reproducible workflows, benchmarking, and responsible (re)use.

Each track was covered by one of the workshop's organizers.

### Standards and reproducible workflows

Ralf covered three ongoing standards efforts: mzPeak [@VanDenBossche2025], a scalable and interoperable format for raw mass spectrometry data; an AnnData-based [@Virshup2024] representation for proteomics quantification, adapted from the format the single-cell community built for annotated data matrices; and an updated Minimum Information About a Proteomics Experiment (MIAPE) guideline that accounts for AI-specific reporting needs.

### Benchmarking

Robbe introduced ProteoBench [@Devreese2025], the community-curated platform for comparing proteomics data analysis workflows, and its planned extension toward benchmarking predictive models rather than the current identification and quantification benchmarks. This extension is the subject of a project submitted to the [EuBIC-MS Hackathon 2027](https://github.com/EuBIC/EuBIC2027/discussions/10).

### Responsible (re)use

Magnus covered ongoing discussions in the responsible (re)use track. On research integrity, he discussed the potential misuse of generative AI to synthesize artificial mass spectrometry data and the implications for scientific integrity. Here, he mentioned recent work from PSI-AI members [@Neely2023; @Adams2026]. Magnus also discussed diversity among both researchers and research subjects in proteomics and the model biases that follow from it. Finally, on privacy, he discussed re-identifiability in mass-spectrometry-based proteomics data [@Li2016; @Boonen2019], an area where PSI-AI is still working out shared concepts and terminology. This track's [contribution to the EuBIC-MS Hackathon 2027](https://github.com/EuBIC/EuBIC2027/discussions/9) covers the provenance of raw mass spectrometry data.

## Get involved

More information on PSI-AI's standards, benchmarks, and guidelines is available at [psi-ai.org](https://psi-ai.org). If this work resonates, reach out at [info@psi-ai.org](mailto:info@psi-ai.org): PSI-AI welcomes new contributors to any of its three tracks.
