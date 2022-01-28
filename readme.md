#### Use the following API
#### https://jsonplaceholder.typicode.com/
- Use this similar schema
```js
    {
    "userId": 1,
    "id": 1,
    "title": "delectus aut autem",
    "completed": false
  }
```
#### Make a post request using the /todos endpoint
- Request:
```js
curl --data "userId=1&title=delectus aut autem&completed=false" https://jsonplaceholder.typicode.com/todos
```
- Response:
```js
    {
    "userId": "1",
    "title": "delectus aut autem",
    "completed": "false",
    "id": 101
    }
```
#### Use the data flag
- Request:
```js
    curl --data "userId=1&title=delectus aut autem&completed=false" https://jsonplaceholder.typicode.com/todos
```
- Response:
```js
   {
    "userId": "1",
    "title": "delectus aut autem",
    "completed": "false",
    "id": 101
    }
```