FROM mysql:8.0.33
LABEL "Projet"="Vprofile"
LABEL "Author"="Subham"

ENV MYSQL_ROOT_PASSWORD="vprofilepass"
ENV MYSQL_DATABASE="accounts"

ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql
