# amfromBot
The PlotBot is a twitter bot that does sentimental analysis on the search #amfromBot @<search_user>.

The Bot searches every 5 minutes, for a tweet with #amfromBot. If a new tweet found, it will do sentimental Analysis on the tweets from that user.

# instructions
Download Python and conda from the links given below
### Python

mac : Goto https://www.python.org/downloads/ and download latest version

windows : Goto https://www.python.org/downloads/windows/ and download latest version

### conda
mac : Goto https://conda.io/docs/user-guide/install/macos.html follow directions

windows : Goto https://conda.io/docs/user-guide/install/windows.html follow directions

#### Remember to add to PATH variable during installiation
To verify goto (Terminal/GitBash) and type `conda -V` or `conda list`.

#### Create conda environment

`conda create -n PythonData python=3.6 anaconda` 

`source activate PythonData`

`python --version`

### Fork the repo and clone to remote

### Api
Create api keys from  https://apps.twitter.com - Twitter

### Do the following in git(windows)/terminal(mac)

`source activate PythonData`

`pip install tweepy`

#### vader- sentiment analysis

`source activate PythonData`

`pip install vaderSentiment==2.5`

if it doesn't work try creating a new conda env:

`conda create -n newPythonData python=3.6 anaconda` 

`source activate PythonData`

`pip install vaderSentiment==2.5`
`jupyter notebook`

open PlotBot.ipynb in jupyter notebook and enter the twitter credentials. 
You can change botname by specifying in #<botname>

The counter can be set infinitely by   `while(True)`

I have retrived only past 100 tweets, can increase the value.




