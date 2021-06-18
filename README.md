 
 ### create .env file in the root of the project and
 #### cd timtech-ecom-app install nodemon
  $ npm install nodemon
 #### install concurrently
  $ npm install concurrently
 #### open a cloudinary account if you dont have one 
 #### then create .env file in the root of your project and enter the following
  MONGO_URI=*enter your mongodb uri here*
  CLOUDINARY_CLOUD_NAME=*enter your cloud_name*
  CLOUDINARY_API_KEY=*enter api key here*
  CLOUDINARY_API_SECRET=*enter your api secret*
 ### open stripe account if you dont have one and still on .env file add
  STRIPE_SECRET=*enter your stripe secret key*
 #### run
  $ npm run install-all
 #### launch the app
  $ npm run dev

