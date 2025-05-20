# Function: <code>usb_endpoint_maxp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8160b603)
Location: include/uapi/linux/usb/ch9.h:605
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/core/urb.c (ffffffff816101e8)
Location: include/uapi/linux/usb/ch9.h:605
Inline: True
```
```
In drivers/usb/core/config.c (0)
Location: include/uapi/linux/usb/ch9.h:605
Inline: True
```
```
In drivers/usb/core/endpoint.c (ffffffff81619449)
Location: include/uapi/linux/usb/ch9.h:605
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:wMaxPacketSize_show
```
```
In drivers/usb/core/devio.c (0)
Location: include/uapi/linux/usb/ch9.h:605
Inline: True
```
```
In drivers/usb/core/devices.c (ffffffff8161e886)
Location: include/uapi/linux/usb/ch9.h:605
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81629331)
Location: include/uapi/linux/usb/ch9.h:605
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81635aa4)
Location: include/uapi/linux/usb/ch9.h:605
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/uapi/linux/usb/ch9.h:605
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8164887d)
Location: include/uapi/linux/usb/ch9.h:605
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
```
In drivers/usb/host/xhci.c (ffffffff8164fc59)
Location: include/uapi/linux/usb/ch9.h:605
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816545cc)
Location: include/uapi/linux/usb/ch9.h:605
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81657596)
Location: include/uapi/linux/usb/ch9.h:605
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816663f0)
Location: include/uapi/linux/usb/ch9.h:628
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/core/urb.c (ffffffff8166fdc1)
Location: include/uapi/linux/usb/ch9.h:628
Inline: True
```
```
In drivers/usb/core/config.c (ffffffff81676828)
Location: include/uapi/linux/usb/ch9.h:628
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/endpoint.c (ffffffff81679609)
Location: include/uapi/linux/usb/ch9.h:628
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:wMaxPacketSize_show
```
```
In drivers/usb/core/devio.c (0)
Location: include/uapi/linux/usb/ch9.h:628
Inline: True
```
```
In drivers/usb/core/devices.c (ffffffff8167eff3)
Location: include/uapi/linux/usb/ch9.h:628
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8168910e)
Location: include/uapi/linux/usb/ch9.h:628
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8169910c)
Location: include/uapi/linux/usb/ch9.h:628
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff816a28ab)
Location: include/uapi/linux/usb/ch9.h:628
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816a9818)
Location: include/uapi/linux/usb/ch9.h:628
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
```
In drivers/usb/host/xhci.c (ffffffff816b0609)
Location: include/uapi/linux/usb/ch9.h:628
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816b5285)
Location: include/uapi/linux/usb/ch9.h:628
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff816b9373)
Location: include/uapi/linux/usb/ch9.h:628
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81693e80)
Location: include/uapi/linux/usb/ch9.h:634
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_init
```
```
In drivers/usb/core/urb.c (ffffffff8169dc1c)
Location: include/uapi/linux/usb/ch9.h:634
Inline: True
```
```
In drivers/usb/core/config.c (ffffffff816a452b)
Location: include/uapi/linux/usb/ch9.h:634
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/endpoint.c (ffffffff816a72e9)
Location: include/uapi/linux/usb/ch9.h:634
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:wMaxPacketSize_show
```
```
In drivers/usb/core/devio.c (0)
Location: include/uapi/linux/usb/ch9.h:634
Inline: True
```
```
In drivers/usb/core/devices.c (0)
Location: include/uapi/linux/usb/ch9.h:634
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/uapi/linux/usb/ch9.h:634
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff816c5026)
Location: include/uapi/linux/usb/ch9.h:634
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff816cf5de)
Location: include/uapi/linux/usb/ch9.h:634
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816d7958)
Location: include/uapi/linux/usb/ch9.h:634
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
```
In drivers/usb/host/xhci.c (ffffffff816de7af)
Location: include/uapi/linux/usb/ch9.h:634
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816e3435)
Location: include/uapi/linux/usb/ch9.h:634
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff816e75f3)
Location: include/uapi/linux/usb/ch9.h:634
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816a94cd)
Location: include/uapi/linux/usb/ch9.h:635
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_init
```
```
In drivers/usb/core/urb.c (ffffffff816b2ed0)
Location: include/uapi/linux/usb/ch9.h:635
Inline: True
```
```
In drivers/usb/core/config.c (ffffffff816b97af)
Location: include/uapi/linux/usb/ch9.h:635
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/endpoint.c (ffffffff816bc639)
Location: include/uapi/linux/usb/ch9.h:635
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:wMaxPacketSize_show
```
```
In drivers/usb/core/devio.c (0)
Location: include/uapi/linux/usb/ch9.h:635
Inline: True
```
```
In drivers/usb/core/devices.c (0)
Location: include/uapi/linux/usb/ch9.h:635
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/uapi/linux/usb/ch9.h:635
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff816d97d7)
Location: include/uapi/linux/usb/ch9.h:635
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff816e3a58)
Location: include/uapi/linux/usb/ch9.h:635
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816ebd86)
Location: include/uapi/linux/usb/ch9.h:635
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
```
In drivers/usb/host/xhci.c (ffffffff816f421d)
Location: include/uapi/linux/usb/ch9.h:635
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816f72ed)
Location: include/uapi/linux/usb/ch9.h:635
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff816fb731)
Location: include/uapi/linux/usb/ch9.h:635
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817148c1)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_init
```
```
In drivers/usb/core/urb.c (ffffffff8171e58c)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
```
```
In drivers/usb/core/config.c (ffffffff817250c2)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/endpoint.c (ffffffff81728009)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:wMaxPacketSize_show
```
```
In drivers/usb/core/devio.c (0)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
```
```
In drivers/usb/core/devices.c (0)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81745e27)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81750278)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81758576)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
```
In drivers/usb/host/xhci.c (ffffffff817604d3)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81764034)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817682a2)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_td_remainder
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817536b8)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_init
```
```
In drivers/usb/core/urb.c (ffffffff8175d08f)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/config.c (ffffffff81763883)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/endpoint.c (ffffffff81766e55)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:wMaxPacketSize_show
```
```
In drivers/usb/core/devio.c (ffffffff817682a7)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_bulk
```
```
In drivers/usb/core/devices.c (0)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81777b71)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81786657)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff8178ff3b)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81797a92)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
```
In drivers/usb/host/xhci.c (ffffffff817a0752)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817a426f)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817aa159)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_td_remainder
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81777aa0)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_init
```
```
In drivers/usb/core/urb.c (ffffffff817816bf)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/config.c (ffffffff81787be7)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/endpoint.c (ffffffff8178b3d5)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:wMaxPacketSize_show
```
```
In drivers/usb/core/devio.c (ffffffff8178caf7)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_bulk
```
```
In drivers/usb/core/devices.c (0)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8179d9c3)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817af42c)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff817b6709)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817bdfd2)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
```
In drivers/usb/host/xhci.c (ffffffff817c6a12)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817ca882)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817d0109)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_td_remainder
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817b5a2d)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_init
```
```
In drivers/usb/core/urb.c (ffffffff817bfbe3)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/config.c (ffffffff817c5946)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
```
```
In drivers/usb/core/endpoint.c (ffffffff817c99e5)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:wMaxPacketSize_show
```
```
In drivers/usb/core/devio.c (ffffffff817cc00d)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_bulk
```
```
In drivers/usb/core/devices.c (0)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817edbc7)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff817f9148)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817fd33a)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
```
In drivers/usb/host/xhci.c (ffffffff81805e4c)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8180ad0d)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8180dbd5)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_td_remainder
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817e6241)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_init
```
```
In drivers/usb/core/urb.c (ffffffff817f0563)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/config.c (ffffffff817f634b)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
```
```
In drivers/usb/core/endpoint.c (ffffffff817fa525)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:wMaxPacketSize_show
```
```
In drivers/usb/core/devio.c (ffffffff817fcc6d)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_bulk
```
```
In drivers/usb/core/devices.c (0)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8181eaa7)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81829fa8)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8182e18a)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
```
In drivers/usb/host/xhci.c (ffffffff81836cfc)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8183bc96)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8183ecc5)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_td_remainder
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818b5e90)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/core/urb.c (ffffffff818bfac9)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/config.c (ffffffff818c64e1)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_ss_endpoint_companion
  - drivers/usb/core/config.c:usb_parse_ss_endpoint_companion
```
```
In drivers/usb/core/endpoint.c (ffffffff818ca745)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:wMaxPacketSize_show
```
```
In drivers/usb/core/devio.c (ffffffff818cbe43)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_bulk
```
```
In drivers/usb/core/devices.c (0)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818ea2cd)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_init
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff818f8146)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:ed_get
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81902a6d)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_submit_common
  - drivers/usb/host/uhci-hcd.c:uhci_submit_control
```
```
In drivers/usb/host/xhci.c (ffffffff81909499)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8190e820)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8191352d)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-ring.c:xhci_td_remainder
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818c4a48)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/core/urb.c (ffffffff818cc689)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/config.c (ffffffff818d211d)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_ss_endpoint_companion
  - drivers/usb/core/config.c:usb_parse_ss_endpoint_companion
```
```
In drivers/usb/core/endpoint.c (ffffffff818d5858)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:wMaxPacketSize_show
```
```
In drivers/usb/core/devio.c (ffffffff818d70eb)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:do_proc_bulk
```
```
In drivers/usb/core/devices.c (0)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818f31bd)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_init
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81900c8d)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:ed_get
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8190b33d)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_submit_common
  - drivers/usb/host/uhci-hcd.c:uhci_submit_control
```
```
In drivers/usb/host/xhci.c (ffffffff81911c72)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
```
In drivers/usb/host/xhci-mem.c (ffffffff819162b7)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8191ab45)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-ring.c:xhci_td_remainder
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818a7ccd)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/core/urb.c (ffffffff818afca6)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/config.c (ffffffff818b566b)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_ss_endpoint_companion
  - drivers/usb/core/config.c:usb_parse_ss_endpoint_companion
