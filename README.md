# Build a RESTful CRUD API with Golang Gin and Gorm

Building a RESTful API built using Golang with the Gin framework and Gorm ORM, utilizing PostgreSQL as the database. Podman is used for containerized database setup.

## Quick Start

1.Clone the repository
>git clone https://github.com/tu0504/Demo_gin_gorm_CRUD/issues
>cd project-name

2.Install dependencies
>go mod tidy

3.Set up environment variables (create a .env file):
>DB_HOST=localhost
>DB_PORT=5432
>DB_USER=postgres
>DB_PASSWORD=yourpassword
>DB_NAME=test
>DB_SSLMODE=disable

4.Run PostgreSQL with Podman

5.Run migrations and start the server
>go run main.go

6.Test
API Endpoints
| Method   | Endpoint    | Description       |
| ---    | ---   | ---     |
| GET | http://localhost:8888/api/tags | Get all items |
| GET | http://localhost:8888/api/tags/:id | Get item by ID |
| POST | http://localhost:8888/api/tags | Create new item |
| PATCH | http://localhost:8888/api/tags/:id | Update item |
| DELETE | http://localhost:8888/api/tags/:id | Delete item |