# Pizza ordering application.

Built on React + Vite

A simple application where users can order one or more pizzas from menu.
No user account requires and no login. Just input their names brfore using the app.
The pizza menu loaded from an API.
User can add multiple pizza to a cart before ordering.
Ordering requires user's name, phone number, and address.
User can make GPS location.
User can make their order as 'priority' for an additional 20% on top of the cart price. User are able to mark their order as 'priority' order even after it has been placed.
Orders are made by sending a POST request with the order data to the API.
Payments are pay at the door, so no payment processing in the app.
Each order will get a unique ID that will display, user can later look up their order based on the ID.

Tech stack with:
Tailwindcss for styling application
React Router for routing and remotestate management
Redux for UI state management