```
```
In drivers/usb/core/endpoint.c (ffffffff818b8d48)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:wMaxPacketSize_show
```
```
In drivers/usb/core/devio.c (ffffffff818ba1ab)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:do_proc_bulk
```
```
In drivers/usb/core/devices.c (ffffffff818be3c6)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_dump_config
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818d697c)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_init
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff818e41fa)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:ed_get
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff818ed637)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_submit_common
  - drivers/usb/host/uhci-hcd.c:uhci_submit_control
```
```
In drivers/usb/host/xhci.c (ffffffff818f5289)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
```
In drivers/usb/host/xhci-mem.c (ffffffff818f9827)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff818fdd00)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-ring.c:xhci_td_remainder
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8193cb42)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/core/urb.c (ffffffff81944e02)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/config.c (ffffffff81d16923)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_ss_endpoint_companion
  - drivers/usb/core/config.c:usb_parse_ss_endpoint_companion
```
```
In drivers/usb/core/endpoint.c (ffffffff8194e808)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:wMaxPacketSize_show
```
```
In drivers/usb/core/devio.c (ffffffff8194ffe0)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:do_proc_bulk
```
```
In drivers/usb/core/devices.c (ffffffff81954787)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_dump_config
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff819716ee)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_init
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff8198049a)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:ed_get
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81989d1f)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_submit_common
  - drivers/usb/host/uhci-hcd.c:uhci_submit_control
```
```
In drivers/usb/host/xhci.c (ffffffff81992f6f)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
```
In drivers/usb/host/xhci-mem.c (ffffffff819982bd)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8199d087)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-ring.c:xhci_td_remainder
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81a94811)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/core/urb.c (ffffffff81a9d468)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/config.c (ffffffff81ee154d)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_ss_endpoint_companion
  - drivers/usb/core/config.c:usb_parse_ss_endpoint_companion
