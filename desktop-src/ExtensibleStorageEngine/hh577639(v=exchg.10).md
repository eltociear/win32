---
title: IJET_LOGTIME.ToDateTime method  (Microsoft.Isam.Esent.Interop)
TOCTitle: 'ToDateTime method '
ms:assetid: M:Microsoft.Isam.Esent.Interop.IJET_LOGTIME.ToDateTime
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.isam.esent.interop.ijet_logtime.todatetime(v=EXCHG.10)
ms:contentKeyID: 39510507
ms.date: 07/30/2014
mtps_version: v=EXCHG.10
f1_keywords:
- Microsoft.Isam.Esent.Interop.IJET_LOGTIME.ToDateTime
dev_langs:
- CSharp
- JScript
- VB
- other
api_name: 
- Microsoft.Isam.Esent.Interop.IJET_LOGTIME.ToDateTime
topic_type: 
- apiref
- kbSyntax
api_type: 
- Managed
api_location: 
- Microsoft.Isam.Esent.Interop.dll
ROBOTS: INDEX,FOLLOW

---

# IJET\_LOGTIME.ToDateTime method

Generate a DateTime representation of this IJET\_LOGTIME.

**Namespace:**  [Microsoft.Isam.Esent.Interop](hh596136\(v=exchg.10\).md)  
**Assembly:**  Microsoft.Isam.Esent.Interop (in Microsoft.Isam.Esent.Interop.dll)

## Syntax

``` vb
'Declaration
Function ToDateTime As Nullable(Of DateTime)
'Usage
Dim instance As IJET_LOGTIME
Dim returnValue As Nullable(Of DateTime)

returnValue = instance.ToDateTime()
```

``` csharp
Nullable<DateTime> ToDateTime()
```

#### Return value

Type: [System.Nullable](http://msdn2.microsoft.com/en-us/library/b3h38hb0)\<[DateTime](http://msdn2.microsoft.com/en-us/library/03ybds8y)\>  
A DateTime representing the IJET\_LOGTIME. If the IJET\_LOGTIME is null then null is returned.  

## See also

#### Reference

[IJET\_LOGTIME interface](hh596687\(v=exchg.10\).md)

[IJET\_LOGTIME members](hh578100\(v=exchg.10\).md)

[Microsoft.Isam.Esent.Interop namespace](hh596136\(v=exchg.10\).md)
