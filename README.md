# ETL Pipeline: MIMIC-IV to OMOP CDM

This repository implements an ETL pipeline to map MIMIC-IV data to the OMOP Common Data Model (CDM). The project focuses on processing and transforming 10 essential tables for seamless integration into OMOP CDM.

## Overview

- **Objective**: Extract, transform, and load healthcare data from MIMIC-IV into OMOP CDM.
- **Tables Processed**: 
  - Person
  - Visit Occurrence
  - Condition Occurrence
  - Procedure Occurrence
  - Drug Exposure
  - Observation Period
  - Death
  - Payer Plan Period
  - Provider
  - Specimen
- **Key Steps**:
  1. **Extract**: Retrieve data from MIMIC-IV PostgreSQL database.
  2. **Transform**: Map and standardize columns to OMOP CDM specifications.
  3. **Load**: Insert transformed data into OMOP CDM database.

## Tools Used

- **Database**: PostgreSQL (MIMIC-IV and OMOP CDM)
- **Languages**: Python (`pandas`, `sqlalchemy`, `pymysql`)
- **Notebook Platform**: Jupyter