```
```
In drivers/usb/core/endpoint.c (ffffffff81aa77f8)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:wMaxPacketSize_show
```
```
In drivers/usb/core/devio.c (ffffffff81aab59a)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:do_proc_bulk
```
```
In drivers/usb/core/devices.c (ffffffff81aae06c)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_dump_config
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81acc58e)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_init
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81adc314)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:ed_get
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81ae7939)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_submit_common
  - drivers/usb/host/uhci-hcd.c:uhci_submit_control
```
```
In drivers/usb/host/xhci.c (ffffffff81aefa2a)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81af54dd)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81afa6ac)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-ring.c:xhci_td_remainder
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c16b2d)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/core/urb.c (ffffffff81c22538)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/config.c (ffffffff81c29d47)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_ss_endpoint_companion
  - drivers/usb/core/config.c:usb_parse_ss_endpoint_companion
```
```
In drivers/usb/core/endpoint.c (ffffffff81c2e6e8)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:wMaxPacketSize_show
```
```
In drivers/usb/core/devio.c (ffffffff81c32a7a)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:do_proc_bulk
```
```
In drivers/usb/core/devices.c (ffffffff81c35a9c)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_dump_config
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81c56d1e)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_init
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81c67615)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:ed_get
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81c73859)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_submit_common
  - drivers/usb/host/uhci-hcd.c:uhci_submit_control
```
```
In drivers/usb/host/xhci.c (ffffffff81c7c77a)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81c82d4d)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81c88acd)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-ring.c:xhci_td_remainder
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c7db07)
Location: include/uapi/linux/usb/ch9.h:650
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/core/urb.c (ffffffff81c894a4)
Location: include/uapi/linux/usb/ch9.h:650
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/config.c (ffffffff81c90d07)
Location: include/uapi/linux/usb/ch9.h:650
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_ss_endpoint_companion
  - drivers/usb/core/config.c:usb_parse_ss_endpoint_companion
