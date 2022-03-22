<h3>Koana - An E-Commerce and Cafe Site</h3>
<h4>Introduction</h4>
<p>This is my first assignment for Nucamp, where I will be creating an e-commerce site for my friend who is the owner of a coffee establishment in Hawaii.<p>
<p>The products are high quality coffee, tea and food items produced exclusively from Hawaii and Japan. Interestingly, the establishment is a reclaimed general shop, which preserves its original structure and the spirit of the local area. There's an interesting dynamic between the products available, the shop's environment, and its friendly music and conversation.<p>
<p>The objective of this project is to not only create a mobile first, functional design, but to encompass this dynamic.</p>

<h4>Part 1 - Landing Page</h4>
<p>Using Bootstrap and Javascript, create a mobile first landing page which includes breakpoints for larger viewports.<p>
<ul><h5>Features:</h5>
    <li>Navbar with collapsible menu on smaller viewports</li>
    <li>Highlighted menu items with captions enclosed in individual forms</li>
    <li>Individual links within each product's form which takes the user either to the online store or directly to the shopping cart</li>
    <li>Footer including links to the other pages as well as social media and contact links</li>
</ul>
<h4>Structure</h4>
<ul><h5>Navbar</h5>
    <li>Icon and logo</li>
    <li>Store</li>
    <li>Cafe</li>
    <li>About</li>
    <li>Contact</li>
    <li>Shopping cart</li>
</ul>
<ul><h5>Body</h5>
    <li>Forms with image</li>
    <li>Link to shopping cart</li>
    <li>Link to online shop</li>
</ul>
<ul><h5>Footer</h5>
    <li>Copyright</li>
     <li>Contact Link</li>
    <li>Social media links</li>
</ul>
<h5>Takeaway</h5>
<p> The challenge was getting the navbar to work properly. I wanted to to have the caret icon toggle between expanded and collapsed states which is not included with Bootstrap. I also wanted to collapse the menu if the user clicked off the menu.</p>
<p>Learned more about the Javascript methods:</p>
<p><strong>.classList (property)</strong> - which will return all classes within the element being looked at</p>
<p><strong>contains (method)</strong> - checks whether the strign contains a sequence of characters or not, returns boolean
<p><strong>offsetParent</strong> - will find the closest positioned ancestor element, working all the way up to the body, if no ancestor elements exist</p>
<p><strong>? (optional chaining)</strong> - prevents method from throwing error if value doesn't exist</p>

<h4>Part 2 - Store Page</h4>
<p>Mobile first page with Bootstrap Grid card layout. There are four categories available on the submenu: coffee, tea, food items, and merch. This menu is also collapsable, following the format of the main menu. Clicking one of the submenu categories toggles the visibility of the categories.<p>
<p>A link to a modal has been added to each card, which takes the user to add to cart window. The user will then have the choice of continuing shopping or going to checkout.</p>
<ul><h5>Features:</h5>
    <li>Navbar with collapsible menu on smaller viewports</li>
    <li>Submenu with collapsible menu which toggles viewability of each category available</li>
    <li>Individual cards of each item available including: image, header, subheader, description, price and link to add to cart</li>
    <li>Footer including links to the other pages as well as social media and contact links</li>
</ul>
<h4>Structure</h4>
<ul><h5>Navbar</h5>
    <li>Icon and logo</li>
    <li>Store<>
    <li>Cafe</li>
    <li>About</li>
    <li>Contact</li>
    <li>Shopping cart</li>
</ul>
<ul><h5>SubMenu</h5>
    <li>Coffee</li>
    <li>Tea</li>
    <li>Food Items</li>
    <li>Merch</li>
</ul>
<ul><h5>Body</h5>
    <li>Grid of cards containing each product</li>
    <li>Link to add-to-cart screen</li>
</ul>
<ul><h5>Footer</h5>
    <li>Copyright</li>
     <li>Contact Link</li>
    <li>Social media links</li>
</ul>
<h5>Takeaway</h5>
<p>Originally, I had 4 seperate pages, but eventually put all categories on the same page to keep everything in memory, and improving perforance. (tbc)</p>