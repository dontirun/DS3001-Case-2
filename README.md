DS3001: Case Study 02
=====================

Team:
* [Arun Donti](https://github.com/dontirun)
* [Arthur Dooner](https://github.com/Shunderpooch/)
* [Jack Mercer](https://github.com/mercer-j)
* [Aditya Nivarthi](https://github.com/SIZMW)

## Description
This project demonstrates analyzing tweets from trending topics of Twitter for user sentiments towards those topics, across regions of the world.

## Building
This project requires the following packages:
* `twitter`: Install with `pip install twitter`
* `basemap`: Download [here](https://sourceforge.net/projects/matplotlib/files/matplotlib-toolkits/basemap-1.0.7/)
* `prettytable`: Install with `pip install prettytable`
* `matplotlib`: Install with `pip install matplotlib`

## Execution
The notebook `case2.ipynb` can be executed top to bottom to produce our results and visualizations.

The existing `Results.json` file is used to load the data. To load the data again from Twitter, enable the flag `retrieve_new_tweets` in the *Data Collection* block. This will attempt to download 10,000 tweets.

## Potential issues

With some systems, colors are repeated for visualizations such as the the histograms and map chart.
This is not the case with most systems, the cause of the issue is currently unknown. 