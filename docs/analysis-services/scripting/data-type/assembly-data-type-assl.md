---
title: "Assembly Data Type (ASSL) | Microsoft Docs"
ms.date: 05/03/2018
ms.prod: sql
ms.technology: analysis-services
ms.component: assl
ms.topic: reference
ms.author: owend
ms.reviewer: owend
author: minewiskan
manager: kfile
---
# Assembly Data Type (ASSL)
[!INCLUDE[ssas-appliesto-sqlas](../../../includes/ssas-appliesto-sqlas.md)]
  Defines an abstract primitive data type that represents a [!INCLUDE[msCoName](../../../includes/msconame-md.md)] [!INCLUDE[dnprdnshort](../../../includes/dnprdnshort-md.md)] assembly or a COM dynamic link library (DLL) associated with a [Server](../../../analysis-services/scripting/objects/server-element-assl.md) or [Database](../../../analysis-services/scripting/objects/database-element-assl.md) element.  
  
> [!IMPORTANT]  
>  COM assemblies might pose a security risk. Due to this risk and other considerations, COM assemblies were deprecated in [!INCLUDE[ssASversion10](../../../includes/ssasversion10-md.md)]. COM assemblies might not be supported in future releases.  
  
## Syntax  
  
```xml  
  
<Assembly>  
   <Name>...</Name>  
   <ID>...</ID>  
   <Description>...</Description>  
   <CreatedTimestamp>...</CreatedTimestamp>  
   <LastSchemaUpdate>...</LastSchemaUpdate>  
   <ImpersonationInfo>...</ImpersonationInfo>  
   <Annotations>...</Annotations>  
</Assembly>  
```  
  
## Data Type Characteristics  
  
|Characteristic|Description|  
|--------------------|-----------------|  
|Base data types|None|  
|Derived data types|[ClrAssembly](../../../analysis-services/scripting/data-type/clrassembly-data-type-assl.md), [ComAssembly](../../../analysis-services/scripting/data-type/comassembly-data-type-assl.md)|  
  
## Data Type Relationships  
  
|Relationship|Element|  
|------------------|-------------|  
|Parent elements|None|  
|Child elements|[Annotations](../../../analysis-services/scripting/collections/annotations-element-assl.md), [CreatedTimestamp](../../../analysis-services/scripting/properties/createdtimestamp-element-assl.md), [Description](../../../analysis-services/scripting/properties/description-element-assl.md), [ID](../../../analysis-services/scripting/properties/id-element-assl.md), [ImpersonationInfo](../../../analysis-services/scripting/properties/impersonationinfo-element-assl.md), [LastSchemaUpdate](../../../analysis-services/scripting/properties/lastschemaupdate-element-assl.md), [Name](../../../analysis-services/scripting/properties/name-element-assl.md)|  
|Derived elements|None|  
  
## Remarks  
 The **Assembly** data type serves as the base data type for the **ComAssembly** element, which represents COM libraries associated with the instance or database, and the **ClrAssembly** element, which represents [!INCLUDE[dnprdnshort](../../../includes/dnprdnshort-md.md)] assemblies associated with the instance or database. For more information about assemblies, see [Multidimensional Model Assemblies Management](../../../analysis-services/multidimensional-models/multidimensional-model-assemblies-management.md).  
  
 The corresponding element in the Analysis Management Objects (AMO) object model is <xref:Microsoft.AnalysisServices.Assembly>.  
  
## See Also  
 [Server Element &#40;ASSL&#41;](../../../analysis-services/scripting/objects/server-element-assl.md)   
 [Database Element &#40;ASSL&#41;](../../../analysis-services/scripting/objects/database-element-assl.md)   
 [Analysis Services Scripting Language XML Data Types &#40;ASSL&#41;](../../../analysis-services/scripting/data-type/analysis-services-scripting-language-xml-data-types-assl.md)  
  
  
