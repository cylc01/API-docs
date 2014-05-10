#AllSaints API

* All API responses can be retrieved in `JSON` and `XML`, simply change your accept header to `application/json` or `application/xml`
* All APIs are paged at 50 resources per page, select a page with the `page` parameter, or follow the links within the response.

##Product API
###http://api.allsaints.com/v1/product/

* List all AllSaints products
* Can be filtered by category name via `category` parameter
* Can be filtered by barcode number via `ean` parameter

##Category API
###http://api.allsaints.com/v1/category/

* Lists all AllSaints product categories

##Store API
###http://api.allsaints.com/v1/store/

* Lists all AllSaints retail locations
* Can be filtered by country via `country` parameter
