# work
Files I use in my work environment and like to share with the world

# DCM4CHEE installatie

Unzip de beide ZIP-files in een directory, bv /data/apps/dcm4chee/

Plaats hierna het bestand libclib_jiio.so in de directory /data/apps/dcm4chee/dcm4chee-2.18.3-psql/bin/native/


# PostgreSQL config

 export PGUSER=postgres
 
 createdb pacsdb
 
 psql pacsdb -f dcm4chee-psql-2.13.6/sql/create.psql

# Overig

export JBOSS_HOME=/data/apps/dcm4chee/jboss-4.2.3.GA
