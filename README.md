# COVID-19 Alberta 
## Analysis & Visualization of COVID-19 in Alberta, Canada

This Jupyter notebook provides analysis and visualization for COVID-19 cases in Alberta, Canada. The notebook is the file named [covid_alberta.ipynb](https://github.com/iamtonyarthur/covid19-alberta/blob/main/covid_alberta.ipynb).

The datasets used are from the Government of Canada's [COVID-19 daily epidemiology update](https://health-infobase.canada.ca/covid-19/epidemiological-summary-covid-19-cases.html) and the Alberta Government's [COVID-19 Alberta statistics](https://www.alberta.ca/stats/covid-19-alberta-statistics.htm). The epidemiology update contains daily COVID-19 cases for the Canadian provinces and territories. The Alberta government dataset shows the daily COVID-19 cases by demography. All other analysis is done using the Government of Canada's daily epidemiology update data.

Links to download datasets:
* Canada dataset: https://health-infobase.canada.ca/src/data/covidLive/covid19-download.csv
* Alberta dataset: https://www.alberta.ca/data/stats/covid-19-alberta-statistics-data.csv 

## How to use the Juypter notebook

The easiest way to use the notebook for free is via Google Colaboratory ("Colab" for short). 
1. Go to Colab at https://colab.research.google.com
2. Login to Colab using your Gmail account. 
3. In Colab, go to File and upload the notebook
4. Click Runtime and run all

You can also choose to upload and run the notebook on your local computer, AWS (Amazon SageMaker), or other environment.

## What information can you get from the notebook

**Basic metrics about COVID-19 in Alberta:**
 - Death
	 - Total deaths in Alberta is 2,390 
 - Active cases
     - Active cases in Alberta is 13,495
     - Active cases in Canaada 34,656
     - Alberta makes up 38.9% of the active cases in Canada 
- Daily cases
     - Latest reported daily cases in Alberta is 1,401 
     - Latest reported daily cases in Canada is 4,161 
     - Alberta makes up 33.7% of the latest reported daily cases in Canada 
     - Latest reported daily tests in Alberta is 12,139 
 - Positivity rate
     - Latest positivity rate in Alberta is 11.5% 
     - Latest positivity rate in Canada is 4.7%
 - Comparative analysis between Alberta and all of Canada
     - Alberta is 11.7% of Canada's population and has 38.9% of the active cases in Canada
     - Active cases in Alberta is 3.3x higher relative to the province's population

**Metrics on children with COVID-19 in Alberta:**
 - Daily cases
	 - Cases with children under 1 year, 1 - 9 years, and 10 - 19 years

**Visualization**

 - Daily cases and 7-day rolling average
 - Daily positivity rate and 7-day rolling average positivity rate
 - Correlation between active cases and 7-day rolling average positivity rate
 - Daily COVID-19 cases by age group

## Future work
I may extend the notebook with additional analysis and also include a short-term forecasting model to predict COVID-19 trends in Alberta.

## Blog post
I am passionate about the COVID-19 situation in Alberta. Read my 17 August 2021 blog post on [Alberta’s concerning approach to COVID-19 and its potential impact](https://skills4ever.com/albertas-concerning-approach-to-covid-19-and-its-potential-impact-12300e780e7b).

## Contact

Creator: Tony Arthur. Follow me or contact me on Twitter/**@iamtonyarthur**.


