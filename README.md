# ai-employment-analysis
Analysis of US employment in AI, Data Science and Software Development using BLS data
AI Employment Analysis
This is my data visualisation project about US employment in Data Science, Software Development, and Computer and Information Research Science.

I used BLS data from May 2023 to compare employment and wages. I also used 2024 and 2025 data to look at how employment estimates changed.
What's included
The notebook contains five types of charts: a bar chart, pie chart, scatter plot, heatmap and line chart. Each chart has an explanation of its purpose, why I chose it and what I found.
Dataset
Download the All data → XLSX files for May 2023, 2024 and 2025 from the BLS website.

Extract them and keep these files in the project folder:
- oesm23all/all_data_M_2023.xlsx
- oesm24all/all_data_M_2024.xlsx
- oesm25all/all_data_M_2025.xlsx
The datasets are not included in the repository because they are large.
How to run
1. Download or clone this repository and open the project folder in VS Code or Jupyter.
2. Install the Python libraries:
   pip install pandas openpyxl matplotlib seaborn
3. Open employment_analysis.ipynb and select your Python kernel.
4. Restart the kernel and run all cells from the top. Loading the Excel files may take a few minutes.
Main findings
Software Developers had the most jobs in 2023, while Research Scientists had the highest average annual wage. Data Scientists had the largest percentage increase in employment estimates between 2023 and 2025, at 36.2%.

These occupations include jobs outside AI. BLS also advises caution when comparing years because the estimates use overlapping survey data.
