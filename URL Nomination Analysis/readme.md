# Nomination Analysis
This notebook analyzes URLs outputted by EDGI's Nomination Tool. 

**Note**: In this analysis, the term "uncrawlable" is avoided as it is not an appropriate representation of what was nominated. Instead, the term "pages with data" is used. This corresponds to URLs that are hosting information or data that is flagged for archiving and "data" is used in a broad sense to mean collections of files, FTP pages, databases, or visualization/interactive features.

Relevant Files:
- *agency_database.csv* - A database of federal agencies and corresponding codes
- *primer_db_040117.csv* - List of subprimer lines and dates of completion
- *NominationToolOutput_121716to040117_cleaned_anon.csv* - Cleaned and anonymized output from the Nomination Tool from Dec 17, 2016 to April 1, 2017


**This analysis includes**:
- Numbers for unique nominated URLs vs. pages with data
- Breakdown of numbers above by agency
- Progess of primer line completion. **Disclaimer**: Using total number of nominated URLs is NOT a good metric to use to understand how much work was done or if an agency was covered. Completion of a primer lines are the best way we know at the moment to denote that a section of a website was screened and seeded appropriately.

Toly Rinberg - April 1, 2017
