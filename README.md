# Login-using-Google-OAuth-using-React-and-NodeJs

A client side application using React and Node-Js for server side.
Explanation
This is a React application - using react-semnatic-ui for UI - to demonstrate a simple add & edit flow with a Node.js as its back-end. The goal of this application is to display a list of invoices and user can add, edit or delete the invoices.

Server Installation & Run
for the server side

Run npm i to install the packages.
Run npm start to start the server.

for the client side

Run npm i to install the packages.
Run npm start to start the frontend.
React Installation & Run
Run npm i to install the packages.
Run npm start to start the application.

Server End points
method	url	Description
GET	/payments/:iban	to search bank payments based on a specific IBAN
GET	/invoice	to get all invoices
GET	/invoice/:id	to get a specific invoice details
POST	/invoice/:id	to update a specific invoice
POST	/invoice	to insert a new invoice
DELETE	/invoice/:id	to delete a invoice
