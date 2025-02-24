# Notes


- [ ] how to deal with goals with N/A minutes?
      - for now gets changed to `??'` - why? why not?

- [ ] how to deal with goals with missing scorer (player name)?
       - (report) upstream error?

```
!! WARN - (goals) scorer empty:
{"date"=>"1980-09-23",
 "home_team"=>"Malaysia",
 "away_team"=>"Qatar",
 "team"=>"Qatar",
 "scorer"=>nil,
 "minute"=>"52",
 "own_goal"=>"FALSE",
 "penalty"=>"FALSE"}

!! WARN - (goals) scorer empty:
{"date"=>"1980-02-29",
 "home_team"=>"Fiji",
 "away_team"=>"Tahiti",
 "team"=>"Tahiti",
 "scorer"=>nil,
 "minute"=>nil,
 "own_goal"=>"FALSE",
 "penalty"=>"FALSE"}

!! WARN - (goals) scorer empty:
{"date"=>"1980-02-29",
 "home_team"=>"Fiji",
 "away_team"=>"Tahiti",
 "team"=>"Tahiti",
 "scorer"=>nil,
 "minute"=>nil,
 "own_goal"=>"FALSE",
 "penalty"=>"FALSE"} 

 !! WARN - (goals) scorer empty:
{"date"=>"1980-02-28",
 "home_team"=>"New Caledonia",
 "away_team"=>"Papua New Guinea",
 "team"=>"New Caledonia",
 "scorer"=>nil,
 "minute"=>nil,
 "own_goal"=>"FALSE",
 "penalty"=>"FALSE"}
```


## todos

- [ ] check the country names 
      - use the old names or the canonical names?

```
current,former,start_date,end_date
Benin,Dahomey,1959-11-08,1975-11-30
Burkina Faso,Upper Volta,1960-04-14,1984-08-04
Curaçao,Netherlands Antilles,1957-03-03,2010-10-10
Czechoslovakia,Bohemia,1903-04-05,1919-01-01
Czechoslovakia,Bohemia and Moravia,1939-01-01,1940-01-01
DR Congo,Belgian Congo,1948-05-25,1956-01-02
DR Congo,Congo-Léopoldville,1963-04-12,1964-07-19
DR Congo,Congo-Kinshasa,1965-01-09,1970-11-24
DR Congo,Zaïre,1971-01-10,1997-04-27
Djibouti,French Somaliland,1947-12-05,1977-06-27
Eswatini,Swaziland,1968-05-01,2018-04-19
Ghana,Gold Coast,1950-05-28,1957-03-06
Guinea-Bissau,Portuguese Guinea,1953-06-02,1973-09-24
Guyana,British Guiana,1905-07-21,1967-08-02
Israel,Mandatory Palestine,1934-03-16,1940-04-27
Malawi,Nyasaland,1957-08-28,1964-07-04
Malaysia,Malaya,1948-06-20,1963-08-16
Myanmar,Burma,1952-03-14,1989-01-01
Northern Ireland,Ireland,1882-02-18,1956-04-11
Republic of Ireland,Irish Free State,1924-05-28,1936-12-06
Republic of Ireland,Éire,1937-01-01,1953-03-25
Russia,Soviet Union,1924-11-16,1991-11-13
Russia,CIS,1992-01-25,1992-06-18
Samoa,Western Samoa,1979-08-31,1996-11-15
Sri Lanka,Ceylon,1952-03-24,1972-05-22
Suriname,Dutch Guyana,1921-01-28,1975-11-25
Tanzania,Tanganyika,1945-01-01,1964-04-26
Vanuatu,New Hebrides,1951-10-04,1980-07-30
Zambia,Northern Rhodesia,1947-02-22,1964-10-25
Zimbabwe,Southern Rhodesia,1946-06-16,1980-04-18
```

