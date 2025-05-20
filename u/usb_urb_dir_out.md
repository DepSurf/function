# Function: <code>usb_urb_dir_out</code>

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
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/usb.h:1655
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/usb.h:1655
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
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/usb.h:1655
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/usb.h:1655
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
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/usb.h:1726
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/usb.h:1726
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
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/usb.h:1727
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/usb.h:1727
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
In drivers/usb/dwc2/hcd.c (ffffffff8177467b)
Location: include/linux/usb.h:1746
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817a95e0)
Location: include/linux/usb.h:1746
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
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
In drivers/usb/dwc2/hcd.c (ffffffff8179997b)
Location: include/linux/usb.h:1746
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817cf56c)
Location: include/linux/usb.h:1746
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
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
In drivers/usb/dwc2/hcd.c (ffffffff817d8bd5)
Location: include/linux/usb.h:1746
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff81800cc7)
Location: include/linux/usb.h:1746
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8180f67d)
Location: include/linux/usb.h:1746
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
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
In drivers/usb/dwc2/hcd.c (ffffffff81809a65)
Location: include/linux/usb.h:1751
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff81831d77)
Location: include/linux/usb.h:1751
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81840a8c)
Location: include/linux/usb.h:1751
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
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
In drivers/usb/dwc2/hcd.c (ffffffff818da3be)
Location: include/linux/usb.h:1758
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_alloc_dma_aligned_buffer
```
```
In drivers/usb/host/xhci.c (ffffffff819043b4)
Location: include/linux/usb.h:1758
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff819151bc)
Location: include/linux/usb.h:1758
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_align_td
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
In drivers/usb/dwc2/hcd.c (ffffffff818e42de)
Location: include/linux/usb.h:1764
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_alloc_dma_aligned_buffer
```
```
In drivers/usb/host/xhci.c (ffffffff8190cc42)
Location: include/linux/usb.h:1764
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8191c78c)
Location: include/linux/usb.h:1764
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_align_td
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
In drivers/usb/dwc2/hcd.c (ffffffff818c719e)
Location: include/linux/usb.h:1773
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_alloc_dma_aligned_buffer
```
```
In drivers/usb/host/xhci.c (ffffffff818f01b2)
Location: include/linux/usb.h:1773
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81900b99)
Location: include/linux/usb.h:1773
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_align_td
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
In drivers/usb/dwc2/hcd.c (ffffffff8195e6de)
Location: include/linux/usb.h:1766
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_alloc_dma_aligned_buffer
```
```
In drivers/usb/host/xhci.c (ffffffff8198ce52)
Location: include/linux/usb.h:1766
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
```
```
In drivers/usb/host/xhci-ring.c (ffffffff819a034d)
Location: include/linux/usb.h:1766
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_align_td
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
In drivers/usb/dwc2/hcd.c (ffffffff81ab8ad3)
Location: include/linux/usb.h:1757
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_alloc_dma_aligned_buffer
```
```
In drivers/usb/host/xhci.c (ffffffff81ae9082)
Location: include/linux/usb.h:1757
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81afda6a)
Location: include/linux/usb.h:1757
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_align_td
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
In drivers/usb/dwc2/hcd.c (ffffffff81c420d3)
Location: include/linux/usb.h:1786
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_alloc_dma_aligned_buffer
```
```
In drivers/usb/host/xhci.c (ffffffff81c75342)
Location: include/linux/usb.h:1786
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81c8c78b)
Location: include/linux/usb.h:1786
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_align_td
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
In drivers/usb/dwc2/hcd.c (ffffffff81ca968e)
Location: include/linux/usb.h:1825
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_alloc_dma_aligned_buffer
```
```
In drivers/usb/host/xhci.c (ffffffff81cdca02)
Location: include/linux/usb.h:1825
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81cf3318)
Location: include/linux/usb.h:1825
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_align_td
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
In drivers/usb/dwc2/hcd.c (ffffffff81d5e33e)
Location: include/linux/usb.h:1808
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_alloc_dma_aligned_buffer
```
```
In drivers/usb/host/xhci.c (ffffffff81d91a22)
Location: include/linux/usb.h:1808
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81da8c58)
Location: include/linux/usb.h:1808
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_align_td
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
In drivers/usb/dwc2/hcd.c (ffff800010a40364)
Location: include/linux/usb.h:1751
Inline: True
```
```
In drivers/usb/host/xhci.c (ffff800010a6e274)
Location: include/linux/usb.h:1751
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
```
In drivers/usb/host/xhci-ring.c (ffff800010a7f860)
Location: include/linux/usb.h:1751
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
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
In drivers/usb/dwc2/hcd.c (c0b12ef0)
Location: include/linux/usb.h:1751
Inline: True
```
```
In drivers/usb/host/xhci.c (c0b428bc)
Location: include/linux/usb.h:1751
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
```
In drivers/usb/host/xhci-ring.c (c0b52bf4)
Location: include/linux/usb.h:1751
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_unmap_td_bounce_buffer
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
In drivers/usb/dwc2/hcd.c (c000000000b00e6c)
Location: include/linux/usb.h:1751
Inline: True
```
```
In drivers/usb/host/xhci.c (c000000000b4289c)
Location: include/linux/usb.h:1751
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
```
In drivers/usb/host/xhci-ring.c (c000000000b5815c)
Location: include/linux/usb.h:1751
Inline: True
Inline callers:
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
In drivers/usb/dwc2/hcd.c (ffffffe00065c250)
Location: include/linux/usb.h:1751
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffe000687794)
Location: include/linux/usb.h:1751
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
```
In drivers/usb/host/xhci-ring.c (ffffffe0006962a0)
Location: include/linux/usb.h:1751
Inline: True
Inline callers:
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
In drivers/usb/dwc2/hcd.c (ffffffff817c1e45)
Location: include/linux/usb.h:1751
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff817ea157)
Location: include/linux/usb.h:1751
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817f8e3c)
Location: include/linux/usb.h:1751
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
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
In drivers/usb/host/xhci.c (ffffffff817af267)
Location: include/linux/usb.h:1751
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817bdfdc)
Location: include/linux/usb.h:1751
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
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
In drivers/usb/dwc2/hcd.c (ffffffff817fe8e5)
Location: include/linux/usb.h:1751
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff81826bf7)
Location: include/linux/usb.h:1751
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8183590c)
Location: include/linux/usb.h:1751
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
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
In drivers/usb/dwc2/hcd.c (ffffffff818189f5)
Location: include/linux/usb.h:1751
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff81840ad7)
Location: include/linux/usb.h:1751
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8184fc42)
Location: include/linux/usb.h:1751
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
</details>
</li>
</ul>

## Differences
