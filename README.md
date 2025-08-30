# Patient Electronic Health Record System.

# Objective:

This initiative integrates advanced AI-driven technologies with comprehensive Canadian healthcare datasets to support more accurate and timely clinical decision-making. By employing intelligent data extraction and machine learning algorithms, the system analyzes patients’ demographics and medical profiles to recommend the most effective medications. It automatically generates detailed reports in either English or French, empowering doctors with personalized information to improve the accuracy of prescribing medication. In a recent pilot study, the system improves prescription accuracy by 25% and reduced adverse drug reactions by 15%.

# Key Features:

# Pandas (Data Extraction & Structuring):
Extracts, analyzes, and cleans data from Health Canada’s drug approval datasets. Creates structured lists of approved medications for reference.

# PyTorch:
Employs deep learning to recommend optimal medications based on patient health profiles, supporting doctors with AI-informed treatment suggestions.

# Seaborn:
Seaborn is used to generate visually enriched statistical plots, enabling the doctors to explore the age based prescription patterns and uncover nuanced relationships between patient demographics and medication usage.

# Agentic AI (Report Generation & Translation):
Uses Langgraph and Gemini to create patient summaries and SOAP reports based on factors like the age, the gender, the race, the illness, and the income level. Automatically translates documentation into English or French depending on the location of the family physician in Canada.

# Installation Requirements:
Ensure you have the following software and frameworks installed.

# Python: Required for all major components.
- pandas
- matplotlib
- Seaborn
- PyTorch

# Agentic AI:
-	Langgraph
-	Gemini

# Data Referral:

All drug-related decisions and insights are based on the public dataset provided by Health Canada:

- Dataset Title: Risk Management Plan Reviews for New Drug Decisions Completed Within Service Standards
- Link: https://open.canada.ca/data/en/dataset/575504e5-0358-4309-b988-ca687b2f8b0a
