This is a Spring Boot microservice that returns a default "Hello, World" greeting when visiting /greeting. If ?name="string" is passed to the url, that string is used in place of "world" when returning the greeting.

This project comes from Spring's Getting Started project: https://spring.io/guides/gs/rest-service/

I modified the greeting that is returned, and I added another unit test to verify that a name of all numbers is handled appropriately. Which I expected to be the case, and is the case. But it was still good practice to add the unit test.
