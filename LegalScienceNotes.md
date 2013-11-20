Notes from a Computational Legal Science perspective on this project:

See this API as a possibility: http://statedecoded.github.io/documentation/api.html

Consider creating a local schema via a meta-data file, using the following API data type:
metadata	array, or null	Contains all metadata about this law that is stored separately in the metadata table.	By default, this contains nothing, but any State Decoded implementation that wants to store additional metadata about laws—data beyond the structure otherwise described here—would emit that metadata here.
