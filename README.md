This project is bootstrapped with create-react-app

## Overview: 
This app enables user to view, select and order food 

##### Getting Started: Installation Instructions
- Download this folder,
- cd react-meals-code,
- npm install
- npm start

### Logic: 
- Maximum Order Limit: 1000  (User can add upto 1000 $ worth of items to cart. After then no more additions are allowed);
- Per Item Limit: 5 (Any item can be added upto 5 qty at a time to cart. No more additions allowed for the product.
- Total Item Limit per Order: 15 (Only 15 amount of items with respect to the previous restriction) can be added. 
- All these are configurable in _App.constants.ts_ file
- Items can be changed in the cart page. 
- Order can be placed only where there is 1 item in the cart and user entered a valid address. 
- Postal code should have 6 digits. 
- Upon submission, it gets handled by a mock promise and enables user to print the order, it will download a pdf. 

### Effort: 7 hours

### Challenges:
Getting started a project from scratch and this gives a chance to refresh basics. 

Tech stack: 
1. React,
2. Redux
3. Redux Saga
4. React Redux
5. React hook form
6. yup 
7. JsPDF
8. Material UI# menu-items
# menu-items
