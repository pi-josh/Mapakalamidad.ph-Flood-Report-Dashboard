# Assessing Flood Reporting Patterns on MapaKalamidad.ph in the Philippines

---

## Table of Contents
1. [Project Overview](#project-overview)
2. [Problem Statement](#problem-statement)
3. [Objectives](#objectives)
4. [Scope and Limitations](#scope-and-limitations)
5. [Analytical Questions](#analytical-questions)
6. [Repository Contents](#repository-contents)
7. [API Usage](#api-usage)
8. [Dashboard Insights Overview](#dashboard-insights-overview)
9. [Installation](#installation)
10. [Contributions](#contributions)
11. [License](#license)

---

## Project Overview
This project evaluates patterns and trends in flood reporting on **MapaKalamidad.ph**, a platform designed to assist in **Disaster Risk Reduction Management (DRRM)** in the Philippines. The analysis focuses on how the platform contributes to raising flood awareness and providing timely information to affected communities.

## Problem Statement
Flooding is one of the most common natural disasters in the Philippines, leading to significant disruption to communities and infrastructure. While platforms like **MapaKalamidad.ph** allow for real-time crowd-sourced flood reporting, there are challenges in utilizing this data for efficient information sharing. This project aims to assess the trends and patterns in flood reporting through **MapaKalamidad.ph** and evaluate how well the platform helps raise awareness of flood incidents and share timely information with affected communities.

## Objectives
The main objectives of this project are to:
- **Identify** the trends in flood reports submitted through MapaKalamidad.ph.
- **Analyze** the frequency and distribution of **flood reports** during the covered time period.
- **Evaluate** the **geographical locations** and **flood depths** reported to assess the platform’s role in raising flood awareness and disseminating timely flood information.

## Scope and Limitations

The analysis focuses on **archival reports** of flood data collected during the months of **January and February**, specifically in flood-affected regions where **MapaKalamidad.ph** was utilized. The evaluation includes data on reported incidents from the platform’s API during this time frame.

However, certain limitations may affect the analysis:
- **Time Frame**: The analysis is restricted to the months of **January–February**, which may not provide a comprehensive view of flood reporting trends during other months.
- **Data Availability**: The study is limited to the data provided by the **MapaKalamidad.ph API**. Additional external sources are not incorporated in this analysis.

## Analytical Questions

1. **What is the average and distribution of flood depths** reported on MapaKalamidad.ph during January–February?
2. **How does flood reporting frequency change over time** during the January–February period?
3. **Which regions reported the most flood incidents**, and what is the corresponding average flood depth for each region?
4. **How does flood severity vary across different regions**?
5. **What is the geographical clustering of flood reports**?

## Repository Contents
- **Jupyter Notebook**: The notebook focuses on data wrangling and processing the MapaKalamidad.ph API dataset to prepare it for analysis and visualization.
    - [mapakalamidad-ph-data-wrangling.ipynb](./mapakalamidad-ph-data-wrangling.ipynb)
 
- **Datasets in JSON Format**: The datasets contain the report from the API.
    - [reports.json](./reports.json): contains the current reports
    - [archive.json](./archive.json): contains archival reports from January to February
    - [cleaned.json](./cleaned.json): contains the cleaned archival reports
  
- **Kaggle Notebook**: View the data wrangling process hosted on Kaggle.
    - [View on Kaggle](https://www.kaggle.com/code/joshuamacatunao/mapakalamidad-ph-data-wrangling)

- **Tableau Project**: A dashboard showcasing insights from the data, such as flood reporting patterns and community feedback.
    - [View Tableau Dashboard](https://public.tableau.com/app/profile/joshua.macatunao/viz/Mapakalamidad_ph-Flood-Report-Dashboard/LandingPage?publish=yes)

## API Usage
The project utilizes **MapaKalamidad.ph's API**, which provides flood-related data in JSON format. The data from the API will be used for real-time analysis, incident reporting, and flood response evaluations. To learn more about the API and how it functions, you can visit the official documentation: [MapaKalamidad.ph API Documentation](https://mapakalamidad.ph/api-documentation).

## Dashboard Insights Overview
### Flood Reports Count:
- **Insight**: Daily flood reports peaked on January 14, with **161 reports**, followed by January 15 with **34 reports**, and February 17 with **28 reports**.
- **Regional Highlight**: The **National Capital Region (NCR)** has the highest flood report counts, particularly on January 14 and 15, indicating it may be more prone to flooding or has better reporting engagement.
- **Notable Observation**: **Eastern Visayas** led on February 17 with **12 reports**, suggesting varying flood impacts across regions.

### Flood Reports Depth:
- **Insight**: The highest daily average flood depth was recorded on **February 13**, at **114 cm**, with significant averages of **98.04 cm** on February 10 and **93.00 cm** on January 29.
- **Regional Focus**: The **Ilocos Region** reported an average flood depth of **93 cm**, although from only one report. Additionally, **NCR** leads in the count of severe flood reports, indicating a potential need for enhanced preparedness in that region.

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/Mapakalamidad.ph-Dashboarding-Project.git
    ```

## Contributions
If you'd like to contribute to this project, feel free to fork the repository and submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).
