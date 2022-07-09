# Emporium ECommerce Website

## Run Locally

### 1. Clone repo

```
$ git clone https://github.com/asqarrsl/emporium.git
$ cd emporium
```

### 2. Setup MongoDB

- Local MongoDB
  - Install it from [here](https://www.mongodb.com/try/download/community)
  - Create .env file in root folder
  - Set MONGODB_URL=mongodb://localhost/amazona
- Atlas Cloud MongoDB
  - Create database at [https://cloud.mongodb.com](https://cloud.mongodb.com)
  - Create .env file in root folder
  - Set MONGODB_URL=mongodb+srv://your-db-connection

### 3. Run Backend

```
$ npm install
$ npm start
```

### 4. Run Frontend

```
# open new terminal
$ cd frontend
$ npm install
$ npm start
```

### 5. Seed Users and Products

- Run on browser: http://localhost:5010/api/users/seed
- It returns user credentials
- Run on browser: http://localhost:5010/api/products/seed
- It creates sample products

### 6. Admin Login

- Run http://localhost:3000/signin
- Enter admin credentials
