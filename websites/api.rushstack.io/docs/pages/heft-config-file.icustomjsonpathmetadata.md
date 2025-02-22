---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@rushstack/heft-config-file](./heft-config-file.md) &gt; [ICustomJsonPathMetadata](./heft-config-file.icustomjsonpathmetadata.md)

## ICustomJsonPathMetadata interface

> This API is provided as a preview for developers and may change based on feedback that we receive. Do not use this API in a production environment.
> 

Used to specify how node(s) in a JSON object should be processed after being loaded.

**Signature:**

```typescript
export interface ICustomJsonPathMetadata 
```

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [customResolver?](./heft-config-file.icustomjsonpathmetadata.customresolver.md) |  | (configurationFilePath: string, propertyName: string, propertyValue: string) =&gt; string | **_(BETA)_** _(Optional)_ If <code>ICustomJsonPathMetadata.pathResolutionMethod</code> is set to <code>PathResolutionMethod.custom</code>, this property be used to resolve the path. |
|  [pathResolutionMethod?](./heft-config-file.icustomjsonpathmetadata.pathresolutionmethod.md) |  | [PathResolutionMethod.custom](./heft-config-file.pathresolutionmethod.md) | **_(BETA)_** _(Optional)_ If this property describes a filesystem path, use this property to describe how the path should be resolved. |

