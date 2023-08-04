# Hosted Link https://ayush19bansal.github.io/cafe-css/

# HTML
![image](https://github.com/Ayush19bansal/cafe-css/assets/118842033/05ccc38b-03d6-4b8c-b47d-d9e083279a0c)
![image](https://github.com/Ayush19bansal/cafe-css/assets/118842033/0cf07d30-2c74-4003-a30a-0460768246a4)

Certainly! This is a snippet of HTML code that represents the structure of a webpage for a café named "CAMPER CAFE." Let's break down the different parts of the code:

1. **Structure**: The code begins with the `body` tag, indicating the start of the webpage's content. Inside the body, there's a `div` element with a class of "menu." This likely represents the main content area of the cafe's menu.

2. **Header Section**: Within the "menu" `div`, there's a `main` element. Inside the `main` element, there's an `h1` tag with the text "CAMPER CAFE," indicating the café's name. Next, there's a `p` tag with a class of "established," containing the text "Est. 2020," which could be the establishment year of the café. A `hr` tag follows, creating a horizontal line.

3. **Coffee Section**: The first `section` contains a `h2` tag with the text "Coffee," indicating the coffee section of the menu. An `img` tag displays an image of coffee. Following that, there are several `article` elements, each representing a coffee item. Each `article` includes a `p` tag with a class indicating the flavor of the coffee and another `p` tag with the price of the coffee.

4. **Desserts Section**: The second `section contains a `h2` tag with the text "Desserts," indicating the dessert section of the menu. An `img` tag displays an image of a pie. Similar to the coffee section, there are several `article` elements, each representing a dessert item. Each `article` includes a `p tag with a class indicating the type of dessert and another `p` tag with the price of the dessert.

5. **Footer**: After the menu content, there's a `hr` element with a class of "bottom-line," creating another horizontal line. A `footer` element contains two `p` tags. The first `p` tag includes an `a` tag linking to an external website (Free Code Camp's website in this case) with the text "Visit our website." 
Overall, this HTML code snippet represents the structure of a webpage for a café, displaying its name, establishment year, menu items (coffee and desserts) with prices, and contact information in the footer. The use of classes and elements like `section`, `article`, and `footer` helps organize and structure the content on the page.


# CSS
![image](https://github.com/Ayush19bansal/cafe-css/assets/118842033/886039e1-1831-47a8-ad20-55ccb2407518)
![image](https://github.com/Ayush19bansal/cafe-css/assets/118842033/5a7c0760-a510-4222-afbd-a2a460f464d7)
![image](https://github.com/Ayush19bansal/cafe-css/assets/118842033/126041a3-8b12-4598-915b-c837453b17cb)

This CSS code is responsible for styling the HTML structure we provided earlier. It defines various styles that will be applied to different elements on the webpage. Let's break down the code:

1. **Global Styles**:
   - The `body` element will have a background image, a sans-serif font family, and 20px padding.
   - `h1` elements will have a larger font size, no margin at the top, and a small margin at the bottom.
   - `h2` elements will have a slightly smaller font size.
   - Elements with the class `established` will have italic font style.
   - `h1`, `h2`, and `p` elements will be centered in terms of text alignment.

2. **Menu Styling**:
   - Elements with the class `menu` will have a specified width (80%), a background color of "burlywood," centered margins (left and right), and padding of 20px.
   - Images (`img` elements) will be centered by using auto margins on both sides.
   - `hr` elements will have a brown background color and border color, creating a brown horizontal line.
   - The class `bottom-line` will add margin at the top.

3. **Typography**:
   - Both `h1` and `h2` elements will have a specific font family (`Impact, serif`).

4. **Item Styles**:
   - Paragraphs within elements with the class `item` will be displayed as inline blocks with a margin at the top and bottom, and a font size of 18px.
   - Elements with the classes `flavor` and `dessert` will have left-aligned text and a width of 75%.
   - Elements with the class `price` will have right-aligned text and a width of 25%.

5. **Footer Styling**:
   - The `footer` element will have a font size of 14px.
   - Elements with the class `address` will have a margin at the bottom.
   - Links (`a` elements) will have a black color.
   - Visited links will also have a black color.
   - Hovering over links will change their color to brown.
   - When a link is clicked (active state), the color will change to brown.

In summary, this CSS code is used to style the café webpage's layout, typography, menu items, and footer. It applies various alignments, colors, and spacing to create an aesthetically pleasing and consistent design for the webpage.


