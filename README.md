# COVID19-datasets
List of all public datasets and interesting ressources on COVID19. This list is not exhaustive. If you find something new please, fork this repository, commit your update, and do a pull-request. You'll find interesting ressources for epidemiologic data analysis (ML algorithms, visualization, litterature, etc.) in the sections below.


## Datasets

Datasets are currently segmented by geography, but feel free to propose another organization if needed (open an issue). Please try to list first the aggregating datasets. You can use keywords for the spatial resolution (e.g. `nationwide`, `regional`, `individual`, etc.)

* **Worldwide**

1.  [CSSEGISandData/COVID-19](https://github.com/CSSEGISandData/COVID-19). Visual Dashboard operated by the Johns Hopkins University Center for Systems Science and Engineering. Aggregating several raw sources of the section below.
2. [COVID-19 Open Research Dataset Challenge (CORD-19)](https://www.kaggle.com/allen-institute-for-ai/CORD-19-research-challenge). The Kaggle initiative to find data-based answers on the desease.
3. [Novel Corona Virus 2019 Dataset](https://www.kaggle.com/sudalairajkumar/novel-corona-virus-2019-dataset) `individual`

* **Asia**

* **North America**

* **Europe**
1. FRANCE [opencovid19-fr/data](https://github.com/opencovid19-fr/data). Aggregation of the `regional` french data.
2. FRANCE [lperez31/coronavirus-france-dataset](https://github.com/lperez31/coronavirus-france-dataset). `individual` french data.


## Raw sources
Data not aggregated nor ready for analysis (e.g. press release)

* **Worldwide**
2. World Health Organization (WHO): https://www.who.int/
3. DXY.cn. Pneumonia. 2020. http://3g.dxy.cn/newh5/view/pneumonia. 
4. BNO News: https://bnonews.com/index.php/2020/02/the-latest-coronavirus-cases/  

* **Asia**
1. National Health Commission of the People’s Republic of China (NHC): http://www.nhc.gov.cn/xcs/yqtb/list_gzbd.shtml 
2. China CDC (CCDC): http://weekly.chinacdc.cn/news/TrackingtheEpidemic.htm 
3. Hong Kong Department of Health: https://www.chp.gov.hk/en/features/102465.html 
4. Macau Government: https://www.ssm.gov.mo/portal/ 
5. Taiwan CDC: https://sites.google.com/cdc.gov.tw/2019ncov/taiwan?authuser=0 
6. Ministry of Health Singapore (MOH): https://www.moh.gov.sg/covid-19


* **North America**
1. US CDC: https://www.cdc.gov/coronavirus/2019-ncov/index.html
2. Government of Canada: https://www.canada.ca/en/public-health/services/diseases/coronavirus.html 
* Australia Government Department of Health: https://www.health.gov.au/news/coronavirus-update-at-a-glance 

* **Europe**
1. European Centre for Disease Prevention and Control (ECDC): https://www.ecdc.europa.eu/en/geographical-distribution-2019-ncov-cases 
2. Italy Ministry of Health: http://www.salute.gov.it/nuovocoronavirus


## Relevant ressources of COVID19 analysis

Segmented by language for algorithms. Add the relevant keywords in description for the scope of the tools e.g. {`COVID19`, `epidemiology`, `generic`, `ML`, `vizualization`}.

* **Collaborative Projects**
1. [OpenCOVID19 France](https://github.com/opencovid19-fr). Concatenation and visualization for the french COVID19 data. 

* **R**
1. [EpiEstim: Estimate Time Varying Reproduction Numbers from Epidemic Curves](https://cran.r-project.org/web/packages/EpiEstim/index.html). {`epidemiology`, `ML`}

* **Python**
1. [COVID-19](https://github.com/DmitrySerg/COVID-19). "combining two general strategies to infection modelling: using Susceptible-Infectious-Recovered/Removed (SIR) model". {`COVID19`, `ML`}
2. [EndemicPy](https://github.com/j-i-l/EndemicPy). "Python package to simulate a vast range of transmission processes on various structures". {`epidemiology`, `ML`}

* **javascript**
1. [coronavirus-api](https://github.com/aitahtman/coronavirus-api). "api dedicated to serve Coronavirus data"
2. [disease](https://github.com/xithiox/disease). "A simple disease spread simulation in p5.js. It can be played [here](https://xithiox.github.io/disease/)." {`epidemiology`, `vizualization`}

## To be added
There is so much accademic/non-accedemic publications that it is difficult to link the different initiatives the ressources. Please add links to publications that relies on datasets or methods not yet public. Before adding elements here, please double check it is not included in another section.

1.  A spatial model of CoVID-19 transmission in England and Wales: early spread and peak timing. Leon Danon, Ellen Brooks-Pollock, Mick Bailey, Matt J Keeling. medRxiv 2020.02.12.20022566; doi: https://doi.org/10.1101/2020.02.12.20022566 
2. COVID-19: Forecasting short term hospital needs in France. Massonnaud, C., Roux, J., Crépey P.. https://www.ea-reperes.com/wp-content/uploads/2020/03/PredictedFrenchHospitNeeds-EHESP-20200316.pdf