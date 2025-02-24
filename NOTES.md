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