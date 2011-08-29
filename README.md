Shopjfy - Caffeinated Shopify Bindings

The Shopjfy library allows Android developers to programatically access the Admin section of Shopify stores.

The API is implemented as JSON over HTTP using the CRest library.

# Usage #

For an example of how to make API calls, take a look at OrdersAPIEndpointTest.java

# MGAssetName.java #

These files were machine generated using the fixtures data from the test assets.  If you need to add additional
functionality to a model, you should make your changes to the subclass AssetName.java.

# Known Issues #

* The only known verb that works is GET, so developers have read-only access to Shopify stores.
* There currently isn't a way to get handshaking to work in order to generate a user password for
  a shop.  It should be possible by setting your callback URL to be yourapp://completeauth or something
  similar.  [Check out Step 4 of this tutorial to get an idea of how it should work](http://donpark.org/blog/2009/01/24/android-client-side-oauth).