---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestParameters := &msgraphsdk.DirectoryObjectRequestBuilderDeleteQueryParameters{
	Id: "https://graph.microsoft.com/v1.0/users/%7Buser-id%7D",
}
options := &msgraphsdk.DirectoryObjectRequestBuilderDeleteRequestConfiguration{
	QueryParameters: requestParameters,
}
groupId := "group-id"
directoryObjectId := "directoryObject-id"
graphClient.GroupsById(&groupId).RejectedSendersById(&directoryObjectId).DeleteWithRequestConfigurationAndResponseHandler(options, nil)


```