```
```
In drivers/usb/core/endpoint.c (ffffffff81c95948)
Location: include/uapi/linux/usb/ch9.h:650
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:wMaxPacketSize_show
```
```
In drivers/usb/core/devio.c (ffffffff81c99d38)
Location: include/uapi/linux/usb/ch9.h:650
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:do_proc_bulk
```
```
In drivers/usb/core/devices.c (ffffffff81c9cdd3)
Location: include/uapi/linux/usb/ch9.h:650
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_dump_config
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/uapi/linux/usb/ch9.h:650
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81cbe3be)
Location: include/uapi/linux/usb/ch9.h:650
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_init
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81cce9a5)
Location: include/uapi/linux/usb/ch9.h:650
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:ed_get
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81cdadff)
Location: include/uapi/linux/usb/ch9.h:650
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_submit_common
  - drivers/usb/host/uhci-hcd.c:uhci_submit_control
```
```
In drivers/usb/host/xhci.c (ffffffff81ce39ea)
Location: include/uapi/linux/usb/ch9.h:650
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81ce98d7)
Location: include/uapi/linux/usb/ch9.h:650
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81cefcdd)
Location: include/uapi/linux/usb/ch9.h:650
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-ring.c:xhci_td_remainder
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81d3275d)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/core/urb.c (ffffffff81d3defd)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/config.c (ffffffff81d458b4)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_ss_endpoint_companion
  - drivers/usb/core/config.c:usb_parse_ss_endpoint_companion
```
```
In drivers/usb/core/endpoint.c (ffffffff81d4a408)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:wMaxPacketSize_show
```
```
In drivers/usb/core/devio.c (ffffffff81d4e908)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:do_proc_bulk
```
```
In drivers/usb/core/devices.c (ffffffff81d51983)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_dump_config
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81d7312e)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_init
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81d838a5)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:ed_get
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81d8fe2f)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_submit_common
  - drivers/usb/host/uhci-hcd.c:uhci_submit_control
```
```
In drivers/usb/host/xhci.c (ffffffff81d98b4a)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81d9f108)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81da54fd)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-ring.c:xhci_td_remainder
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffff800010a14eb8)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_init
```
```
In drivers/usb/core/urb.c (ffff800010a2011c)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/config.c (ffff800010a273a8)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
```
```
In drivers/usb/core/endpoint.c (ffff800010a2bb44)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:wMaxPacketSize_show
```
```
In drivers/usb/core/devio.c (ffff800010a2ddac)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_bulk
```
```
In drivers/usb/core/devices.c (0)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (ffff800010a45ed0)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
```
In drivers/usb/host/ehci-hcd.c (ffff800010a5a5c0)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
```
```
In drivers/usb/host/ohci-hcd.c (ffff800010a6334c)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
```
In drivers/usb/host/uhci-hcd.c (ffff800010a6be68)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
```
In drivers/usb/host/xhci.c (ffff800010a74bb0)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
```
In drivers/usb/host/xhci-mem.c (ffff800010a799f8)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/usb/host/xhci-ring.c (ffff800010a7d5f0)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-mtk-sch.c (ffff800010a8e390)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mtk-sch.c:xhci_mtk_drop_ep_quirk
  - drivers/usb/host/xhci-mtk-sch.c:xhci_mtk_add_ep_quirk
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c0aed0d8)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/core/urb.c (c0af730c)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/config.c (c0afd324)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
```
```
In drivers/usb/core/endpoint.c (c0b01484)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:wMaxPacketSize_show
```
```
In drivers/usb/core/devio.c (c0b03c60)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_bulk
```
```
In drivers/usb/core/devices.c (0)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (c0b18638)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
```
In drivers/usb/host/ehci-hcd.c (c0b2c010)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
```
```
In drivers/usb/host/ohci-hcd.c (c0b376d0)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
```
In drivers/usb/host/uhci-hcd.c (c0b3c974)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_submit_common
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
```
In drivers/usb/host/xhci.c (c0b48650)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
```
In drivers/usb/host/xhci-mem.c (c0b4d410)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/usb/host/xhci-ring.c (c0b508bc)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_td_remainder
```
```
In drivers/usb/host/xhci-mtk-sch.c (c0b5ffa8)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mtk-sch.c:xhci_mtk_drop_ep_quirk
  - drivers/usb/host/xhci-mtk-sch.c:xhci_mtk_add_ep_quirk
