---
layout: bidder
title: Escalax
description: Prebid Escalax Bidder Adaptor
biddercode: escalax
usp_supported: true
ccpa_supported: true
coppa_supported: true
schain_supported: true
media_types: banner, video, native
safeframes_ok: true
deals_supported: true
pbjs: true
pbs: true
sidebarType: 1
floors_supported: true
prebid_member: false
fpd_supported: false
gvl_id: none
multiformat_supported: will-bid-on-one
ortb_blocking_supported: true
userIds: all
---

### Note

The Escalax Bidding adapter requires setup before beginning. Please contact us at <connect@escalax.io>

### Bid Params for Prebid Server

{: .table .table-bordered .table-striped }
| Name | Scope | Description | Example | Type |
|---------------|----------|-----------------------|-----------|-----------|
| `sourceId` | required | Patner name | `'partner'` | `string` |
| `accountId` | required | Hash | `'0800fc577294'` | `string` |

### Bid Params for Prebid.js

{: .table .table-bordered .table-striped }
| Name | Scope | Description | Example | Type |
|---------------|----------|-----------------------|-----------|-----------|
| `sourceId` | required | Unique hash | `'partner'` | `string` |
| `accountId` | required | Unique name | `'0800fc577294'` | `string` |
| `subdomain` | optional | Escalax region | `'bidder_us'` | `string` |
