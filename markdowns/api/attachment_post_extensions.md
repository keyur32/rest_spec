# Create Extension

Use this API to create a new Extension.
### HTTP request
```http
POST /users/<objectId>/Events/<Id>/Attachments/<Id>/Extensions
POST /groups/<objectId>/Events/<Id>/Attachments/<Id>/Extensions
POST /users/<objectId>/Messages/<Id>/Attachments/<Id>/Extensions

```
### Request headers
| Name       | Type | Description|
|:---------------|:--------|:----------|
| X-Sample-Header  | string  | Sample of how the HTTP headers used by the API could be displayed.|

### Request body
In the request body, supply a JSON representation of [Extension](../resources/extension.md) object.


### Response
If successful, this method returns `201, Created` response code and [Extension](../resources/extension.md) object in the response body.

### Example
##### Response
Here is an example of the response.
```json
HTTP/1.1 201 Created
Content-type: application/json
Content-length: 22
{
  "Id": "Id-value"
}
```

<!-- uuid: 118f422e-5f8e-4840-9062-ea6a91a63013
2015-10-09 15:58:16 UTC -->