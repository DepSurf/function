# Function: <code>usb_endpoint_dir_out</code>

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
In drivers/usb/core/hcd.c (0)
Location: include/uapi/linux/usb/ch9.h:461
Inline: True
```
```
In drivers/usb/core/urb.c (0)
Location: include/uapi/linux/usb/ch9.h:461
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff816126e1)
Location: include/uapi/linux/usb/ch9.h:461
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_enable_endpoint
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/uapi/linux/usb/ch9.h:461
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/uapi/linux/usb/ch9.h:461
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
In drivers/usb/core/hcd.c (ffffffff8166f476)
Location: include/uapi/linux/usb/ch9.h:484
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_reset_endpoint
```
```
In drivers/usb/core/urb.c (0)
Location: include/uapi/linux/usb/ch9.h:484
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff81672681)
Location: include/uapi/linux/usb/ch9.h:484
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_enable_endpoint
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8169b5cb)
Location: include/uapi/linux/usb/ch9.h:484
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
```
```
In drivers/usb/host/xhci.c (0)
Location: include/uapi/linux/usb/ch9.h:484
Inline: True
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
In drivers/usb/core/hcd.c (ffffffff8169d156)
Location: include/uapi/linux/usb/ch9.h:490
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_reset_endpoint
```
```
In drivers/usb/core/urb.c (0)
Location: include/uapi/linux/usb/ch9.h:490
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff816a0331)
Location: include/uapi/linux/usb/ch9.h:490
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_enable_endpoint
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff816c96ab)
Location: include/uapi/linux/usb/ch9.h:490
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
```
```
In drivers/usb/host/xhci.c (0)
Location: include/uapi/linux/usb/ch9.h:490
Inline: True
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
In drivers/usb/core/hcd.c (ffffffff816b2525)
Location: include/uapi/linux/usb/ch9.h:491
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_reset_endpoint
```
```
In drivers/usb/core/urb.c (0)
Location: include/uapi/linux/usb/ch9.h:491
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff816b5501)
Location: include/uapi/linux/usb/ch9.h:491
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_enable_endpoint
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff816de03e)
Location: include/uapi/linux/usb/ch9.h:491
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
```
```
In drivers/usb/host/xhci.c (0)
Location: include/uapi/linux/usb/ch9.h:491
Inline: True
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
In drivers/usb/core/hcd.c (ffffffff8171dba8)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_reset_endpoint
```
```
In drivers/usb/core/urb.c (0)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff81720d91)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_enable_endpoint
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8174a77b)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
```
```
In drivers/usb/host/xhci.c (0)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
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
In drivers/usb/core/hcd.c (ffffffff8175c80c)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_reset_endpoint
```
```
In drivers/usb/core/urb.c (ffffffff8175d1c2)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/message.c (ffffffff8175fbad)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_enable_endpoint
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8178a64d)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
```
```
In drivers/usb/host/xhci.c (ffffffff817a0def)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
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
In drivers/usb/core/hcd.c (ffffffff81780dcc)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_reset_endpoint
```
```
In drivers/usb/core/urb.c (ffffffff81781839)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/message.c (ffffffff8178416d)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_enable_endpoint
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817ac2ed)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
```
```
In drivers/usb/host/xhci.c (ffffffff817c70af)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
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
In drivers/usb/core/hcd.c (ffffffff817be7dc)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_reset_endpoint
```
```
In drivers/usb/core/urb.c (ffffffff817bfd01)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/message.c (ffffffff817c24ad)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_enable_endpoint
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817eb507)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
```
```
In drivers/usb/host/xhci.c (ffffffff818064a6)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
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
In drivers/usb/core/hcd.c (ffffffff817ef13c)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_reset_endpoint
```
```
In drivers/usb/core/urb.c (ffffffff817f0681)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/message.c (ffffffff817f2e2d)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_enable_endpoint
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8181c3d7)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
```
```
In drivers/usb/host/xhci.c (ffffffff81837356)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
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
In drivers/usb/core/hcd.c (ffffffff818be76c)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_reset_endpoint
```
```
In drivers/usb/core/urb.c (ffffffff818bfb52)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/message.c (ffffffff818c297f)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_enable_interface
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818f2cf7)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
```
```
In drivers/usb/host/xhci.c (ffffffff81909ae6)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
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
In drivers/usb/core/hcd.c (ffffffff818cb36c)
Location: include/uapi/linux/usb/ch9.h:503
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_reset_endpoint
```
```
In drivers/usb/core/urb.c (ffffffff818cc7a4)
Location: include/uapi/linux/usb/ch9.h:503
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/message.c (ffffffff818cec9f)
Location: include/uapi/linux/usb/ch9.h:503
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_enable_interface
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818fbc17)
Location: include/uapi/linux/usb/ch9.h:503
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
```
```
In drivers/usb/host/xhci.c (ffffffff81912472)
Location: include/uapi/linux/usb/ch9.h:503
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
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
In drivers/usb/common/common.c (ffffffff818a2b86)
Location: include/uapi/linux/usb/ch9.h:503
Inline: True
Inline callers:
  - drivers/usb/common/common.c:usb_decode_interval
