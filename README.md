# Timestamp Microservice

A REST API built with Node.js and Express that converts dates into Unix timestamps and UTC date strings.

## Features

- Convert valid dates to Unix timestamps and UTC strings
- Accept Unix timestamps as input
- Return the current date and time when no date is provided
- Handle invalid dates gracefully

## Technologies Used

- Node.js
- Express.js
- JavaScript

## API Endpoints

### Current Date
GET `/api`

### Date String
GET `/api/2015-12-25`

### Unix Timestamp
GET `/api/1451001600000`

## Example Response

```json
{
  "unix": 1451001600000,
  "utc": "Fri, 25 Dec 2015 00:00:00 GMT"
}
```

## Error Response

```json
{
  "error": "Invalid Date"
}
```

## About

This project was completed as part of the **freeCodeCamp Back End Development and APIs** certification.

---
**Author:** Musapu Nyendwa
