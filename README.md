# MIREDA Partnership

![MIREDA Logo](./assets/mireda-logo.png)

## Mother and Infant Research Electronic Data Analysis (MIREDA)

The **MIREDA Partnership** is a UK-wide collaboration that harmonises electronic birth cohorts into a common data model to enable **federated, reproducible life-course research** across nations and Trusted Research Environments (TREs).

The partnership brings together major maternal and child health datasets from England, Wales, and Scotland, transforming them into the **OMOP Common Data Model (CDM)** to support consistent, cross-cohort analyses while data remain securely within their host environments.

Together, the harmonised cohorts represent over 18 million births, enabling research into rare exposures, policy impacts, and long-term health outcomes across the life course.

---

## About the Project

MIREDA is funded by the UK Medical Research Council and brings together five major electronic birth cohorts:

- Born in Wales  
- Born in Scotland  
- Born in Bradford  
- Born in South London (eLIXIR)  
- Clinical Practice Research Datalink (CPRD) birth cohorts  

Each cohort remains within its own secure TRE, but harmonisation into OMOP enables:

- Federated analysis without sharing raw data  
- Reproducible analytical pipelines  
- Cross-nation and international comparisons  
- Large-scale studies of rare exposures and outcomes  

---

## Purpose of This GitHub Organisation

This GitHub organisation provides open technical resources developed by the MIREDA partnership, including:

### 1. OMOP Mapping Resources
- Standardised mapping specifications
- Carrot Mapper JSON files
- Metadata and vocabulary mapping examples
- Cohort-specific and harmonised mappings

### 2. ETL and Transformation Code
- Scripts for data extraction, transformation, and loading
- Post-processing and quality-assurance scripts
- Helper tools for handling OMOP limitations

### 3. Analytical Methods
- Reproducible study pipelines
- Example federated analyses
- Cohort-comparable study definitions

### 4. Documentation and Methods
- Technical documentation
- Harmonisation decisions
- Data structure guidance
- Known issues and solutions

### 5. Troubleshooting and Common Issues
- OMOP pregnancy modelling approaches
- Mother–infant linkage solutions
- Vocabulary mapping challenges
- Practical solutions from real-world cohort harmonisation

---

## Accessing the Data

The harmonised MIREDA datasets are accessed through the **Health Data Research UK Gateway**:

https://healthdatagateway.org/en/collection/119

Data are not held centrally. Each cohort:

- Remains within its own Trusted Research Environment
- Is governed by local data controllers
- Requires separate access approval

Federated analysis enables the same code to run across all sites without moving sensitive data.

---

## Getting Started

1. Explore repositories for:
   - Mapping specifications
   - ETL pipelines
   - Analytical examples

2. Review documentation for:
   - OMOP structure in birth cohorts
   - Mother–infant linkage methods
   - Harmonisation decisions

3. Apply for data access through the HDR UK Gateway if you wish to run analyses.

---

## Citation

If you use MIREDA resources, please cite:

Seaborne et al.  
*UK electronic birth cohort data harmonisation using a common data model*  
(Final publication details to be added once available.)

---

## Funding

Funded by the **UK Medical Research Council (MRC)**  
Partnership Grant: **MR/X02055X/1**

Additional support from:

- Health Data Research UK
- NIHR Birmingham Biomedical Research Centre

---

## Contact

**MIREDA Partnership**  
Centre for Population Health  
Swansea University Medical School  

Project pages:  
https://gtr.ukri.org/projects?ref=MR%2FX02055X%2F1  
https://centreforpopulationhealth.org/projects/mireda/

---

## Licence

Unless otherwise stated, code in this organisation is released under an open-source licence.  
See individual repositories for licence details.
