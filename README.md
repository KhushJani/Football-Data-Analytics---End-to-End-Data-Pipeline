# Football-Data-Analytics---End-to-End-Data-Pipeline

This Python-based project crawls data from Wikipedia using Apache Airflow, cleans it and pushes it Azure Data Lake for processing.


## System Architecture
![image](https://github.com/KhushJani/Football-Data-Analytics---End-to-End-Data-Pipeline/assets/88198216/134f9c08-4b8b-49de-896f-44f7124e5331)


## Requirements
- Python 3.9 (minimum)
- Docker
- PostgreSQL
- Apache Airflow 2.6 (minimum)

## Getting Started

1. Clone the repository.
   ```bash
   git clone https://github.com/airscholar/FootballDataEngineering.git](https://github.com/KhushJani/Football-Data-Analytics---End-to-End-Data-Pipeline.git
   ```

2. Install Python dependencies.
   ```bash
   pip install -r requirements.txt
   ```
   
## Running the Code With Docker

1. Start your services on Docker with
   ```bash
   docker compose up -d
   ``` 
2. Trigger the DAG on the Airflow UI.

## How It Works
1. Fetches data from Wikipedia.
2. Cleans the data.
3. Transforms the data.
4. Pushes the data to Azure Data Lake.
