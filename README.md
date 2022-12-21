# sdge-outages

Tracking outage data from [https://www.sdge.com/residential/customer-service/outage-center/outage-map](https://www.sdge.com/residential/customer-service/outage-center/outage-map 'outage map').

Git Scraping experiment based upon the talk by [Simon Willison](https://simonwillison.net/2021/Mar/5/git-scraping/ 'Git scraping, the five minute lightning talk').\
I was looking to test the use of [Github Actions](https://www.actionsbyexample.com/ 'GitHub Actions by Example') and learn about the .yml file architecture.\
The scape.yml file is from [Simon Willison's code here](https://github.com/simonw/ca-fires-history/blob/main/.github/workflows/scrape.yml 'scrape.yml') and slightly changed to fit this repo.

SDGE JSON data pulled from: [Outage Map](https://www.sdge.com/residential/customer-service/outage-center/outage-map-locations-json 'scrape.yml').

Future ToDo: [Graph Map Coords with KepplerGl](https://twitter.com/simonw/status/1188612640651661312?s=20&t=DuF6xgum6JauRPpgEu_nFw)

NOTE: scrape.yml contains the daemon to control scrape time every four hours at the 37th minute.