```
```
In drivers/usb/core/hcd.c (ffffffff818ae98c)
Location: include/uapi/linux/usb/ch9.h:503
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_reset_endpoint
```
```
In drivers/usb/core/urb.c (ffffffff818afc7d)
Location: include/uapi/linux/usb/ch9.h:503
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/message.c (ffffffff818b22d0)
Location: include/uapi/linux/usb/ch9.h:503
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_enable_interface
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818de8c7)
Location: include/uapi/linux/usb/ch9.h:503
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
```
```
In drivers/usb/host/xhci.c (ffffffff818f5ab1)
Location: include/uapi/linux/usb/ch9.h:503
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
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
In drivers/usb/common/common.c (ffffffff8193789c)
Location: include/uapi/linux/usb/ch9.h:503
Inline: True
Inline callers:
  - drivers/usb/common/common.c:usb_decode_interval
```
```
In drivers/usb/core/hcd.c (ffffffff81943af0)
Location: include/uapi/linux/usb/ch9.h:503
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_reset_endpoint
```
```
In drivers/usb/core/urb.c (ffffffff81944dd1)
Location: include/uapi/linux/usb/ch9.h:503
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/message.c (ffffffff819475c0)
Location: include/uapi/linux/usb/ch9.h:503
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_enable_interface
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8197a537)
Location: include/uapi/linux/usb/ch9.h:503
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
```
```
In drivers/usb/host/xhci.c (ffffffff81993b49)
Location: include/uapi/linux/usb/ch9.h:503
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
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
In drivers/usb/common/common.c (ffffffff81a8ef50)
Location: include/uapi/linux/usb/ch9.h:503
Inline: True
Inline callers:
  - drivers/usb/common/common.c:usb_decode_interval
```
```
In drivers/usb/core/hcd.c (ffffffff81a9bf81)
Location: include/uapi/linux/usb/ch9.h:503
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_reset_endpoint
```
```
In drivers/usb/core/urb.c (ffffffff81a9d433)
Location: include/uapi/linux/usb/ch9.h:503
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/message.c (ffffffff81a9ff00)
Location: include/uapi/linux/usb/ch9.h:503
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_enable_interface
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81ad7d07)
Location: include/uapi/linux/usb/ch9.h:503
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
```
```
In drivers/usb/host/xhci.c (ffffffff81af065f)
Location: include/uapi/linux/usb/ch9.h:503
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
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
In drivers/usb/common/common.c (ffffffff81c10920)
Location: include/uapi/linux/usb/ch9.h:503
Inline: True
Inline callers:
  - drivers/usb/common/common.c:usb_decode_interval
```
```
In drivers/usb/core/hcd.c (ffffffff81c20e21)
Location: include/uapi/linux/usb/ch9.h:503
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_reset_endpoint
```
```
In drivers/usb/core/urb.c (ffffffff81c22503)
Location: include/uapi/linux/usb/ch9.h:503
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/message.c (ffffffff81c25340)
Location: include/uapi/linux/usb/ch9.h:503
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_enable_interface
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81c62cf7)
Location: include/uapi/linux/usb/ch9.h:503
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
```
```
In drivers/usb/host/xhci.c (ffffffff81c7d47b)
Location: include/uapi/linux/usb/ch9.h:503
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
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
In drivers/usb/common/common.c (ffffffff81c77591)
Location: include/uapi/linux/usb/ch9.h:506
Inline: True
Inline callers:
  - drivers/usb/common/common.c:usb_decode_interval
```
```
In drivers/usb/core/hcd.c (ffffffff81c87da1)
Location: include/uapi/linux/usb/ch9.h:506
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_reset_endpoint
```
```
In drivers/usb/core/urb.c (ffffffff81c8946f)
Location: include/uapi/linux/usb/ch9.h:506
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/message.c (ffffffff81c8c2cd)
Location: include/uapi/linux/usb/ch9.h:506
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_enable_interface
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81cca0f7)
Location: include/uapi/linux/usb/ch9.h:506
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
```
```
In drivers/usb/host/xhci.c (ffffffff81ce46ee)
Location: include/uapi/linux/usb/ch9.h:506
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
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
In drivers/usb/common/common.c (ffffffff81d2bf91)
Location: include/uapi/linux/usb/ch9.h:503
Inline: True
Inline callers:
  - drivers/usb/common/common.c:usb_decode_interval
