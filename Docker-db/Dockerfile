FROM mysql:5.7

ENV MYSQL_ROOT_PASSWORD="root"

ENV MYSQL_DATABASE="accounts"

EXPOSE 3306

ADD accountsdb.sql docker-entrypoint-initdb.d/accountsdb.sql
