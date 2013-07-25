Dynasty League Free Agent Scraper
=================================

nfl(.py) solves a problem I encontered when participating in a 32 team NFL Dynasty Fantasy Football league.
The issue was that because the player pool penetration was so deep (with 32 teams there are very few players that do not get drafted from actual NFL rosters) I was having trouble keeping track of which players, among those still remaining, I should draft. My problem was compounded by the fact that due to the vagaries of the slow draft leage setup and a week of vacation, I was 17 picks behind the other owners and needed to make a slew of picks all at once.

Features
--------

* Scrapes myfantasyleague.com freeagent pages and returns a list of players
* Matches available players to a list of projections and outputs a list of players
* Assuming our projections are listed in decending order by value, output will reflect this
* Output is grepable by position for quick and dirty filtering. e.g. "nfl | grep CB" will list all available cornerbacks.

Dependencies
------------

* requests
* BeautifulSoup

The script assumes that you already have a set of projections loaded into a sqlite database. It further assumes you are using myfanstasyleague.com as your provider.

License
--------
WTFPL v. 2.0