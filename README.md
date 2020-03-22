# Lyrics Corpora

There is a documents folder which describes the structure and management. There is data folder which has the JSON files. 

Why Lyrics "Corpora"? In latin the III declination of -us is -ora in nominative in this ["corpus" case](http://latindictionary.wikidot.com/noun:corpus). I am pulling from multiple sources, not just one.

There might be a frontend someday if this thing-y thing seems even remotely useful and working (hint: what is optimization?)
## This will be updated later on.

To my knowledge there exists no similar if you take out the question of a google search "[name_of_the_song] lyrics"

[Example](https://www.google.com/search?client=firefox-b-d&q=remember+the+name+lyrics)

Why? I'll add one crucial thing: highlighting and seeing similar songs.

Right now you can do [this too](https://www.google.com/search?client=firefox-b-d&q=back+when+mark+walberg+was+lyrics)
But there is no highlighting and similar songs.

Edit: I've seen it before but it simply does not work all of the times. There is something like [](https://www.google.com/search?client=firefox-b-d&q=t%C3%A4%C3%A4+kaikki+tuntuu+ilman+rakkautta&oq=t%C3%A4%C3%A4+kaikki+tuntuu+ilman+rakkautta every now and then. Trick is to do it without adding "[...] lyrics".

Now I am rethinking why I'm doing this. 

## Installation
Will be added later.
You will be needing python 3.6 and git installed!
```
git clone https://github.com/avhalo/lyrco.git
cd lyrco
python ./main.py [args]
```

### Requirements
Will bea added later. Install pip3 or pip
```
pip install [stuff]
```

### Pull requests:

Option 1: https://github.com/avhalo/lyrco/pulls

Option 2: Do your own branch and I'll check it. Post it [here](https://github.com/avhalo/lyrco/issues)

*ALL REQUESTS ARE WELCOME* Especielly one with better optimization, better styling code (_under debate naturally_), and better structure. Even typofixes are welcome. If you spot an error, report it.


### Future:
Use ML to do stuff. One thing I can think of is to set the lyrics in a NLP based DL library (TF ofc) and set the syllables as a paremeter (wiktionary helps) and creat rap-eti-rap song or other random lyrics. If it really works (it won't) I'll make it genre-specific (hardcore indie) and term-specific (love songs, songs mentioning "bitch"). Shits complicated. And I am not a ml engineer.

More simple would be to link to a youtube-video (will be proably done via search). The name of the songs will be mentioned. However. For now it will be a terminal based so I am thinking wheter there will be links to specific artists and their songs. Could see that happening. Would need to modify some parts. Will edit this later if this feature will be impelemnted.

Google could have a implemented embedding of youtube songs (or Google Music) with their lyrics. That is: they have extremely (? Don't know current status) good audio-to-text enginge so that at the same time you could do little karaoke. Note: will not be implemented in this little extremely small and probably time-complexity hungry pick-and-mix (shitty construct, kyhäelmä/väsäys).

### MAJOR PROBLEM

I won't go in depth at all but there is thing called licensing. How something like lyricfind.com avoids this? They don't. at least if you compare the results of above mentioned examples. There is no author or who the lyrics belong to (as in members of the band). There is a mention of who is the artist. However, If you look up "imdb corpus" you'll see also that there are no writers mentioned, just the movies. How the whole business runs is by deceiving. That's what I'm implementing.  It is considered what the euphemism level after the fact that for some song mixture on youtube which even list the authors and licensees.

## Also

There is github lyrics corpora. I just don't like it. It is not fully featured but neither will this be. 