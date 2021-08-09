# ATP Ranking Singles

The ATP Rankings are the Association of Tennis Professionals' (ATP) merit-based method for determining the rankings in men's tennis. The top-ranked player is the player who, over the previous 52 weeks, has garnered the most ranking points on the ATP Tour. Points are awarded based on how far a player advances in tournaments and the category of those tournaments.
(based on: [Wikipedia](https://en.wikipedia.org/wiki/List_of_ATP_number_1_ranked_singles_tennis_players))

ATP Ranking is updated every Monday.

## Data
CSV file contains rankings for each tennis player since 1973/08/23 till 2021/08/02 (ordered by the ranking's week descending).

File contains the following columns:
```python
['Date', 'Ranking', 'Move', 'Country', 'Player', 'Age', 'Points', 'Tourn Played', 'Points Dropping', 'Next Best']
```
The data comes from the [ATP website](https://www.atptour.com/en/rankings/singles)

## Get the data
For **Python** or **R** you can use the code snippets below:

### R:
```r
df <- readr::read_csv('https://github.com/jpawlata/ATP_Ranking/blob/main/data/atp_ranking,csv')
```

### Python:
```python
import pandas as pd
df = pd.read_csv('https://github.com/jpawlata/ATP_Ranking/blob/main/data/atp_ranking,csv')
```

## Update
If you need an up to date data file, feel free to run the script.
It takes some time to finish so... you need to be patient :)

## Run the script
To run the script I use Google Colab. gdrive.ipynb file allows to mount your Google Drive into the Colab environment.

If you want to run the script using Google Colab - just copy all the cells from the gdrive.ipynb at the top of the atp_scraper.ipynb file and add your project folder's name instead of 'YOUR-FOLDER' placeholder.

## License
MIT