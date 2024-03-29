# Backend Task 

## Introduction
This project is a Node.js backend application that interacts with a third-party API to fetch product transaction data, initializes a MongoDB database with seed data, and provides various APIs for querying and analyzing the data.

## Technologies Used

- Node.js
- Express.js (Node.js backend framework)
- MongoDB 
- Axios (HTTP client for making requests)
- CORS (Cross-Origin Resource Sharing middleware)
- Dotenv (Environment variable management)
- Mongoose (MongoDB object modeling for Node.js)
- Nodemon (Utility for automatic server restart)

## ENDPOINTS
1. Initialize Database
2. List All Transactions
3. Statistics
4. Bar Chart
5. Pie Chart
6. Combined Response

## Sample Requests

- Initialize Database
  
  ```npm http://localhost:3000/initialize-database```

- List All Transactions:
  
  ```npm http://localhost:3000/transactions?month=January&page=1&perPage=10```

- Statistics
  
  ```npm http://localhost:3000/statistics?month=February```

- Bar Chart:
  
  ```npm http://localhost:3000/bar-chart?month=March```

- Pie Chart:
  
  ```npm http://localhost:3000/pie-chart?month=April```

- Combined Response:
  
  ```npm http://localhost:3000/combined-response?month=May```
  
