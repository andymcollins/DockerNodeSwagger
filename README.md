
* Node.js - running API
* Nodemon - Autorestarts when saved in Dev
* ESLint - Linting
* Swagger - API design
* Docker - Containerization
* Docker Compose - Building and development

To runthe app:
1. Build and run it either...
  * ... in production mode: `docker-compose up --build`
  * ... or in development mode: `docker-compose -f docker-compose.yml -f docker-compose.dev.yml up --build`
2. Visit the Swagger UI at http://localhost:3000/docs/
3. to get current date http://localhost:3000/gettime/v1

