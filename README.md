# Shopify-Font-Awesome

Save yourself the time of having to add in the necessary liquid asset_urls to get Font Awesome to work on your Shopify store.

## Setup

Follow the steps below to setup Font Awesome on your Shopify store.

### Asset uploads

Upload all the files from the assets folder into your theme assets.

### Implement

Open your theme's _Layout > theme.liquid_, and add the following into your header.

```liquid
  <!-- Font-Awesome ================================================== -->
  {{ 'font-awesome.min.css' | asset_url | stylesheet_tag }}
```

### Enjoy!

All done! Now go ahead and use Font Awesome anywhere on your store. Take a look at these [examples](http://fortawesome.github.io/Font-Awesome/examples/).

Also look at [all the icons to choose from](http://fortawesome.github.io/Font-Awesome/icons/).

## Authors

- The awesome people who made [Font Awesome](https://github.com/FortAwesome/Font-Awesome)
- Shopified by [Adrian Pawliszko](http://nairda.ca)