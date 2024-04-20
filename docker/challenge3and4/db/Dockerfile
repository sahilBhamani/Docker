FROM mariadb:latest

# Set environment variables
ENV MYSQL_ROOT_PASSWORD=12345  
ENV MYSQL_DATABASE=database

# When the container starts, run this SQL script
COPY init/init.sql /docker-entrypoint-initdb.d/

# Expose port 3306 for connections
EXPOSE 3306
