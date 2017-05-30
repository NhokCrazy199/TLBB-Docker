FROM mysql:5.7

COPY ./initdb.d/*.sql /docker-entrypoint-initdb.d/

EXPOSE 3306
CMD ["mysqld"]
