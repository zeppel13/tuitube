# tuitube
minimal tui youtube (invidious) frontend made in c++

Very much still a work in progress. Build with cmake. Dependancies:
- youtube-dl
- mpv
- curlpp

What's working:
- Subscriptions page
- Opening videos
- Searching for videos

What's planned:
- Popular / trending page
- Include channel results in search
- Browsing channels
- Suggested videos
- An easier way to add subscriptions

How to add subscriptions:
The file is at "~/.config/tuitube_subs", add as "{channel id / name}" from the channel url, with one per line. To use, run the binary file after building and press "r" to refresh the subscriptions.

![Screenshot](https://github.com/djt3/tuitube/blob/master/tuitube.png?raw=true)
