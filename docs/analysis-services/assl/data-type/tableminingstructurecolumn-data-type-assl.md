---
title: "TableMiningStructureColumn Data Type (ASSL) | Microsoft Docs"
ms.date: 07/25/2018
ms.prod: sql
ms.technology: analysis-services
ms.custom: assl
ms.topic: reference
ms.author: owend
ms.reviewer: owend
author: minewiskan
manager: kfile
---
# TableMiningStructureColumn Data Type (ASSL)

  Defines a derived data type that represents a [MiningStructureColumn](miningstructurecolumn-data-type-assl.md) element that contains nested tables, as opposed to the scalar values associated with the [ScalarMiningStructureColumn](scalarminingstructurecolumn-data-type-assl.md) element that contains scalar values.  
  
## Syntax  
  
```xml  
  
<TableMiningStructureColumn>  
   <!-- The following elements extend MiningStructureColumn -->  
   <ForeignKeyColumn>..</ForeignKeyColumn>  
   <SourceMeasureGroup>..</SourceMeasureGroup>  
   <Columns>..</Columns>  
   <Translations>..</Translations>  
</TableMiningStructureColumn>  
```  
  
## Data Type Characteristics  
  
|Characteristic|Description|  
|--------------------|-----------------|  
|Base data types|[MiningStructureColumn](miningstructurecolumn-data-type-assl.md)|  
|Derived data types|None|  
  
## Data Type Relationships  
  
|Relationship|Element|  
|------------------|-------------|  
|Parent elements|None|  
|Child elements|[Columns](../collections/columns-element-assl.md), [ForeignKeyColumn](../objects/foreignkeycolumn-element-assl.md), [SourceMeasureGroup](../objects/sourcemeasuregroup-element-assl.md), [Translations](../collections/translations-element-assl.md)|  
|Derived elements|[Column](../objects/column-element-assl.md) ([Columns](../collections/columns-element-assl.md) collection of [MiningStructure](../objects/miningstructure-element-assl.md))|  
  
## Remarks  
 The corresponding element in the Analysis Management Objects (AMO) object model is <xref:Microsoft.AnalysisServices.TableMiningStructureColumn>.  
  
## See Also  
 [Analysis Services Scripting Language XML Data Types &#40;ASSL&#41;](analysis-services-scripting-language-xml-data-types-assl.md)  
  
  
