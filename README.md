# Descriptve, visual and statistical analysis of the factors that influenced Data Scientist Salaries in 2020-2022

## Task Description: 

An HR agency is studying labour market trends in IT. The company aims to conduct research based on salary data in the IT industry for the years 2020–2022.

This research aims to identify the **key factors influencing the salaries of Data Scientists**. Additionally, it will address key questions posed by the HR agency, including:

* Is there an annual salary increase for Data Scientists?
* How do Data Scientist and Data Engineer salaries compare in 2022?
* How do Data Scientist salaries vary across companies of different sizes?
* Is there a correlation between the presence of Data Scientist and Data Engineer roles and company size?

Any other notable patterns found in the data will also be highlighted in the analysis.

**To ensure statistical validity**, various tests will be applied to assess the significance of the findings, including:

* Tests for continuous variables:
    * Single-sample tests
    * Two-sample tests
    * Multiple-sample tests
* A test for categorical variables.

__The data set includes:__
* **work_year** – The year in which the salary was paid.
* **experience_level** – The level of experience for this position during the year, with the following possible values:
    * **EN** – Entry-level/Junior
    * **MI** – Mid-level/Intermediate
    * **SE** – Senior-level/Expert
    * **EX** – Executive-level/Director
* **employment_type** – Type of employment for this role:
    * **PT** – Part-time
    * **FT** – Full-time
    * **CT** – Contract
    * **FL** – Freelance
* **job_title** – The role in which the employee worked during the year.
* **salary** – The total gross salary paid.
* **salary_currency** – The currency in which the salary was paid, represented as an ISO 4217 currency code.
* **salary_in_usd** – Salary converted to US dollars (exchange rate divided by the average USD rate for the corresponding year via fxdata.foorilla.com).
* **employee_residence** – The primary country of residence of the employee during the work year, represented as an ISO 3166 country code.
* **remote_ratio** – The proportion of work performed remotely, with possible values:
    * **0** – No remote work (less than 20%)
    * **50** – Partially remote work
    * **100** – Fully remote work (more than 80%)
* **company_location** – The country of the employer’s headquarters or contract-based branch, represented as an ISO 3166 country code.
* **company_size** – The average number of employees working at the company during the year:
    * **S** – Fewer than 50 employees (small company)
    * **M** – 50 to 250 employees (medium company)
    * **L** – More than 250 employees (large company)
 
