---
description: Host web content in your Win32 app with the Microsoft Edge WebView2 control
title: Microsoft Edge WebView2 for Win32 apps
author: MSEdgeTeam
ms.author: msedgedevrel
ms.date: 12/09/2019
ms.topic: reference
ms.prod: microsoft-edge
ms.technology: webview
keywords: IWebView2, IWebView2WebView, webview2, webview, win32 apps, win32, edge
---

# interface IWebView2ContainsFullScreenElementChangedEventHandler 

```
interface IWebView2ContainsFullScreenElementChangedEventHandler
  : public IUnknown
```

The caller implements this method to receive the ContainsFullScreenElementChanged events.

## Summary

 Members                        | Descriptions
--------------------------------|---------------------------------------------
[Invoke](#invoke) | Called to provide the implementer with the event args for the corresponding event.

There are no event args for this event.

## Members

#### Invoke 

Called to provide the implementer with the event args for the corresponding event.

> public HRESULT [Invoke](#invoke)([IWebView2WebView5](IWebView2WebView5.md#iwebview2webview5) * webview,IUnknown * args)

There are no event args and the args parameter will be null.

