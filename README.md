# 🚀 GeoDjango Backend Project 🌍
GeoDjango Backend Project is a RESTful API service built with Django REST Framework. It enables transportation providers to define and alter their service areas dynamically as custom polygons.

## 🛠 Tech Stack
* 🐍 Python
* 🔵 Django REST Framework
* 🌐 GeoDjango
* 🌱 Celery
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
git clone git@github.com:JuniorGunner/drf_geodjango_api.git
cd drf_geodjango_api
```

2. Setup Environment Variables
Create a .env file in the root directory and setup your environment variables. Example:
```
POSTGRES_USER=postgres
POSTGRES_PASSWORD=yourpassword
POSTGRES_DB=geodjango_db
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

<!--_Note: Refer to the API documentation available at <deployed_url>/docs for detailed API endpoint information._

## ⚙️ Running Tests
To run the tests, use the following command:
```
docker-compose exec web python manage.py test
```

 ## 📝 API Documentation
Please refer to the API documentation generated with <your_choice_of_documentation_tool> available at <deployed_url>/docs.

## 🚁 Deployment
The application is deployed on AWS. Here is the link to access the live application: <aws_deployment_link>

## 📬 Feedback
If you have any feedback or issues, please open a GitHub issue under this repository.

## 👩‍💻 Developer
Junior - csf.junior90@gmail.com -->
