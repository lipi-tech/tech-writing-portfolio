# Weather API Documentation

## 📘 Introduction

The Weather API allows you to get current weather data for any city.

## 🔑 Authentication

You must sign up and get an API key to use this API.

Example API key: `YOUR_API_KEY`

## 📥 Endpoint

GET https://api.example.com/weather?city={city_name}&key={API_KEY}


### Parameters:

| Parameter | Description         | Example     |
| --------- | ------------------- | ----------- |
| `city`    | Name of the city    | `London`    |
| `key`     | Your API key        | `abc123xyz` |

## 📤 Response Example

```json
{
  "city": "London",
  "temperature": "18°C",
  "condition": "Cloudy"
}
```




## ⚠️ Error Codes

| Code | Meaning                              |
|------|--------------------------------------|
| 401  | Unauthorized (Invalid API key)      |
| 404  | City not found                      |