```
```
In drivers/usb/core/hcd.c (ffffffff81d3c7f1)
Location: include/uapi/linux/usb/ch9.h:503
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_reset_endpoint
```
```
In drivers/usb/core/urb.c (ffffffff81d3dec3)
Location: include/uapi/linux/usb/ch9.h:503
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/message.c (ffffffff81d40dad)
Location: include/uapi/linux/usb/ch9.h:503
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_enable_interface
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81d7efd7)
Location: include/uapi/linux/usb/ch9.h:503
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
```
```
In drivers/usb/host/xhci.c (0)
Location: include/uapi/linux/usb/ch9.h:503
Inline: True
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
In drivers/usb/core/hcd.c (ffff800010a1eed4)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_reset_endpoint
```
```
In drivers/usb/core/urb.c (ffff800010a2021c)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/message.c (ffff800010a23838)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_enable_endpoint
```
```
In drivers/usb/host/ehci-hcd.c (ffff800010a59a60)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
```
```
In drivers/usb/host/xhci.c (ffff800010a75398)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mtk-sch.c (ffff800010a8e288)
Location: include/uapi/linux/usb/ch9.h:496
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
In drivers/usb/core/hcd.c (c0af65c8)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_reset_endpoint
```
```
In drivers/usb/core/urb.c (c0af748c)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/message.c (c0af9e20)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_enable_endpoint
```
```
In drivers/usb/host/ehci-hcd.c (c0b28ab8)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
```
```
In drivers/usb/host/xhci.c (c0b48dac)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mtk-sch.c (c0b5fe80)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mtk-sch.c:xhci_mtk_drop_ep_quirk
  - drivers/usb/host/xhci-mtk-sch.c:xhci_mtk_add_ep_quirk
```
```
In drivers/usb/gadget/udc/core.c (0)
Location: include/uapi/linux/usb/ch9.h:496
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
In drivers/usb/core/hcd.c (c000000000ad9134)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_reset_endpoint
```
```
In drivers/usb/core/urb.c (c000000000ada540)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/message.c (c000000000ade350)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_enable_endpoint
```
```
In drivers/usb/host/ehci-hcd.c (c000000000b229a0)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
```
```
In drivers/usb/host/xhci.c (c000000000b4b630)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
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
In drivers/usb/core/hcd.c (ffffffe0006427c4)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_reset_endpoint
```
```
In drivers/usb/core/urb.c (ffffffe000643582)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/message.c (ffffffe000645f20)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_enable_endpoint
```
```
In drivers/usb/host/ehci-hcd.c (ffffffe0006752ec)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
```
```
In drivers/usb/host/xhci.c (ffffffe00068d440)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
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
In drivers/usb/core/hcd.c (ffffffff817a751c)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_reset_endpoint
```
```
In drivers/usb/core/urb.c (ffffffff817a8a61)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/message.c (ffffffff817ab20d)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_enable_endpoint
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817d47b7)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
```
```
In drivers/usb/host/xhci.c (ffffffff817ef706)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
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
In drivers/usb/core/hcd.c (ffffffff81798f6c)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_reset_endpoint
```
```
In drivers/usb/core/urb.c (ffffffff8179a471)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/message.c (ffffffff8179cc0d)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_enable_endpoint
```
```
In drivers/usb/host/xhci.c (ffffffff817b4816)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
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
In drivers/usb/core/hcd.c (ffffffff817e3fbc)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_reset_endpoint
```
```
In drivers/usb/core/urb.c (ffffffff817e5501)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/message.c (ffffffff817e7cad)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_enable_endpoint
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81811257)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
```
```
In drivers/usb/host/xhci.c (ffffffff8182c1d6)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
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
In drivers/usb/core/hcd.c (ffffffff817fe25c)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_reset_endpoint
```
```
In drivers/usb/core/urb.c (ffffffff817ff761)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/message.c (ffffffff81801efd)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_enable_endpoint
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8182bd27)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
```
```
In drivers/usb/host/xhci.c (ffffffff818461bf)
Location: include/uapi/linux/usb/ch9.h:496
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
</details>
</li>
</ul>

## Differences
