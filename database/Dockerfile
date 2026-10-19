FROM mysql:8.0

# Copy initialization SQL scripts into the container
# Any .sql or .sh files copied here will execute when the container is first created
COPY ./init.sql /docker-entrypoint-initdb.d/

EXPOSE 3306
