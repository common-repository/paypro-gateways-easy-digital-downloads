=== PayPro Gateways - Easy Digital Downloads ===
Contributors: paypro
Tags: paypro, payments, betalingen, psp, gateways, woocommerce, ideal, bank transfer, paypal, afterpay, creditcard, visa, mastercard, mistercash, bancontact, sepa, overboeking, incasso
Requires at least: 3.8
Tested up to: 5.5
Stable tag: 1.0.3
License: GPLv2
License URI: http://opensource.org/licenses/GPL-2.0

With this plugin you easily add all PayPro payment gateways to your Easy Digital Downloads webshop.

== Description ==

This plugin is the official PayPro plugin for Easy Digital Downloads. It is easy to use, quick to install and actively maintained by PayPro. 

Currently the plugin supports the following gateways:

* iDEAL
* iDEAL QR 
* PayPal
* Bancontact
* Sofort
* Afterpay
* SEPA Overboeking
* Mastercard
* Visa

= Features =

* Support for all PayPro payment methods
* Settings for each payment method
* WordPress Multisite support
* Translations for English and Dutch
* Test mode support
* Debug mode for easy debugging
* Automatic status changes

= Note =

In order to use this plugin you need to have a PayPro account and you need to have setup a 'Webshop' in the PayPro dashboard.

== Installation ==

= Requirements =

* PHP version 5.3 or greater
* For EDD version 2.9.x : Wordpress 4.4 or greater
* For EDD version 3.0.x : Wordpress 4.7 or greater

= Automatic installation =

1. In the WordPress admin panel go to **Plugins** -> **Add New**. Search for ‘PayPro Gateways – Easy Digital Downloads', and click **Install Now**.
2. Click Activate after installation.
3. Go to General Settings under Plugins -> Easy Digital Downloads label.
4. Make sure Currency is set to Euros (€) under General -> Currency.
5. Set your PayPro API key in PayPro Settings under Payment Gateways -> PayPro .
6. Now enable the payment methods you want in Payment Gateways under Payment Gateways -> General.
7. Your webshop is now ready to use PayPro gateways.

= Manual installation =

1. Downalod the plugin.
2. In the WordPress admin panel go to Plugins -> Add New. Click Upload Plugin to upload the plugin file, and click Install Now.
3. Click Activate after installation.
4. Go to General Settings under Plugins -> Easy Digital Downloads label.
5. Make sure Currency is set to Euros (€) under General -> Currency.
6. Set your PayPro API key in PayPro Settings under Payment Gateways -> PayPro .
7. Now enable the payment methods you want in Payment Gateways under Payment Gateways -> General.
8. Your webshop is now ready to use PayPro gateways.

Do you need help installing the PayPro plugin, please contact support@paypro.nl

== Frequently Asked Questions ==

= Where do I find my PayPro API key? =
You can find your PayPro API key in your dashboard at 'Webshop Koppelen' in the PayPro dashboard.

= When do I need to add a product ID? =
If you want to make use of affiliate marketing or you want to use the mastercard, visa or sofort gateway you have to supply a product ID.

= Where do I find my product ID? =
You can find your product id at 'Webshop Koppelen' in the PayPro dashboard.

== Screenshots ==

1. Overview of the PayPro settings.
2. Settings for an individual payment method.
3. Example of the checkout payment method selection.

== Changelog == 

= 1.0.3 =

Add check if EDD plugin is active before initializing

= 1.0.2 =

First stable release
