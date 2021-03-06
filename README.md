Server-side of [texas-plan-em](https://github.com/juanflo/texas-plan-em) using MongoDB and web sockets

### To run locally
1. Clone the repository
2. Create a `.env` file in the root and copy the contents of `.env.sample`. Fill out the fields with your mongoDB information
3. Run `npm install`
4. Run `npm run devstart`
5. Browse to [(http://localhost:3005/)]

App structure:

```
.
├── public                # CSS files
├── routes                # Router files
|   ├── index.js          # Routes
├── socket                # Socket files
|   ├── index.js          # Server Socket.io implementation
├── models                # Schema files
|   ├── schemas.js        # User and Session schemas
└── app.js                # Express entry point file
```

