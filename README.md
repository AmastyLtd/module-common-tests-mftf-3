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