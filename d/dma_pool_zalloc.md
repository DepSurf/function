# Function: <code>dma_pool_zalloc</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff816a91d6)
Location: include/linux/dmapool.h:27
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816b3811)
Location: include/linux/dmapool.h:27
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
In drivers/usb/host/ohci-hcd.c (ffffffff816cf52f)
Location: include/linux/dmapool.h:27
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816d72f6)
Location: include/linux/dmapool.h:27
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816e19c1)
Location: include/linux/dmapool.h:27
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
In drivers/usb/host/ohci-hcd.c (ffffffff816e39b3)
Location: include/linux/dmapool.h:27
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816eb726)
Location: include/linux/dmapool.h:27
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816f5bdc)
Location: include/linux/dmapool.h:27
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
In drivers/usb/host/ohci-hcd.c (ffffffff817501d3)
Location: include/linux/dmapool.h:27
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81757f16)
Location: include/linux/dmapool.h:27
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8176343d)
Location: include/linux/dmapool.h:27
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
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
In drivers/usb/host/ohci-hcd.c (ffffffff8178fe9c)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81797439)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817a369b)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
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
In drivers/usb/host/ohci-hcd.c (ffffffff817b666a)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817bd979)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817c99db)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
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
In drivers/usb/host/ohci-hcd.c (ffffffff817f94d5)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:td_alloc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817fcaf9)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81809dec)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
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
In drivers/usb/host/ohci-hcd.c (ffffffff8182a335)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:td_alloc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8182d949)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8183ad6c)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
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
In drivers/usb/host/ohci-hcd.c (ffffffff818f7d62)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:td_alloc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81901b26)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8190d79c)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
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
In drivers/usb/host/ohci-hcd.c (ffffffff819008b2)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:td_alloc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8190a3f2)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8191533c)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
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
In drivers/dma/lgm/lgm-dma.c (ffffffff817086e5)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff818e3e1d)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:td_alloc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff818ee9aa)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff818f884e)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
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
In drivers/dma/lgm/lgm-dma.c (ffffffff81784505)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff819800bd)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:td_alloc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8198b186)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81996f6d)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
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
In drivers/dma/lgm/lgm-dma.c (ffffffff818bb1d5)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81ad0000)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81adbfd7)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:td_alloc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81ae6a39)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81af3e25)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
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
In drivers/dma/lgm/lgm-dma.c (ffffffff81a09c95)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81c5b140)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81c672b7)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:td_alloc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81c72844)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81c81413)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
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
In drivers/dma/lgm/lgm-dma.c (ffffffff81a52b25)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81cc27c0)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81cce64e)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:td_alloc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81cd9e44)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81cea3c3)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
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
In drivers/dma/lgm/lgm-dma.c (ffffffff81a9e8a4)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81d774bf)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81d8354e)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:td_alloc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81d8ee83)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81d9fc4f)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
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
In drivers/usb/host/ohci-hcd.c (ffff800010a63788)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:td_alloc
```
```
In drivers/usb/host/uhci-hcd.c (ffff800010a69004)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
```
In drivers/usb/host/xhci-mem.c (ffff800010a7887c)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
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
In drivers/usb/host/ohci-hcd.c (c0b37944)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:td_alloc
```
```
In drivers/usb/host/uhci-hcd.c (c0b394e8)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
```
In drivers/usb/host/xhci-mem.c (c0b4c49c)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
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
In drivers/usb/host/ohci-hcd.c (c000000000b3698c)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:td_alloc
```
```
In drivers/usb/host/uhci-hcd.c (c000000000b38880)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
```
In drivers/usb/host/xhci-mem.c (c000000000b4fccc)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
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
In drivers/usb/host/ohci-hcd.c (ffffffe00067c63a)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:td_alloc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffe000681dfe)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
```
In drivers/usb/host/xhci-mem.c (ffffffe000690342)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
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
In drivers/usb/host/ohci-hcd.c (ffffffff817e2715)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:td_alloc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817e5d29)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817f311c)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817b82bc)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
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
In drivers/usb/host/ohci-hcd.c (ffffffff8181f1b5)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:td_alloc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff818227c9)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8182fbec)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
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
In drivers/usb/host/ohci-hcd.c (ffffffff81839125)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:td_alloc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8183dee9)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_alloc_qh
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81849d8c)
Location: include/linux/dmapool.h:52
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
</details>
</li>
</ul>

## Differences
