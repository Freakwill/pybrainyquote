# PyBrainyquote


Get quotes from brainyquote. Make you life positive. It is more powerful then [viveksb007/pybrainyquote](https://github.com/viveksb007/pybrainyquote)

Requirements
-------------

requests
bs4
furl


Download
---------

`pip install pybrainyquote`


Why
--------

The original one `brainyquote` is too simple. 


Grammar
--------
    
Import

    from pybrainyquote import *

Get quotes

    Quote.today(topic=what you like) # get today topic
    get_popular_topics() # have a look at the lists popular topics, if you do not have any idea
    get_topics()
    get_authors()

    Quote.find_all(topic)     # just try the following
    Quote.find(topic)
    Quote.find(topic)

Future
-------
Define a search engine for quotes, and a method to get one quote randomly. (Completed partly)
