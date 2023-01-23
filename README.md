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

**Catalog**
- Hover over item block highlights item title and show overlay with “View Item” text for item image.
- Click on item block to navigate user to Item details page.
- Filters for Catalog page are implemented as dropdown lists on Desktop.
- Dropdown is opened on hover over filter bar element.
- Selected filter value are highlighted in dropdown list.

**Item details page**
- Click on “Back to catalog” link to navigate user to Catalog page.
- Click on buttons in Size and Color sections highlights it. Only one button per section can be selected.
- Click on "Add to bag" item to update items count and Total Cost in header. Items count are increased by one, Total Cost is increased by discountedPrice.
