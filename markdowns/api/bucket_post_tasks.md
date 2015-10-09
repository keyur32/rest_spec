# Create Task

Use this API to create a new Task.
### HTTP request
```http
POST /buckets/<id>/tasks
POST /plans/<id>/buckets/<id>/tasks
POST /users/<objectId>/plans/<id>/buckets/<id>/tasks

```
### Request headers
| Name       | Type | Description|
|:---------------|:--------|:----------|
| X-Sample-Header  | string  | Sample of how the HTTP headers used by the API could be displayed.|

### Request body
In the request body, supply a JSON representation of [Task](../resources/task.md) object.


### Response
If successful, this method returns `201, Created` response code and [Task](../resources/task.md) object in the response body.

### Example
##### Response
Here is an example of the response.
```json
HTTP/1.1 201 Created
Content-type: application/json
Content-length: 641
{
  "createdBy": "createdBy-value",
  "assignedTo": "assignedTo-value",
  "planId": "planId-value",
  "bucketId": "bucketId-value",
  "title": "title-value",
  "orderHint": "orderHint-value",
  "assigneePriority": "assigneePriority-value",
  "percentComplete": 99,
  "startDate": "datetime-value",
  "assignedToDate": "datetime-value",
  "createdDate": "datetime-value",
  "assignedBy": "assignedBy-value",
  "dueDate": "datetime-value",
  "hasNotes": true,
  "previewType": "previewType-value",
  "completedDate": "datetime-value",
  "numberOfReferences": 99,
  "appliedCategories": {
  },
  "id": "id-value",
  "version": "version-value"
}
```

<!-- uuid: 86e983d0-b58c-4535-8efc-7c2a722b9979
2015-10-09 15:58:16 UTC -->