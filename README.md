# CRUD Notes API

## API Endpoints

- GET: https://crud-notes.herokuapp.com/api/notes
- GET: https://crud-notes.herokuapp.com/api/notes/:id
- POST: https://crud-notes.herokuapp.com/api/notes + Body
- PUT: https://crud-notes.herokuapp.com/api/notes/:id + Body
- DELETE: https://crud-notes.herokuapp.com/api/notes/:id

Use POSTMAN or Thunder Client (VS Code Extension) to test API

## Body Structure

```
{
    content: String,
    important: Boolean
}
```
