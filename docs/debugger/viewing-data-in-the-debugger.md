---
title: "Create custom views of data in the debugger | Microsoft Docs"
description: Learn the various ways  to inspect and modify program state in Visual Studio debugger. These include the Autos and Watch windows, DataTips, and Visualizers.  
ms.date: "08/08/2023"
ms.topic: "conceptual"
dev_langs:
  - "CSharp"
  - "VB"
  - "FSharp"
  - "C++"
  - "JScript"
helpviewer_keywords:
  - "debugging [Visual Studio], inspecting programs"
  - "debugger, viewing data"
ms.assetid: 13e1105f-f987-402e-9108-ec6ac12be042
author: "mikejo5000"
ms.author: "mikejo"
manager: jmartens
ms.technology: vs-ide-debug
ms.workload:
  - "multiple"
---
# Create custom views of data in the Visual Studio debugger (C#, Visual Basic, C++)

 [!INCLUDE [Visual Studio](~/includes/applies-to-version/vs-windows-only.md)]

The [!INCLUDE[vsprvs](../code-quality/includes/vsprvs_md.md)] debugger provides many tools for inspecting and modifying the state of your program. Most of these tools function only in break mode.

## Create custom views of data in variable windows and DataTips

 Many of the [debugger windows](../debugger/debugger-windows.md), such as the **Autos** and **Watch** windows, allow you to inspect variables. You can customize how C++ types, managed objects, and your own types are shown in the debugger variable windows and in [DataTips](../debugger/view-data-values-in-data-tips-in-the-code-editor.md). For more information, see [Create custom views of C++ objects](../debugger/create-custom-views-of-native-objects.md) and [Create custom views of .NET objects](../debugger/create-custom-views-of-managed-objects.md).

## Create custom visualizers

 Visualizers enable you to view the contents of an object or variable in a meaningful way. In the Visual Studio debugger, a visualizer refers to the different windows that you can open using the magnifying glass ![VisualizerIcon](../debugger/media/dbg-tips-visualizer-icon.png "Visualizer icon") icon. For example, the HTML visualizer shows how an HTML string would be interpreted and displayed in a browser. You can access visualizers from DataTips, the **Watch** window, the **Autos** window, and the **Locals** window. The **QuickWatch** dialog box also provides a visualizer. For more information:

- To create a visualizer for .NET objects, see [Custom visualizers](../debugger/create-custom-visualizers-of-data.md).
- To create a visualizer for C/C++ objects, see [UIVisualizer element](../debugger/create-custom-views-of-native-objects.md#BKMK_UIVisualizer) within the [Natvis](../debugger/create-custom-views-of-native-objects.md) documentation. Also, see the [C/C++ custom visualizer sample](https://github.com/Microsoft/ConcordExtensibilitySamples/tree/master/CppCustomVisualizer) or the [SQLite native Debugger Visualizer](https://github.com/Microsoft/VSSDK-Extensibility-Samples/tree/master/SqliteVisualizer) sample.

## See also

- [First look at the debugger](../debugger/debugger-feature-tour.md)
- [Command window](../ide/reference/command-window.md)
- [Debugger security](../debugger/debugger-security.md)
