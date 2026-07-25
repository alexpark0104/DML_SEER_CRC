# Causal Impact of Social Determinants on Colorectal Cancer Mortality
**Author:** Alex Park

## Project Overview
This repository contains the code for a population-based study utilizing the SEER (Surveillance, Epidemiology, and End Results) database. The goal of this project is to isolate and quantify the causal effects of socioeconomic barriers (such as income deprivation and rural isolation) on late-stage colorectal cancer mortality in early-onset cohorts.

## Methodology
Instead of standard correlational regression, this pipeline utilizes **Double Machine Learning (DML)** via the `dowhy` library. This allows for rigorous causal inference by controlling for biological confounders like tumor grade and patient demographics.

## Key Findings
* Generated an algorithmic triage tool simulation for hospitals to identify highly vulnerable patients based on isolated causal coefficients.
* Quantified the exact percentage shift in mortality risk per $1,000 drop in median income and per-step increase in rurality.

## Files
* `DML_SEER_CRC.ipynb` : The complete Python pipeline (Data cleaning, Feature Engineering, DML Causal Model, and Visualizations).
