---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestBody := msgraphsdk.New()
requestBody.SetAdditionalData(map[string]interface{}{
	"@odata.id": "https://graph.microsoft.com/v1.0/policies/tokenLifetimePolicies/cd3d9b57-0aee-4f25-8ee3-ac74ef5986a9",
}
applicationId := "application-id"
tokenLifetimePolicyId := "tokenLifetimePolicy-id"
graphClient.ApplicationsById(&applicationId).TokenLifetimePoliciesById(&tokenLifetimePolicyId).Post(requestBody)


```