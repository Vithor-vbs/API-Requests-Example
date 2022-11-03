## API-Requests-Example
This code introduces the basics of writing a RESTful web service API with Go and the Gin Web Framework (Gin).
It is a RESTful API server with two endpoints, this project will be a repository of data about vintage jazz records.

### /albums

- GET – Get a list of all albums, returned as JSON.
- POST – Add a new album from request data sent as JSON.

### /albums/:id

- GET – Get an album by its ID, returning the album data as JSON.
