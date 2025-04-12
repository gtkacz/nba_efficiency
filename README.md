Inspired by [Hardwood Paroxysm's tweet](https://x.com/HPbasketball/status/1910709892169818573), I decided to do a slightly more in-depth analysis on the most efficient 30 PPG seasons in NBA history.

# Methodology

I decided to calculate all of the efficiency myself based off of raw total stats, as basketball-reference rounds all of their per-game statistics to 1 decimal place, affecting precision. So the process was: fetch the total stats for the season in question -> calculate each player's averages by stat/GP -> filter out non-qualified players -> calculate shooting efficiency.

To qualify, a player must:

1. Play in at least 58 games for the season.
2. Have an average of at least 20 MPG for the season.
3. Have an average of at least 29.5 PPG (rounded to one decimal place) for the season.

To calculate eFG% the formula is `((PTS - FT) / 2) / FGA`

To calculate TS% the formula is `(PTS) / (2 * (FGA + (0.44 * FTA)))`

To calculate their relative versions, it is the player's stat itself divided by the league's average of the same stat.

Per Game data goes back to the 1951-52 season. Per 75 Possessions data goes back to the 1973-74 season.

All data belongs to Sports Reference and was fetched and used in compliance with their Terms of Use.

# Results

## Per Game

### Ranked by eFG%

|Player|Year|PTS|eFG%|
|:-|:-|-:|-:|
|Stephen Curry|2015-16|30.1|63|
|Nikola Jokić|2024-25|29.8|62.5|
|Giannis Antetokounmpo|2023-24|30.4|62.4|
|Giannis Antetokounmpo|2024-25|30.4|60.8|
|Stephen Curry|2020-21|32|60.5|
|Giannis Antetokounmpo|2019-20|29.5|58.9|
|Giannis Antetokounmpo|2021-22|29.9|58.2|
|Kareem Abdul-Jabbar|1970-71|31.7|57.7|
|Shaquille O'Neal|1999-00|29.7|57.4|
|Kareem Abdul-Jabbar|1971-72|34.8|57.4|

### Ranked by eFG+%

|Player|Year|PTS|eFG+%|
|:-|:-|-:|-:|
|Kareem Abdul-Jabbar|1970-71|31.7|128.5|
|Kareem Abdul-Jabbar|1971-72|34.8|126.2|
|Stephen Curry|2015-16|30.1|125.4|
|Wilt Chamberlain|1965-66|33.5|124.6|
|Wilt Chamberlain|1960-61|38.4|122.7|
|Walt Bellamy|1961-62|31.6|121.8|
|Kareem Abdul-Jabbar|1972-73|30.2|121.5|
|Wilt Chamberlain|1963-64|36.8|121|
|Shaquille O'Neal|1999-00|29.7|120.1|
|Wilt Chamberlain|1964-65|34.7|119.8|

### Ranked by TS%

|Player|Year|PTS|TS%|
|:-|:-|-:|-:|
|Stephen Curry|2015-16|30.1|66.9|
|Nikola Jokić|2024-25|29.8|66.3|
|Joel Embiid|2022-23|33.1|65.5|
|Stephen Curry|2020-21|32|65.5|
|Adrian Dantley|1983-84|30.6|65.2|
|Giannis Antetokounmpo|2023-24|30.4|64.9|
|Shai Gilgeous-Alexander|2024-25|32.7|63.7|
|Shai Gilgeous-Alexander|2023-24|30.1|63.6|
|Kevin Durant|2013-14|32|63.5|
|Giannis Antetokounmpo|2021-22|29.9|63.3|

### Ranked by TS+%

|Player|Year|PTS|TS+%|
|:-|:-|-:|-:|
|Stephen Curry|2015-16|30.1|123.7|
|Kareem Abdul-Jabbar|1970-71|31.7|121.2|
|Adrian Dantley|1983-84|30.6|120.1|
|Kareem Abdul-Jabbar|1971-72|34.8|119.6|
|Jerry West|1964-65|31|119.5|
|Oscar Robertson|1963-64|31.4|118.8|
|Oscar Robertson|1960-61|30.5|118.4|
|Bob McAdoo|1973-74|30.6|118.2|
|Oscar Robertson|1966-67|30.5|118.2|
|Jerry West|1965-66|31.3|117.6|

## Per 75 Possessions

### Ranked by eFG%

|Player|Year|PTS/75|eFG%|
|:-|:-|-:|-:|
|Stephen Curry|2015-16|31.9|62.9|
|Giannis Antetokounmpo|2023-24|31.2|62.5|
|Nikola Jokić|2021-22|29.8|61.9|
|Giannis Antetokounmpo|2024-25|32.3|60.8|
|Stephen Curry|2020-21|33|60.6|
|Giannis Antetokounmpo|2020-21|30.1|59.9|
|Giannis Antetokounmpo|2018-19|29.5|59.8|
|Giannis Antetokounmpo|2019-20|33.2|58.8|
|Shaquille O'Neal|1994-95|30|58.4|
|Shaquille O'Neal|1997-98|30.1|58.3|

### Ranked by eFG+%

|Player|Year|PTS/75|eFG+%|
|:-|:-|-:|-:|
|Stephen Curry|2015-16|31.9|125.4|
|Shaquille O'Neal|1997-98|30.1|122|
|Shaquille O'Neal|1994-95|30|116.7|
|Nikola Jokić|2021-22|29.8|116.4|
|Karl Malone|1989-90|30.4|116|
|Giannis Antetokounmpo|2023-24|31.2|114.3|
|Giannis Antetokounmpo|2018-19|29.5|114|
|Stephen Curry|2020-21|33|112.6|
|Michael Jordan|1990-91|32|112.5|
|Michael Jordan|1989-90|32|112.3|

### Ranked by TS%

|Player|Year|PTS/75|TS%|
|:-|:-|-:|-:|
|Stephen Curry|2015-16|31.9|66.9|
|Nikola Jokić|2021-22|29.8|66|
|Joel Embiid|2022-23|35.6|65.6|
|Stephen Curry|2020-21|33|65.5|
|Giannis Antetokounmpo|2023-24|31.2|65|
|Giannis Antetokounmpo|2018-19|29.5|64.3|
|Shai Gilgeous-Alexander|2024-25|34.4|63.7|
|Shai Gilgeous-Alexander|2023-24|31.8|63.5|
|Kevin Durant|2013-14|31.4|63.5|
|Giannis Antetokounmpo|2020-21|30.1|63.3|

### Ranked by TS+%

|Player|Year|PTS/75|TS+%|
|:-|:-|-:|-:|
|Stephen Curry|2015-16|31.9|123.6|
|Kevin Durant|2013-14|31.4|117.4|
|Karl Malone|1989-90|30.4|116.6|
|Nikola Jokić|2021-22|29.8|116.5|
|Giannis Antetokounmpo|2018-19|29.5|114.9|
|Stephen Curry|2020-21|33|114.5|
|Michael Jordan|1988-89|30|114.2|
|Michael Jordan|1990-91|32|113.3|
|Isaiah Thomas|2016-17|31.8|113.3|
|Joel Embiid|2022-23|35.6|112.8|
