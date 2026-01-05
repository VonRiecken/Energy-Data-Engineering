This repository contains the data analysis and predictive modeling project for the EDE 2025-2026 semester. The primary objective is to apply independent data organization and statistical methods to develop a robust linear regression model.

🎯 **Project Goals**
The project is divided into two core analytical phases, focused on moving from raw data to a balanced, high-performing predictive model:
Part 1: Exploratory Data Analysis (EDA)
Statistical Exploration: Quantitative analysis of dataset distributions and properties.
Visual Insights: Focused graphical representations to identify patterns essential for modeling.
Correlation Analysis: Investigating the relationships between independent variables and the target variable.
Part 2: Model Training & Evaluation
Iterative Development: Training at least five different regression models ranging from single-feature to complex multi-feature architectures.
Feature Engineering: Systematic selection and creation of features to optimize the bias-variance trade-off.
Validation: Implementation of k-fold cross-validation to ensure model generalization and prevent overfitting.
Final Selection: Comparative visualization and selection of the best-performing model based on goodness-of-fit metrics.

📦 **Deliverables**
The project is submitted as a comprehensive Jupyter Notebook containing:
Functional Code: Reproducible analysis that runs out-of-the-box.
Markdown Documentation: Integrated explanations of methods and results.
HTML Export: A static version of the notebook for accessibility.
Source Files: Any modified data files necessary for the notebook to run.

📊 **Presentation Requirements**
The project is presented directly from the Jupyter Notebook (no external slides).
Duration: Maximum 15 minutes.
Focus: Results, methodology, and high-level highlights.
Team Participation: Equal contribution to the presentation by all members.

📑 **Documentation & Transparency**
The notebook includes a mandatory appendix detailing:
Student Contributions
Student
Responsibilities & Tasks
Contribution (%)
Student 1
e.g., EDA, Feature Engineering
XX%
Student 2
e.g., Model Selection, Validation
XX%

**Sources & AI Disclosure**
External Sources: List of all libraries, papers, and websites used.
AI Usage: Transparent disclosure of how LLMs or coding assistants were utilized (e.g., for debugging, documentation, or initial brainstorming).

⚖️ **Evaluation Criteria**
Submissions are graded based on:
Technical Quality: Correctness, completeness, and programming style.
Analytical Depth: Application of theory and creativity in problem-solving.
Communication: Conciseness and clarity of the documentation and presentation.


**Project 9**: Heating and cooling power DFAB
Dataset:
"dfab_2019_2022_resampled.csv" (Resampled to 15 min time steps and merged)

Metadata:
"dfab_metadata.csv"

**Objective**:

Predict: heating_cooling_power
Regressor variables: irrad kitchen_active_power setp_371 setp_472 setp_474 setp_476 setp_571 setp_573 setp_574 shower_471 shower_571 temp_371 temp_472 temp_474 temp_476 temp_571 temp_573 temp_574 temp_amb total_active_power

Excluded variables (valve settings): y1_371 y1_472 y1_474 y1_476 y1_571 y1_573 y1_574 y2_371 y2_472 y2_476 y2_571 y2_574 y3_371 y3_472 y3_476 y3_571 y3_574 y4_371 y5_371 y6_371 y7_371

**Sources**:

Heer, Philipp (2024). NEST Open Building Data for Energy Demand and User Practice. figshare. Collection. https://doi.org/10.6084/m9.figshare.c.7178787.v1
Paper: https://www.nature.com/articles/s41597-024-03292-2
