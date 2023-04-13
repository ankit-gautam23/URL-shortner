# URL-shortner

Step 1: Create a Spring Boot Project
Create a new Spring Boot project using your preferred IDE or by using the Spring Initializr.

Step 2: Add Dependencies
Add the following dependencies to your project:

Spring Web
Spring Data JPA
H2 Database
Apache Commons Codec
Step 3: Create Model Classes
Create two model classes: Url and ShortUrl.

The Url class will store the original long URL, and the ShortUrl class will store the shortened URL and its corresponding long URL.

Step 4: Create Repository Interfaces
Create two repository interfaces: UrlRepository and ShortUrlRepository, which will extend the JpaRepository interface.

Step 5: Create Controller Classes
Create a controller class for each model class: UrlController and ShortUrlController.

The UrlController will handle requests to create a new URL, and the ShortUrlController will handle requests to create a new shortened URL.

Step 6: Implement Shortening Logic
Implement the logic for shortening URLs in the ShortUrlController. This can be done using a unique identifier such as a random string, or by using an algorithm like base64 encoding.

Step 7: Implement Redirection
Implement the logic for redirecting the shortened URL to its corresponding long URL in the ShortUrlController.

Step 8: Test the Application
Test the application by creating a new URL and a corresponding shortened URL, and then testing the redirection.

This is just a basic outline of how to create a URL shortener using Spring Boot. You can customize the implementation based on your requirements.




