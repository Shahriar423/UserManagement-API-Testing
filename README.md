# User Management API Testing Project (Postman)

## API Source
This project uses [JSONPlaceholder](https://jsonplaceholder.typicode.com/) — a free online REST API used for testing and prototyping.

All test scenarios (GET, POST, PUT, DELETE) are based on endpoints provided by this mock API.

## 🔧 Tools Used:
- Postman
- pm.test scripting
- Collection Runner
- CSV for Data-driven Test

## ✅ Test Scenarios:
1. Get All Users
2. Get Single User (Valid & Invalid)
3. Create User (POST) with CSV
4. Update User (PUT)
5. Delete User (DELETE)
6. Response Validation
7. Pre-request Dynamic ID

## 🧪 Sample Assertions:
```js
pm.test("Status code is 200", function () {
    pm.response.to.have.status(200);
});
