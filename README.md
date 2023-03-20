# fyp-coding-challenge

Task: Create a hierarchical menu displaying products (via API) by collapsible categories with "add to favorites" functionality.

# Functionality Requirements
1. Using the Fetch promise API get JSON file. Combine into a normalized JS data structure.
2. Iterate through the data structure and generate the HTML elements and event listeners.
3. Hovering over a product name will reveal it’s sale price.
4. Clicking / tapping on any of the products should “Add to Favorites”. This state will display a heart toggle (SVG) next to the product. The list of favorite products will persist between sessions in local storage. Mock a Google Analytics custom event to capture that the product has been favorited.
