FROM mysql:8.0.33
LABEL "project"="Vprofile"
LABEL "Author"="Shivaraj"

ENV MYSQL_ROOT_PASSEOR="vprodbpass"
ENV MYSQL_DATABASE="accounts"

ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql