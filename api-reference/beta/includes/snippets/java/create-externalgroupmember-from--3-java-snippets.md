---
description: "Automatically generated file. DO NOT MODIFY"
---

```java

GraphServiceClient graphClient = GraphServiceClient.builder().authenticationProvider( authProvider ).buildClient();

ExternalGroupMember externalGroupMember = new ExternalGroupMember();
externalGroupMember.id = "1431b9c38ee647f6a";
externalGroupMember.type = ExternalGroupMemberType.USER;

graphClient.external().connections("contosohr").groups("31bea3d537902000").members()
	.buildRequest()
	.post(externalGroupMember);

```