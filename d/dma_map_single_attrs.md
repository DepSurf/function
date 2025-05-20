# Function: <code>dma_map_single_attrs</code>

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
In drivers/tty/serial/8250/8250_dma.c (ffffffff8150968e)
Location: include/asm-generic/dma-mapping-common.h:11
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/usb/core/hcd.c (ffffffff8160d440)
Location: include/asm-generic/dma-mapping-common.h:11
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff816282a2)
Location: include/asm-generic/dma-mapping-common.h:11
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
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
In drivers/virtio/virtio_ring.c (ffffffff8175922c)
Location: include/linux/dma-mapping.h:169
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8155b631)
Location: include/linux/dma-mapping.h:169
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/usb/core/hcd.c (ffffffff8166cfe6)
Location: include/linux/dma-mapping.h:169
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8168f2ca)
Location: include/linux/dma-mapping.h:169
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff816b95ed)
Location: include/linux/dma-mapping.h:169
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
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
In drivers/virtio/virtio_ring.c (ffffffff817857ac)
Location: include/linux/dma-mapping.h:180
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81587ddb)
Location: include/linux/dma-mapping.h:180
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/usb/core/hcd.c (ffffffff8169ace6)
Location: include/linux/dma-mapping.h:180
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff816bd38a)
Location: include/linux/dma-mapping.h:180
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff816e786d)
Location: include/linux/dma-mapping.h:180
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
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
In drivers/virtio/virtio_ring.c (ffffffff8154ee8f)
Location: include/linux/dma-mapping.h:223
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8159c269)
Location: include/linux/dma-mapping.h:223
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/usb/core/hcd.c (ffffffff816b0069)
Location: include/linux/dma-mapping.h:223
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff816d13d9)
Location: include/linux/dma-mapping.h:223
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff816fb477)
Location: include/linux/dma-mapping.h:223
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
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
In drivers/virtio/virtio_ring.c (ffffffff815b262f)
Location: include/linux/dma-mapping.h:226
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81601572)
Location: include/linux/dma-mapping.h:226
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/usb/core/hcd.c (ffffffff8171b5ae)
Location: include/linux/dma-mapping.h:226
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8173da49)
Location: include/linux/dma-mapping.h:226
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81767fe7)
Location: include/linux/dma-mapping.h:226
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81773cdf)
Location: include/linux/dma-mapping.h:226
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
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
In drivers/virtio/virtio_ring.c (ffffffff815eaabd)
Location: include/linux/dma-mapping.h:226
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8163a80d)
Location: include/linux/dma-mapping.h:226
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/usb/core/hcd.c (ffffffff8175a3d6)
Location: include/linux/dma-mapping.h:226
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81775826)
Location: include/linux/dma-mapping.h:226
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8177e3c5)
Location: include/linux/dma-mapping.h:226
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817a95f2)
Location: include/linux/dma-mapping.h:226
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817b4333)
Location: include/linux/dma-mapping.h:226
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
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
In drivers/virtio/virtio_ring.c (ffffffff81604d23)
Location: include/linux/dma-mapping.h:574
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81658ad3)
Location: include/linux/dma-mapping.h:574
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/usb/core/hcd.c (ffffffff8177e93c)
Location: include/linux/dma-mapping.h:574
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8179ae69)
Location: include/linux/dma-mapping.h:574
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817a4a62)
Location: include/linux/dma-mapping.h:574
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817cf57a)
Location: include/linux/dma-mapping.h:574
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817da8af)
Location: include/linux/dma-mapping.h:574
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
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
In drivers/virtio/virtio_ring.c (ffffffff81637634)
Location: include/linux/dma-mapping.h:577
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8168dfb3)
Location: include/linux/dma-mapping.h:577
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/usb/core/hcd.c (ffffffff817bceb9)
Location: include/linux/dma-mapping.h:577
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff817d9fea)
Location: include/linux/dma-mapping.h:577
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817e3ca2)
Location: include/linux/dma-mapping.h:577
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8180f9e7)
Location: include/linux/dma-mapping.h:577
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8181afd1)
Location: include/linux/dma-mapping.h:577
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
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
In drivers/virtio/virtio_ring.c (ffffffff81659389)
Location: include/linux/dma-mapping.h:580
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816b0505)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/usb/core/hcd.c (ffffffff817ed946)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8180ae81)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81814a83)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81840e1a)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8184bc7e)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
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
In drivers/virtio/virtio_ring.c (ffffffff81709c0b)
Location: include/linux/dma-mapping.h:585
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff817639f1)
Location: include/linux/dma-mapping.h:585
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/usb/core/hcd.c (ffffffff818bcdca)
Location: include/linux/dma-mapping.h:585
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818da741)
Location: include/linux/dma-mapping.h:585
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_alloc_split_dma_aligned_buf
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818e6904)
Location: include/linux/dma-mapping.h:585
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81911b1e)
Location: include/linux/dma-mapping.h:585
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-ring.c:xhci_align_td
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8191eabf)
Location: include/linux/dma-mapping.h:585
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
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
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8167c29a)
Location: include/linux/dma-mapping.h:271
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
```
In drivers/virtio/virtio_ring.c (ffffffff81726b7b)
Location: include/linux/dma-mapping.h:271
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8177e9f7)
Location: include/linux/dma-mapping.h:271
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/usb/core/hcd.c (ffffffff818c9abc)
Location: include/linux/dma-mapping.h:271
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818e4d94)
Location: include/linux/dma-mapping.h:271
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818efa40)
Location: include/linux/dma-mapping.h:271
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
```
```
In drivers/usb/host/xhci.c (ffffffff8190cb14)
Location: include/linux/dma-mapping.h:271
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81918ce0)
Location: include/linux/dma-mapping.h:271
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-ring.c:xhci_align_td
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8192614e)
Location: include/linux/dma-mapping.h:271
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
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
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8165f14a)
Location: include/linux/dma-mapping.h:314
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
```
In drivers/virtio/virtio_ring.c (ffffffff8170a82b)
Location: include/linux/dma-mapping.h:314
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81762347)
Location: include/linux/dma-mapping.h:314
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/usb/core/hcd.c (ffffffff818acb3d)
Location: include/linux/dma-mapping.h:314
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818c7c63)
Location: include/linux/dma-mapping.h:314
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818d3164)
Location: include/linux/dma-mapping.h:314
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
```
```
In drivers/usb/host/xhci.c (ffffffff818f0074)
Location: include/linux/dma-mapping.h:314
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
```
```
In drivers/usb/host/xhci-ring.c (ffffffff818fc260)
Location: include/linux/dma-mapping.h:314
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-ring.c:xhci_align_td
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8190981e)
Location: include/linux/dma-mapping.h:314
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
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
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff816d1cfa)
Location: include/linux/dma-mapping.h:322
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
```
In drivers/virtio/virtio_ring.c (ffffffff81786532)
Location: include/linux/dma-mapping.h:322
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff817e6400)
Location: include/linux/dma-mapping.h:322
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/usb/core/hcd.c (ffffffff81941b8e)
Location: include/linux/dma-mapping.h:322
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8195fb20)
Location: include/linux/dma-mapping.h:322
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8196dc04)
Location: include/linux/dma-mapping.h:322
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
```
```
In drivers/usb/host/xhci.c (ffffffff8198cd04)
Location: include/linux/dma-mapping.h:322
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8199b150)
Location: include/linux/dma-mapping.h:322
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-ring.c:xhci_align_td
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff819aa08f)
Location: include/linux/dma-mapping.h:322
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
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
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff817fae3e)
Location: include/linux/dma-mapping.h:322
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
```
In drivers/virtio/virtio_ring.c (ffffffff818bd284)
Location: include/linux/dma-mapping.h:322
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81925999)
Location: include/linux/dma-mapping.h:322
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/usb/core/hcd.c (ffffffff81a9b1be)
Location: include/linux/dma-mapping.h:322
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81ab9fb0)
Location: include/linux/dma-mapping.h:322
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81ac8203)
Location: include/linux/dma-mapping.h:322
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
```
```
In drivers/usb/host/xhci.c (ffffffff81ae8f05)
Location: include/linux/dma-mapping.h:322
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81af892d)
Location: include/linux/dma-mapping.h:322
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-ring.c:xhci_align_td
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81b085e9)
Location: include/linux/dma-mapping.h:322
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
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
In drivers/virtio/virtio_ring.c (ffffffff81a0c0d4)
Location: include/linux/dma-mapping.h:327
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81a823c9)
Location: include/linux/dma-mapping.h:327
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/usb/core/hcd.c (ffffffff81c2000e)
Location: include/linux/dma-mapping.h:327
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81c433a0)
Location: include/linux/dma-mapping.h:327
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81c52563)
Location: include/linux/dma-mapping.h:327
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
```
```
In drivers/usb/host/xhci.c (ffffffff81c751b5)
Location: include/linux/dma-mapping.h:327
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81c868ef)
Location: include/linux/dma-mapping.h:327
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-ring.c:xhci_align_td
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81c97b4b)
Location: include/linux/dma-mapping.h:327
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
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
In drivers/virtio/virtio_ring.c (ffffffff81a54ff3)
Location: include/linux/dma-mapping.h:328
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81acd9c9)
Location: include/linux/dma-mapping.h:328
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/usb/core/hcd.c (ffffffff81c86f8e)
Location: include/linux/dma-mapping.h:328
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81caab00)
Location: include/linux/dma-mapping.h:328
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81cb9b23)
Location: include/linux/dma-mapping.h:328
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
```
```
In drivers/usb/host/xhci.c (ffffffff81cdc2d5)
Location: include/linux/dma-mapping.h:328
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81ced71f)
Location: include/linux/dma-mapping.h:328
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-ring.c:xhci_align_td
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81cfee81)
Location: include/linux/dma-mapping.h:328
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
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
In drivers/virtio/virtio_ring.c (ffffffff81aa60c0)
Location: include/linux/dma-mapping.h:333
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81b20a99)
Location: include/linux/dma-mapping.h:333
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/usb/core/hcd.c (ffffffff81d3b9ee)
Location: include/linux/dma-mapping.h:333
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81d5f7b0)
Location: include/linux/dma-mapping.h:333
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81d6e893)
Location: include/linux/dma-mapping.h:333
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
```
```
In drivers/usb/host/xhci.c (ffffffff81d912f5)
Location: include/linux/dma-mapping.h:333
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81da34e2)
Location: include/linux/dma-mapping.h:333
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-ring.c:xhci_align_td
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81db3f81)
Location: include/linux/dma-mapping.h:333
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dma/mv_xor.c (ffff8000108074b0)
Location: include/linux/dma-mapping.h:580
Inline: True
Direct callers:
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mv_xor.c:mv_xor_channel_add
```
```
In drivers/soc/fsl/qbman/qman.c (ffff800010816414)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/qman.c:qman_init_fq
```
```
In drivers/virtio/virtio_ring.c (ffff80001082262c)
Location: include/linux/dma-mapping.h:580
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffff80001088bac8)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/tty/serial/msm_serial.c (ffff8000108a39b4)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:msm_handle_tx
```
```
In drivers/iommu/io-pgtable-arm.c (ffff8000108cb434)
Location: include/linux/dma-mapping.h:580
Inline: True
```
```
In drivers/iommu/rockchip-iommu.c (ffff8000108d9358)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_map
```
```
In drivers/net/ethernet/broadcom/bgmac.c (ffff8000109e3644)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_start_xmit
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109eb768)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
```
```
In drivers/usb/core/hcd.c (ffff800010a1c870)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffff800010a417e0)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffff800010a4dc48)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/xhci-ring.c (ffff800010a7f86c)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffff800010a8b994)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
```
In drivers/firmware/qcom_scm-64.c (ffff800010b4f9c8)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/firmware/qcom_scm-64.c:qcom_scm_call
```
**Symbols:**

