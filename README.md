# ASPR-Treatment
This project analyzes the U.S. Department of Health & Human Services (HHS) ASPR Treatment Locator dataset (snapshot: July 2025) to understand nationwide access and equity of outpatient COVID-19 and influenza antiviral treatments.

The workflow integrates Excel, SQL, and Tableau to clean, explore, and visualize over 61,000 outpatient treatment site records across all 50 states.

Objective
- Quantify the share of treatment sites supplied by the U.S. Government (USG) vs. commercial channels.
- Measure treatment availability and accessibility by state and per 100 K residents.
- Evaluate Patient Assistance Program (PAP) participation and medication stocking rates (Paxlovid, Lagevrio, Influenza antivirals).
  
Tools & Workflow
Excel:
  – Data cleaning, removing U.S. territories, standardizing field names, and formatting tables for import.

SQL (MySQL) 
– Exploratory Data Analysis (EDA):
- Created CTEs to compare USG vs. commercial supply (1.4% vs 98.6%)
- Aggregated treatment site counts and normalized by state population (per 100 K residents).
-Identified top and bottom states in active treatment availability (e.g., New Hampshire vs South Dakota).
- Ranked provider networks — independent pharmacies (33 K sites) lead, followed by CVS, Walgreens, and Walmart

Tableau 
– Built an interactive dashboard visualizing
-National supply split (USG 1.4%, Commercial 98.7%)
- Active site distribution and per-capita access by state.
-Treatment availability by medication type and PAP participation rates.

Key Insights
- Commercial supply dominates the outpatient treatment network.  only 1.4% of sites receive U.S. Government-supplied inventory.
- Smaller states (West Virginia, New Hampshire) show 6× higher per-capita access compared to large states like Texas.
- Only 40% of all sites actively report antiviral stock.
-Independent pharmacies remain crucial for rural and local access.
