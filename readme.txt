=== Integrate Razorpay for Contact Form 7 ===
Contributors: vinaysaini30, abhilashg90
Tags: razorpay, contact form 7, donation, payment, payments, online payment, contact form, contact form razorpay, contact form 7 razorpay 
Requires at least: 5.6
Tested up to: 6.5.2
Stable tag: 2.0.3
Requires PHP: 7.2
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html
 
Seamlessly integrates Razorpay with Contact Form 7

== Description ==

This Razorpay Add-on is a WordPress plugin for Contact Form 7.  It seamlessly integrates the Razorpay Payment Gateway with the forms created through Contact Form 7 plugin. Developers can now add this for easy payments in their Contact Form 7 on WordPress platform for their website’s customers. 

Note: The sole dependency of this plugin is “Contact Form 7”. It is mandatory to install the same first and then continue with the Razorpay Addon.

If you want any customization or found any bugs you can contact us [here](https://www.codolin.com/contact?utm_source=wordpress&utm_medium=plugin&utm_campaign=integrate-razorpay-cf7&utm_id=integrate-razorpay-cf7).

= Features =

You will have the following features in the Razorpay panel (payments and settings) after successful installation- 

* Individual activation/deactivation of Razorpay in different forms
* Individual detail addition (item id, item price, name, etc.) in different forms
* Both “Test” or “Live” mode 
* API integration credentials inputs of ID and secret key present
* Company name can be added
* “Return URL” option for a landing page after payment
* All the payments listed under Razorpay Payment page on WordPress dashboard
* Payments can be filtered according to forms, status, dates, etc.
* View more information related to individual payments in a popup.
* A payment can be searched using internally generated Order ID. 
* “Error” upon entering wrong credentials 

= Key Features in Premium Edition =

* **Pre-defined Pricing Options:** Enable users to select from preset pricing options configured within the form, overriding the default item price. Ideal for offering multiple price points predefined by the administrator.
* **User-defined Pricing:** Allow users to enter their own price, providing greater flexibility and enabling custom pricing based on user input.
* **FormData Collection:** Efficiently gather and store user-submitted form data related to payments. This feature ensures you capture all relevant details provided by users during the Razorpay payment process, offering valuable insights into their interactions and enhancing your record-keeping capabilities.
* **Export CSV:** Easily export comprehensive order, payment, and user-submitted form data into a CSV file for efficient record-keeping and analysis.
* **Custom Order ID Prefix:** Set custom prefixes for Order IDs to better organize and track your orders. Personalize your order management system with identifiable prefixes.
* **Order Shortcode:** Display detailed order information such as Order ID, Item ID, Item Name, and Item Price on the Thank You page using a simple shortcode.
* **Order Success Redirect:** Customize the redirect URL after a successful payment, directing users to either an internal Thank You page or an external URL of your choice.
* **Customize Razorpay Payment Popup:** Personalize the Razorpay Payment Popup to match your website’s branding by customizing the logo, theme color, and backdrop color.
* **Autofill Customer Information:** Automatically pre-fill customer details such as Name, Email, and Phone in the Razorpay Payment Popup, streamlining the payment process by reducing the need for repeated data entry.

**[Get Premium](https://cf7rzppa.codolin.com/?utm_source=plugin_user&utm_medium=plugin&utm_campaign=upsell)** with various features & support.

== Installation ==

* Upload the plugin zip file through the WordPress admin panel “Upload Plugin” button.
* Activate the plugin from the plugin list page.
* You’ll notice a “Razorpay” column on the form editing panel. Also, a “Razorpay Settings” and “Razorpay Payments” panels will show on your left WordPress Dashboard under the Contact Form 7 Plugin.
* Choose the mode (sandbox or live).
* If you already have a Razorpay account, provide necessary Razorpay API credentials (key ID and key secret) received from your Razorpay Dashboard to make use of Razorpay API services. You can also add the company name and return URL. 
* Upon integration, you are ready to use the gateway for different forms.
* Enable the Razorpay payment checkbox and provide necessary product/item details per form that has been created through Contact Form 7.  

== Frequently Asked Questions ==

== Screenshots ==

1. Razorpay Settings per Contact Form 7
2. Razorpay General Settings
3. Razorpay Payments list page
4. Individual Razorpay Payment detail view
5. Find Payment based on internal order number
6. Filter Payments based on Contact Form 7
7. Filter Payments based on status(success | failure | pending)

== Changelog ==

= 2.0.3 - 2024-05-21 =
* Updated: Feature contents.

= 2.0.2 - 2024-05-14 =
* Fixed: Bug related to rzp activation check.

= 2.0.1 - 2024-04-12 =
* Added: New sections. Compatible with V-p107.

= 2.0.0 - 2024-04-05 =
* Added: New sections. Compatible with V-p106.
* Fixed: Payment pop loader.

= 1.0.9 - 2024-03-08 =
* Added: New sections. Compatible with V-p105.

= 1.0.8 - 2024-03-06 =
* Added: New sections. Compatible with V-p104.

= 1.0.7 - 2024-03-04 =
* Added: New sections. Compatible with V-p103.

= 1.0.6 - 2024-02-21 =
* Added: New sections. Compatible with V-p102.

= 1.0.5 - 2024-02-13 =
* Added: New sections. Compatible with V-p101.
* Tested: Compatible with wordpress version(6.4.3).

= 1.0.4 - 2024-02-02 =
* Added: New sections.

= 1.0.3 - 2024-01-29 =
* Added: New sections. Compatible with V-p100.
* Tested: Compatible with wordpress version(6.4.2). 

= 1.0.2 - 2023-10-23 =
* Added: Compatible with wordpress version(6.3.2).

= 1.0.1 - 2022-02-04 =
* Fixed: Razorpay payment poup not triggering.
* Changed: Razorpay default mode set to Test.

= 1.0 - 2022-02-02 =
* Added: First commit.