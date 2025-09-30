# ChemistryShinyTools: An R Package for Chemistry-Focused Shiny Applications

[![build-status](https://github.com/sawsimeon/ChemistryShinyTools/actions/workflows/publish-proposal.yaml/badge.svg)](https://github.com/sawsimeon/ChemistryShinyTools/actions/workflows/publish-proposal.yaml)

## Overview
`ChemistryShinyTools` is an open-source R package designed to simplify the creation of R Shiny applications for chemistry and cheminformatics research. It provides modular, user-friendly tools for visualizing molecular data, integrating machine learning models, and ensuring reproducible workflows, targeting applications in drug discovery, QSAR modeling, and molecular analysis. This package proposal is submitted to the R Consortium’s Infrastructure Steering Committee (ISC) to advance the R ecosystem and support the chemistry research community.

Developed by Saw Simeon, a PhD with expertise in R Shiny development and cheminformatics (e.g., publications in *Nature Protocols* 2023 and *Journal of Cheminformatics* 2020), `ChemistryShinyTools` aligns with the [R Consortium’s mission](https://www.r-consortium.org) to:
- Promote R as the preferred language for statistical computing in chemistry.
- Support infrastructure by providing reusable Shiny modules and utilities.
- Increase user adoption through accessible documentation and tutorials.
- Foster collaboration by hosting the project on GitHub for open contributions.

## Proposal Goals
This project aims to:
1. **Simplify Shiny App Development**: Offer pre-built Shiny modules for visualizing chemical data (e.g., molecular structures, SMILES strings, QSAR descriptors), reducing development time for chemists.
2. **Enhance Reproducibility**: Provide templates and tools for reproducible workflows, integrating machine learning for tasks like virtual screening and activity prediction, inspired by the author’s work on kinase inhibition and drug discovery.
3. **Promote Collaboration**: Encourage contributions from the R and chemistry communities via GitHub, aligning with the R Consortium’s goal of equitable participation.
4. **Explore Innovative Features**: Optionally integrate Web3 technologies (e.g., IPFS for decentralized data storage) to enhance transparency in cheminformatics research, reflecting the author’s interest in Web3 since 2017.

## Key Features
- **Interactive Shiny Modules**: Build dashboards for molecular visualization (e.g., logP vs. molecular weight plots, dose-response curves).
- **Machine Learning Integration**: Simplified wrappers for training and visualizing QSAR models, ensuring reproducibility (e.g., based on *Journal of Cheminformatics* 2020).
- **Chemical Data Processing**: Tools for handling molecular data (e.g., rcdk for molecular fingerprints), leveraging the author’s experience with HPC clusters.
- **Reproducible Workflows**: Git integration and documentation templates for transparent research.
- **Web3 Exploration**: Experimental support for decentralized data storage to log molecular screening results.

## Target Audience
- Chemists and cheminformaticians seeking intuitive tools for data exploration.
- R users building Shiny apps for chemistry applications.
- Researchers in drug discovery, molecular modeling, and related fields.

## License

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons Licence" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">ISC Boilerplate</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/stephlocke" property="cc:attributionName" rel="cc:attributionURL">Stephanie Locke</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.<br />Based on a work at <a xmlns:dct="http://purl.org/dc/terms/" href="https://github.com/RConsortium/isc-proposal" rel="dct:source">https://github.com/RConsortium/isc-proposal</a>.
