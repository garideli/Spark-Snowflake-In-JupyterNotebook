# Spark-Snowflake-In-JupyterNotebook
This project showcases a data pipeline that integrates Snowflake and Spark to analyze retail sales data. It uses Snowflake's sample datasets and Spark for data processing, enabling insights that address common challenges in the retail industry, using Jupyter Notebook

## How to Replicate

```bash
# Step 1: Clone this repository
git clone https://github.com/garideli/Spark-Snowflake-In-JupyterNotebook.git
cd Spark-Snowflake-In-JupyterNotebook

# Step 2: Set up a .env file in the root directory with the following content
echo "ENV_PATH=/absolute/path/to/.env
SNOWFLAKE_USER=your_snowflake_username
SNOWFLAKE_PASSWORD=your_snowflake_password" > .env

# Step 3: Install dependencies
pip install -r requirements.txt

# Step 4: Run the notebook
jupyter notebook retail_sales_analysis.ipynb

