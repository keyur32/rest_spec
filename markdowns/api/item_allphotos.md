# item: allPhotos


### HTTP request
```http
POST /drives/<id>/root/allPhotos
POST /shares/<id>/items/<id>/allPhotos
POST /drives/<id>/items/<id>/allPhotos

```
### Request headers
| Name       | Type | Description|
|:---------------|:--------|:----------|
| X-Sample-Header  | string  | Sample of how the HTTP headers used by the API could be displayed.|

### Request body

### Response
If successful, this method returns `200, OK` response code and [item](../resources/item.md) collection object in the response body.

### Example
Here is an example of how to call this API.
##### Request
```http
POST /drives/<id>/root/allPhotos
Content-type: application/json
Content-length: 0
```
##### Response
```json
HTTP/1.1 200 OK
Content-type: application/json
Content-length: 665
{
  "content": "content-value",
  "createdBy": {
  },
  "createdDateTime": "datetime-value",
  "cTag": "cTag-value",
  "description": "description-value",
  "eTag": "eTag-value",
  "id": "id-value",
  "lastModifiedBy": {
  },
  "lastModifiedDateTime": "datetime-value",
  "name": "name-value",
  "parentReference": {
  },
  "size": 99,
  "webDavUrl": "webDavUrl-value",
  "webUrl": "webUrl-value",
  "audio": {
  },
  "deleted": {
  },
  "file": {
  },
  "fileSystemInfo": {
  },
  "folder": {
  },
  "image": {
  },
  "location": {
  },
  "openWith": {
  },
  "photo": {
  },
  "searchResult": {
  },
  "shared": {
  },
  "specialFolder": {
  },
  "video": {
  }
}
```

<!-- uuid: 3e37a32e-f70b-4e30-bc77-c6900ffc5d89
2015-10-09 15:58:17 UTC -->