```
ffff8000108074b0-ffff800010807558: dma_map_single_attrs.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dma/mv_xor.c (c092523c)
Location: include/linux/dma-mapping.h:580
Inline: True
Direct callers:
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mv_xor.c:mv_xor_channel_add
```
```
In drivers/virtio/virtio_ring.c (c093f6c8)
Location: include/linux/dma-mapping.h:580
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (c0989400)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/tty/serial/msm_serial.c (c099cc38)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:msm_handle_tx
```
```
In drivers/iommu/io-pgtable-arm.c (c09bff54)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/iommu/io-pgtable-arm.c:__arm_lpae_alloc_pages
```
```
In drivers/iommu/omap-iommu.c (c09c47b8)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/iommu/omap-iommu.c:omap_iommu_attach_dev
  - drivers/iommu/omap-iommu.c:iopte_alloc
```
```
In drivers/iommu/rockchip-iommu.c (c09c6d30)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_map
```
```
In drivers/iommu/exynos-iommu.c (c09ca6f8)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/iommu/exynos-iommu.c:exynos_iommu_map
  - drivers/iommu/exynos-iommu.c:exynos_iommu_domain_alloc
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0acdb2c)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
```
```
In drivers/net/ethernet/ti/davinci_cpdma.c (c0ad7138)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_chan_submit_si
```
```
In drivers/usb/core/hcd.c (c0af5820)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (c0b13f6c)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/dwc2/hcd_ddma.c (c0b1fd30)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/xhci-ring.c (c0b52c28)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (c0b5dd9c)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
```
In drivers/usb/gadget/udc/core.c (c0b73e00)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/usb/gadget/udc/core.c:usb_gadget_map_request_by_dev
```
```
In drivers/i2c/busses/i2c-imx.c (c0b9a948)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_dma_xfer
```
```
In drivers/mmc/host/sdhci.c (c0c24c18)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci.c:sdhci_setup_host
```
```
In drivers/firmware/qcom_scm-32.c (c0c36218)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/firmware/qcom_scm-32.c:qcom_scm_call
```
```
In drivers/firmware/tegra/ivc.c (c0c43910)
Location: include/linux/dma-mapping.h:580
Inline: True
```
```
In drivers/staging/emxx_udc/emxx_udc.c (c0c5c1ec)
Location: include/linux/dma-mapping.h:580
Inline: True
```
**Symbols:**

```
c092523c-c0925318: dma_map_single_attrs.constprop.0 (STB_LOCAL)
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
In drivers/virtio/virtio_ring.c (c0000000008ccb2c)
Location: include/linux/dma-mapping.h:580
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (c0000000009343dc)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/tpm/tpm_ibmvtpm.c (c000000000969100)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_probe
  - drivers/char/tpm/tpm_ibmvtpm.c:ibmvtpm_interrupt
