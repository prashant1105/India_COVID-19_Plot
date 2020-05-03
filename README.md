# India_COVID-19_Plot
The Jupyter Notebook includes plotting of number of cases of Corona Virus in every state of India.

DataSet Used: covid19-india-datasets
DataSet Link: https://storage.googleapis.com/kaggle-data-sets/592389/1083801/bundle/archive.zip?GoogleAccessId=web-data@kaggle-161607.iam.gserviceaccount.com&Expires=1588651173&Signature=JCedqDs%2FTDr%2FGI38xjylHVmJwsk5B3bDKp%2FRotQAX3uVisGYAo9%2FOqPSt79f1OPfzOcZU0BcuDzevgtFMDVAZu1%2FCVwp4kQ%2FNCaawEft3%2Fpva41FSilhekjzVL%2Fwe1cScbRkvDrq%2BKzcB45D94I1nk3pij2fIorkNan1oL%2BB4WE5uN%2B%2BOZsS8TQ8XPJNWSV2SqQnjINiSjefjvZgk5ItULGUke01GoJ1OnDp1doYGGkQsyfztt5MVd4fDwYPoRVvRrUq5rMblMkscaUd9V4rQQseytKivlfCT3RZq3mku%2FYfycnCiQO6Hj4xv%2BR195IU2CXIyzSO33%2B%2FmIrSJITYNA%3D%3D&response-content-disposition=attachment%3B+filename%3Dcovid19-india-datasets.zip

Libraries Used:
  numpy for Math related Operations (very less used)
  pandas for DataFrame and reading the DatasEt.
  Folium: for creating Maps of India and plotting number of current cases against each state.
    Folium is a powerful Python library that helps us to create several types of Leaflet maps. The fact that the Folium           results are interactive makes this library is very useful for dashboard building.
  requests: for getting the data from the URL.
  urllib.request
  BeautifulSoup: for Scraping the data from Google News page about COVID-19 cases and transforming it to Pandas Dataframe
  Matplotlib
  Seaborn: For creating Piechart and Histograms.

DataSet Columns:
  Name of State / UT : This column includes the names of the State or Union Territories of India. (Most Important)***
  Total Confirmed cases (Including 76 foreign Nationals) : This contains the total confirmed cases of COVID-19 in India on a particular date.
  Cured/Discharged/Migrated : This contains the number of cured or migrated or discharged cases for each state.
  Death : Number of deaths in a state.
  Date : Date for which the cases were recorded in the dataset.
  Latitude : Latitude of each state or Union Territory of India. (Most Important)***
  Longitude : Longitude of each state or Union Territory of India. (Most Important)***
  Total cases : Total number of cases so far.

*** From the dataset I have used only 3 columns namely, 'Name of State / UT', 'Latitude', 'Longitude'.
For number of cases I have used the Google News statistics with source being Wikipedia.
Link of Source: https://news.google.com/covid19/map?hl=en-IN&gl=IN&ceid=IN%3Aen&mid=%2Fm%2F03rk0
