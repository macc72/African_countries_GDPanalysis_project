# African_countries_GDPanalysis_project

I fetched data from wikipedia ['here']([url](https://en.wikipedia.org/wiki/List_of_African_countries_by_GDP_(nominal))) and did some cleaning and filtering.

### Overview of the data obtained.
Type - table 
Number of columns - 5 -> Rank |	Country | Nominal GDP (million US$) | Population | Per capita (US$)
Number of rows - 55 (54 countries of Africa + Total)

After cleaning the data: 


<class 'pandas.core.frame.DataFrame'>

RangeIndex: 55 entries, 0 to 54

Data columns (total 5 columns):

Column                    Non-Null Count  Dtype \n

0   Rank                      55 non-null     object\n
1   Country                   55 non-null     object\n
2   Nominal GDP(million US$)  55 non-null     int64 \n
3   Population                55 non-null     int64 \n
4   Per capita(US$)           55 non-null     int64 \n
dtypes: int64(3), object(2) \n
memory usage: 2.3+ KB
