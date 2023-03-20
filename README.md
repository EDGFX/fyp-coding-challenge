# fyp-coding-challenge

Task: Create a hierarchical menu displaying products (via API) by collapsible categories with "add to favorites" functionality.

# Functionality Requirements
1. Using the Fetch promise API get JSON file. Combine into a normalized JS data structure.
2. Iterate through the data structure and generate the HTML elements and event listeners.
3. Hovering over a product name will reveal it’s sale price.
4. Clicking / tapping on any of the products should “Add to Favorites”. This state will display a heart toggle (SVG) next to the product. The list of favorite products will persist between sessions in local storage. Mock a Google Analytics custom event to capture that the product has been favorited.

# Things I Would Have Done Better With More Time
1. I've never encountered JSON-LD before during my time as a web developer. While I understand the overall concept in practice (similar to SEO-centric schema markup and meta data for website pages), I didn't really understand how to properly implement this within the context of this coding challenge given all of the products and categories present. 

2. Accessibility by way of keyboard navigation. The requirements for accessibility are relatively new for me given their more prominent emergence in the web development space due to a flurry of lawsuits that have been brought forth over the last few years. In my current role, we do our best to make sure we abide by as many WCAG 2.x and ADA-compliance standards as possible within the WordPress framework. Aside from design-related guidelines such as proper contrast, text spacing, and alt text, we largely rely on accessiBe software (https://accessibe.com/) to do most of the heavy lifting for us. As such, properly implementing this at the more foundational level through vanilla JS, HTML, and CSS would've required me to do a lot more research and testing which would have come at a considerate time investment.
