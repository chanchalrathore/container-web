FROM mysql:8.0.33
LABEL "project"="vprofile"
LABEL "author"="chanchal"

ENV MYSQL_ROOT_PASSWORD="secret"
ENV MUSQL_DATABASE="accounts"

ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql
