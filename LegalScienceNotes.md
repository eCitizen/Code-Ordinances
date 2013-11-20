Notes from a Computational Legal Science perspective on this project:

See this API as a possibility: http://statedecoded.github.io/documentation/api.html

Consider creating a local schema via a meta-data file, using the following API data type:
metadata	array, or null	Contains all metadata about this law that is stored separately in the metadata table.	By default, this contains nothing, but any State Decoded implementation that wants to store additional metadata about laws—data beyond the structure otherwise described here—would emit that metadata here.

Some key items for meta data are:
People
Place
Time
Topic
Authoritative Source


Consider including links in the Open Data Socrata site to the GitHub laws (this repo) and also from the laws/ordinances TO the referenced health inspection API results...!


YELP LIVES Health standards http://www.yelp.com/healthscores
