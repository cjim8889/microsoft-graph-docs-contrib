---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

// Code snippets are only available for the latest version. Current version is 5.x

// To initialize your graphClient, see https://learn.microsoft.com/en-us/graph/sdks/create-client?from=snippets&tabs=csharp
var result = await graphClient.NetworkAccess.Reports.MicrosoftGraphNetworkaccessEntitiesSummariesWithStartDateTimeWithEndDateTime(DateTimeOffset.Parse("{endDateTime}"),DateTimeOffset.Parse("{startDateTime}")).GetAsync((requestConfiguration) =>
{
	requestConfiguration.QueryParameters.Filter = "trafficType eq 'microsoft365'";
});


```