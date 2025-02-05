This repository contains the second project for the Relational Database course on FreeCodeCamp. It includes a `.sql` dump file that can be loaded into a database for practice. To load the dump file, you can use the MySQL or PostgreSQL command line by running `mysql -u [username] -p [database_name] < worldcup.sql` or `psql -U [username] -d [database_name] -f worldcup.sql`. Alternatively, graphical tools can be used to import the file through their respective import options.

### Running the scripts

- `insert_data.sh` - This script reads data from `games.csv` and inserts it into the database. Run it using: `./insert_data.sh` in a bash terminal.
- `queries.sh` - This script performs various queries on the database to retrieve insights from the data. Run it using: `./queries.sh` in a bash terminal.
