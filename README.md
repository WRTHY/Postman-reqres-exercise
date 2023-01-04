# Postman-reqres-exercise
Project resulting from exploratory API testing/ learning

reqres site for API testing: https://reqres.in/
Postman JSON(include in repository): https://api.postman.com/collections/24855208-cab2babf-9439-4003-829b-2cb30002983c?access_key=PMAT-01GNYX3FPAABNZM0VZ294VGC2E

---Desc---

The reqres site contains the following user methods that I decided to write my API tests against:
-	List Users (Get)
-	Single User (Get)
-	Single User Not Found (Get)
-	Create (Post)
-	Update (Put)
-	Update (Patch)
-	Delete (Delete)

Given time spent exploratory testing the reqres site using postman, and the following details can be tested for each of the above methods:
-	Status Code: Ensure that the correct status code is received based on operation (viewing a user should return a code 200 vs deleting a user should return a code 404)
-	Header: Ensure that the specified header is received in the response (could check for a common header such as Content-Type for a Get operation)
-	Response Time: Ensure the API operation occurs in a correct time frame (Bound a simple Get operation by 200ms)
-	Response Body: Ensure that the content received in the response is correct (Verify several of the data fields in the response json against the expected output on the reqres site)
