 #### open a cloudinary account if you dont have one.
 #### cd timtech-ecom-app 
 #### then create .env file in the root of your project and enter the following
  MONGO_URI=*enter your mongodb uri here*
  CLOUDINARY_CLOUD_NAME=*enter your cloud_name*<br>
  CLOUDINARY_API_KEY=*enter api key here*<br>
  CLOUDINARY_API_SECRET=*enter your api secret*
 ### open stripe account if you dont have one and still on .env file add
  STRIPE_SECRET=*enter your stripe secret key*
 #### install nodemon
  $ npm install nodemon
 #### install concurrently
  $ npm install concurrently
 #### run
  $ npm run install-all
 #### launch the app
  $ npm run dev

