# Common Tests MFTF3

<h3>31 specific tests, for checking basic magento functionality with Amasty extensions.<h3>
<h2>Installation</h2>
<h3>Pre-conditions:</h3>
Install MFTF: [Getting started](https://developer.adobe.com/commerce/testing/functional-testing-framework/getting-started/) <br>
We recommend that you turn off the Magento_TwoFactorAuth module for ease of testing or configure credentials: [Configuring two-factor authentication](https://developer.adobe.com/commerce/testing/functional-testing-framework/two-factor-authentication/)
<h3>Instruction:</h3>
<p>To install the package, run the following commands:</p>
<code>composer require amasty/module-common-tests-mftf-3</code><br>
<code>php bin/magento setup:upgrade</code><br>
<code>php bin/magento setup:di:compile </code><br>
<code>php bin/magento setup:static-content:deploy (your locale)</code><br>
<h2>Run tests</h2>
<p>To run the tests, run the following command:</p>
<p>In Magento Commerce:</p> 
<code>vendor/bin/mftf run:group AmDef -r</code><br>
<p>In Open Source Magento:</p>
<code>vendor/bin/mftf run:group AmDefCE -r</code><br>

<h2>Other Amasty extensions</h2>
-> <a href="https://amasty.com/google-shopping-feed-for-magento-2.html" target="_blank">Google Shopping Feed for Magento 2</a><br>
-> <a href="https://amasty.com/google-rich-snippets-for-magento-2.html" target="_blank">Google Rich Snippets for Magento 2</a><br>
-> <a href="https://amasty.com/google-page-speed-optimizer-powered-by-speedsize-for-magento-2.html" target="_blank">GPSO powered by SpeedSize</a><br>
-> <a href="https://amasty.com/google-page-speed-optimizer-for-magento-2.html" target="_blank">Google Page Speed Optimizer for Magento 2</a><br>
-> <a href="https://amasty.com/google-map-for-magento-2.html" target="_blank">Google Map for Magento 2</a><br>
-> <a href="https://amasty.com/google-invisible-recaptcha-for-magento-2.html" target="_blank">Google Invisible reCaptcha for Magento 2</a><br>
-> <a href="https://amasty.com/google-indexing-api-for-magento-2.html" target="_blank">Google Indexing API for Magento 2</a><br>
-> <a href="https://amasty.com/google-customer-reviews-for-magento-2.html" target="_blank">Google Customer Reviews for Magento 2</a><br>
-> <a href="https://amasty.com/google-automated-discounts-for-magento-2.html" target="_blank">Google Automated Discounts Premium for Magento 2</a><br>
-> <a href="https://amasty.com/google-account-login-for-magento-2.html" target="_blank">Google Account Login for Magento 2</a><br>
-> <a href="https://amasty.com/gift-wrap-for-magento-2.html" target="_blank">Gift Wrap for Magento 2</a><br>
-> <a href="https://amasty.com/gift-card-for-magento-2.html" target="_blank">Gift Card for Magento 2</a><br>
-> <a href="https://amasty.com/geoip-for-magento-2.html" target="_blank">GeoIP Redirect for Magento 2</a><br>
-> <a href="https://amasty.com/generate-and-import-coupons-for-magento-2.html" target="_blank">Generate and Import Coupons for Magento 2</a><br>
-> <a href="https://amasty.com/magento-geoip-redirect.html" target="_blank">GeoIP Redirect</a><br>
-> <a href="https://amasty.com/magento-gdpr.html" target="_blank">GDPR</a><br>
-> <a href="https://amasty.com/magento-full-page-cache.html" target="_blank">Full Page Cache</a><br>
-> <a href="https://amasty.com/magento-form-builder.html" target="_blank">Custom Form</a><br>
