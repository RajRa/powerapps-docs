---
title: PowerApps component framework Manifest Schema Reference | Microsoft Docs
description: 
keywords:
ms.author: nabuthuk
manager: 
ms.date: 06/4/2018
ms.reviewer: ""
ms.service: "crm-online"
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "article"
ms.assetid: 045a395b-4475-48dd-8f67-6bc2b33cd89c
---

# Manifest schema reference

[!INCLUDE[cc-beta-prerelease-disclaimer](../../../includes/cc-beta-prerelease-disclaimer.md)]

This section contains reference documentation for manifest schema generated using the PowerApps CLI.

> [!IMPORTANT]
> - PowerApps component framework is a preview feature.
> - [!INCLUDE[cc_preview_features_definition](../../../includes/cc-preview-features-definition.md)] 
> - [!INCLUDE[cc_preview_features_no_MS_support](../../../includes/cc-preview-features-no-ms-support.md)]

|Element|Description|
|----|-----------|
|[code](code.md)|[!INCLUDE [code-description](includes/code-description.md)]|
|[control](control.md)|[!INCLUDE [control-description](includes/control-description.md)]|
|[css](css.md)|[!INCLUDE [css-description](includes/css-description.md)]|
|[data-set](data-set.md)|[!INCLUDE [data-set-description](includes/data-set-description.md)]|
|[html](html.md)|[!INCLUDE [html-description](includes/html-description.md)]|
|[img](img.md)|[!INCLUDE [img-description](includes/img-description.md)]|
|[manifest](manifest.md)|Manifest is the metadata file that defines a component. It is an XML document that describes<br/> - The namespace of the component.<br/> - The kind of data it can be configured, either a field or a data-set.<br/> - Any properties that can be configured in the application when the component is added.<br/> - A list of resource files that the component needs.<br/> - One of them must be a JavaScript web resource. This JavaScript must include a function that will instantiate an object. This implements an interface that exposes methods that are required for the component to work. This is called the component implementation library.<br/> - The name of a JavaScript function in the component implementation library that will return an object that applies the required interface.<br/> When someone configures a component in the application, the data in the manifest filters out the available components so that only valid components for the context are available for configuration. The properties defined in the manifest for a component are rendered as configuration fields so that the person configuring the control can specify values. These property values are then available to your component function at run time.|
|[property](property.md)|[!INCLUDE [property-description](includes/property-description.md)]|
|[property-set](property-set.md)|[!INCLUDE [property-set-description](includes/property-set-description.md)]|
|[resources](resources.md)|[!INCLUDE [resources-description](includes/resources-description.md)]|
|[resx](resx.md)|[!INCLUDE [resx-description](includes/resx-description.md)]|
|[type-group](type-group.md)|[!INCLUDE [type-group-description](includes/type-group-description.md)]|


### Related topics

[PowerApps component framework Manifest Schema Reference](index.md)<br/>
[PowerApps component framework API Reference](../reference/index.md)<br/>
[PowerApps component framework Overview](../overview.md)