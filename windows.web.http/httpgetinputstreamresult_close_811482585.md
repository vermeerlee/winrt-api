---
-api-id: M:Windows.Web.Http.HttpGetInputStreamResult.Close
-api-type: winrt method
ms.custom: 19H1
---

<!-- Method syntax.
public void HttpGetInputStreamResult.Close()
-->

# Windows.Web.Http.HttpGetInputStreamResult.Close

## -description
Closes the [HttpGetInputStreamResult](httpgetinputstreamresult.md) instance and releases allocated resources.

## -remarks
The **Close** method releases allocated resources used by the [HttpGetInputStreamResult](httpgetinputstreamresult.md) instance. The **Close**** method can manage the lifetime of system resources used by a Windows Runtime object.

In the .NET Framework 4.5, this method projects as the **Dispose** method. In Visual C++ component extensions (C++/CX), this method projects as the destructor (delete operator).

Apps written in JavaScript, C#, or VB.NET use garbage collection to release resources; the object and associated resources don't get released until the garbage collection pass runs. The **Close** method allows an app to release these resources early rather than waiting for the object to be released by garbage collection.

Apps written in C++ or CX don't have a **Close** method since these apps can destroy the object. In C++ and CX, objects are released when they fall out of program scope or as part of the destructor (delete operator) for the object.

## -see-also

## -examples

