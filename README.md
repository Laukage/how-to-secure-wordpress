# Securing your WordPress site

As WordPress is widely recognized as the number one CMS globally, with a dominant market share. As of 2024, it powers about **43-45%** of all websites on the internet and holds a **60-65%** share of the CMS market, far outpacing competitors like Joomla, Drupal, and Shopify
Because of it's market share, it is heavily targetted by threat actors and therefore should be safeguarded properly as the risk is intensely heightened.

![Summary-graphs-1](https://github.com/user-attachments/assets/750ba9ce-3412-4707-a286-cc77e5e3ae28)



### TL;DR Quick tips & Recommandations:
* **1.** Spring Cleaning - Remove any unused plugins and themes.
* **2.** Update WordPress and plugions regularly, use this plugin to do that: https://wordpress.org/plugins/bulletproof-security/
* **3.** Install SSL certificate using lets' encrypt and certbot.
* **4.** Backup your WordPress site regularrly
* **5.** Use trusted WordPress plugins and Themes, Downloads+Reviews usually paints the picture.
* **6.** Securing WP-Admin Login credentials
  * **6.1.** Enable 2FA on your Administrator accounts: https://wordpress.org/plugins/wordfence/
  * **6.2.** Change the WordPress Login Page URL
  * **6.3.** Limit Login Attempts
  * **6.4.** Log Idle Users Out Automatically
  * **6.5.** Scan for Malware
* **7.** WordPress Security Configuration
  * **7.1.** Disable PHP Error Reporting
  * **7.2.** Turn File Editing off
  * **7.3.** .htaccess file
  * **7.4.** XML-RPC
  * **7.5.** Hide WordPress Version
  * **7.6.** Block hotlinking
