# Metformin MICOM Analysis for Prediabetic Patients

This repository contains the code and analysis supporting the paper:

**"How diet and metformin modulate the metabolic phenotype of gut-microbiota: a digital microbiota approach in prediabetic patients"**  
Juan José Oropeza-Valdez, Cristian Padron-Manrique, Jorge E. Arellano-Villavicencio, Aarón Vázquez-Jiménez, Laura E Hernández-Juárez, Xavier Soberon, María de Lourdes Reyes-Escogido, Rodolfo Guardado-Mendoza, Osbaldo Resendis-Antonio 

The repository includes two Jupyter notebooks that implement microbial community metabolic modeling using MICOM. The notebooks simulate the effects of metformin treatment and dietary interventions (Western, Mediterranean, and Milpa diets) on the gut microbiota of prediabetic patients.

---

## Table of Contents

- [Overview](#overview)
- [Installation](#installation)
- [References](#references)

---

## Overview

This project uses genome-scale community metabolic modeling (MICOM) to:

- **Simulate Metabolic Fluxes:** Assess the metabolic activity of the gut microbiota in prediabetic patients.
- **Time-Dependent Analysis:** Evaluate changes induced by metformin treatment at baseline, 6 months, and 12 months.
- **Dietary Impact:** Compare how different dietary patterns (Western, Mediterranean, and Milpa) affect microbial metabolic fluxes.
- **Knockout Analysis:** Explore bacterial knockout experiments to analyze microbial community dynamics.

The analysis is directly based on the methodologies described in the accompanying paper. Two primary notebooks are provided:

- **Metformin_micom.ipynb:** Contains the main analysis pipeline and metabolic flux simulations.
- **KOs metformin.ipynb:** Performs bacterial knockout analyses to explore cooperative and competitive interactions within the microbial community.

---

## Installation

We use MICOM for metabolic modeling from https://micom-dev.github.io/micom/ by Cristian Diener

pip install micom 

