# Exploratory Data Analysis of Data Science Jobs' Salaries

## Objective
Starting out on a career in data science was exciting, but left me with a load of questions. Apart from the job sections involved in the rather broad ‘data science’, I wanted to find out what regions of the world had the most demand for data scientists, leading to a higher compensation, or pay. What would be the difference between working as a data analyst for a small, medium or large firm and how much does these affect your pay/growth?

This case study focuses on this, as we use data to come to accurate conclusions. Here we look into the top earners by job title across data science, and correlate it with company size, experience level, company location, etc.


## Dataset Information
The data used for this study is obtained by aggregated data from [ai-jobs.net](https://aijobs.net), under this [license](https://creativecommons.org/publicdomain/zero/1.0/).

1. `work_year`: The year the salary was paid.
2. `experience_level`: The experience level in the job during the year with the following possible values:

    - `EN` = Entry-level/Junior
    - `MI` = Mid-level/Intermediate
    - `SE` = Senior-level/Expert
    - `EX` = Executive-level/Director

3. employment_type: The type of employement for the role:
    
    - `PT` = Part-time
    - `FT` = Full-time
    - `CT` = Contract
    - `FL` = Freelance

4. `job_title`: The role worked in during the year.
5. `salary`: The total gross salary amount paid.
6. `salary_currency`: The currency of the salary paid as an ISO 4217 currency code.
7. `salary_in_usd`: The salary in USD
8. `employee_residence`: Employee's primary country of residence in during the work year as an ISO 3166 country code.
9. `remote_ratio`: The overall amount of work done remotely, possible values are as follows:

    - `0` = No remote work (less than 20%)
    - `50` = Partially remote
    - `100` = Fully remote (more than 80%)

10. `company_location`: The country of the employer's main office or contracting branch as an ISO 3166 country code.

11. `company_size`: The average number of people that worked for the company during the year:

    - `S` = less than 50 employees (small)
    - `M` = 50 to 250 employees (medium)
    - `L` = more than 250 employees (large)

## Conclusion
- (Coming Soon)