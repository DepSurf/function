# Function: <code>usb_urb_dir_in</code>

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
Location: include/linux/usb.h:1646
Inline: True
```
```
In drivers/usb/core/message.c (0)
Location: include/linux/usb.h:1646
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/usb.h:1646
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
In drivers/usb/core/hcd.c (0)
Location: include/linux/usb.h:1643
Inline: True
```
```
In drivers/usb/core/message.c (0)
Location: include/linux/usb.h:1643
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/usb.h:1643
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (ffffffff816b9a9d)
Location: include/linux/usb.h:1643
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
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
In drivers/usb/core/hcd.c (0)
Location: include/linux/usb.h:1643
Inline: True
```
```
In drivers/usb/core/message.c (0)
Location: include/linux/usb.h:1643
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/usb.h:1643
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (ffffffff816e7d0d)
Location: include/linux/usb.h:1643
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
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
In drivers/usb/core/hcd.c (0)
Location: include/linux/usb.h:1714
Inline: True
```
```
In drivers/usb/core/message.c (0)
Location: include/linux/usb.h:1714
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/usb.h:1714
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (ffffffff816fbe46)
Location: include/linux/usb.h:1714
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
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
In drivers/usb/core/hcd.c (0)
Location: include/linux/usb.h:1715
Inline: True
```
```
In drivers/usb/core/message.c (0)
Location: include/linux/usb.h:1715
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/usb.h:1715
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817689b6)
Location: include/linux/usb.h:1715
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
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
In drivers/usb/core/hcd.c (ffffffff8175c386)
Location: include/linux/usb.h:1734
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
```
```
In drivers/usb/core/message.c (ffffffff8175f207)
Location: include/linux/usb.h:1734
Inline: True
Inline callers:
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81773bcd)
Location: include/linux/usb.h:1734
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817aa31d)
Location: include/linux/usb.h:1734
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
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
In drivers/usb/core/hcd.c (ffffffff81780946)
Location: include/linux/usb.h:1734
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
```
```
In drivers/usb/core/message.c (ffffffff81782abe)
Location: include/linux/usb.h:1734
Inline: True
Inline callers:
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8179985d)
Location: include/linux/usb.h:1734
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817d02cd)
Location: include/linux/usb.h:1734
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
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
In drivers/usb/core/hcd.c (ffffffff817be34f)
Location: include/linux/usb.h:1734
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
```
```
In drivers/usb/core/message.c (ffffffff817c340d)
Location: include/linux/usb.h:1734
Inline: True
Inline callers:
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/core/devio.c (ffffffff817cb098)
Location: include/linux/usb.h:1734
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/usb/dwc2/hcd.c (ffffffff817d8a7d)
Location: include/linux/usb.h:1734
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8180dd90)
Location: include/linux/usb.h:1734
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
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
In drivers/usb/core/hcd.c (ffffffff817eecaf)
Location: include/linux/usb.h:1739
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
```
```
In drivers/usb/core/message.c (ffffffff817f3d8d)
Location: include/linux/usb.h:1739
Inline: True
Inline callers:
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/core/devio.c (ffffffff817fbc98)
Location: include/linux/usb.h:1739
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8180990d)
Location: include/linux/usb.h:1739
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8183ee80)
Location: include/linux/usb.h:1739
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
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
In drivers/usb/core/hcd.c (ffffffff818be2da)
Location: include/linux/usb.h:1746
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
```
```
In drivers/usb/core/message.c (ffffffff818c390d)
Location: include/linux/usb.h:1746
Inline: True
Inline callers:
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/core/devio.c (ffffffff818cd428)
Location: include/linux/usb.h:1746
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818da49d)
Location: include/linux/usb.h:1746
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (ffffffff819136e2)
Location: include/linux/usb.h:1746
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
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
In drivers/usb/core/hcd.c (ffffffff818caeda)
Location: include/linux/usb.h:1752
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
```
```
In drivers/usb/core/message.c (ffffffff81c1ceca)
Location: include/linux/usb.h:1752
Inline: True
Inline callers:
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/core/devio.c (ffffffff818d6aa8)
Location: include/linux/usb.h:1752
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818e43bd)
Location: include/linux/usb.h:1752
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff8190c899)
Location: include/linux/usb.h:1752
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_unmap_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_unmap_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8191ace1)
Location: include/linux/usb.h:1752
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
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
In drivers/usb/core/hcd.c (ffffffff818ae4fa)
Location: include/linux/usb.h:1761
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
```
```
In drivers/usb/core/message.c (ffffffff81c0ed90)
Location: include/linux/usb.h:1761
Inline: True
Inline callers:
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/core/devio.c (ffffffff818bbae6)
Location: include/linux/usb.h:1761
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818c727d)
Location: include/linux/usb.h:1761
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff818efdbb)
Location: include/linux/usb.h:1761
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_unmap_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_unmap_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
```
```
In drivers/usb/host/xhci-ring.c (ffffffff818fdea7)
Location: include/linux/usb.h:1761
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
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
In drivers/usb/core/hcd.c (ffffffff819435ca)
Location: include/linux/usb.h:1754
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
```
```
In drivers/usb/core/message.c (ffffffff81d15f30)
Location: include/linux/usb.h:1754
Inline: True
Inline callers:
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/core/devio.c (ffffffff81952125)
Location: include/linux/usb.h:1754
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8195eb4d)
Location: include/linux/usb.h:1754
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff8198c9cb)
Location: include/linux/usb.h:1754
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_unmap_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_unmap_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8199d23c)
Location: include/linux/usb.h:1754
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
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
In drivers/usb/core/hcd.c (ffffffff81a9ba2c)
Location: include/linux/usb.h:1745
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
```
```
In drivers/usb/core/message.c (ffffffff81ee0abd)
Location: include/linux/usb.h:1745
Inline: True
Inline callers:
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/core/devio.c (ffffffff81aa938a)
Location: include/linux/usb.h:1745
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81ab89e7)
Location: include/linux/usb.h:1745
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_free_dma_aligned_buffer
```
```
In drivers/usb/host/xhci.c (ffffffff81ae8c59)
Location: include/linux/usb.h:1745
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_unmap_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_unmap_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81afa884)
Location: include/linux/usb.h:1745
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
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
In drivers/usb/core/hcd.c (ffffffff81c2089c)
Location: include/linux/usb.h:1774
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
```
```
In drivers/usb/core/message.c (ffffffff81c234ff)
Location: include/linux/usb.h:1774
Inline: True
Inline callers:
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/core/devio.c (ffffffff81c3066a)
Location: include/linux/usb.h:1774
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81c41fc7)
Location: include/linux/usb.h:1774
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_free_dma_aligned_buffer
```
```
In drivers/usb/host/xhci.c (ffffffff81c74e59)
Location: include/linux/usb.h:1774
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_unmap_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_unmap_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81c88ca6)
Location: include/linux/usb.h:1774
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
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
In drivers/usb/core/hcd.c (ffffffff81c8781c)
Location: include/linux/usb.h:1813
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
```
```
In drivers/usb/core/message.c (ffffffff81c8a47f)
Location: include/linux/usb.h:1813
Inline: True
Inline callers:
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/core/devio.c (ffffffff81c9790a)
Location: include/linux/usb.h:1813
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81ca9577)
Location: include/linux/usb.h:1813
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_free_dma_aligned_buffer
```
```
In drivers/usb/host/xhci.c (ffffffff81cdbf79)
Location: include/linux/usb.h:1813
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_unmap_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_unmap_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81cefeb6)
Location: include/linux/usb.h:1813
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
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
In drivers/usb/core/hcd.c (ffffffff81d3c26c)
Location: include/linux/usb.h:1796
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
```
```
In drivers/usb/core/message.c (ffffffff81d3ee9f)
Location: include/linux/usb.h:1796
Inline: True
Inline callers:
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/core/devio.c (ffffffff81d4c3ea)
Location: include/linux/usb.h:1796
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81d5e227)
Location: include/linux/usb.h:1796
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_free_dma_aligned_buffer
```
```
In drivers/usb/host/xhci.c (ffffffff81d90f99)
Location: include/linux/usb.h:1796
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_unmap_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_unmap_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81da56d6)
Location: include/linux/usb.h:1796
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
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
In drivers/usb/core/hcd.c (ffff800010a1ea28)
Location: include/linux/usb.h:1739
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
```
```
In drivers/usb/core/message.c (ffff800010a22e58)
Location: include/linux/usb.h:1739
Inline: True
Inline callers:
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/core/devio.c (ffff800010a2d6bc)
Location: include/linux/usb.h:1739
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/usb/dwc2/hcd.c (ffff800010a401bc)
Location: include/linux/usb.h:1739
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (ffff800010a7d794)
Location: include/linux/usb.h:1739
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
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
In drivers/usb/core/hcd.c (c0af6170)
Location: include/linux/usb.h:1739
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
```
```
In drivers/usb/core/message.c (c0af876c)
Location: include/linux/usb.h:1739
Inline: True
Inline callers:
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/core/devio.c (c0b02704)
Location: include/linux/usb.h:1739
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/usb/dwc2/hcd.c (c0b12d84)
Location: include/linux/usb.h:1739
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (c0b50b04)
Location: include/linux/usb.h:1739
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
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
In drivers/usb/core/hcd.c (c000000000ad8af0)
Location: include/linux/usb.h:1739
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
```
```
In drivers/usb/core/message.c (c000000000adc258)
Location: include/linux/usb.h:1739
Inline: True
Inline callers:
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/core/devio.c (c000000000aead3c)
Location: include/linux/usb.h:1739
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/usb/dwc2/hcd.c (c000000000b00c1c)
Location: include/linux/usb.h:1739
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (c000000000b55d34)
Location: include/linux/usb.h:1739
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
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
In drivers/usb/core/hcd.c (ffffffe000642464)
Location: include/linux/usb.h:1739
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
```
```
In drivers/usb/core/message.c (ffffffe00064487c)
Location: include/linux/usb.h:1739
Inline: True
Inline callers:
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/core/devio.c (ffffffe00064f562)
Location: include/linux/usb.h:1739
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/usb/dwc2/hcd.c (ffffffe00065becc)
Location: include/linux/usb.h:1739
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_free_dma_aligned_buffer
```
```
In drivers/usb/host/xhci-ring.c (ffffffe000694572)
Location: include/linux/usb.h:1739
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
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
In drivers/usb/core/hcd.c (ffffffff817a708f)
Location: include/linux/usb.h:1739
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
```
```
In drivers/usb/core/message.c (ffffffff817ac16d)
Location: include/linux/usb.h:1739
Inline: True
Inline callers:
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/core/devio.c (ffffffff817b4078)
Location: include/linux/usb.h:1739
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/usb/dwc2/hcd.c (ffffffff817c1ced)
Location: include/linux/usb.h:1739
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817f7230)
Location: include/linux/usb.h:1739
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
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
In drivers/usb/core/hcd.c (ffffffff81798ae3)
Location: include/linux/usb.h:1739
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
```
```
In drivers/usb/core/message.c (ffffffff8179db6d)
Location: include/linux/usb.h:1739
Inline: True
Inline callers:
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/core/devio.c (ffffffff817a5aa8)
Location: include/linux/usb.h:1739
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817bc3d0)
Location: include/linux/usb.h:1739
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
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
In drivers/usb/core/hcd.c (ffffffff817e3b2f)
Location: include/linux/usb.h:1739
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
```
```
In drivers/usb/core/message.c (ffffffff817e8c0d)
Location: include/linux/usb.h:1739
Inline: True
Inline callers:
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/core/devio.c (ffffffff817f0b18)
Location: include/linux/usb.h:1739
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/usb/dwc2/hcd.c (ffffffff817fe78d)
Location: include/linux/usb.h:1739
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81833d00)
Location: include/linux/usb.h:1739
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
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
In drivers/usb/core/hcd.c (ffffffff817fde06)
Location: include/linux/usb.h:1739
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
```
```
In drivers/usb/core/message.c (ffffffff81802e5d)
Location: include/linux/usb.h:1739
Inline: True
Inline callers:
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/core/devio.c (ffffffff8180ad58)
Location: include/linux/usb.h:1739
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8181889d)
Location: include/linux/usb.h:1739
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8184dfca)
Location: include/linux/usb.h:1739
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
</details>
</li>
</ul>

## Differences
