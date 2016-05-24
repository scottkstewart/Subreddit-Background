# Subreddit-Background

Fun little script to set the background of any unix system (using feh) to a random submission on the frontpage of a particular subreddit, based on arguments when called command-line. Best when coupled with cron for a continually changing background. For example, the following may be a good line to add to one's crontab to refresh the background hourly:
```
0 * * * * /path/to/file/SetBackground guineapigs
```

Done in python3 with a dependency on feh and BeautifulSoup 4. By Scott Stewart.
