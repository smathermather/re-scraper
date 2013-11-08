re-scraper
==========

re-scraper is a simple web page which allows for search string redirect of parcel number to Cuyahoga County Fiscal Officer Real Estate web site.

Historically (nearly 5 years ago), parcels on the Cuyahoga County Fiscal Officer Real Estate web site could be directly accessed using HTTP GET, e.g. http://fiscalofficer.cuyahogacounty.us/AuditorApps/real-property/REPI/general.asp?12345678.  This was useful as it made direct hyperlinking and scraping easy.  Since that time, a POST has been necessary.

This small web page now allows one to GET parcel pages directly by performing the POST request from the location.search portion of the address string.

### Example

http://69.54.58.147/?11213076

###### BTW, this probably doesn't qualify as a scraper...
