---
title: Font.ColorIndex property (Excel)
keywords: vbaxl10.chm559076
f1_keywords:
- vbaxl10.chm559076
ms.prod: excel
api_name:
- Excel.Font.ColorIndex
ms.assetid: e5fa27eb-b905-dd5d-a3b5-69a94492a6c4
ms.date: 06/08/2017
localization_priority: Normal
---


# Font.ColorIndex property (Excel)

Returns or sets a  **Variant** value that represents the color of the font.


## Syntax

_expression_. `ColorIndex`

_expression_ A variable that represents a [Font](Excel.Font-graph-property.md) object.


## Remarks

The color is specified as an index value into the current color palette, or as one of the following  **[xlColorIndex](Excel.XlColorIndex.md)** constants:


-  **xlColorIndexAutomatic**
    
-  **xlColorIndexNone**
    

## Example

This example changes the font color in cell A1 on Sheet1 to red.


```vb
Worksheets("Sheet1").Range("A1").Font.ColorIndex = 3
```


## See also


[Font Object](Excel.Font(object).md)

[!include[Support and feedback](~/includes/feedback-boilerplate.md)]
