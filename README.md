# Debut Theme - Cart Hover

IMPORTANT! This is an advanced tutorial and is not supported by Shopify. Knowledge of web design languages such as HTML, CSS, JavaScript, and Liquid is required.

This plugin purely with html and css only for design. for function basicly with jquery and ajaxrify-cart, not much needs to be updated again in this plugin. if there is time I will renew again in the near future.
To install this plugin must not enable ajax notifications for debut theme users, for other themes you can adjust it yourself according to taste and Do with your own risk. happy coding! :)

# Code Sample
<div class="hover">
            {% include 'cart-hover' %}
</div>


# Installation

>To start the initial installation, you are required to disable the ajax cart notification feature for the debut theme. other than that you can adjust to your theme.
besides the debut themes, add this cdn to your theme.liquid you can search in
https://code.jquery.com/
for debut theme you can skip this step

1. if you have finished deactivating the feature, please install the ajaxrify-cart application in the shopify app store apps.shopify.com/ajaxrify-cart and install the application in your theme and follow the directions from ajaxrify for further installation
2. create a new snippet file with the name cart-hover and enter the code below. after entering the code, edit the header.liquid file and add the code
{% include 'cart-hover'%}
in the desired section then save
3. add the css code for the additions below then save
4. edit the theme.js file and add this code at the bottom then save and the installation is complete

> If you have any questions for this plugin, contact us at dhias@bolehdicoba.com
