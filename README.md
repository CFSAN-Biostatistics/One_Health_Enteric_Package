# One Health Enteric Metadata Package

**Standardized, machine-readable metadata for genomic surveillance of enteric microbial organisms**

---

## Overview

The Genomics for Food Safety (GenFS) Metadata Workgroup is a cross-agency collaboration involving the U.S. Department of Agriculture (USDA), Centers for Disease Control and Prevention (CDC), National Center for Biotechnology Information (NCBI), and Food and Drug Administration (FDA).

The workgroup’s goal is to expand and standardize contextual metadata for enteric pathogen surveillance and research in the United States—transitioning from predominantly free-text data to structured, machine-readable formats that support interoperability and advanced analysis.

The **One Health Enteric Metadata Package** was developed by integrating and extending:
- [NCBI Pathogen Metadata Package](https://www.ncbi.nlm.nih.gov/biosample/docs/packages/#pathogen)  
- [MIxS Food Extensions](https://genomicsstandardsconsortium.github.io/mixs/)

This package is designed to comprehensively represent the full One Health sampling space for enteric microbes.

---

## What’s Included

The package consists of:

### Core Metadata
A set of attributes applicable across all sample types, capturing general sample and isolate information.

### One Health Sub-Packages  
(*Sub-packages are domain-specific groupings of attributes tailored to particular sample types.*)

Four domain-specific sub-packages covering major sampling contexts:
- **Human and animal hosts**  
- **Food samples**  
- **Food production and processing environments**  
- **Environmental sources** (e.g., water, air, natural environments)

### Standardization Features
- Controlled vocabularies and ontology-backed terms  
- Curated picklists for consistent data entry  
- Defined attribute requirements and guidance  
- Example use cases contributed by participating agencies  

---

## Why This Matters

This package enables high-quality, structured metadata collection to support:

- Pathogen surveillance relevant to Food Safety
- Integration of genomic and contextual data  
- Machine learning and advanced analytics    
- Investigations of:
  - Virulence and pathogenicity  
  - Environmental adaptation and stress tolerance  
  - Antimicrobial resistance  
  - Risk assessment  
  - Source attribution  

---

## Getting Started

- Download the latest full package or sub-packages from the **Releases** section of this repository.  
- Select the sub-package(s) appropriate for your sample type.  
- Use alongside submission workflows such as NCBI BioSample.

A generic submission template is also available via the NCBI BioSample Submission Portal:  
https://submit.ncbi.nlm.nih.gov/biosample/template/

---

## Package Structure

The metadata package is organized into:
- A **core attribute set** shared across all samples  
- Four **domain-specific sub-packages** aligned to One Health sample types  

Each sub-package includes:
- Attribute definitions  
- Guidance and examples  
- Requirement levels (e.g., required, recommended, optional)  

---

## Contributing and Feedback

Questions, suggestions, or proposed improvements can be submitted via the **Issues** page of this repository.

---

## Acknowledgments

This work is a collaborative effort across USDA, CDC, NCBI, and FDA, with contributions from multiple domain experts supporting One Health data standardization.
[![CC BY 4.0][cc-by-shield]][cc-by]

## Licencing
This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
