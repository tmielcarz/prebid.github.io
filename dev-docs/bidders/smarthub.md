---
layout: bidder
title: SmartHub
description: SmartHub Bidder Adapter
biddercode: smarthub
usp_supported: true
schain_supported: true
media_types: banner, video, native
gdpr_supported: true
pbjs: true
pbs: true
pbs_app_supported: true
sidebarType: 1
---

### Prebid.js Bid Params

{: .table .table-bordered .table-striped }
| Name          | Scope    | Description                     | Example                             | Type      |
|---------------|----------|---------------------------------|-------------------------------------|-----------|
| `partnerName` | required | Unique partner name             | `'partnertest'`                     | `string`  |
| `seat`        | required | Seat value                      | `'9Q20EdGxzgWdfPYShScl'`            | `string`  |
| `token`       | required | Token                           | `'eKmw6alpP3zWQhRCe3flOpz0wpuwRFjW'` | `string`  |
| `iabCat`      | optional | Array of IAB content categories that describe the content producer | `['IAB1-1', 'IAB3-1', 'IAB4-3']`    | `Array(String)`   |
| `minBidfloor`  | optional | Minimal CPM value               | `0.03`                              | `float`    |
| `pos`         | optional | The position of the placement on the page, see Open RTB spec v2.5.    | `4`                                 | `number`  |

### Prebid Server Bid Params

{: .table .table-bordered .table-striped }
| Name          | Scope    | Description         | Example                              | Type     |
|---------------|----------|---------------------|--------------------------------------|----------|
| `partnerName` | required | Unique partner name | `'partnertest'`                      | `string` |
| `seat`        | required | Seat value          | `'9Q20EdGxzgWdfPYShScl'`             | `string` |
| `token`       | required | Token               | `'eKmw6alpP3zWQhRCe3flOpz0wpuwRFjW'` | `string` |
