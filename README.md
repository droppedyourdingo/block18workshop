Unit Tests 

Prompt 1 - A function called "multiplication" that returns the product of the two input numbers.

1. Expect multiply(2, 3) to be a number
2. Expect multiply(2, 3) to be 6
3. Expect multiply('a', 3) to be an error
4. Expect multiply(2, true) to be 2

Prompt 2 - A function called "concatOdds" takes two arrays of integers as arguments. It should return a single array that only contains the odd numbers, in ascending order, from both of the arrays. 

1. Expect concatOdds([3,2,1], [5,6,7]) to be [1,3,5,7]
2. Expect concatOdds([2,4], [2,4]) to be []
3. Expect concatOdds(["three","four","five"], ["one","two"]) to be []
4. Expect concatOdds([3,"four",5], ["one","two"]) to be [3,5]
5. Expect concatOdds([1,1,4], [1,3,5]) to be [1,3,5]


Functional Tests

A shopping cart checkout feature that allows a user to check out as a guest (without an account), or as a logged-in user. They should be allowed to do either, but should be asked if they want to create an account or log in if they check out as a guest. 

1. When a user checkout without any items in the cart, they should show a popup saying "nothing in cart"
2. When a user checkout as a logged-in user, they should move onto the checkout screen
3. When a user checkout as a guest, they should show a popup asking if they want to create an account/log in or continue checking out
4. When a user continues to checkout as guest, they should be prompted to fill out billing and shipping information
5. When a user clicks on log-in, they should be shown a prompt asking for email and password
