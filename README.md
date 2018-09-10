Login using psql

`sudo -u postgres psql`

`CREATE DATABASE example_gis;`

Move into this database:

`\connect example_gis;`

Create the postgis extension:

`CREATE EXTENSION postgis;`

