---
title: "&lt;workflowControlEndpoint&gt;"
ms.date: "03/30/2017"
ms.assetid: 6c89e76c-643b-4b6a-9b25-628f753d7027
---
# &lt;workflowControlEndpoint&gt;
This configuration element defines a standard endpoint for controlling the execution of workflow instances (create, run, suspend, terminate, etc).  
  
\<system.ServiceModel>  
\<standardEndpoints>  
  
## Syntax  
  
```xml  
<system.serviceModel>
  <standardEndpoints>
    <workflowControlEndpoint>
      <standardEndpoint name="String" />
    </workflowControlEndpoint>
  </standardEndpoints>
</system.serviceModel>
```  
  
## Attributes and Elements  
 The following sections describe attributes, child elements, and parent elements.  
  
### Attributes  
  
|Attribute|Description|  
|---------------|-----------------|  
|name|A String that specifies the name of the configuration of the standard endpoint. The name is used in the `endpointConfiguration` attribute of the service endpoint to link a standard endpoint to its configuration.|  
  
### Child Elements  
 None.  
  
### Parent Elements  
  
|Element|Description|  
|-------------|-----------------|  
|[\<standardEndpoints>](../../../../../docs/framework/configure-apps/file-schema/wcf/standardendpoints.md)|A collection of standard endpoints that are pre-defined endpoints with one or more of their properties (address, binding, contract) fixed.|  
  
## See also
- <xref:System.ServiceModel.Activities.WorkflowControlEndpoint>
