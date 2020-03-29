# Covid19 timeseries data
Covid19 timeseries data store

This is data repository for covid 19 history. Webcrawlers is taking snapshot for every GMT 00:00 sources below and converting to CSV. There is some data normalization steps for different sources like country code or other stuffs. Sometimes there is some data inconsistency between days, we are keeping update, if newly counts lower than older, we are updating older rows. 

*If you feels wrong data for own country, please open an issue.

## Files

Country data
`countryReport/country/{countryCode}.csv`

Daily Data
`countryReport/daily/{YYYY-MM-DD}.csv`

Raw Data
`countryReport/raw/rawReport.csv`

## Customized Country Codes

X1: Diamon Princess

X2: Jersey and Guernsey is assumed to be Channel Islands

X3: MS Zaandam

## Data sources
* World Health Organization (WHO): https://www.who.int/ <br>
* DXY.cn. Pneumonia. 2020. http://3g.dxy.cn/newh5/view/pneumonia.  <br>
* BNO News: https://bnonews.com/index.php/2020/02/the-latest-coronavirus-cases/  <br>
* National Health Commission of the People’s Republic of China (NHC): <br>
 http://www.nhc.gov.cn/xcs/yqtb/list_gzbd.shtml <br>
* China CDC (CCDC): http://weekly.chinacdc.cn/news/TrackingtheEpidemic.htm <br>
* Hong Kong Department of Health: https://www.chp.gov.hk/en/features/102465.html <br>
* Macau Government: https://www.ssm.gov.mo/portal/ <br>
* Taiwan CDC: https://sites.google.com/cdc.gov.tw/2019ncov/taiwan?authuser=0 <br>
* US CDC: https://www.cdc.gov/coronavirus/2019-ncov/index.html <br>
* Government of Canada: https://www.canada.ca/en/public-health/services/diseases/coronavirus.html <br>
* Australia Government Department of Health: https://www.health.gov.au/news/coronavirus-update-at-a-glance <br>
* European Centre for Disease Prevention and Control (ECDC): https://www.ecdc.europa.eu/en/geographical-distribution-2019-ncov-cases 
* Ministry of Health Singapore (MOH): https://www.moh.gov.sg/covid-19
* Italy Ministry of Health: http://www.salute.gov.it/nuovocoronavirus
* Johns Hopkins CSSE: https://github.com/CSSEGISandData/COVID-19
