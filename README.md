# JSON Placeholder API Collection

This project is a Postman collection for interacting with the JSONPlaceholder API, a free online REST API used for prototyping and testing. The collection includes a series of requests to fetch, create, update, and delete resources such as posts, comments, and users. Additionally, it contains automated tests to verify the accuracy and performance of the API responses and some skipped tests under specific conditions

# Features

# 1. Posts

Get All Posts: Fetches all posts.

Get Specific Post: Retrieves a specific post by its ID.

Add New Post: Create a new post with a title and body.

Edit Post (PUT): Updates an entire post.

Edit Post (PATCH): Modifies a part of the post.

Delete Post: Removes a post by ID.

# 2. Comments

Get Comments for Specific Post (Path): Fetches comments related to a specific post.

Get Comments for Specific Post (Query): Retrieves comments for a post using query parameters.


# 3. Users

Get All Users: Retrieves a list of users.

Get Specific User: Fetches details of a particular user by ID.

Get User Albums: Lists albums associated with a specific user.

Get User Todos: Retrieves a list of "to-do" items for a specific user.

# Automated Tests

Each request contains Postman tests to:

Verify response status codes (e.g., 200 OK, 404 Not Found).

Ensure response times are below 400ms.

Validate the correctness of IDs and other data fields.

Check for the proper count of posts, comments, and users.

# Variables

Base_URL_JSON: The base URL of the JSONPlaceholder API.

POST_ID: The ID of the post being interacted with.

UserId: The ID of the user being referenced.

This collection is useful for anyone looking to understand basic RESTful API operations, practice API testing, or prototype web applications.

