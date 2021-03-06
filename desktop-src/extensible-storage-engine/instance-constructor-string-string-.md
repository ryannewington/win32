---
title: Instance constructor (String, String)
TOCTitle: Instance constructor (String, String)
ms:assetid: M:Microsoft.Isam.Esent.Interop.Instance.#ctor(System.String,System.String)
ms:mtpsurl: https://msdn.microsoft.com/library/microsoft.isam.esent.interop.instance.instance(v=EXCHG.10)
ms:contentKeyID: 55103267
ms.date: 07/30/2014
ms.topic: reference
dev_langs:
- vb
- csharp
api_name: 
- Microsoft.Isam.Esent.Interop.Instance..ctor
topic_type: 
- apiref
- kbSyntax
api_type: 
- Managed
api_location: 
- Microsoft.Isam.Esent.Interop.dll
ROBOTS: INDEX,FOLLOW

---

# Instance constructor (String, String)

Initializes a new instance of the Instance class. The underlying JET_INSTANCE is allocated, but not initialized.

**Namespace:**  [Microsoft.Isam.Esent.Interop](hh596136\(v=exchg.10\).md)  
**Assembly:**  Microsoft.Isam.Esent.Interop (in Microsoft.Isam.Esent.Interop.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    name As String, _
    displayName As String _
)
'Usage
Dim name As String
Dim displayName As String

Dim instance As New Instance(name, displayName)
```

``` csharp
public Instance(
    string name,
    string displayName
)
```

#### Parameters

  - name  
    Type: [System.String](/dotnet/api/system.string)  
    
    The name of the instance. This string must be unique within a given process hosting the database engine.

<!-- end list -->

  - displayName  
    Type: [System.String](/dotnet/api/system.string)  
    
    A display name for the instance. This will be used in eventlog entries.

## See also

#### Reference

[Instance class](dn350923\(v=exchg.10\).md)

[Instance members](dn350944\(v=exchg.10\).md)

[Instance overload](dn350946\(v=exchg.10\).md)

[Microsoft.Isam.Esent.Interop namespace](hh596136\(v=exchg.10\).md)