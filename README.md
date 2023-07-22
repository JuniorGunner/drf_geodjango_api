# 🚀 Mozio Backend Project 🌍
Mozio Backend Project is a RESTful API service built with Django REST Framework. It enables transportation providers to define and alter their service areas dynamically as custom polygons. This project is designed to streamline Mozio's international expansion by simplifying integration with various transportation suppliers.

## 🛠 Tech Stack
* 🐍 Python
* 🔵 Django REST Framework
* 🌐 GeoDjango
* 🐘 PostgreSQL
* 🔺 PostGIS
* 📦 Docker
* ☁️ AWS (Optional for deployment)


## 🌟 Highlights
* CRUD operations for Providers and Service Areas
* Efficient querying of service areas by latitude/longitude pair
* Unit tests to ensure API functionality
* Comprehensive API documentation
* Deployed on AWS for real-world testing

## 🚀 Getting Started
1. Clone the repo
```
git clone https://github.com/your-github-user/mozio-backend-project.git
cd mozio-backend-project
```

2. Setup Environment Variables
Create a .env file in the root directory and setup your environment variables. Example:
```
POSTGRES_USER=postgres
POSTGRES_PASSWORD=yourpassword
POSTGRES_DB=mozio_db
```

3. Start the project
```
docker-compose up --build -d
```

## 📘 API Endpoints
* POST /providers - Add a new provider
* GET /providers - Get all providers
* GET /providers/:id - Get a provider by ID
* PUT /providers/:id - Update a provider by ID
* DELETE /providers/:id - Delete a provider by ID
* POST /service_areas - Add a new service area
* GET /service_areas - Get all service areas
* GET /service_areas/:id - Get a service area by ID
* PUT /service_areas/:id - Update a service area by ID
* DELETE /service_areas/:id - Delete a service area by ID
* GET /service_areas/query?lat=:latitude&lng=:longitude - Query service areas by latitude and longitude
