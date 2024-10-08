---
title: "USBDevice: selectConfiguration() method"
short-title: selectConfiguration()
slug: Web/API/USBDevice/selectConfiguration
page-type: web-api-instance-method
status:
  - experimental
browser-compat: api.USBDevice.selectConfiguration
---

{{APIRef("WebUSB API")}}{{SeeCompatTable}}{{SecureContext_Header}}{{AvailableInWorkers}}

The **`selectConfiguration()`** method of the
{{domxref("USBDevice")}} interface returns a {{jsxref("promise")}} that resolves when
the specified configuration is selected.

## Syntax

```js-nolint
selectConfiguration(configurationValue)
```

### Parameters

- `configurationValue`
  - : The number of a device-specific configuration.

### Return value

A {{jsxref("promise")}}.

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}
