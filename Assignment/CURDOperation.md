### Objectives

After this exercise, you should be able to:

- HTTP method
- Request and Response
- Retrieving data from req body
- exception handling 
- API testing with postman App

### Exercise

0. create 4 router with get post delete and update in user controller file
1. write 4 service for get post delete and update service in user service file
2. while any one access get router then it should call get user controller and from their it should call user service
3. for get take data in query and path simply return all value from array of object
4. for POST, DELETE and PUT take data as body parameter and perform push, delete and update in a array
5. install postman https://www.postman.com/
6. test all the api localhost:3000/"endpoint name"
7. write exception handling case in service
8. for create api if any one not providing any thing and hitting api through data is required exception
9. for get api if any one hit api and no data in the array it should through no data found exception
10. if the user want to update some thing and data is not their it should through data not found exception
11. in delete if data is not their it should return data not found exception