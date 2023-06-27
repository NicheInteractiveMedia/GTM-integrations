# Shopping Gives Custom Template for GA4

An easy way to track clicks and views on the ShoppingGives Widget.

This custom tag allows you to track all the ShoppingGives Widget interactions, without the hassle of configuring each tag.

The tag needs your GA4 Measurement ID to collect the data correctly. 

The tag also requires two triggers to function propperly:

  - An Element Visibility trigger with the following configuration:
    - Selection method: CSS Selector
    - Element selector: .sg-widget
    - When to fire this trigger: Once per page

  - A Click trigger that fires on all clicks

This is based on a previous version for UA: https://github.com/NicheInteractiveMedia/GTM-Template
