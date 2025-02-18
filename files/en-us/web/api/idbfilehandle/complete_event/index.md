---
title: "IDBFileEvent: complete event"
slug: Web/API/IDBFileHandle/complete_event
page-type: web-api-event
status:
  - deprecated
  - non-standard
browser-compat: api.IDBFileHandle.complete_event
---

{{APIRef("IndexedDB")}}{{deprecated_header}}

> **Note:** The three non-standard interfaces {{domxref("IDBMutableFile")}}, {{domxref("IDBFileHandle")}}, and {{domxref("IDBFileRequest")}} are [disabled by default](#browser_compatibility).
> Consider using the [File and Directory Entries API](/en-US/docs/Web/API/File_and_Directory_Entries_API) instead.

The **`complete`** is fired when a read or write operation is successful.

This event is not cancelable and does not bubble.

## Syntax

Use the event name in methods like {{domxref("EventTarget.addEventListener", "addEventListener()")}}, or set an event handler property.

```js
addEventListener("complete", (event) => {});
onerror = (complete) => {};
```

## Event type

A generic {{domxref("Event")}}.

## Specifications

This feature is not part of any current specification. It is no longer on track to become a standard.

## Browser compatibility

This event is not supported by any current browser.
From Firefox 102 it is behind the preference `dom.fileHandle.enabled`.

## See also

- {{domxref("IDBFileHandle")}}
