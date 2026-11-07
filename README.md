: Dashboard (dashboard.html)

What it is: A small app that shows café menu items as cards. You can search, filter and sort them, and the screen updates instantly without reloading.

How it works:
1. The menu items live in a JavaScript list called items, each with a name, category, price, stock and rating.
2. A state object remembers what you've chosen: the search text, category, low-stock checkbox and sort order.
3. Whenever you type or tap something, the code filters the list, sorts it and redraws the cards. That's the "real time" part.
4. The four summary cards at the top (items shown, average price, low stock, average rating) recalculate from whatever is currently visible.
5. If nothing matches, an "empty state" message appears.

"Zero libraries" means I used plain JavaScript only, with no React, jQuery or similar.
