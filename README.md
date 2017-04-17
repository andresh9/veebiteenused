1)REST-api.rar installation:

1. Download .rar package
2. Import "REST_app" and "REST_service" as "Maven > Existing Maven Projects" in Eclipse EE
3. Run "REST_app" project as "Run on Server" (Apache v8.0 must be configured)
4. Run "REST_service" project as "Run on Server" (Apache v8.0 must be configured)
5. Open browser with URL: http://localhost:8080/REST_app/ and add, delete or edit cars list

Link that can be used to sort cars by model that start with letter "3" for example, but user can choose other too if cars with starting letter are present in the base: http://localhost:8080/REST_app/service/search?model=3

Second link to get all cars in json:
http://localhost:8080/REST_service/service/cars

2)idu0080-kodutoo2.rar ("Hajuspäringu veahaldus" home assignment 2) installation:

1. Download .rar package
2. Import "Yl4_Kodune_Klient" and "Yl4_Kodune_Server" as "General > Existing Projects into Workplace" in Eclipse EE
3. Run "Yl4_Kodune_Server" project as "Run on Server" (Apache v8.0 must be configured)
4. Open "Yl4_Kodune_Klient" project and run file "build.xml" as "Ant Build" (into console must be set Ant view: window > show view > other > ant )
5. If everything went right, then you can see set pricelist in console

3)idu0080-kodutoo3.rar ("Asünkroonse päringu ülesanne" home assignment 3) installation:

1. Download .rar package
2. Import "idu0080-kodutoo3" as "General > Existing Projects into Workplace" in Eclipse EE
3. Run files "EmbeddedBroker.java", "Consumer.java" and "Producer.java" in Command Prompt with Apache Ant in same sequence as described here (Apache Ant must be configured for Windows)
4. If everything went right, then you can response sending and receiveing in command prompt Consumer window
