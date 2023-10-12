## Supermarket List API

The main objective is to make life easier for the application user with a dynamic supermarket list. The API aims to organize this shopping list.

O objetivo principal é facilitar a vida do usúario da aplicação com uma lista dinamica de supermercado. A API tem como objetivo organizar essa lista de compras.

### Technologies used

- Node.js
- Express
- Mongoose
- MongoDB
- Nodemon

### Required Technologies

- Node.js installed (https://nodejs.org)
- MongoDB instance running:
  Ex: Running witch docker

```
docker run --name supermarket-list -p 27017:27017 -d mongo
```

### Steps to run the project

1. Clone the repo:

```
git clone https://github.com/EdSantiag0/supermarket-list-api.git
```

2. Navigate to the repo:

```

cd supermarket-list-api
```

3. Install the dependencies:

```
npm install
```

4. Run the API:

```
npm run start:dev
```

### Avaible endpoints

- [GET]/list-items
- [POST]/list-items
- [DELETE]/list-items/:id
- [UPDATE]/list-items/:id
