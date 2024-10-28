
# Variety Food Truck Ordering Program

## **Overview**

This program allows users to place orders from a menu with multiple categories, including **Snacks, Meals, Drinks, and Desserts**. The program guides the user through the menu, allowing them to select items, specify quantities, and provides a summary and total cost for their order.

## Features

  **Menu Categories:** The menu is organized into categories and subcategories, making it easy for users to navigate.
  
  **Itemized Orders:** Each item in the order is stored with its name, price, and quantity, enabling detailed billing.
  
  **Continuous Ordering:** Users can add multiple items to their order in a single session.
  
  **Order Summary:** After completing the order, a summary is printed, listing each item, its quantity, and the total cost.

## Data structures used

1. Menu dictionary which holds the food category, options within the category and its price
2. Order list - populated when the customer places the order
3. Menu_items - is a dictionaly that holds the menu items displayed when the customer chooses a category and the options within the category

## Program Structure

1. The program starts with a "Welcome message" and the menu of the food category for the customer to choose.
2. When the customers chooses a food category, the customer is then asked to choose an item within that category and the quantity.
3. The menu item and the quantity is stored in the order list.
4. The customer is then given an option to continue or close the order.
5. If the customer wantes to continue, the menu options are again displayed and the order list is filled with the next order.
6. If the customer chooses not to continue, the receipt is printed and the total cost of the order is displayed.
7. User input is also validated for the correctness or "Item numbers", "Menu options" and correct responses. 