```
```
In drivers/usb/musb/musb_host.c (c0b6b8c0)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/musb/musb_host.c:musb_urb_enqueue
```
```
In drivers/usb/musb/musb_gadget.c (c0b6f034)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/musb/musb_gadget.c:musb_gadget_enable
```
```
In drivers/usb/gadget/udc/core.c (c0b71b10)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/gadget/udc/core.c:usb_ep_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c000000000acd1f8)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_init
```
```
In drivers/usb/core/urb.c (c000000000ada3d8)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/config.c (c000000000ae2f10)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
```
```
In drivers/usb/core/endpoint.c (c000000000ae8b4c)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:wMaxPacketSize_show
```
```
In drivers/usb/core/devio.c (c000000000aec9d8)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_bulk
```
```
In drivers/usb/core/devices.c (0)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (c000000000b09fdc)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
```
In drivers/usb/host/ehci-hcd.c (c000000000b1d430)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
```
```
In drivers/usb/host/ohci-hcd.c (c000000000b365a0)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
```
In drivers/usb/host/uhci-hcd.c (c000000000b3bca0)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
```
In drivers/usb/host/xhci.c (c000000000b4ace0)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
```
In drivers/usb/host/xhci-mem.c (c000000000b51064)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/usb/host/xhci-ring.c (c000000000b55b48)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffe000639f32)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_init
```
```
In drivers/usb/core/urb.c (ffffffe000643480)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/config.c (ffffffe000649096)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
```
```
In drivers/usb/core/endpoint.c (ffffffe00064ceb8)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:wMaxPacketSize_show
```
```
In drivers/usb/core/devio.c (ffffffe00064e6a0)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_bulk
```
```
In drivers/usb/core/devices.c (0)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (ffffffe000662904)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
```
In drivers/usb/host/ehci-hcd.c (ffffffe000671e0e)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
```
```
In drivers/usb/host/ohci-hcd.c (ffffffe00067c4a0)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
```
In drivers/usb/host/uhci-hcd.c (ffffffe0006840b4)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
```
In drivers/usb/host/xhci.c (ffffffe00068cd32)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
```
In drivers/usb/host/xhci-mem.c (ffffffe000691182)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffe0006943aa)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8179e621)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_init
```
```
In drivers/usb/core/urb.c (ffffffff817a8943)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/config.c (ffffffff817ae72b)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
```
```
In drivers/usb/core/endpoint.c (ffffffff817b2905)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:wMaxPacketSize_show
```
```
In drivers/usb/core/devio.c (ffffffff817b504d)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_bulk
```
```
In drivers/usb/core/devices.c (0)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817d6e87)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff817e2388)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817e656a)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
```
In drivers/usb/host/xhci.c (ffffffff817ef0ac)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817f4046)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817f7075)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_td_remainder
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817902a1)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_init
```
```
In drivers/usb/core/urb.c (ffffffff8179a353)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/config.c (ffffffff817a012b)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
```
```
In drivers/usb/core/endpoint.c (ffffffff817a4335)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:wMaxPacketSize_show
```
```
In drivers/usb/core/devio.c (ffffffff817a6a7d)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_bulk
```
```
In drivers/usb/core/devices.c (0)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff817b41bc)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817b91e6)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817bc215)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_td_remainder
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817db0c1)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_init
```
```
In drivers/usb/core/urb.c (ffffffff817e53e3)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/config.c (ffffffff817eb1cb)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
```
```
In drivers/usb/core/endpoint.c (ffffffff817ef3a5)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:wMaxPacketSize_show
```
```
In drivers/usb/core/devio.c (ffffffff817f1aed)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_bulk
```
```
In drivers/usb/core/devices.c (0)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81813927)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff8181ee28)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8182300a)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
```
In drivers/usb/host/xhci.c (ffffffff8182bb7c)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81830b16)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81833b45)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_td_remainder
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817f5351)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_init
```
```
In drivers/usb/core/urb.c (ffffffff817ff643)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/config.c (ffffffff8180540b)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
  - drivers/usb/core/config.c:usb_parse_endpoint
```
```
In drivers/usb/core/endpoint.c (ffffffff818095e5)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:wMaxPacketSize_show
```
```
In drivers/usb/core/devio.c (ffffffff8180bd2d)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_bulk
```
```
In drivers/usb/core/devices.c (0)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8182e7c7)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81838d98)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8183e72a)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
```
In drivers/usb/host/xhci.c (ffffffff81845b4c)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8184ace6)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8184de20)
Location: include/uapi/linux/usb/ch9.h:640
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_td_remainder
```
</details>
</li>
</ul>

## Differences
