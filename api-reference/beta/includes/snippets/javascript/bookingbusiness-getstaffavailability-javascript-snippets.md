---
description: "Automatically generated file. DO NOT MODIFY"
---

```javascript

const options = {
	authProvider,
};

const client = Client.init(options);

let getStaffAvailability = await client.api('/bookingBusinesses/Contosolunchdelivery@contoso.onmicrosoft.com/getStaffAvailability')
	.version('beta')
	.get();

```