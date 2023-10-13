# Module 2 Coding Assignment - Shopping List App

**Assignment Instructions:** The goal of this assignment is to create a dynamic shopping list application that allows users to move items from a "To Buy" list to an "Already Bought" list. The application should be developed using AngularJS and follow specific rules and guidelines.

## General Idea

The idea of this assignment is to create a "check-off" shopping list application. Imagine being in a store with a shopping list that allows you to mark items as "bought." Instead of physically checking items off, the bought items will be moved to the "Already Bought" list.

My HTML page should display two lists: "To Buy" and "Already Bought."

- The "To Buy" list should be pre-populated with at least 5 items, each with a name and quantity.
- Next to each item in the "To Buy" list should be a "Bought" button. When clicked, the item should move to the "Already Bought" list.
- The "Already Bought" list should be initially empty and display the message "Nothing bought yet." The message should appear only when the list is empty.
- Once an item is bought and appears in the "Already Bought" list, it should be displayed in the format "Bought item_quantity item_name."
- If the user "buys" every item on the "To Buy" list, the message "Everything is bought!" should be displayed instead of an empty "To Buy" list.

## Rules

Breaking these rules will result in failing the assignment:

1. Do not use regular HTML `onclick` attributes to bind behavior to the button. Use AngularJS for behavior binding.
2. Do not look up anything in the DOM of the browser at any point in your JavaScript code.
3. Implement more than one controller to handle both lists and data. Create a service to share data between controllers.

## Steps

To complete the assignment, follow these steps:

1. Create a GitHub account and a repository for this assignment.
2. Set up your GitHub repository for GitHub Pages to host and view your finished web page.
3. Create a folder in your repository to contain your solution for this assignment.
4. Copy the provided HTML/CSS from the assignment2-starter-code folder into your solution folder (or create your own HTML/CSS).
5. Import AngularJS into your project.
6. Declare the `ng-app` on the HTML or body element and name your app "ShoppingListCheckOff."
7. Create `app.js` and declare two controllers using the `controller as` syntax: "ToBuyController" and "AlreadyBoughtController." Implement data sharing between these controllers using a service named "ShoppingListCheckOffService."
8. Use the service to store both "to buy" and "bought" items in separate arrays.
9. Implement the functionality to move items from the "To Buy" list to the "Already Bought" list.
10. Use AngularJS directives like `ng-if` and `ng-repeat` to display and hide messages and loop over the items.
11. Ensure that your JavaScript code is inside an IIFE and that your dependency injections are protected from minification.
12. Once you're satisfied with your solution, add, commit, and push your code to your GitHub repository.


Happy coding!
