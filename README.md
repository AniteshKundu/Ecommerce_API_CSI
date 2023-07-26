Technology
  The application is built with:

  Node.js 
  MongoDB 
  Express 
  Bootstrap 
  FontAwesome 
  Stripe API v3: used for payment in the checkout page
  Mapbox API: used to show the map in the about us page
  AdminBro: used and customized to implement the admin panel
  Nodemailer: used to send emails from the contact us form
  Passport: used for authentication
  Express Validator: used for form validation

  Features
The application displays a virtual bags store that contains virtual products and contact information.

Users can do the following:

Create an account, login or logout
Browse available products added by the admin
Add products to the shopping cart
Delete products from the shopping cart
Display the shopping cart
To checkout, a user must be logged in
Checkout information is processed using stripe and the payment is send to the admin
The profile contains all the orders a user has made
Admins can do the following:

Login or logout to the admin panel
View all the information stored in the database. They can view/add/edit/delete orders, users, products and categories. The cart model cannot be modified by an admin because a cart is either modified by the logged in user before the purchase or deleted after the purchase.
