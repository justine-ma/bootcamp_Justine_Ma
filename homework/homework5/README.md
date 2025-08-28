## Data Storage

### Folder Structure
- `data/raw/` - Contains original, unprocessed data in CSV format
- `data/processed/` - Contains cleaned and processed data in Parquet format

### Formats Used
- **CSV**: Used for raw data storage because it's human-readable and widely supported
- **Parquet**: Used for processed data because it's columnar, compressed, and preserves data types

### Env Variables
- `DATA_DIR_RAW=./data/raw` - Path for raw CSV files
- `DATA_DIR_PROCESSED=./data/processed` - Path for processed Parquet files