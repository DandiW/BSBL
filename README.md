BSBL: BASEBALL SIGNINGS BETWEEN LEAGUES
Data Visualization project
Please visit: http://www.dandiw.com/#/bsbl/ for detail information


MOTIVATION:

Spring Training
Lot of Trades now

MAIN PROBLEM:

Is there a correlation between the World Series winner and trades?

TOOLS:

MLB API (Dataset of teams)
D3.js
SQLite and Flask
Web Server (open to public)



**Development Guide:**

1. Install Pip. You'll need this if you ever use Python. https://pip.pypa.io/en/stable/installing/
2. Run pip install -r requirements.txt
3. Run python runserver.py
4. Navigate to http://127.0.0.1:9001/

Everything else should get setup automatically!

API Guide:
```
/api/{year}
```
gives a list of all the trades for a year as a csv
