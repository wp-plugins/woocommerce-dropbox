=== WooCommerce Dropbox ===
Contributors: Vadiem Janssens
Tags: woocommerce, dropbox, downloadable product
Requires at least: 4.0
Tested up to: 4.1
Stable tag: 1.0.4
License: GPL v3

Easily choose a Dropbox file to be used as a Downloadable Product for WooCommerce.

== Description ==
The Dropbox extension for WooCommerce gives you the power and ease of use of serving your downloadable products
through the Dropbox infrastructure.
Easily choose a file from your Dropbox account via the Choose from Dropbox button and the plugin will do the rest.
Your customers will never see the files came from Dropbox and the files public link will never be exposed.

Please carefully read the [installation instructions](http://www.wordpress.org/plugins/woocommerce-dropbox/installation/).

> <strong>Before using this plugin:</strong><br>
> Dropbox has usage limits on public links when using a free, pro or business account. Please be aware of this limitation before you use this plugin.<br>
> <br>
> <strong>Free account:</strong> 20GB per day or 100,000 downloads before the link automatically expires<br>
> <strong>Pro or Business account:</strong> 200GB per day before the link automatically expires (no limit on number of downloads)<br>
> <br>
> This plugin is in best use for PDF's, Text documents, Excel Documents etc. (not for video's or other large files)<br>
> More information on the usage limits can be found [here](https://www.dropbox.com/help/4204)

= Development =
Development takes place at [this GitHub Repository](https://github.com/vjanssens/woocommerce-dropbox)

== Installation ==
Important; make sure you have installed and activated WooCommerce.

1. Upload the `woocommerce-dropbox` folder to the `/wp-content/plugins/` directory
2. Activate the WooCommerce Dropbox plugin through the 'Plugins' menu in WordPress
3. Go to [the Dropbox Developers app console](https://www.dropbox.com/developers/apps)
4. Press the blue button `Create app`
5. Choose `Drop-ins app`
6. Set a unique app-name (eg. `[storename]-woocommerce`)
7. Copy your app key
8. While on the settings tab add your domain to `Drop-ins domains`
9. Go back to your WordPress site
10. Go to `WooCommerce` -> `Settings`
11. Open the tab `Integration` -> `Dropbox Integration`
12. Paste your API-key and save changes.

Dropbox for WooCommerce is now installed and configured.

> Still having trouble with the installation? Plugin not working as you would expect?
> Please open a support ticket in [the support forums](https://wordpress.org/support/plugin/woocommerce-dropbox)

== Changelog ==

= 1.0.4 =
* Tested plugin for WordPress version 4.1

= 1.0.3 =
* Fix URL encoding bug

= 1.0.2 =
* Bugfixes

= 1.0.1 =
* Bugfixes

= 1.0 =
* Initial version