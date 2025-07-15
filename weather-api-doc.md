# Weather API Documentation

The Weather API allows you to get current weather data for any city.

---

## 🔑 Authentication

You must obtain an API key to access the Weather API. Include this key in every request.

Example:
```
API key: YOUR_API_KEY
```

---

## 📥 Endpoint

```
GET https://api.example.com/weather?city={city_name}&key={API_KEY}
```

---

### Parameters:

| Parameter | Description         | Example     |
| --------- | ------------------- | ----------- |
| `city`    | Name of the city    | `London`    |
| `key`     | Your API key        | `abc123xyz` |

---

## 📤 Response Example

```json
{
  "city": "London",
  "temperature": "18°C",
  "condition": "Cloudy"
}
```

---


## ⚠️ Error Codes

| Code | Meaning | Suggested Action |
| ---- | ------- | ---------------- |
| 401  | Unauthorized | Check your API key |
| 404  | Not Found | Verify the city name |
| 500  | Server Error | Try again later |

---

✅ *Use this documentation to integrate weather data into your application.*
