Standard Format for Request and Respond

 API Endpoints
    Create User
    URL: /api/person
    Method: POST
    Request Body: JSON object with name and email fields.
    Response: JSON object with a success message and the created user's name.

    Retrieve User
    URL: /api/person/:name
    Method: GET
    Response: JSON object with user details based on the provided name.

    Retrieve All Users
    URL: /api/person
    Method: GET
    Response: JSON array containing all user records.

    Update User
    URL: /api/person/:name
    Method: PUT
    Request Body: JSON object with updated email field.
    Response: JSON object with a success message and the updated user's name.

    Delete User
    URL: /api/person/:name
    Method: DELETE
    Response: No content (204) on successful deletion.


Sample useage
get all person
https://hng2a.onrender.com/api
{"id":1,"name":"bernard","email":"bernard@gmail.com"},{"id":2,"name":"Ese","email":"ese@gmail.com"},{"id":3,"name":"Ejiro","email":"ejiro@gmail.com"}

get person by name
https://hng2a.onrender.com/api/Ese

{
    "id": 2,
    "name": "Ese",
    "email": "ese@gmail.com"
}


