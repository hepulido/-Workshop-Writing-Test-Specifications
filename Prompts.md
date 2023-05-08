<!-- Unit Tests

Prompt 1 - A function called "multiplication" that returns the product of the two input numbers.

Prompt 1 Tests -

multiplication(2, 3) should return 6
multiplication(0, 100) should return 0
multiplication(10, -2) should return -20
multiplication("2", 3) should throw an error
multiplication(NaN, 3) should throw an error
multiplication(2, Infinity) should return Infinity
Prompt 2 - A function called "concatOdds" takes two arrays of integers as arguments. It should return a single array that only contains the odd numbers, in ascending order, from both of the arrays.

Prompt 2 Tests -

concatOdds([3, 2, 1], [9, 1, 1, 1, 4, 15, -1]) should return [-1, 1, 3, 9, 15]
concatOdds([], []) should return an empty array
concatOdds([1, 2, 3], [4, 5, 6]) should return [1, 3, 5]
concatOdds(["1", 2, "3"], [4, "5", 6]) should return [1, 3, 5]
concatOdds([2, 4, 6], [8, 10, 12]) should return an empty array
Functional Tests

Prompt 3 - A shopping cart checkout feature that allows a user to check out as a guest (without an account), or as a logged-in user. They should be allowed to do either, but should be asked if they want to create an account or log in if they check out as a guest.

Prompt 3 Tests -

When the user clicks on the checkout button with an empty cart, they should see an error message saying the cart is empty.
When the user clicks on the checkout button with items in the cart, they should be prompted to either log in, create an account, or check out as a guest.
When the user checks out as a guest, they should be prompted to enter their shipping and billing information, and they should see a confirmation page with their order details.
When the user logs in, their saved information (shipping, billing, and payment information) should be displayed, and they should be asked to confirm it. They should then see a confirmation page with their order details.
When the user creates a new account, they should be prompted to enter their shipping and billing information, as well as create a password. They should then see a confirmation page with their order details.
When the user logs in and their cart already has items in it, the items should be transferred to the new session after logging in.
When the user logs in and their cart already has items in it, but those items are no longer available, the user should be shown an error message and the item should be removed from the cart. -->