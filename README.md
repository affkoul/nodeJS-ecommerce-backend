# nodeJS-ecommerce-backend
NodeJS Ecommerce Back-end with Paypal payment

1. Clone the repository code.

2. Configure properly your .env file following the file env.sample.

3. Open the file server.js and configure properly your server's SSL key and cert when creating the Express JS Server.

4. If you prefer to use nodemailer than mailgun, like I did, then head to the file orderRoutes.js in the folder routes and configure your mail sending information properly. However, if you decide to use mailgun, then make sure to comment out lines 160 to 189 in this file and uncomment lines 142 to 158.

5. cd back to the root directory and run npm install to install all the dependencies required.

6. Next, run npm start to launch the server.

7. Then, open your browser and go to https://domain.com:port/api/seed to create 1 admin user, a general user, and 4 products as writen in the file data.js.

8. That's it. Way to go!

## Front-end

[Front-end](https://github.com/affkoul/reactJS-ecommerce-frontend)

![GAC Logo](https://geniusandcourage.com/favicon.ico)

Ecommerce Back-end with Paypal payment By [GAC DEV](https://geniusandcourage.com)

