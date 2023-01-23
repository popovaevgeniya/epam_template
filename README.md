# epam_template
Shop website - project for EPAM Systems internship 2020

You can view the site at the link https://popovaevgeniya.github.io/epam_template/start.html

I used HTML, CSS, JavaScript.

The site has 3 additional pages:

Catalog page https://popovaevgeniya.github.io/epam_template/catalog.html

Product page https://popovaevgeniya.github.io/epam_template/item.html

Shopping bag page https://popovaevgeniya.github.io/epam_template/shopping-bag.html

## About project
### Markup
- For screen width larger than 375px pages are used mobile layout.
- For screen width larger than 768px page is used tablet layout.
- For screen width larger than 1024px page is used desktop layout.
- Main content area stretch 1180px.
- Promo blocks (that take full width on desktop layout) stretch 1300px.
- Border separators that take full width on desktop stretch wider and “fade out” at the ends.
- HTML tags semantic is used.
- All links and buttons have noticeable hover and active state.
- Mobile version has mobile menu.

### Functionality
**Homepage (Start)**
- Click on “Nike Red” (block under header) to navigate user to Item details page.
- Click on “Caps & Hats” (block under header) to navigate user to Catalog page.
- When “Nike Red” and “Caps & Hats” blocks are resized – on table and desktop they maintain aspect ratio and take 50% of container width. For mobile - “Caps & Hats” hidden, and “Nike Red” take 100% of container and maintain its aspect ratio.
- Click on item block inside “Best offer” and “New arrivals” blockto navigate user to Item details page.
- Click on “Add to bag” button to navigate user to Shopping bag page.
- Click on “All arrivals” button to navigate user to Catalog page.
- Search field is collapsed by default on tablet. Click on magnifying glass icon to expand search field to the left. 
- “Best offer” functionality:
  - Click on Up arrow above item to change it to previous item in list.
  - Click on Down arrow above item to change it to previous item in list.
  - When item is changed – total price and discounted price are recalculated. 
  - Total price in header is calculated with respect to discount.

**Catalog**
- Hover over item block highlights item title and show overlay with “View Item” text for item image.
- Click on item block to navigate user to Item details page.
- Filters for Catalog page are implemented as dropdown lists on Desktop.
- Dropdown is opened on hover over filter bar element.
- Selected filter value are highlighted in dropdown list.

**Item details page**
- Click on “Back to catalog” link to navigate user to Catalog page.
- Click on buttons in Size and Color sections highlights it. Only one button per section can be selected.
- Click on “Add to bag” item to update items count and Total Cost in header. Items count are increased by one, Total Cost is increased by discountedPrice.
- Photos switcher is Implemented. Click on thumbnail to replace main image with full size image of itself, and make thumbnail active. (Not all images were provided in full size format.)

**Shopping bag**
- Shopping bag page displays only discounted price values.
- Hover over item block highlights item title and show overlay with “View Item” text for item image.
- Click on "Clear bag" link to remove all product items from Shopping bag and replace them with text "Your shopping bag is empty. Use Catalog to add new items".
- Total Cost from header and items count are displayed as (0).
- Click on "Buy now" is removed all product items from Shopping bag and replace them with text "Thank you for your purchase".
- Click on “+” or “-“ button in “Quantity” field to increase/decrease this number by 1.
- “Total Cost” at the bottom and Total Cost and Quantity in the header are updated accordingly to action and discountedPrice of the element item provided.
- “Total Cost” at the bottom and Total Cost and Quantity in the header are updated accordingly to Quantity of removed items and their total discountedPrice.
