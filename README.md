Techism Data
============

This repository contains the techism data (tech events and user groups in Munich) from 2008 to 2017.

File `techism-data.dump` contains a dump of the PostgreSQL database. Only previously public data (events, tags, locations, organizations) is included, internal data like users was removed. Restore into an existing PostgreSQL database with `psql -f techism-data.dump`.

File `techism-events.csv` contains a CSV export of the event data.

File `techism-events.ipynb` is a Jupyter Notebook with some analysis and visualizations of the event data.

