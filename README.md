# McLiquid Shopify Theme

The McLiquid Theme is for demonstration purposes. It is built by Shopify to highlight some of the platform's key features and highlight the performance of the platform.

**Demo link**: https://mcliquid.myshopify.com/

## Interesting features

* Use of custom Category metaobjects that are used to create a nested navigation.
  * Each metaobject has pointers to its children categories (also Category metaobjects).
  * We make use of repeating blocks to render those children categories. 
* Each category metaobject has an associated (smart) collection field to be rendered on the category metaobject page.
* Various performance optimizations (e.g. preload, prefetch, speculation rules).

## License

This theme is licensed under the [MIT License](LICENSE).
