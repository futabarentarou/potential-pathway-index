<p align="center">
  <img src="assets/bannerPotential_Pathway_Index.png" alt="Potential Pathway Index Banner" width="100%">
</p>

# # Potential Pathway Index

## Early Learning Friction Detection with Behavioral Data

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Processing-lightgrey)
![Scikit--Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange)
![Status](https://img.shields.io/badge/Status-Baseline%20Model%20Completed-green)

---

## Project Overview

**Potential Pathway Index** is a data science project focused on detecting early signs of learning friction and potential student misalignment using behavioral data from an online learning environment.

The project uses the **Open University Learning Analytics Dataset (OULAD)** to analyze whether early student behavior during the first 30 days of a course can help identify students who are at risk of withdrawal or failure.

The goal is not to label students permanently.

The goal is to explore whether early behavioral signals can support timely, responsible, and interpretable intervention.

---

## Core Question

> Can early learning behavior help identify students at risk of dropout, failure, or unresolved learning friction?

---

## Target Definition

The original dataset contains a final course outcome column called `final_result`.

For this project, a binary target was created:

| Final Result | Target |
|---|---|
| `Withdrawn` | `1` |
| `Fail` | `1` |
| `Pass` | `0` |
| `Distinction` | `0` |

The target variable is:

```text
at_risk_misalignment