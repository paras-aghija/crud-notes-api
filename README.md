# CRUD Notes API

## API Endpoints

- GET: https://curd-notes.herokuapp.com/api/notes
- GET: https://curd-notes.herokuapp.com/api/notes/:id
- POST: https://curd-notes.herokuapp.com/api/notes + Body
- PUT: https://curd-notes.herokuapp.com/api/notes/:id + Body
- DELETE: https://curd-notes.herokuapp.com/api/notes/:id

Use POSTMAN or Thunder Client (VS Code Extension) to test API

## Body Structure

```
{
    content: String,
    important: Boolean
}
```
