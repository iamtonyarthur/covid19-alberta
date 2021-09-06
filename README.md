# COVID-19 Alberta 
## Analysis & Visualization of COVID-19 in Alberta, Canada

Using a Jupyter notebook, I get data from the from the **Government of Canada**'s [COVID-19 daily epidemiology update](https://health-infobase.canada.ca/covid-19/epidemiological-summary-covid-19-cases.html) and provide some analysis and visualization for COVID-19 cases in Alberta, Canada. The notebook is the file named [covid_alberta.ipynb](https://github.com/iamtonyarthur/covid19-alberta/blob/main/covid_alberta.ipynb).

You can manually download the COVID-19 dataset from [here](https://health-infobase.canada.ca/src/data/covidLive/covid19-download.csv). It contains daily COVID-19 cases for the Canadian provinces and territories. 

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

**Visualization**

 - Daily cases and 7-day rolling average
 - Daily positivity rate and 7-day rolling average positivity rate
 - Correlation between active cases and 7-day rolling average positivity rate

## Future work
I may extend the notebook with additional analysis and also include a short-term forecasting model to predict COVID-19 trends in Alberta.

## Blog post
I feel strongly about the COVID-19 situation in Alberta. Read my 17 August 2021 blog post on [Alberta’s concerning approach to COVID-19 and its potential impact](https://skills4ever.com/albertas-concerning-approach-to-covid-19-and-its-potential-impact-12300e780e7b).

## Contact

Creator: Tony Arthur. You can follow me or contact me on Twitter/**@iamtonyarthur**.


