# catalog-implementor-survey
A survey of non-standardized catalog API's and provider metadata for imagery and other geo-asset catalogs. This work is meant
to inform the Spatio-Temporal Asset Metadata and Catalog work, see [STAC](https://github.com/radiantearth/stac-spec) repo.

This repo contains two folders:

[catalog-apis/](catalog-apis/) is a survey of API's that serve up imagery. Each provides an overview of their experiences
providing a search api for imagery or other geospatial assets. Where possible there is also an OpenAPI 2.0 / swagger spec.

[json-metadata/](json-metadata/) is a survey of the JSON responses that often come from the API's (though may come from 
other flat files and other locations as well). All were accessed online, and are subject to the rights of the data owner,
and are simply meant to be informative of what everyone is doing.

Contributions are encouraged, listing other API's and JSON metadata of interest. Non-json metadata can also be contributed,
though probably in another folder, so that the json ones can all be easily compared.