```
```
In drivers/usb/core/hcd.c (c000000000ad7ea0)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (c000000000b0250c)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/dwc2/hcd_ddma.c (c000000000b15460)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/xhci-ring.c (c000000000b583ac)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (c000000000b67904)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
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
In drivers/virtio/virtio_ring.c (ffffffe000518f16)
Location: include/linux/dma-mapping.h:580
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffe000555442)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/usb/core/hcd.c (ffffffe0006415b6)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffe00065d80e)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffe00066a690)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/xhci-ring.c (ffffffe000696000)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffe0006a06fe)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
```
In drivers/mmc/host/mmc_spi.c (ffffffe00071baba)
Location: include/linux/dma-mapping.h:580
Inline: True
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
In drivers/virtio/virtio_ring.c (ffffffff8161f229)
Location: include/linux/dma-mapping.h:580
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81675f75)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/usb/core/hcd.c (ffffffff817a5d26)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff817c3261)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817cce63)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817f91ca)
Location: include/linux/dma-mapping.h:580
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
In drivers/virtio/virtio_ring.c (ffffffff81613849)
Location: include/linux/dma-mapping.h:580
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81655055)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/usb/core/hcd.c (ffffffff81798256)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817be36a)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817c91ce)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
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
In drivers/virtio/virtio_ring.c (ffffffff8164d1c9)
Location: include/linux/dma-mapping.h:580
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816a4345)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/usb/core/hcd.c (ffffffff817e27c6)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff817ffd01)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81809903)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81835c9a)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81840afe)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
```
In drivers/i2c/busses/i2c-amd-mp2-plat.c (ffffffff81868f68)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_xfer
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
In drivers/virtio/virtio_ring.c (ffffffff81667859)
Location: include/linux/dma-mapping.h:580
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816be7d5)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/usb/core/hcd.c (ffffffff817fd516)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81819e11)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81823a13)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8184ffd0)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8185afce)
Location: include/linux/dma-mapping.h:580
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
</details>
</li>
</ul>

## Differences
