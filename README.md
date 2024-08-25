## RESTful API🗂️

### Description

A RESTful API built with Node.js and Express.js for managing user data. This API supports CRUD operations: Create, Read, Update, and Delete user records. 🔄

### Features (CRUD)

- **Create**: Add new users with unique IDs. ✍️
- **Read**: Retrieve a list of all users or a specific user by ID. 📋
- **Update**: Modify user information by ID. ✏️
- **Delete**: Remove users by ID. 🗑️

### Technologies Used

- **Node.js**: JavaScript runtime for building server-side applications. 🚀
- **Express.js**: Web framework for Node.js to handle routing and middleware. 🛠️
- **UUID**: Library to generate unique identifiers for users. 🔢

### API Endpoints

#### `GET /users` 📋

Retrieve a list of all users.

- **Response**: JSON array of user objects.

#### `POST /users` ✍️

Create a new user.

- **Request Body**: JSON object with user details (e.g., `firstName`, `lastName`, `age`).
- **Response**: Confirmation message with the name of the added user.

#### `DELETE /users/:id` 🗑️

Delete a user by ID.

- **URL Parameter**: `id` - The unique identifier of the user to delete.
- **Response**: Confirmation message with the ID of the deleted user.

#### `PATCH /users/:id` ✏️

Update user information by ID.

- **URL Parameter**: `id` - The unique identifier of the user to update.
- **Request Body**: JSON object with updated user details.
- **Response**: Confirmation message with the ID of the updated user.
