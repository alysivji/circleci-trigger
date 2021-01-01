# CircleCI Trigger


```bash
curl -u ${CIRCLECI_TOKEN}: -X POST --header "Content-Type: application/json" -d '{
 "parameters": {
   "deploy": true,
   "environment": "development",
   "tag": "my-branch"
 }
}' https://circleci.com/api/v2/project/alysivji/circleci-trigger/pipeline
```
