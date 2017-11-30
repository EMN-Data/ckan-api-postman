## Setup Instructions

1. Download Postman https://www.getpostman.com/apps. It's free to use (you may pay for more features)
2. Open Postman and click Import > Import From Link
3. Copy and paste the link below into form and Import

`https://www.getpostman.com/collections/6177c70a5ed4d84ae5ac`

4. Click the settings gear icon and select Manage environment
5. Click Add
6. Name this environment, e.g. datahub.h2awsm.org
7. Click the orange Bulk Edit button above the table of Key Values
8. Copy and paste the set of key:values below into the form
9. Click the orange Key-Value Edit button to return to the table view
10. Update the api-key value with your Datahub API key

```
host:https://datahub.h2awsm.org
api-version:3
base-url:{{host}}{{api-root}}
api-root:/api/{{api-version}}/action
api-key:00000000-0000-0000-0000-000000000000
project-admin:00000000-0000-0000-0000-000000000000
project-editor:00000000-0000-0000-0000-000000000000
project-member:00000000-0000-0000-0000-000000000000
project-no-role:00000000-0000-0000-0000-000000000000
package-admin:00000000-0000-0000-0000-000000000000
package-editor:00000000-0000-0000-0000-000000000000
package-member:00000000-0000-0000-0000-000000000000
package-no-role:00000000-0000-0000-0000-000000000000
resource-admin:00000000-0000-0000-0000-000000000000
resource-editor:00000000-0000-0000-0000-000000000000
resource-member:00000000-0000-0000-0000-000000000000
resource-no-role:00000000-0000-0000-0000-000000000000
```

To update your Postman collection reimport with the link and select replace the existing collection.
