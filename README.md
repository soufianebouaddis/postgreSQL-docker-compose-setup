# postgresDB

A Docker Compose setup for PostgreSQL and pgAdmin. This configuration provides a fully functional PostgreSQL database and a web-based administration interface using pgAdmin.

## Features

- **PostgreSQL**: A powerful, open-source object-relational database.
- **pgAdmin**: A feature-rich web interface for managing PostgreSQL databases.
- Data persistence using Docker volumes to ensure your data is not lost when containers are stopped or removed.

## Prerequisites

- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)

## Setup Instructions

1. Clone this repository:
   ```bash
   git clone https://github.com/soufianebouaddis/postgreSQL-docker-compose-setup.git
   cd postgreSQL-docker-compose-setup
   docker-compose -p postgres_db up -d
