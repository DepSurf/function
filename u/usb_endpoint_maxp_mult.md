# Function: <code>usb_endpoint_maxp_mult</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff8169de8d)
Location: include/uapi/linux/usb/ch9.h:646
Inline: True
```
```
In drivers/usb/core/devices.c (ffffffff816acd73)
Location: include/uapi/linux/usb/ch9.h:646
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff816c52a5)
Location: include/uapi/linux/usb/ch9.h:646
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816e343a)
Location: include/uapi/linux/usb/ch9.h:646
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
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
In drivers/usb/core/urb.c (ffffffff816b2f08)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
```
```
In drivers/usb/core/devices.c (ffffffff816c1fea)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff816d9a3c)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816f72f3)
Location: include/uapi/linux/usb/ch9.h:647
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
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
In drivers/usb/core/urb.c (ffffffff8171e5c4)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
```
```
In drivers/usb/core/devices.c (ffffffff8172ddba)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8174608c)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81764039)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
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
In drivers/usb/core/urb.c (ffffffff8175d21c)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/devices.c (ffffffff8176cc75)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817868b8)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817a4274)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
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
In drivers/usb/core/urb.c (ffffffff81781893)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/devices.c (ffffffff817912c5)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817af651)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817ca887)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
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
In drivers/usb/core/urb.c (ffffffff817bfd5d)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/devices.c (ffffffff817cf897)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_dump_desc
```
```
In drivers/usb/dwc2/hcd.c (ffffffff817dc5d7)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817ede41)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8180ad12)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
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
In drivers/usb/core/urb.c (ffffffff817f06dd)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/devices.c (ffffffff81800707)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_dump_desc
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8180d4fd)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8181ed21)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8183bc9b)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
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
In drivers/usb/core/urb.c (ffffffff818bfbac)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/devices.c (ffffffff818d0b5c)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_dump_config
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818de34d)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818ea4db)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_init
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8190e825)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
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
In drivers/usb/core/urb.c (ffffffff818cc7fe)
Location: include/uapi/linux/usb/ch9.h:659
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/devices.c (ffffffff818dafc9)
Location: include/uapi/linux/usb/ch9.h:659
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_dump_config
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818e81b6)
Location: include/uapi/linux/usb/ch9.h:659
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818f33cb)
Location: include/uapi/linux/usb/ch9.h:659
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_init
```
```
In drivers/usb/host/xhci-mem.c (ffffffff819162bc)
Location: include/uapi/linux/usb/ch9.h:659
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
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
In drivers/usb/core/urb.c (ffffffff818afcd7)
Location: include/uapi/linux/usb/ch9.h:659
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/devices.c (ffffffff818be449)
Location: include/uapi/linux/usb/ch9.h:659
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_dump_config
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818ccebd)
Location: include/uapi/linux/usb/ch9.h:659
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818d6b83)
Location: include/uapi/linux/usb/ch9.h:659
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_init
```
```
In drivers/usb/host/xhci-mem.c (ffffffff818f982c)
Location: include/uapi/linux/usb/ch9.h:659
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
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
In drivers/usb/core/urb.c (ffffffff81944e34)
Location: include/uapi/linux/usb/ch9.h:659
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/devices.c (ffffffff81954809)
Location: include/uapi/linux/usb/ch9.h:659
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_dump_config
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81966c92)
Location: include/uapi/linux/usb/ch9.h:659
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff819718fd)
Location: include/uapi/linux/usb/ch9.h:659
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_init
```
```
In drivers/usb/host/xhci-mem.c (ffffffff819982c2)
Location: include/uapi/linux/usb/ch9.h:659
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
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
In drivers/usb/core/urb.c (ffffffff81a9d49a)
Location: include/uapi/linux/usb/ch9.h:659
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/devices.c (ffffffff81aae0d9)
Location: include/uapi/linux/usb/ch9.h:659
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_dump_config
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81ac0e3f)
Location: include/uapi/linux/usb/ch9.h:659
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81acc7b9)
Location: include/uapi/linux/usb/ch9.h:659
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_init
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81af54e2)
Location: include/uapi/linux/usb/ch9.h:659
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
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
In drivers/usb/core/urb.c (ffffffff81c2256a)
Location: include/uapi/linux/usb/ch9.h:659
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/devices.c (ffffffff81c35b09)
Location: include/uapi/linux/usb/ch9.h:659
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_dump_config
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81c4aa28)
Location: include/uapi/linux/usb/ch9.h:659
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81c56f49)
Location: include/uapi/linux/usb/ch9.h:659
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_init
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81c82d52)
Location: include/uapi/linux/usb/ch9.h:659
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
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
In drivers/usb/core/urb.c (ffffffff81c894d4)
Location: include/uapi/linux/usb/ch9.h:662
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/devices.c (ffffffff81c9ce42)
Location: include/uapi/linux/usb/ch9.h:662
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_dump_config
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81cb1ff3)
Location: include/uapi/linux/usb/ch9.h:662
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81cbe5e7)
Location: include/uapi/linux/usb/ch9.h:662
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_init
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81ce98dc)
Location: include/uapi/linux/usb/ch9.h:662
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
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
In drivers/usb/core/urb.c (ffffffff81d3df2f)
Location: include/uapi/linux/usb/ch9.h:659
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/devices.c (ffffffff81d519f2)
Location: include/uapi/linux/usb/ch9.h:659
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_dump_config
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81d66d03)
Location: include/uapi/linux/usb/ch9.h:659
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81d73357)
Location: include/uapi/linux/usb/ch9.h:659
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_init
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81d9f10d)
Location: include/uapi/linux/usb/ch9.h:659
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
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
In drivers/usb/core/urb.c (0)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
```
```
In drivers/usb/core/devices.c (ffff800010a34538)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_dump_desc
```
```
In drivers/usb/dwc2/hcd.c (ffff800010a45ed8)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
```
In drivers/usb/host/ehci-hcd.c (ffff800010a5a808)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
```
```
In drivers/usb/host/xhci-mem.c (ffff800010a799fc)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
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
In drivers/usb/core/urb.c (c0af74e8)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/devices.c (c0b07d48)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_dump_desc
```
```
In drivers/usb/dwc2/hcd.c (c0b18638)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
```
In drivers/usb/host/ehci-hcd.c (c0b2c25c)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
```
```
In drivers/usb/host/xhci-mem.c (c0b4d414)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/usb/musb/musb_host.c (c0b6b8d8)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/musb/musb_host.c:musb_urb_enqueue
```
```
In drivers/usb/musb/musb_gadget.c (c0b6f01c)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/musb/musb_gadget.c:musb_gadget_enable
```
```
In drivers/usb/gadget/udc/core.c (c0b7389c)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
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
In drivers/usb/core/urb.c (c000000000ada5a4)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/devices.c (c000000000af2000)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_dump_desc
```
```
In drivers/usb/dwc2/hcd.c (c000000000b09ff8)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
```
In drivers/usb/host/ehci-hcd.c (c000000000b1d6d0)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
```
```
In drivers/usb/host/xhci-mem.c (c000000000b51068)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
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
In drivers/usb/core/urb.c (ffffffe0006435d8)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/devices.c (ffffffe00065218a)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_dump_desc
```
```
In drivers/usb/dwc2/hcd.c (ffffffe000662914)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
```
In drivers/usb/host/ehci-hcd.c (ffffffe000672022)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
```
```
In drivers/usb/host/xhci-mem.c (ffffffe000691190)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
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
In drivers/usb/core/urb.c (ffffffff817a8abd)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/devices.c (ffffffff817b8ae7)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_dump_desc
```
```
In drivers/usb/dwc2/hcd.c (ffffffff817c58dd)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817d7101)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817f404b)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
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
In drivers/usb/core/urb.c (ffffffff8179a4cd)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/devices.c (ffffffff817aa517)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_dump_desc
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817b91eb)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
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
In drivers/usb/core/urb.c (ffffffff817e555d)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/devices.c (ffffffff817f5587)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_dump_desc
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8180237d)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81813ba1)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81830b1b)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
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
In drivers/usb/core/urb.c (ffffffff817ff7bd)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/devices.c (ffffffff8180f7c7)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_dump_desc
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8181c48d)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8182ea41)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8184aceb)
Location: include/uapi/linux/usb/ch9.h:652
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
</details>
</li>
</ul>

## Differences
