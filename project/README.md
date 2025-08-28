# Credit Risk Modeling 

## Project Description and Structure
This project develops a machine learning model to predict loan default probability.  
The repository is structured as follows:

- **/data/**: Datasets used for training and testing  
- **/data/raw/**: Unprocessed raw data (not committed to Git)  
- **/notebooks/**: Jupyter notebooks for exploration and experimentation  
- **/src/**: Source code for data processing, modeling, and evaluation  
- **/docs/**: Documentation, reports, and project write-ups  
- **README.md**: Project overview and instructions

## Data Storage

### Folder Structure
- `data/raw/` - Contains original, unprocessed data in CSV format
- `data/processed/` - Contains cleaned and processed data in Parquet format

### Formats Used
- **CSV**: Used for raw data storage because it's human-readable and widely supported
- **Parquet**: Used for processed data because it's columnar, compressed, and preserves data types

### Env Variables
- `DATA_DIR_RAW=../data/raw` - Path for raw CSV files
- `DATA_DIR_PROCESSED=../data/processed` - Path for processed Parquet files