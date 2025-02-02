# Data Science Projects

This repository contains a collection of Data Science projects that demonstrate various skills in data analysis, modeling, and deployment.

## Projects

### 1. Near Eart Object (NEO) ETL Pipeline
- **Description**: This project extracts, transforms, and loads (ETL) data from NASA's Near-Earth Object (NEO) API to analyze asteroid close approaches. The pipeline collects asteroid data, cleans and formats it, 
and stores it in a structured format for further analysis.
- **Tools Used**: Python, Pandas, PySpark, Requests, PostgreSQL
- **Key Features**
  - Data Extraction – Fetches asteroid close-approach data from NASA's API.
  - Data Transformation – Converts JSON response into a structured DataFrame.
  - Data Cleaning – Ensures valid datetime formatting and removes invalid records.
  - Data Storage – Stores the final dataset in a PySpark DataFrame for analysis.
  - Scalability – Uses PySpark for efficient big data processing.
    
### 2. Exoplanet ESI Ranking
- **Description**:  This project analyzes exoplanetary data from the NASA Exoplanet Archive to compute the Earth Similarity Index (ESI), a quantitative measure of how similar an exoplanet is to Earth based on its stellar flux and planetary radius. The analysis ranks exoplanets by their ESI score, identifying the most potentially habitable candidates.
- **Tools Used**: Python, Pandas, NumPy, Seaborn, Matplotlib
- **Key Features**:
  - Preprocesses exoplanet data by handling missing values and removing duplicate observations
  - Implements a computational model to evaluate planetary habitability(ESI) 
  - Identifies and ranks the top 10 exoplanets with the highest Earth similarity
  - Visualizes the ESI distribution to highlight trends in planetary characteristics


## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/skoc3r/Data-Science-projects.git
   cd Data-Science-Projects
