Jackett
======

About
-----

Jackett works as a proxy server: it translates queries from apps (Sonarr, Radarr, SickRage, CouchPotato, Mylar, DuckieTV, etc) into tracker-site-specific http queries, parses the html response, then sends results back to the requesting software. This allows for getting recent uploads (like RSS) and performing searches. Jackett is a single repository of maintained indexer scraping & translation logic - removing the burden from other apps.

Install
-------

Just execute below code to install.

`wget https://raw.githubusercontent.com/thelastofus/pirates-mediaserver-2021/master/jackett/jackett-install.sh -O - -o /dev/null|bash`


Update
------

DOES NOT WORK - FETCHING WITH JACKETT FUCKED. 
