  # Spring MVC and Thymeleaf
     
     -------------
     Build the executable
     -------------
        mvn -DskipTests=true package 

     Access the app using
        Windows: http://192.168.99.100:8080/spring-mvc-example-war-1.0.0/#
        Ubuntu : http://localhost:8080/spring-mvc-example-war-1.0.0/#

     -------------
     Build docker image
     -------------
         docker build -t springmvc-thymeleaf-war .

     -------------
     Run app as Docker container
     -------------
         docker run -p 8888:8080 --name springmvc-thymeleaf-c springmvc-thymeleaf-war

     Access the app using
         Windows: http://192.168.99.100:8888/spring-mvc-example-war-1.0.0/#a 
         Ubuntu : http://localhost:8888/spring-mvc-example-war-1.0.0/#
