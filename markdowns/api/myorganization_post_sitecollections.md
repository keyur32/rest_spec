# Create SiteCollection

Use this API to create a new SiteCollection.
### Prerequisites
The following **scopes** are required to execute this API: 
### HTTP request
<!-- { "blockType": "ignored" } -->
```http
POST /myOrganization/siteCollections

```
### Request headers
| Name       | Type | Description|
|:---------------|:--------|:----------|
| X-Sample-Header  | string  | Sample HTTP header. Update accordingly or remove if not needed|

### Request body
In the request body, supply a JSON representation of [SiteCollection](../resources/sitecollection.md) object.


### Response
If successful, this method returns `201, Created` response code and [SiteCollection](../resources/sitecollection.md) object in the response body.

### Example
##### Request
Here is an example of the request.
<!-- {
  "blockType": "request",
  "name": "create_sitecollection_from_myorganization"
}-->
```http
POST /myOrganization
```
In the request body, supply a JSON representation of [SiteCollection](../resources/sitecollection.md) object.
##### Response
Here is an example of the response.
<!-- {
  "blockType": "response",
  "truncated": false,
  "@odata.type": "microsoft.graph.sitecollection"
} -->
```http
HTTP/1.1 201 Created
Content-type: application/json
Content-length: 22

{
  "id": "id-value"
}
```

<!-- uuid: 93713206-fa02-48df-97bb-72304b6d766e
2015-10-25 12:56:09 UTC -->
<!-- {
  "type": "#page.annotation",
  "description": "Create SiteCollection",
  "keywords": "",
  "section": "documentation",
  "tocPath": ""
}-->