# Changelog #

The changelog below will provide updates on what is being worked on and the outcome of these features been added to future releases. Checkout the [CoCart blog](https://cocart.xyz/news/) for updates on new coming releases. Feedback is always appreciated. 😄

## v2.1 - RC 1 ##

* NEW: Added support for guest carts with a new endpoint to retrieve those carts.
* NEW: Able to transfer a cart from your headless store to the web.
* NEW: Can now add items to cart using a products SKU ID.
* NEW: When an item is updated, removed or restored... the cart totals are re-calculated.
* Dev: Added filter `cocart_add_to_cart_validation` to allow plugin developers to pass their own validation before item is added to the cart.
* Dev: Added filters to override the product name `cocart_product_name` and product title `cocart_product_title` when getting the cart contents.
* Dev: Added filter `cocart_item_thumbnail_src` to override the source URL of the product thumbnail when getting the cart contents.
* Dev: Added filter `cocart_add_to_cart_quantity` to override the quantity when adding an item.
* Dev: Added filter `cocart_add_cart_item_data` so other plugins can pass cart item data when adding an item.
* Dev: Added filters so the returned response messages can be changed.
* Dev: Added conditional filter for returning a cart item.