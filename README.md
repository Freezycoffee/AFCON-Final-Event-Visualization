### This Repository created using open data from [Statsbomb](http://https://statsbomb.com/news/statsbomb-release-free-2023-african-cup-of-nations-data/ "Statsbomb") AFCON 2023


#### Open Data StatsBomb
We can use [mplsoccer](http://https://mplsoccer.readthedocs.io/en/latest/mplsoccer.statsbomb.html "mplsoccer") package to access the dataset.

```python
!pip install mplsoccer #If  you haven't installed it yet

from mplsoccer import Sbopen

#See the list of matches available
parser = Sbopen()
matches = parser.match(competition_id=1267,season_id=107) # this for AFCON 2023

# For the event data
events, related, freeze, tactics = parser.event(match_id=)
```
