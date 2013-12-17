
This is a bare minimum effort port of Plausible Labs Access migration tool from SQLite to Postgres. It inserts an '_' if there is a space in the name of a table or column.


## Building the Tool

    ant dist

# Running the Tool

    java -jar vendor/jars/mdb-postgresql.jar access_file_name database_name username password
