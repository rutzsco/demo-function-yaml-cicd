# Sample YAML pipelines with webhook trigger.

### 1. Create Webhook Service Connection

![ServiceConnectionInfo](ServiceConnectionInfo.png)

### 2. Create Pipeline with Webhook Trigger

TBD

### 3. Test Webhook Trigger

Request Url Template - "https://dev.azure.com/<ADOOrganization>/_apis/public/distributedtask/webhooks/<WebHookName>?api-version=6.0-preview"

![WebHookPostman](WebHookPostman.png)

### 4. Create EventGrid Webhook Subscription

![WebHookPostman](EventGridSubscription.png)



## Reference

- https://learn.microsoft.com/en-us/azure/devops/release-notes/2020/pipelines/sprint-172-update