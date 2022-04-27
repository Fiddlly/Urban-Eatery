# Urban Eatery

> \*"**Good Food for Good Moments"\***

![Untitled](Frontend/src/images/ReadmeCanvas.png)

> **_Urban Eatery is an app where you can order your favourite food from the menu and Pay online using your credit card and enjoy the most delicious food at your doorsteps. Our main motivation is to "bring every foodie facility right at your doorsteps, providing you the full comfort"._**

---

# Project Setup

- Download and extract the Zip File.

```bash
# After that enter the server directory ( backend of our application )
cd server

# For installing backend dependencies run
npm install

# For starting Backend Server (Node Server)
npm start

# Now go back to previous directory
cd ..

# Now enter the frontend directory
cd Frontend

# Again for installing frontend dependencies run
npm install

# For starting Frontend Server (React Server)
npm start
```
# To run using Docker setup 
 docker compose up 
 
 # To run tests in backend
 npm test
 
 # To generate report in backend
 npm run test -report

# Required API_KEYs/Secrets to start 
  STRIPE_API_KEY="" // stripe api key for payment .env backend,
  HEROKU_API_KEY="" // ADD to github secrets for backend server github, 
  JWT_SECRET=""   // to create jwt tokens in .env backend,
  DB=""  // Database url in .env backend
  
  

# Live website

[https://foodie-eb5cd.web.app/](https://foodie-eb5cd.web.app/)

# Contributors

| Name           | Roll Number  |
| -------------- | ------------ |
| Himanshu Pal   | S20190010064 |
| Nishchay Verma | S20190010128 |
| Abhishek Jain  | S20190010003 |

                                        Copyright © 2022 Urban Eatery. Proudly created with ❤️
