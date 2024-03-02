# Basic Typescript
How to enhance your javascript project with basic typescript

## Section
- Recapture with 060243110 - Javascript Programming (IT) / 060233113 - Advanced Computer Programming (INE)
- ES6 Javascript syntax
- What about typescript
- Install and Setup typescript
- Hello types!
- If you don't know type
- Interface and Type
- Reuse Interface and Type
- Recheck types with zod
- Typescript CRUD with express.js
- JSDoc and @ts-check alternative typescript
- Bonus: Type-safe with [elysiajs](https://github.com/elysiajs/elysia) and eden (Not recomend for production because elysia is beta version)

### Recapture javascript programming
Reference: 060243110 - Javascript Programming (Anirach Mingkhwan)

### ES6 Javascript syntax
CommonJS
```javascript
const express = require('express');

const app = express();

app.get("/", (req, res) => res.send({ message: "Hello, World!" }));

app.listen(3000, () => console.log("Server listen on port 3000"));

modules.export = app; // Default export
```

ES6
```javascript
import express from "express";

const app = express();

app.get("/", (req, res) => res.send({ message: "Hello, World!" }));

app.listen(3000, () => console.log("Server listen on port 3000"));

export default express; // Default export
```
