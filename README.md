# 16-fast-react-pizza

Fast-React-Pizza-CO.

<img width="1446" alt="Screenshot 2025-03-08 at 22 20 46" src="https://github.com/user-attachments/assets/9a06e591-bfd9-4e67-bbbe-503b7f9be4fb" />
<img width="1440" alt="Screenshot 2025-03-08 at 22 21 00" src="https://github.com/user-attachments/assets/79947770-2dc1-4edf-a71f-aab4584d23a9" />

Fast-React-Pizza
---------------------

Fast React Pizza Co. is a Redux project where people can order pizza without authentication.

Table of Contents
-------------------

Project-requirements-from-the-business
Getting Started
References
Project requirements from the business

Very simple application, where users can order one or more pizzas from a menu
Requires no user accounts and no login: users just input their names before using the app
The pizza menu can change, so it should be loaded from an API
Users can add multiple pizzas to a cart before ordering
Ordering requires just the user’s name, phone number, and address
If possible, GPS location should also be provided, to make delivery easier
User’s can mark their order as “priority” for an additional 20% of the cart price
Orders are made by sending a POST request with the order data (user data + selected pizzas) to the API
Payments are made on delivery, so no payment processing is necessary in the app
Each order will get a unique ID that should be displayed, so the user can later look up their order based on the ID
Users should be able to mark their order as “priority” order even after it has been placed

Technologies
-----------------
React
Tailwindcss
React Router
Redux
Back To The Top

Getting Started
--------------------
To start the project, it is necessary to download the files from the github repository and after that run this commands:
'npm i'
'npm run dev'


References
-----------------
I made this project with the help of Jonas Schmedtmann in the React course: React course


