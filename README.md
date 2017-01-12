# MYSQL_DKAN
DKAN Mysql Database Repository Storing Databases for the CMAP SDLC

INSTALL or LOAD ***

To install the database use the following commands...

1) Clone the repository to a Linux directory.

2) $ mysql -u root -p

   enter the password as prompted

3) Enter the following command inside mysql at the prompt

   mysql > source /YOUR/DIRECTORY/DATABASENAME.sql

The database should now be visable using the following command

show databases;

EXPORT or DUMP ***

cd /YOUR/DIRECTORY/

$ mysqldump -u root -p THE_DATABASE_NAME > database_name_date.sql
