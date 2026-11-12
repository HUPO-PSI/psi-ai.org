---
title: "IMSC 2026 workshop: Is our proteomics data ready for AI?"
subtitle: "A recap of the PSI-AI workshop at IMSC 2026"
description: "Recap of the PSI-AI workshop at the 2026 International Mass Spectrometry Conference, with updates from the three PSI-AI tracks: standards and reproducible workflows, benchmarking, and responsible (re)use."
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

After the polls, an introduction to HUPO-PSI and the PSI-AI working group led into background on what AI is (and is not), how AI is applied in proteomics, and why PSI-AI was set up. The rest of the workshop gave an update on each of PSI-AI's three tracks, summarized below.

## Updates from the PSI-AI tracks

Each track was presented by one of the workshop's organizers.

### Standards and reproducible workflows

Ralf covered three ongoing standards efforts: mzPeak [@VanDenBossche2025], a scalable and interoperable format for raw mass spectrometry data; an AnnData-based [@Virshup2024] representation for proteomics quantification, adapted from the format the single-cell community built for annotated data matrices; and an updated Minimum Information About a Proteomics Experiment (MIAPE) guideline that accounts for AI-specific reporting needs.

### Benchmarking

Robbe introduced ProteoBench [@Devreese2025], the community-curated platform for comparing proteomics data analysis workflows, and its planned extension toward benchmarking predictive models rather than the current identification and quantification benchmarks. This extension is the subject of a project submitted to the [EuBIC-MS Hackathon 2027](https://github.com/EuBIC/EuBIC2027/discussions/10).

### Responsible (re)use

Magnus covered ongoing discussions in the responsible (re)use track. On research integrity, he discussed the potential misuse of generative AI to synthesize artificial mass spectrometry data and the implications for scientific integrity. Here, he mentioned recent work from PSI-AI members [@Neely2023; @Adams2026]. Magnus also discussed diversity among both researchers and research subjects in proteomics and the model biases that follow from it. Finally, on privacy, he discussed re-identifiability in mass-spectrometry-based proteomics data [@Li2016; @Boonen2019], an area where PSI-AI is still working out shared concepts and terminology. This track's [contribution to the EuBIC-MS Hackathon 2027](https://github.com/EuBIC/EuBIC2027/discussions/9) covers the provenance of raw mass spectrometry data.

## Get involved

More information on PSI-AI's standards, benchmarks, and guidelines is available at [psi-ai.org](https://psi-ai.org). If this work resonates, reach out at [info@psi-ai.org](mailto:info@psi-ai.org): PSI-AI welcomes new contributors to any of its three tracks.
