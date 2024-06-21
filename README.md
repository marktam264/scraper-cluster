# Scraper Cluster

A web scraper that runs in a k8s cluster.

This will have 4 scrapers and a process which will take scraper data and create a word frequency entry that is stored in a PostgresSQL database. It will also have a viewer for the database that the user can use.
