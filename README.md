Installation:

1. Download .rar package
2. Import "REST_app" and "REST_service" as "Maven > Existing Maven Projects"
3. Run "REST_app" project as "Run on Server" (Apache v8.0 must be configured)
4. Run "REST_service" project as "Run on Server" (Apache v8.0 must be configured)
5. Open browser with URL: http://localhost:8080/REST_app/ and add, delete or edit cars list

Link that can be used to sort cars by model that start with letter "e" for example, but user can choose other too if cars with starting letter are present in the base: http://localhost:8080/REST_app/service/search?model=e

Second link to get all cars in json:
http://localhost:8080/REST_service/service/cars 
