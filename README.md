<h1 align='center'>  Library Management System CLI </h1>
<h3 align='center'>  (HTTP Server) & (CLI Client) </h4>

- The system divided into HTTP Server (**RESTful API**) and Client (**CLI**)
- Librarians use the command-line interface to call the server then make specific operations.
- Backend system designed to encompass all the features needed for a functioning library.

## Librarians Operations

- <b>Book has</b> [id, title, publication date, author, genre, publisher, language]
- <b>LocalReader has</b> [id, name, gender, birthday, height, weight, employment]

### Readers Operations 👴🏻:

1. Add a reader
2. Remove a reader
3. Search for a reader by ID
4. Search for a reader by name
5. Get all readers info

### Books Operations 📚:

1. Add a book
2. Get all books info
3. Get all books sorted by title (alphabetically)
4. Get all books sorted by publication date
5. Search for a book by id
6. Search for a book by title

## Requirements

- [GO 1.20](https://golang.org/)

## Getting Started

### 1. Run The Server

Start the server.go, that is located in sever directory.

    go run server.go

### 2. Run The Client (CLI)

Start the client.go, that is located in client directory.

    go run client.go

<div align='center'>
    <img alt="golang-logo" src="https://user-images.githubusercontent.com/48678280/103093126-20da7a00-4602-11eb-88ab-0903f976509b.png">
</div>

---
