---
description: "Automatically generated file. DO NOT MODIFY"
---

```javascript

const options = {
	authProvider,
};

const client = Client.init(options);

let userProcessingResults = await client.api('/identityGovernance/lifecycleWorkflows/workflows/{workflowid}/userProcessingResults')
	.version('beta')
	.get();

```