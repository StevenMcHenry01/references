# SERVER - Apollo server, redis, express, graphql, typeorm

## Note) This is a starter with simple auth built in. Delete all user stuff if you do not wish to include that aspect

### Installation:
1. install the database that you will be using
   - ex) yarn add pg - for postgres
2. create .env.development file and fill out according to your specifications and the .env.example schema
   - ex) 
      - PORT=8080
      - DB_TYPE=postgres
      - DB_HOST=localhost
      - DB_PORT=5432
      - DB_USERNAME=BillyBob
      - DB_PASSWORD=123123123
      - DB_DATABASE_NAME=cool_database
      - CORS_ORIGIN=http://localhost:3000
      - REDIS_URL=127.0.0.1:6379
      - SESSSION_SECRET=cool_secret_bro

3. go through config and eslint and set anything different you wish
4. make sure a database is created with the name you provided
5. install dependencies
6. go through each file and fix any potential errors

### Running:
1. after installing dependencies and fixing errors, open up a terminal and run yarn watch to generate js
2. in seperate window run yarn dev and make sure database populates correctly
3. You should no be live on port 8080
