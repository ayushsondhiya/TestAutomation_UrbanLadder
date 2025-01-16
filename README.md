# Hackathon Project: Display Bookshelves

## Problem Statement
Display the name and price of:
1. Bookshelves below Rs. 15000, including out of stock, with storage type as open.
2. Take the first 3 study chair details with the highest recommendation. If more than one item has the same price, include those details as well.

## Detailed Description
### Task 1: Display Bookshelves
1. Display the name and price of the first 3 bookshelves below Rs. 15000, with storage type as open, and exclude out of stock items.

### Task 2: Retrieve Sub-menu Items
1. From the Collections menu, retrieve all sub-menu items under "Being-At-home" and store them in a list. Display the list.

### Task 3: Customize Gift Card
1. Choose "Birthday/Anniversary" gift card.
2. Customize the gift card and fill in the "From" and "To" details with one invalid input (e.g., invalid email).
3. Capture and display the error message.

## Key Automation Scope
- Handling alerts
- Drag and drop functionality
- Search option
- Extracting menu items and storing them in collections
- Navigating back to the home page
- Scrolling down the web page
- Filling forms (in different objects on the web page)
- Capturing warning messages

## Steps to Execute
1. **Bookshelves Display**:
   - Open the Urban Ladder home page.
   - Search for bookshelves.
   - Apply filters to show items priced below Rs. 15000.
   - Apply filters to exclude out of stock items.
   - Select the category "Wall Shelves" or similar.
   - Sort items by price from high to low.
   - Fetch the top 3 items and print their details.

2. **Retrieve Sub-menu Items**:
   - Open the Urban Ladder home page.
   - Click on the Collections menu.
   - Retrieve and display all sub-menu items under "Being-At-home".

3. **Check ULServices**:
   - Open the Urban Ladder home page.
   - Click on the UlServices.
   - Scroll down to form.
   - Fill out all the details.
   - Click on Submit button
   - 
## Technologies Used
- Selenium
- Java
- Maven
- TestNG
- Apache POI (for data-driven testing)
- Page Object Model (POM)

## How to Run
1. Clone the repository.
2. Open the project in your preferred IDE.
3. Update the `pom.xml` file with the required dependencies.
4. Run the test cases using TestNG.

## Contributors
- Ayush Sondhiya

## License
This project is licensed under the MIT License.
