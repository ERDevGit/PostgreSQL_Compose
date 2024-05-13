README

Instructions for First Time Use:

Always follow these steps:
1º RUN.BAT
2º Terminate once the postgreSQL folder has been created (KILL.BAT)
3º Copy .conf files
4º RUN.BAT

Description:

This docker-compose file will start a postgreSQL image and a pgAdmin image.

The default credentials for pgAdmin are:

PGADMIN_DEFAULT_EMAIL: "admin@admin.com"
PGADMIN_DEFAULT_PASSWORD: "admin"

Upon the first run, create the tables from the SQL file.

Connecting to pgAdmin from Your Computer:

If you wish to connect from your computer using pgAdmin:

Add server
Host address: localhost
Database: admin
Username: admin
Password: admin

If you are connecting from the pgAdmin running at http://localhost/:

The default credentials for pgAdmin are:
PGADMIN_DEFAULT_EMAIL: "admin@admin.com"
PGADMIN_DEFAULT_PASSWORD: "admin"
Add server
Host address: admin