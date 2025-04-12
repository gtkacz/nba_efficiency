Inspired by [Hardwood Paroxysm's tweet](https://x.com/HPbasketball/status/1910709892169818573), I decided to do a slightly more in-depth analysis on the most efficient 30 PPG seasons in NBA history.

# Methodology

I decided to calculate all of the efficiency myself based off of raw total stats, as basketball-reference rounds all of their per-game statistics to 1 decimal place, affecting precision. So the process was: fetch the total stats for the season in question -> calculate each player's averages by stat/GP -> filter out non-qualified players -> calculate shooting efficiency.

To qualify, a player must:

1. Play in at least 58 games for the season.
2. Have an average of at least 20 MPG for the season.
3. Have an average of at least 29.5 PPG (rounded to one decimal place) for the season.

To calculate eFG% the formula is `((PTS - FT) / 2) / FGA`

To calculate TS% the formula is `(PTS) / (2 * (FGA + (0.44 * FTA)))`

To calculate their relative versions (reFG, rTS), it is the player's stat itself minus the league's average of the same stat. Meaning a rTS% of 5 is 5 percentual points above league average TS% for the season.

To calculate their adjusted versions (eFG+, TS+), it is the player's stat itself divided by the league's average of the same stat. Meaning a TS+% of 110 is 110% of the league average TS% for the season.

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

### Ranked by reFG%

|Player|Year|PTS|reFG%|
|:-|:-|-:|-:|
|Stephen Curry|2015-16|30.1|12.8|
|Kareem Abdul-Jabbar|1970-71|31.7|12.8|
|Kareem Abdul-Jabbar|1971-72|34.8|11.9|
|Wilt Chamberlain|1965-66|33.5|10.7|
|Kareem Abdul-Jabbar|1972-73|30.2|9.8|
|Shaquille O'Neal|1999-00|29.7|9.6|
|Wilt Chamberlain|1960-61|38.4|9.4|
|Walt Bellamy|1961-62|31.6|9.3|
|Wilt Chamberlain|1963-64|36.8|9.1|
|Bob McAdoo|1973-74|30.6|8.8|

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

### Ranked by rTS%

|Player|Year|PTS|rTS%|
|:-|:-|-:|-:|
|Stephen Curry|2015-16|30.1|12.8|
|Adrian Dantley|1983-84|30.6|10.9|
|Kareem Abdul-Jabbar|1970-71|31.7|10.6|
|Kareem Abdul-Jabbar|1971-72|34.8|9.9|
|Kevin Durant|2013-14|32|9.4|
|Jerry West|1964-65|31|9.3|
|Adrian Dantley|1981-82|30.3|9.2|
|Bob McAdoo|1973-74|30.6|9.1|
|Oscar Robertson|1963-64|31.4|9.1|
|Oscar Robertson|1966-67|30.5|9|

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

### Ranked by reFG%

|Player|Year|PTS/75|reFG%|
|:-|:-|-:|-:|
|Stephen Curry|2015-16|31.9|12.7|
|Shaquille O'Neal|1997-98|30.1|10.5|
|Nikola Jokić|2021-22|29.8|8.7|
|Shaquille O'Neal|1994-95|30|8.4|
|Karl Malone|1989-90|30.4|7.8|
|Giannis Antetokounmpo|2023-24|31.2|7.8|
|Giannis Antetokounmpo|2018-19|29.5|7.4|
|Stephen Curry|2020-21|33|6.8|
|Giannis Antetokounmpo|2024-25|32.3|6.5|
|Michael Jordan|1990-91|32|6.1|

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

### Ranked by rTS%

|Player|Year|PTS/75|rTS%|
|:-|:-|-:|-:|
|Stephen Curry|2015-16|31.9|12.8|
|Nikola Jokić|2021-22|29.8|9.4|
|Kevin Durant|2013-14|31.4|9.4|
|Karl Malone|1989-90|30.4|8.9|
|Giannis Antetokounmpo|2018-19|29.5|8.3|
|Stephen Curry|2020-21|33|8.3|
|Michael Jordan|1988-89|30|7.6|
|Joel Embiid|2022-23|35.6|7.5|
|Isaiah Thomas|2016-17|31.8|7.3|
|Michael Jordan|1990-91|32|7.1|

---

# Aggregations
Considering the average rank for each metric used, these are the most and least statistically efficient seasons ever:

### Per Game

|Player|Year|PTS|eFG%|TS%|eFG+%|TS+%|reFG%|rTS%|
|:-|:-|-:|-:|-:|-:|-:|-:|-:|
|Kareem Abdul-Jabbar|1971-72|34.8|57.4|60.3|126.2|119.6|11.9|9.9|
|Kareem Abdul-Jabbar|1970-71|31.7|57.7|60.6|128.5|121.2|12.8|10.6|
|Stephen Curry|2015-16|30.1|63|66.9|125.4|123.7|12.8|12.8|
|Stephen Curry|2020-21|32|60.5|65.5|112.5|114.5|6.7|8.3|
|Kevin Durant|2013-14|32|56|63.5|111.7|117.3|5.9|9.4|
|Karl Malone|1989-90|31|56.7|62.6|115.9|116.6|7.8|8.9|
|Adrian Dantley|1983-84|30.6|55.8|65.2|112.7|120.1|6.3|10.9|
|Adrian Dantley|1981-82|30.3|57|63.1|115.2|117.1|7.5|9.2|
|Nikola Jokić|2024-25|29.8|62.5|66.3|115.2|115|8.2|8.7|
|Bob McAdoo|1973-74|30.6|54.7|59.4|119.2|118.2|8.8|9.1|

|Player|Year|PTS|eFG%|TS%|eFG+%|TS+%|reFG%|rTS%|
|:-|:-|-:|-:|-:|-:|-:|-:|-:|
|Jerry Stackhouse|2000-01|29.8|44.5|52.1|94|100.6|-2.8|0.3|
|Allen Iverson|2001-02|31.4|42.2|48.9|88.4|94|-5.5|-3.1|
|Pete Maravich|1976-77|31.1|43.3|49.2|93.1|96.2|-3.2|-1.9|
|Dominique Wilkins|1985-86|30.3|47.2|53.6|95.6|99.1|-2.1|-0.5|
|Allen Iverson|2000-01|31.1|44.7|51.8|94.6|100|-2.6|0|
|Allen Iverson|2004-05|30.7|45.3|53.2|93.9|100.6|-2.9|0.3|
|Dominique Wilkins|1987-88|30.7|47.4|53.4|97|99.2|-1.5|-0.4|
|Elgin Baylor|1959-60|29.6|42.4|48.9|103.4|105.7|1.4|2.6|
|World B. Free|1979-80|30.2|47.7|54.4|98.1|102.4|-0.9|1.3|
|Rick Barry|1974-75|30.6|46.4|50.9|101.5|101.3|0.7|0.7|

### Per 75 Possessions

|Player|Year|PTS/75|eFG%|TS%|eFG+%|TS+%|reFG%|rTS%|
|:-|:-|-:|-:|-:|-:|-:|-:|-:|
|Stephen Curry|2015-16|31.9|62.9|66.9|125.4|123.6|12.7|12.8|
|Stephen Curry|2020-21|33|60.6|65.5|112.6|114.5|6.8|8.3|
|Nikola Jokić|2021-22|29.8|61.9|66|116.4|116.5|8.7|9.4|
|Giannis Antetokounmpo|2023-24|31.2|62.5|65|114.3|112|7.8|7|
|Joel Embiid|2022-23|35.6|57.5|65.6|105.4|112.8|3|7.5|
|Karl Malone|1989-90|30.4|56.7|62.6|116|116.6|7.8|8.9|
|Kevin Durant|2013-14|31.4|56.1|63.5|111.9|117.4|6|9.4|
|Giannis Antetokounmpo|2021-22|32.7|58.1|63.3|109.2|111.8|4.9|6.7|
|Giannis Antetokounmpo|2018-19|29.5|59.8|64.3|114|114.9|7.4|8.3|
|Michael Jordan|1990-91|32|54.8|60.5|112.5|113.3|6.1|7.1|

|Player|Year|PTS/75|eFG%|TS%|eFG+%|TS+%|reFG%|rTS%|
|:-|:-|-:|-:|-:|-:|-:|-:|-:|
|Allen Iverson|2000-01|29.5|44.9|51.9|94.9|100.3|-2.4|0.1|
|Allen Iverson|2005-06|29.8|46.7|54.4|95.3|101.5|-2.3|0.8|
|Russell Westbrook|2014-15|30.8|45.6|53.7|92|100.6|-4|0.3|
|Dominique Wilkins|1987-88|30.4|47.4|53.3|97|99.1|-1.5|-0.5|
|Kobe Bryant|2010-11|29.7|48.7|54.9|97.8|101.4|-1.1|0.8|
|DeMarcus Cousins|2016-17|29.7|49.8|56.3|96.9|101.9|-1.6|1.1|
|Michael Jordan|1997-98|30|47.4|53.4|99.1|101.9|-0.4|1|
|Russell Westbrook|2016-17|33.6|47.6|55.4|92.7|100.3|-3.8|0.2|
|Luka Dončić|2021-22|30.3|52.8|57|99.2|100.8|-0.4|0.4|
|Bradley Beal|2020-21|30.2|53|59.2|98.6|103.4|-0.8|2|

---

# Artefacts

A complete sheet of all qualified seasons can be found at: [https://docs.google.com/spreadsheets/d/1DOhIu3i5gV1NQwAZc6rbBl7qU6NhloBr/edit?usp=sharing&ouid=114071196241084372453&rtpof=true&sd=true](https://docs.google.com/spreadsheets/d/1DOhIu3i5gV1NQwAZc6rbBl7qU6NhloBr/edit?usp=sharing&ouid=114071196241084372453&rtpof=true&sd=true)