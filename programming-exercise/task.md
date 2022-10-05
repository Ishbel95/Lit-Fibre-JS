// JavaScript exercise
// This function mysteriously got wiped from our online ordering system,
// and there's no history of it in source control...
// The function takes an array of product names (see the calls below).
// It needs to calculate the order total both in terms of price and of calories and return them in an object:
// {
// totalPrice: ???,
// totalCalories: ???
// }
// The bakeryProducts and cafeProducts arrays contain all the details you'll need about the business' products (pretend the data is from a database or REST API).
//
// For extra points, check if any promotions (from the promotions array) can be applied, based on the products that are passed in, and reflect any change in total price.
// Promotions should override the price of a pair of products,
// where one of the products is found in the "applicableFromBakery" array and the other is found in the "applicableFromCafe" array.
// Example:
// products = ["toast", "tea", "blueberry muffin"]
// totalPrice would normally be 1.0 (toast) + 1.0 (tea) + 2.5 (muffin) = 4.5
// With the "breakfast to go" promotion, we can override the cost of the tea and toast with 1.8:
// totalPrice becomes 1.8 (toast + tea promotion) + 2.5 (muffin) = 4.3
//
// A basic implementation could search for valid pairs of products and apply promotions in the order that it finds them
// A more advanced version could calculate the ideal promotions to apply, resulting in the lowest possible total
//
// Do as little or as much as you feel like of this exercise, the point isn't to pass/fail your JavaScript skills,
// but to see how you go about using the language and how you approach solving a given problem
