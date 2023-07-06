# Python Foundations for Data Analysis & Business Intelligence

This repository consists of some of the assignments and hands-on practices that I have done by taking the [Python Foundations for Data Analysis & Business Intelligence](https://www.udemy.com/course/python-foundations-for-data-analysis/) course on Udemy. The course covers the building blocks of base Python for Data Analysis & BI: 

* Master the building blocks of base Python, including data types, variables, loops, functions and more
* Learn how to use Jupyter Notebooks to write, manage, and comment your Python code
* Analyze and manipulate numeric data, text strings, lists, tuples, dictionaries and sets
* Explore raw data using conditional logic, nested loops, custom functions, and comprehensions
* Use Python's Openpyxl package to read & write data to Excel worksheets
* Build solid, foundational Python skills for data analysis & business intelligence

### [The **Maven Ski Shop** Course Project](./Section13_final_project/)

Act as a newly hired Data Analyst for **Maven Ski Shop**, the world's #1 store for skis, snowboards, and winter gear. The team is beginning to use Python for data analysis. 

The assignment is to prepare for scalabe growth, the business is transitioning to Python as their primary tool for tracking **inventory**, **pricing**, and **promotions**. 

The first task is to analyze sales data from the shop's recent Black Friday promotion. 

The objectives are **use Python to:**
* Process missing data fields
* Reshape and aggregate transactional data
* Calculate KPIs and deliver insights on Black Friday Sales
* Build a simple data pipeline and export processed data to Excel to share with leadership

---
### Setup & Run Jupyter Notebooks in VS Code w/ Virtual Env & Kernels

I completed below setup instead of using Anaconda (course instruction):
* create a virtual environment
  ```
  python3 -m venv jupyter-env 
  ```
* activate the virtual env
  ```
  source jupyter-env/bin/activate
  ```
* Installation 

  ```
  pip install jupyterlab
  
  pip install ipykernel
  ```
  _Validate that the install has succeeded by running `jupyter-lab` from your command line. A new tab should open in your browser, with the JupyterLab application running._
  
  * install useful Python packages in this virtual env
  

  ```
  pip install numpy
  pip install pandas
  pip install openpyxl
  pip install matplotlib
  ```
  
* register the new virtual env with Jupyter so that you can use it within JupyterLab

  ```
  python3 -m ipykernel install --user --name=‘maven-python‘ 
  ```
  
Now open an existing/create a new `.ipynb` file in VS Code and select the `maven-python` Kernel to use


<img src="./certificate.png" width=90% height=90%>

