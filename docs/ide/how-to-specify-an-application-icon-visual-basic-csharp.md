---
title: 'How to: Specify an application icon (Visual Basic, C#)'
description: Learn how to use the Icon property to specify the icon that File Explorer and the Windows taskbar displays for the compiled application.
ms.date: 11/04/2016
ms.topic: how-to
helpviewer_keywords:
- icons [Visual Studio], application
- application properties [Visual Studio], icons
- application icons [Visual Studio]
author: TerryGLee
ms.author: tglee
manager: jmartens
ms.technology: vs-ide-general
ms.workload:
- dotnet
---
# How to: Specify an application icon (Visual Basic, C#)

 [!INCLUDE [Visual Studio](~/includes/applies-to-version/vs-windows-only.md)]

The `Icon` property for a project specifies the icon file (*.ico*) that will be displayed for the compiled application in **File Explorer** and in the Windows taskbar.

The `Icon` property can be accessed in the **Application** pane of the **Project Designer**; it contains a list of icons that have been added to a project either as resources or as content files.

> [!NOTE]
> After you set the icon property for an application, you might also set the `Icon` property of each **Window** or **Form** in the application. For information about window icons for Windows Presentation Foundation (WPF) standalone applications, see <xref:System.Windows.Window.Icon%2A> property.

## To specify an application icon

1. In **Solution Explorer**, choose a project node (not the **Solution** node).

1. On the menu bar, choose **Project** > **Properties**.

1. When the **Project Designer** appears, choose the **Application** tab.

1. **(Visual Basic)**&mdash;In the **Icon** list, choose an icon (*.ico*) file.

    **C#**&mdash;Near the **Icon** list, choose the **\<Browse...>** button, and then browse to the location of the icon file that you want.

## See also

- [Application page, Project Designer (Visual Basic)](../ide/reference/application-page-project-designer-visual-basic.md)
- [Application page, Project Designer (C#)](../ide/reference/application-page-project-designer-csharp.md)
