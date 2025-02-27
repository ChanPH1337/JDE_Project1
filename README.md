# **Introduction**

## **Overview**

This project investigates the impact of user behavior on battery performance across various mobile devices. By analyzing user activities, such as app usage, screen-on time, and the number of apps installed, the study identifies patterns that contribute to battery drainage. Additionally, device-specific attributes like operating systems and device models are examined for their role in battery longevity.

## **Problem Statement**

Battery life remains one of the most significant concerns for mobile users. However, it is influenced by behaviors that are not always well understood, leading to suboptimal device usage and unnecessary battery wear. The lack of actionable insights into how usage patterns affect battery performance creates inefficiencies for both users and device manufacturers. This project seeks to bridge this knowledge gap by identifying and analyzing the factors contributing to battery drain.

## **Project Scope**

### ETL Pipeline Implementation

Extraction - Using Kaggle hub library and Kaggle API to retrieve datasets from Kaggle in CSV and JSON formats programmatically.​

Transformation - Cleaning and merging datasets using Pandas, normalizing JSON structures, handling missing values, and ensuring data type consistency.​

Load - Utilizing sqlalchemy to connect Python with PostgreSQL, enabling data loading and querying in both local and cloud-based instances.​<br>
<br>

### Database Management

-Design a relational database schema to store and query data efficiently.​

-Designate primary keys for unique identification, foreign keys for referential integrity, and apply necessary constraints.​

-Develop Entity-Relationship Diagrams (ERD) to visualize the structure of the database, including entities, attributes, and relationships.​

-Implement databases on local and cloud instances using PostgreSQL.​<br>
<br>

### Visualization and Insights

Create visualizations using Matplotlib to present findings on primary factors influencing battery drain, including app usage, screen-on time, and number of apps installed.​<br>
<br>

### Challenges and Limitations
Address technical challenges encountered during data integration and analysis.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/your-repo.git
   cd your-repo
   ```

2. Install dependencies (if applicable):
   ```bash
   pip install -r requirements.txt
   ```

## Usage

Run the Jupyter Notebook to explore the project:

```bash
jupyter notebook Interim_Project_Documentation_Final_v1.ipynb
```

## Example Code

```python
#Install relevant packages
!pip install sqlalchemy
!pip install psycopg2
!pip install kaggle

# Install kagglehub package with minimal output
!pip install kagglehub -q
```

```python
#Import relevant main packages
import pandas as pd
import numpy as np
import sqlalchemy as db
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.

