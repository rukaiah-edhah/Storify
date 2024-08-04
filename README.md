# Storify - Pantry Tracker App

This is the second project of my Headstarter Fellowship, where we used Firebase for the backend database, Material UI for the design, Next.js for the application framework, and Vercel for deployment.

## Project Overview

### Purpose

The goal of this project was to create a Pantry Tracker as an inventory management system to learn and write clean CRUD operations.

### CRUD Operations

1. **Create**: Add new items to the pantry inventory.
   - Users can add new items with a specified name and quantity.
   - The `addItem` function checks if the item exists and either increments its quantity or creates a new entry.

2. **Read**: View all pantry items.
   - Users can view a list of all items in the pantry.
   - The `updateInventory` function retrieves all items from Firebase and displays them.

3. **Update**: Modify the quantity of existing items.
   - Users can increase or decrease the quantity of any item.
   - The `addItem` function increments the quantity, and the `removeItem` function decrements the quantity or deletes the item if the quantity reaches zero.

4. **Delete**: Remove items from the pantry.
   - Users can delete items from the inventory if the quantity is zero.
   - The `removeItem` function handles the deletion process.

Additionally, users can search and filter items to quickly find what they need.