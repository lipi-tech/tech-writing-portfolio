# Book Info API Documentation

This guide explains how to use the Book Info API to retrieve details about books.

---

## 🔐 Authentication

You must include a valid API key with each request.

Example:
```
API key: YOUR_API_KEY
```

---

## 📥 Endpoint

```
GET https://api.example.com/book?title={book_title}&key={API_KEY}
```

---

## 🔧 Parameters

| Parameter | Description           | Example         |
| --------- | --------------------- | --------------- |
| `title`   | Title of the book     | `Pride and Prejudice` |
| `key`     | Your API key          | `abc123xyz`     |

---

## 📤 Example Response

```json
{
  "title": "Pride and Prejudice",
  "author": "Jane Austen",
  "year": "1813"
}
```

---

## ⚠️ Error Codes

| Code | Meaning | Suggested Action |
| ---- | ------- | ---------------- |
| 401  | Unauthorized | Ensure your API key is valid |
| 404  | Not Found | Check that the book title is correct |
| 500  | Server Error | Try again later or contact support |

---

✅ *Use this documentation to easily retrieve book information using the API.*
