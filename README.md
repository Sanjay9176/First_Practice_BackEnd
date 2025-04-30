# 🛒 Simple Node.js Backend - Add to Cart

This is a beginner-level Node.js backend project using the CommonJS module system. It includes a simple `add to cart` functionality to demonstrate how modules work in Node.js.

##  Project Files

- `cart.js` – Exports a function to simulate adding to cart.
- `index.js` – Imports and uses the function.
- `package.json` – Project setup with `nodemon` for running the server.

##  How to Run

1. Install dependencies:
   ```bash
   npm install
2. Also Install nodemon to run the server continuously
   ```bash
   npm Install nodemon or npm i nodemon
3. Connect the nodemon in packet.json file and run
   ```bash
   npm start
#Example of packet.json-> 
## package.json
```
{
  "name": "backend",
  "types": "commonjs",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "start": "nodemon index.js",
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "keywords": [],
  "author": "",
  "license": "ISC",
  "type": "commonjs"
}
