---
title: "Analyze a tabular model in Excel | Microsoft Docs"
ms.custom: ""
ms.date: "02/21/2018"
ms.prod: analysis-services
ms.prod_service: "analysis-services, azure-analysis-services"
ms.component: ""
ms.reviewer: ""
ms.suite: "pro-bi"
ms.technology: 
  
ms.component: multidimensional-tabular
ms.component: data-mining
ms.tgt_pltfrm: ""
ms.topic: conceptual
f1_keywords: 
  - "sql13.asvs.bidtoolset.chooseperspect.f1"
ms.assetid: 47fa45fc-60ab-41a1-bde3-5781c8462889
caps.latest.revision: 13
author: "Minewiskan"
ms.author: "owend"
manager: "kfile"
---
# Analyze a tabular model in Excel  
[!INCLUDE[ssas-appliesto-sqlas-aas](../../includes/ssas-appliesto-sqlas-aas.md)]
  The Analyze in Excel feature in [!INCLUDE[ssBIDevStudioFull](../../includes/ssbidevstudiofull-md.md)] opens Microsoft Excel, creates a data source connection to the model workspace database, and adds a PivotTable to the worksheet. Model objects (tables, columns, measures, hierarchies, and KPIs) are included as fields in the PivotTable field list.  
  
> [!NOTE]  
>  To use the Analyze in Excel feature, you must have Microsoft Office 2003 or later installed on the same computer as [!INCLUDE[ssBIDevStudio](../../includes/ssbidevstudio-md.md)]. If Office is not installed on the same computer, you can use Excel on another computer and connect to the model workspace database as a data source. You can then manually add a PivotTable to the worksheet. Model objects (tables, columns, measures, and KPIs) are included as fields in the PivotTable field list.  
  
## Tasks  
  
#### To analyze a tabular model project by using the Analyze in Excel feature  
  
1.  In [!INCLUDE[ssBIDevStudio](../../includes/ssbidevstudio-md.md)], click the **Model** menu, and then click **Analyze in Excel**.  
  
2.  In the **Choose Credential and Perspective** dialog box, select one of the following credential options to connect to the model workspace data source:  
  
    -   To use the current user account, select **Current Windows User**.  
  
    -   To use a different user account, select **Other Windows User**.  
  
         Typically, this user account will be a member of a role. No password is required. The account can only be used in the context of an Excel connection to the workspace database.  
  
    -   To use a security role, select **Role**, and then in the listbox, select one or more roles.  
  
         Security roles must be defined using the Role Manager. For more information, see [Create and Manage Roles](../../analysis-services/tabular-models/create-and-manage-roles-ssas-tabular.md).  
  
3.  To use a perspective, in the **Perspective** listbox, select a perspective.  
  
     Perspectives (other than default) must be defined using the Perspectives dialog box. For more information, see [Create and Manage Perspectives](../../analysis-services/tabular-models/create-and-manage-perspectives-ssas-tabular.md).  
  
> [!NOTE]  
>  The PivotTable Field List in Excel does not refresh automatically as you make changes to the model project in the model designer. To refresh the PivotTable Field List, in Excel, on the **Options** ribbon, click **Refresh**.  
  
## See also  
 [Analyze in Excel](../../analysis-services/tabular-models/analyze-in-excel-ssas-tabular.md)  
  
  
