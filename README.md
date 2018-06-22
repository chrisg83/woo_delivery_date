# woo_delivery_date

<p>Adds Order Delivery date to the "Shipping Method" section of invoices and packing lists</p>

* "Show shipping method" should be enabled for invoices!

* This Code is Designed to Go in the WordPress Subtheme Functions.php

# The Original Code came from:
https://github.com/skyverge/wc-plugins-snippets/blob/master/woocommerce-print-invoices-packing-lists/add-order-delivery-date-to-shipping.php

# Woo Plugin Extensions:

WooCommerce Order Delivery
https://woocommerce.com/products/woocommerce-order-delivery/

WooCommerce Print Invoices & Packing lists
https://woocommerce.com/products/print-invoices-packing-lists/

# Other Plugins

* With a Slight modification to this code you can also make it work for the Pickup Date Addon for Order Delivery Date for WooCommerce Plugin By Tyche Softwares.

You just need to swap out the

```

"$delivery_date = get_post_meta( $order_id, '_delivery_date', true );"
```
The name of the hook/function is different, you will have to look up the replacement for "_ delivery_date"

* Tyche Softwares - Pickup Date Add-on for Order Delivery Date for WooCommerce Plugin https://www.tychesoftwares.com/store/premium-plugins/pickup-date-addon-order-delivery-date-woocommerce-plugin/

## My Experiences

I run into a few bugs using this plugin, it would ignore some of the delivery rules and was not passing certain credit card processing info through which was the reason I eventually switched to WooThemes New Plugin Extension By Themesquad 
