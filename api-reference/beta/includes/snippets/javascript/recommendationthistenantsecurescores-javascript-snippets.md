---
description: "Automatically generated file. DO NOT MODIFY"
---

```javascript

const options = {
	authProvider,
};

const client = Client.init(options);

let recommendation = await client.api('/directory/recommendations/tenantSecureScores')
	.version('beta')
	.get();

```