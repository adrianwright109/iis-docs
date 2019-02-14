---
title: TrackChangedEventArgs.StreamType Property  (Microsoft.Web.Media.SmoothStreaming)
TOCTitle: StreamType Property
ms:assetid: P:Microsoft.Web.Media.SmoothStreaming.TrackChangedEventArgs.StreamType
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.web.media.smoothstreaming.trackchangedeventargs.streamtype(v=VS.90)
ms:contentKeyID: 23961229
ms.date: 05/02/2012
mtps_version: v=VS.90
f1_keywords:
- Microsoft.Web.Media.SmoothStreaming.TrackChangedEventArgs.StreamType
- Microsoft.Web.Media.SmoothStreaming.TrackChangedEventArgs.get_StreamType
- Microsoft.Web.Media.SmoothStreaming.TrackChangedEventArgs.set_StreamType
dev_langs:
- CSharp
- JScript
- VB
- c++
api_location:
- Microsoft.Web.Media.SmoothStreaming.dll
api_name:
- Microsoft.Web.Media.SmoothStreaming.TrackChangedEventArgs.get_StreamType
- Microsoft.Web.Media.SmoothStreaming.TrackChangedEventArgs.set_StreamType
- Microsoft.Web.Media.SmoothStreaming.TrackChangedEventArgs.StreamType
api_type:
- Managed
topic_type:
- apiref
- kbSyntax
product_family_name: VS
ROBOTS: INDEX,FOLLOW
---

# StreamType Property

Gets or sets the StreamType property.

**Namespace:**  [Microsoft.Web.Media.SmoothStreaming](microsoft-web-media-smoothstreaming-namespace_1.md)  
**Assembly:**  Microsoft.Web.Media.SmoothStreaming (in Microsoft.Web.Media.SmoothStreaming.dll)

## Syntax

``` vb
'Declaration

  Public Property StreamType As MediaStreamType
'Usage

  Dim instance As TrackChangedEventArgs
Dim value As MediaStreamType

value = instance.StreamType
```

``` csharp
  public MediaStreamType StreamType { get; private set; }
```

``` c++
  public:
property MediaStreamType StreamType {
    MediaStreamType get ();
    private: void set (MediaStreamType value);
}
```

``` jscript
  function get StreamType () : MediaStreamType
private function set StreamType (value : MediaStreamType)
```

#### Property Value

Type: [System.Windows.Media. . :: . .MediaStreamType](https://msdn.microsoft.com/en-us/library/cc672180\(v=vs.90\))  
A MediaStream object.  

## Version Information

#### Silverlight

Supported in: 4  

#### Silverlight for Windows Phone

Supported in: Windows Phone OS 7.0  

## Permissions

  - Full trust for the immediate caller. This member cannot be used by partially trusted code. For more information, see [Using Libraries from Partially Trusted Code](https://msdn.microsoft.com/en-us/library/8skskf63\(v=vs.90\)).

## See Also

#### Reference

[TrackChangedEventArgs Class](trackchangedeventargs-class-microsoft-web-media-smoothstreaming_1.md)

[Microsoft.Web.Media.SmoothStreaming Namespace](microsoft-web-media-smoothstreaming-namespace_1.md)
