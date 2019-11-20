to start the server

```
npm install
node index.js
```
docker build -t fake-simple-json-datasource:latest .
docker run -d -p 3333:3333 fake-simple-json-datasource:latest