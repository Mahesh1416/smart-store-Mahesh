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
 
  # Project 6 (OLAP analysis)
  - Business goal
    - There were three business goals. The first was to evaluate which category of products gets sold more in which of the four regions. The second goal was focused on      
      finding the total sales are greater in which quarter and month of the year. The final goal was to evaluate which customer spent more on the products.
   - Data Source
        - I imported the three files (customer, product and sales) files in Power BI directly and then created the graphs, tables and analysis trying to answer those
          business goal questions.
   - Tools
        - I used Microsoft Power BI tool to create those tables and graphs.
   - Workflow and logic
        - <img width="959" alt="Screenshot 2025-04-19 174226" src="https://github.com/user-attachments/assets/045eeab9-2bf5-4d4d-9fb1-e09ad03f0396" />

   - Results
    
    <img width="956" alt="Screenshot 2025-04-19 172408" src="https://github.com/user-attachments/assets/31c2d1c6-29af-4169-9a22-778dc59cedb7" />

    
<img width="941" alt="Screenshot 2025-04-19 162306" src="https://github.com/user-attachments/assets/bd8856a6-6721-439f-adef-2bb427fb00bf" />

   - Suggested Business action
        - I recommend the company to focus more on the sales during August, January, June and October as the sales were low during these periods. A further study is warranted to look investigate on those trends. Similalry, the sale of electronic items seems to be very high which tells us that there is a very high demand for electronic products so further exploration on different types of electronic items that can be sold should be explored.
    
   - Challenges
        - Overall, this project was very challenging in the beginning. I had to use Power BI directly for this project because I had a hard time connecting with the JDBC driver on mac.
    
   # Final Project
   - Section 1. The Business Goal
   - My business goal was to identify which product is most profitable by month and region
   - Section 2. Data Source
   - I imported the three files (customer, product and sales) files in Power BI directly and then created the graphs, tables and analysis trying to answer those
          business goal questions.
   - Section 3. Tools used
   - Power BI
   - Section 4. Workflow and Logic
   - I used Power BI to prepare the data and used Power BI to find ways to create graphs (by slicing and dicing) to provide useful answers for my business goals in the 
     dashboard. I created multiple graphs that answered my questions and those charts were used to make my dashboard.
   - Section 5. Results
   - <img width="952" alt="Screens![Uploading workflow and logic.png…]()
hot 2025-04-24 142132" src="https://github.com/user-attachments/assets/e4a446ee-4652-40b7-b214-e7a7566b86d8" />

- Section 6. Suggested Business Action
- Based on my analsysis, it appears that the product which is sold best in atleast 3 regions (eastern, southern and western) is laptop. Therefore, I recommend the company to stock more laptops for the coming year in those regions. To continue to have higher sales from laptop, I would also recommend the company for more targeted sales advertisement on laptops as the demand is quite high in those regions. Based on my line chart, it appears that there is lower sales in the months of June, January, October and August. I recommend the company to investigate further on why the sales are so low during those months thereby warranting a more thorough study. 

- Section 7. Challenges
- The initial challenges I had for this project was to slice and dice the data in a way that would answer the questions related to the business goals.
- Section 8. Ethical Considerations.
- Some of the important ethical considerations are to make sure that we focus on stores and regions that are not performing well along with high performing locations and stores. It is very important to uplift those underperforming ones rather than using the data to justify to focus only on high performing ones.
  





     
          


