# smart-store-Mahesh
# smart-sales-starter-files

Starter files to initialize the smart sales project.

-----p

## Project Setup Guide (1-Mac/Linux)

Run all commands from a terminal in the root project folder. 

### Step 1A - Create a Local Project Virtual Environment

```shell
python3 -m venv .venv
```

### Step 1B - Activate the Virtual Environment

```shell
source .venv/bin/activate
```

### Step 1C - Install Packages

```shell
python3 -m pip install --upgrade -r requirements.txt
```

### Step 1D - Optional: Verify .venv Setup

```shell
python3 -m datafun_venv_checker.venv_checker
```

### Step 1E - Run the initial project script

```shell
python3 scripts/data_prep.py
```

-----

## Project Setup Guide (2-Windows)

Run all commands from a PowerShell terminal in the root project folder.

### Step 2A - Create a Local Project Virtual Environment

```shell
py -m venv .venv
```

### Step 2B - Activate the Virtual Environment

```shell
.venv\Scripts\activate
```

### Step 2C - Install Packages

```shell
py -m pip install --upgrade -r requirements.txt
```

### Step 2D - Optional: Verify .venv Setup

```shell
py -m datafun_venv_checker.venv_checker
```

### Step 2E - Run the initial project script

```shell
py scripts/data_prep.py
```

-----



# Commit the changes with a meaningful message  
git commit -m "add starter files"  


# Push changes to GitHub on the main branch  
git push -u origin main  


# After making additional changes on README, use these commands:  
git add .  

git commit -m "Update README with commands"  

git push  






## Initial Package List

- pip
- loguru
- ipykernel
- jupyterlab
- numpy
- pandas
- matplotlib
- seaborn
- plotly
- pyspark==4.0.0.dev1
- pyspark[sql]
- git+https://github.com/denisecase/datafun-venv-checker.git#egg=datafun_venv_checker

# Project 4
- We designed our data warehouse schema
- created data models consisting of one fact table (Sales) and two dimension tables (Products) and (customers)
- we created schema and loaded the data in python
- We created a new file named etl_to_dw.py
- We copied the code from the repo, adjusted it for the prepared data
- For mac we activated the virtual environment and ran the following script
   - source .venv/bin/activate
   - python3 scripts/etl_to_dw.py

