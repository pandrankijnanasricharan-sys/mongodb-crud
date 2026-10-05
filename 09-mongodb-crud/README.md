# Experiment 9 - MongoDB CRUD

Make sure MongoDB is running.

```bash
npm install
npm start
```

Use Postman/Thunder Client.

### POST /students
```json
{
  "name": "Sita",
  "branch": "CSM",
  "year": 3
}
```

### GET
`GET http://localhost:3000/students`

### PUT
`PUT http://localhost:3000/students/<mongodb-id>`

### DELETE
`DELETE http://localhost:3000/students/<mongodb-id>`
