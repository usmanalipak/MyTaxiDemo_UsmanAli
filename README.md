# MyTaxiDemoTest
### MyTaxiDemoTest.java contains the Espresso test for follwoing test case:
* Login with Username: **whiteelephant261** and Password: **video**
* Type **sa** in the **Search driver here** field
* Tap on **Sarah Friedrich** from search results
* Tap on **Call** button of **Sarah Friedrich**
------------------------------------------------
### If app has different types of users (driver and passenger), then following test scenarios should be tested:
* Each different type of user should be authenticated properly. 
* Each different type of user should be able to access only those screens for which he is authorized. 
* If a user had two different types of roles, then he should be able to access all possible screens of both roles.
* If a user had both roles (driver and passenger), then he should have different profile for each role.
* If user is logged in as a passenger, then he should be able request for a taxi.
* If user is logged in as a driver, then he should be able see incoming requests from passenger(s).
