# Linux files management #

## Description ##
Examples of linux files management

## Examples ##
~~~
1.- Header of csv
head -1 mlb_players.csv

2.- Count lines of csv
wc -l mlb_players.csv

3.- Check 50th row
head -50 mlb_players.csv | tail -1

4.- Check duplicate rows
uniq -d mlb_players.csv

5.- Remove duplicate rows
uniq -u mlb_players.csv > mlb_players_uniq.csv

6.- Sort by Age ascending (show 10)
sort -n -t',' -k6 mlb_players.csv | head -10

7.- Sort by Age descending (show 10)
sort -n -t',' -k6 -r mlb_players.csv | head -10

8.- Show number of columns
awk -F "," '{print NF}' mlb_players.csv | head -1
~~~

P.D. Let's go play !!!
