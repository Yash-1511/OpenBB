---
title: cik_map
description: Learn how to retrieve the CIK number corresponding to a ticker symbol
  using the python obb.regulators.sec.cik_map function. Understand the available parameters,
  return values, and data structure.
keywords: 
- CIK number
- ticker symbol
- python obb.regulators.sec.cik_map function
- get data for symbol
- provider parameter
- returns
- results
- warnings
- chart object
- metadata info
- data
- central index key
---

<!-- markdownlint-disable MD041 -->

Get the CIK number corresponding to a ticker symbol.

## Syntax

```jsx<span style={color: 'red'}>=OBB.REGULATORS.SEC.CIK_MAP(symbol;[provider])</span>```

### Example

```excel wordwrap
=OBB.REGULATORS.SEC.CIK_MAP("AAPL")
```

---

## Parameters

| Name | Type | Description | Optional |
| ---- | ---- | ----------- | -------- |
| **symbol** | **Text** | **Symbol to get data for.** | **False** |
| provider | Text | Options: sec, defaults to sec. | True |

---

## Return Data

| Name | Description |
| ---- | ----------- |
| cik | Central Index Key (provider: sec) |