---
title: Api.MakeKey method (JET_SESID, JET_TABLEID, Int64, MakeKeyGrbit) (Microsoft.Isam.Esent.Interop)
TOCTitle: MakeKey method (JET_SESID, JET_TABLEID, Int64, MakeKeyGrbit)
ms:assetid: M:Microsoft.Isam.Esent.Interop.Api.MakeKey(Microsoft.Isam.Esent.Interop.JET_SESID,Microsoft.Isam.Esent.Interop.JET_TABLEID,System.Int64,Microsoft.Isam.Esent.Interop.MakeKeyGrbit)
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.isam.esent.interop.api.makekey(v=EXCHG.10)
ms:contentKeyID: 55100841
ms.date: 07/30/2014
ms.topic: article
dev_langs:
- vb
- csharp
api_name: 
- Microsoft.Isam.Esent.Interop.Api.MakeKey
topic_type: 
- kbSyntax
- apiref
api_type: 
- Managed
api_location: 
- Microsoft.Isam.Esent.Interop.dll
ROBOTS: INDEX,FOLLOW

---

# Api.MakeKey method (JET\_SESID, JET\_TABLEID, Int64, MakeKeyGrbit)

Constructs a search key that may then be used by [JetSeek(JET\_SESID, JET\_TABLEID, SeekGrbit)](dn334003\(v=exchg.10\).md) and [JetSetIndexRange(JET\_SESID, JET\_TABLEID, SetIndexRangeGrbit)](dn334024\(v=exchg.10\).md).

**Namespace:**  [Microsoft.Isam.Esent.Interop](hh596136\(v=exchg.10\).md)  
**Assembly:**  Microsoft.Isam.Esent.Interop (in Microsoft.Isam.Esent.Interop.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub MakeKey ( _
    sesid As JET_SESID, _
    tableid As JET_TABLEID, _
    data As Long, _
    grbit As MakeKeyGrbit _
)
'Usage
Dim sesid As JET_SESID
Dim tableid As JET_TABLEID
Dim data As Long
Dim grbit As MakeKeyGrbitApi.MakeKey(sesid, tableid, data, _
    grbit)
```

``` csharp
public static void MakeKey(
    JET_SESID sesid,
    JET_TABLEID tableid,
    long data,
    MakeKeyGrbit grbit
)
```

#### Parameters

  - sesid  
    Type: [Microsoft.Isam.Esent.Interop.JET\_SESID](hh596745\(v=exchg.10\).md)  
    
    The session to use.

<!-- end list -->

  - tableid  
    Type: [Microsoft.Isam.Esent.Interop.JET\_TABLEID](hh566310\(v=exchg.10\).md)  
    
    The cursor to create the key on.

<!-- end list -->

  - data  
    Type: [System.Int64](http://msdn2.microsoft.com/en-us/library/6yy583ek)  
    
    Column data for the current key column of the current index.

<!-- end list -->

  - grbit  
    Type: [Microsoft.Isam.Esent.Interop.MakeKeyGrbit](hh578182\(v=exchg.10\).md)  
    
    Key options.

## See also

#### Reference

[Api class](dn292211\(v=exchg.10\).md)

[Api members](dn292213\(v=exchg.10\).md)

[MakeKey overload](dn334039\(v=exchg.10\).md)

[Microsoft.Isam.Esent.Interop namespace](hh596136\(v=exchg.10\).md)
