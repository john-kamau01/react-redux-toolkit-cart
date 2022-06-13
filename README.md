# ReactJS Shopping Cart that implements the Redux Toolkit

In this project, I created a shopping cart that implemented the React Redux Toolkit. The items in the cart are loaded via a store and the state of the store can be accessible from multiple components.

The functionalities of the application include:

# 1. Clear cart functionality

The cart can be cleared by clicking the clear cart button. 

# 2. Increment, decrement and remove individual items in the cart

The items can solely be incremented, decremented and removed from the cart. This has been achieved by created reducer methods that can increment/decrement the items based on the state of the store. The items can also be completely removed from the cart using the 'remove' button.

# 3. Amount and total functionality

Whenever a user increments, decrements, or removes items from the cart, the amount of items will increase, decrease or be completely removed from the cart and the total will be calculated correctly based on the current state of the cart.

# Redux Toolkit

The redux toolkit has made the state of the application very easy to maintain. 