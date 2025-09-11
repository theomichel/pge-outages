# pge-outages

This repository is a fork of simonw's [original PG&E outages scraper](https://github.com/simonw/pge-outages). It tracks outages reported on the [PG&E outages map](https://pgealerts.alerts.pge.com/outage-tools/outage-map/) over time, using [Git scraping](https://simonwillison.net/2020/Oct/9/git-scraping/).

The difference between this fork and the original is that this one accesses a different dataset from the PG&E GIS server, which should offer a more complete picture of outages. See here for more info on why: https://github.com/simonw/pge-outages/issues/4#issuecomment-1928758853. 

This repository started tracking outages using the new dataset on August 25th, 2025 into the file "pge-events.jso". Use that file for the new data and format. Outages.json is the original data from the parent repository.
