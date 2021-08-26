# Order of operation
- spider.py to crawl a web site and store pages linked to it into the database; recording link between pages. stores data in spider.sqlite
- spdump.py for cleaning data
- sprank.py to rank the pages. Assigns weights to pages based on number of links. Then ranks pages on the basis of those weights. Iterate it as much as you want.
- spdump.py for cleaning again
- spreset.py to restart the page rank calculations without re- spidering the wab pages.
- spjson.py to create  spider.js
