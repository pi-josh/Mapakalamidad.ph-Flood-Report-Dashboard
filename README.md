# Assessing Flood Reporting Patterns on MapaKalamidad.ph in the Philippines

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
This simple project focuses on evaluating the patterns and trends in flood reporting on **MapaKalamidad.ph**, a platform designed to assist in **Disaster Risk Reduction Management (DRRM)** in the Philippines. By analyzing flood reports submitted through the platform, we aim to understand the platform's impact on flood preparedness and response activities.

## Problem Statement
Flooding is one of the most common natural disasters in the Philippines, causing significant disruption to communities and infrastructure. Despite the existence of platforms like **MapaKalamidad.ph** for real-time crowd-sourced flood reporting, challenges persist in ensuring efficient data collection and analysis to support timely response and recovery efforts. This project seeks to evaluate the trends and patterns in flood reporting through **MapaKalamidad.ph** and assess how well the platform facilitates real-time information sharing during flood events.

## Objectives
The main objectives of this project are to:
- **Identify** the trends in flood reports submitted through MapaKalamidad.ph.
- **Analyze** the frequency and distribution of flood reports during the covered time period.
- **Evaluate** the types of incidents reported and their geographical locations to assess the platform’s role in flood preparedness and response.

## Scope and Limitations

The analysis focuses on **archival reports** of flood data collected during the months of **January and February**, specifically in flood-affected regions where **MapaKalamidad.ph** was utilized. The evaluation includes data on reported incidents from the platform’s API during this time frame.

However, certain limitations may affect the analysis:
- **Time Frame**: The analysis is restricted to the months of **January–February**, which may not provide a comprehensive view of flood reporting trends during other months.
- **Data Availability**: The study is limited to the data provided by the **MapaKalamidad.ph API**. Additional external sources are not incorporated in this analysis.

## Analytical Questions

1. **What are the trends in flood reports** during the specified time period (January–February) in regions affected by floods?
2. **How frequently are flood incidents reported** on MapaKalamidad.ph, and what types of incidents are most commonly reported?
3. **What is the geographical distribution** of flood reports in the available data, and which regions are most impacted by floods based on the API data?
4. **What are the patterns in response times** as indicated by the data in the system?
5. **How does the number of reports change over time** during the flood events covered by the dataset?

## Repository Contents
- **Jupyter Notebook**: The notebook focuses on data wrangling and processing the MapaKalamidad.ph API dataset to prepare it for analysis and visualization.
    - [Notebook.ipynb](./mapakalamidad-ph-data-wrangling.ipynb)
  
- **Kaggle Notebook**: View the full data wrangling process hosted on Kaggle.
    - [View on Kaggle](https://www.kaggle.com/code/joshuamacatunao/mapakalamidad-ph-data-wrangling)

- **Tableau Project**: A dashboard showcasing insights from the data, such as flood reporting patterns and community feedback.
    - [View Tableau Dashboard](link_to_your_tableau_project)

## API Usage
The project utilizes **MapaKalamidad.ph's API**, which provides flood-related data in JSON format. The data from the API will be used for real-time analysis, incident reporting, and flood response evaluations. To learn more about the API and how it functions, you can visit the official documentation: [MapaKalamidad.ph API Documentation](https://mapakalamidad.ph/api-documentation).

## Dashboard Insights Overview
*This section will provide an overview of the insights viewers can expect to find in the Tableau dashboard, including key metrics on flood reporting patterns, incident reporting frequency, and geographical distribution.* (To be updated)

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/Mapakalamidad.ph-Dashboarding-Project.git
    ```
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Contributions
If you'd like to contribute to this project, feel free to fork the repository and submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).
