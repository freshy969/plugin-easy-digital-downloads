# Easy Digital Downloads plugin for Paylike

This plugin is *not* developed or maintained by Paylike but kindly made
available by a user.

Released under the GPL V3 license: https://opensource.org/licenses/GPL-3.0


## Supported Easy Digital Downloads versions

- \>= 2.7.5

## Installation

1.Once you have installed Easy Digital Downloads on your Wordpress setup, follow these simple steps:
  Signup at (paylike.io) [https://paylike.io] (it’s free)
  
  1. Create a live account
  1. Create an app key for your Easy Digital Downloads website
  1. Upload the plugin files to the `/wp-content/plugins/edd-paylike` directory.
  1. Activate the plugin through the 'Plugins' screen in WordPress.
  1. Insert the app key and your public key in the Payment Gateways settings for the Paylike payment plugin
  

## Updating settings

Under the Easy Digital Downloads paylike settings, you can:
 * Update the payment method text in the payment gateways list
 * Update the title that shows up in the payment popup 
 * Add test/live keys
 * Change the capture type (Captured/Preapproved)
 
 
 ## Transactions 

 There are three transaction operations which you can do:
1. Capture - in order to capture a preapproved payment, you can click "Process Preapproved" on the payment history page for that specific order in the WordPress admin.
2. Void - the only way we void a transaction is when this is preapproved, but not "captured". the button for "Cancel Preapproval" is on payment history page.
3. Refund - in order to refund, you need to have a order with the status "Completed", move it to "Refunded", check the option that appears below "Refund in Paylike", and click update.
 
  