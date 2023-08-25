# Postman - API testing

## Simple Books API
### Documentation:
[```https://github.com/vdespa/introduction-to-postman-course/blob/main/simple-books-api.md```](https://github.com/vdespa/introduction-to-postman-course/blob/main/simple-books-api.md)

## Instruction to run Postman collection:
1. Download my [Postman collection](https://github.com/agnieszkafras/postman-API-testing/blob/main/Simple_Books_API.postman_collection.json).

2. Download and install [Node.js](https://nodejs.org/en/download/current).
  
3. Open command prompt and install Newman:

```npm install -g newman```

4. Install Newman HTML reporter (optionally):

```npm install -g newman-reporter-htmlextra```

5. Run Newman:

```newman run Simple_Books_API.postman_collection.json```

or run Newman HTML reporter:

```newman run Simple_Books_API.postman_collection.json -r htmlextra -n 1```
