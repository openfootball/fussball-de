# Internationals

A mirror of the [International football results from 1872 to 2024](https://github.com/martj42/international_results)
dataset by Mart Jürisoo
using the Football.TXT format.

> This dataset includes 47,960 results of international football matches starting from the very first official match in 1872 up to 2024. 
> The matches range from FIFA World Cup to FIFI Wild Cup to regular friendly matches. 
> The matches are strictly men's full internationals and the data does not include Olympic Games or matches where at least one of the teams was the nation's B-team, U-23 or a league select team.




Tip - You can use the [`fbtxt2json` command-line tool](https://github.com/sportdb/footty/tree/master/fbtxt2json) to convert any file in the Football.TXT format to JSON. 

Let's try to convert the FIFI Wild Cup 2006
in the Football.TXT format (see [`fifi_wild_cup/2006_fifi_wild_cup.txt`](https://github.com/openfootball/internationals/blob/master/fifi_wild_cup/2006_fifi_wild_cup.txt)) to JSON:

```
$ fbtxt2json internationals/fifi_wild_cup/2006_fifi-wild_cup.txt -o wild_cup.json
```



