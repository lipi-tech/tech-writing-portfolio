#Book Info API

## 📘 Introduction
The Book Info API provides details such as title, author, publication year, and genre based on the book title.


## 🔑 Authentication
You must register and get an API key to use this API.

Example API key: `YOUR_API_KEY`

## 📥 Endpoint
```
GET https://api.example.com/book?title={book_title}&key={API_KEY}
```
### Parameters:

| Parameter | Description         | Example     |
| --------- | ------------------- | ----------- |
| `title`    | Title of the book   | `The Hobbit`    |
| `key`     | API key       | `abc123` |

## 📤 Response Example
```json
{
  "title": "The Hobbit",
  "author": "J.R.R. Tolkien",
  "year": 1937,
  "genre": "Fantasy"
}
```
## ⚠️ Error Codes

| Code | Meaning                              |
|------|--------------------------------------|
| 401  | Unauthorized (Invalid API key)      |
| 404  | Book not found                      |