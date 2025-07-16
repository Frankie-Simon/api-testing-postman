# api-testing-postman

API test collection for a RESTful service using Postman and Newman CLI.

## Overview
This project contains a sample Postman collection that tests a simple GET request to [jsonplaceholder.typicode.com](https://jsonplaceholder.typicode.com). It includes:

- Status code validation (expects 200 OK)
- Basic JSON response tests
- Example for learning API test automation with Postman and Newman

## Files
- `collection.json` – the exported Postman collection containing the test.

## How to Run with Newman

Make sure you have [Newman](https://www.npmjs.com/package/newman) installed:

```
npm install -g newman
```

Then run the collection with:

```
newman run collection.json
```

---

✅ *Feel free to fork or clone and adapt for your own practice projects.*
