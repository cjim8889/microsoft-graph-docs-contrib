---
description: "Automatically generated file. DO NOT MODIFY"
---

```python

# THE PYTHON SDK IS IN PREVIEW. FOR NON-PRODUCTION USE ONLY

graph_client = GraphServiceClient(credentials, scopes)

query_params = MessagesRequestBuilder.MessagesRequestBuilderGetQueryParameters(
		select = ["subject","body","bodyPreview","uniqueBody"],
)

request_configuration = MessagesRequestBuilder.MessagesRequestBuilderGetRequestConfiguration(
query_parameters = query_params,
headers = {
			'Prefer' : "outlook.body-content-type=\"text\"",
}

)

result = await graph_client.me.messages.get(request_configuration = request_configuration)


```