# Function: <code>dma_mapping_error</code>

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
In drivers/tty/serial/8250/8250_dma.c (ffffffff81509709)
Location: include/asm-generic/dma-mapping-common.h:316
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/agp/intel-gtt.c (ffffffff815226c6)
Location: include/asm-generic/dma-mapping-common.h:316
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/usb/core/hcd.c (ffffffff8160d4b0)
Location: include/asm-generic/dma-mapping-common.h:316
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81628305)
Location: include/asm-generic/dma-mapping-common.h:316
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
In drivers/virtio/virtio_ring.c (ffffffff8150f1ec)
Location: include/linux/dma-mapping.h:471
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8155b6b1)
Location: include/linux/dma-mapping.h:471
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81575570)
Location: include/linux/dma-mapping.h:471
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/usb/core/hcd.c (ffffffff8166d0e3)
Location: include/linux/dma-mapping.h:471
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff816b968d)
Location: include/linux/dma-mapping.h:471
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
In drivers/virtio/virtio_ring.c (ffffffff8153b33c)
Location: include/linux/dma-mapping.h:523
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81587e58)
Location: include/linux/dma-mapping.h:523
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/agp/intel-gtt.c (ffffffff815a1c00)
Location: include/linux/dma-mapping.h:523
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/usb/core/hcd.c (ffffffff8169ade0)
Location: include/linux/dma-mapping.h:523
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff816e7907)
Location: include/linux/dma-mapping.h:523
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
In drivers/virtio/virtio_ring.c (ffffffff8154ebcc)
Location: include/linux/dma-mapping.h:566
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8159c2e3)
Location: include/linux/dma-mapping.h:566
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/agp/intel-gtt.c (ffffffff815b57e7)
Location: include/linux/dma-mapping.h:566
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
```
```
In drivers/usb/core/hcd.c (ffffffff816b01a2)
Location: include/linux/dma-mapping.h:566
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff816fba6b)
Location: include/linux/dma-mapping.h:566
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
In drivers/virtio/virtio_ring.c (ffffffff815b2385)
Location: include/linux/dma-mapping.h:561
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816015ee)
Location: include/linux/dma-mapping.h:561
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8161c83a)
Location: include/linux/dma-mapping.h:561
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
```
```
In drivers/usb/core/hcd.c (ffffffff8171b70b)
Location: include/linux/dma-mapping.h:561
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817685ea)
Location: include/linux/dma-mapping.h:561
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81773d41)
Location: include/linux/dma-mapping.h:561
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
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff81549564)
Location: include/linux/dma-mapping.h:565
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/virtio/virtio_ring.c (ffffffff815ea7e5)
Location: include/linux/dma-mapping.h:565
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8163a88c)
Location: include/linux/dma-mapping.h:565
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816565f1)
Location: include/linux/dma-mapping.h:565
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
```
```
In drivers/usb/core/hcd.c (ffffffff8175a52c)
Location: include/linux/dma-mapping.h:565
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81775898)
Location: include/linux/dma-mapping.h:565
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817a9672)
Location: include/linux/dma-mapping.h:565
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817b4396)
Location: include/linux/dma-mapping.h:565
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
```
In net/core/page_pool.c (ffffffff818bd76b)
Location: include/linux/dma-mapping.h:565
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
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
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8155fc61)
Location: include/linux/dma-mapping.h:437
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/virtio/virtio_ring.c (ffffffff8160648b)
Location: include/linux/dma-mapping.h:437
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add
  - drivers/virtio/virtio_ring.c:virtqueue_add
  - drivers/virtio/virtio_ring.c:virtqueue_add
  - drivers/virtio/virtio_ring.c:virtqueue_add
  - drivers/virtio/virtio_ring.c:virtqueue_add
  - drivers/virtio/virtio_ring.c:virtqueue_add
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81658b4b)
Location: include/linux/dma-mapping.h:437
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81674451)
Location: include/linux/dma-mapping.h:437
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
```
```
In drivers/usb/core/hcd.c (ffffffff8177ea78)
Location: include/linux/dma-mapping.h:437
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8179aecc)
Location: include/linux/dma-mapping.h:437
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817cf605)
Location: include/linux/dma-mapping.h:437
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817da904)
Location: include/linux/dma-mapping.h:437
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
```
In net/core/page_pool.c (ffffffff818e4b3c)
Location: include/linux/dma-mapping.h:437
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
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
In mm/hmm.c (ffffffff812c36a2)
Location: include/linux/dma-mapping.h:440
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_dma_map
  - mm/hmm.c:hmm_range_dma_map
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8158ff1f)
Location: include/linux/dma-mapping.h:440
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/virtio/virtio_ring.c (ffffffff8163a2cd)
Location: include/linux/dma-mapping.h:440
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8168e022)
Location: include/linux/dma-mapping.h:440
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816aa410)
Location: include/linux/dma-mapping.h:440
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/usb/core/hcd.c (ffffffff817bcff4)
Location: include/linux/dma-mapping.h:440
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff817da044)
Location: include/linux/dma-mapping.h:440
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8180fa7b)
Location: include/linux/dma-mapping.h:440
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8181b038)
Location: include/linux/dma-mapping.h:440
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
```
In net/core/page_pool.c (ffffffff819343a5)
Location: include/linux/dma-mapping.h:440
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
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
In mm/hmm.c (ffffffff812d56d1)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_dma_map
  - mm/hmm.c:hmm_range_dma_map
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815b1f3f)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/virtio/virtio_ring.c (ffffffff8165c528)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816b054b)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816cd150)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/usb/core/hcd.c (ffffffff817eda31)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8180aeb9)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81840bae)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8184bcaa)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
```
In net/core/page_pool.c (ffffffff81966fdb)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
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
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8165b523)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/virtio/virtio_ring.c (ffffffff8170b985)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81763a62)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81781fde)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_setup_scratch_page
```
```
In drivers/usb/core/hcd.c (ffffffff818bcfa5)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818da7d4)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_alloc_split_dma_aligned_buf
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81911c2f)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_align_td
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8191eb58)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
```
In net/core/page_pool.c (ffffffff81a3a6fc)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ba9931)
Location: include/linux/dma-mapping.h:433
Inline: True
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
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8167c2fe)
Location: include/linux/dma-mapping.h:94
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
```
In drivers/virtio/virtio_ring.c (ffffffff817287f5)
Location: include/linux/dma-mapping.h:94
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8177ea58)
Location: include/linux/dma-mapping.h:94
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81c09f37)
Location: include/linux/dma-mapping.h:94
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_setup_scratch_page
```
```
In drivers/usb/core/hcd.c (ffffffff818c9c37)
Location: include/linux/dma-mapping.h:94
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818e4dff)
Location: include/linux/dma-mapping.h:94
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/host/xhci.c (ffffffff8190cb6d)
Location: include/linux/dma-mapping.h:94
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81918d4d)
Location: include/linux/dma-mapping.h:94
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_align_td
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff819261b6)
Location: include/linux/dma-mapping.h:94
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
```
In net/core/page_pool.c (ffffffff81a3cbe0)
Location: include/linux/dma-mapping.h:94
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81bb94fd)
Location: include/linux/dma-mapping.h:94
Inline: True
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
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8165f1b3)
Location: include/linux/dma-mapping.h:94
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
```
In drivers/virtio/virtio_ring.c (ffffffff8170bfcf)
Location: include/linux/dma-mapping.h:94
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff817623a9)
Location: include/linux/dma-mapping.h:94
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81bfbb15)
Location: include/linux/dma-mapping.h:94
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/usb/core/hcd.c (ffffffff818acca3)
Location: include/linux/dma-mapping.h:94
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818c7cd3)
Location: include/linux/dma-mapping.h:94
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/host/xhci.c (ffffffff818f00ce)
Location: include/linux/dma-mapping.h:94
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
```
```
In drivers/usb/host/xhci-ring.c (ffffffff818fc2ce)
Location: include/linux/dma-mapping.h:94
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_align_td
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81909887)
Location: include/linux/dma-mapping.h:94
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
```
In net/core/page_pool.c (ffffffff81a23b05)
Location: include/linux/dma-mapping.h:94
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_dma_map
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ba852f)
Location: include/linux/dma-mapping.h:94
Inline: True
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
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff816d1d63)
Location: include/linux/dma-mapping.h:94
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
```
In drivers/virtio/virtio_ring.c (ffffffff81788311)
Location: include/linux/dma-mapping.h:94
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff817e6462)
Location: include/linux/dma-mapping.h:94
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81cfc710)
Location: include/linux/dma-mapping.h:94
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/usb/core/hcd.c (ffffffff81941cff)
Location: include/linux/dma-mapping.h:94
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8195fb9f)
Location: include/linux/dma-mapping.h:94
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/host/xhci.c (ffffffff8198cd5e)
Location: include/linux/dma-mapping.h:94
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8199b1be)
Location: include/linux/dma-mapping.h:94
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_align_td
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff819aa0f8)
Location: include/linux/dma-mapping.h:94
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
```
In net/core/page_pool.c (ffffffff81ad8175)
Location: include/linux/dma-mapping.h:94
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_dma_map
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81c76288)
Location: include/linux/dma-mapping.h:94
Inline: True
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
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff817faea3)
Location: include/linux/dma-mapping.h:94
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
```
In drivers/virtio/virtio_ring.c (ffffffff818bf90d)
Location: include/linux/dma-mapping.h:94
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff819259f7)
Location: include/linux/dma-mapping.h:94
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81ec4f23)
Location: include/linux/dma-mapping.h:94
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/usb/core/hcd.c (ffffffff81a9b313)
Location: include/linux/dma-mapping.h:94
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81aba02f)
Location: include/linux/dma-mapping.h:94
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/host/xhci.c (ffffffff81ae8f5f)
Location: include/linux/dma-mapping.h:94
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81af8999)
Location: include/linux/dma-mapping.h:94
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_align_td
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81b08659)
Location: include/linux/dma-mapping.h:94
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
```
In net/core/page_pool.c (ffffffff81c58f45)
Location: include/linux/dma-mapping.h:94
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_dma_map
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81e1a690)
Location: include/linux/dma-mapping.h:94
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_dma_map
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
In drivers/virtio/virtio_ring.c (ffffffff81a0f769)
Location: include/linux/dma-mapping.h:94
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81a8242b)
Location: include/linux/dma-mapping.h:94
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81aa3dec)
Location: include/linux/dma-mapping.h:94
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/usb/core/hcd.c (ffffffff81c20162)
Location: include/linux/dma-mapping.h:94
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81c4341f)
Location: include/linux/dma-mapping.h:94
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/host/xhci.c (ffffffff81c7520f)
Location: include/linux/dma-mapping.h:94
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81c8695c)
Location: include/linux/dma-mapping.h:94
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_align_td
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81c97bbb)
Location: include/linux/dma-mapping.h:94
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
```
In net/core/page_pool.c (ffffffff81e0ee95)
Location: include/linux/dma-mapping.h:94
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_dma_map
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ff1bab)
Location: include/linux/dma-mapping.h:94
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_dma_map
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
In drivers/virtio/virtio_ring.c (ffffffff81a58818)
Location: include/linux/dma-mapping.h:95
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81acda2b)
Location: include/linux/dma-mapping.h:95
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81aef6ec)
Location: include/linux/dma-mapping.h:95
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/usb/core/hcd.c (ffffffff81c870e2)
Location: include/linux/dma-mapping.h:95
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81caab7b)
Location: include/linux/dma-mapping.h:95
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/host/xhci.c (ffffffff81cdc32f)
Location: include/linux/dma-mapping.h:95
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81ced78c)
Location: include/linux/dma-mapping.h:95
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_align_td
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81cfeeed)
Location: include/linux/dma-mapping.h:95
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
```
In net/core/page_pool.c (ffffffff81e82655)
Location: include/linux/dma-mapping.h:95
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_dma_map
```
```
In net/xdp/xsk_buff_pool.c (ffffffff8206ddb7)
Location: include/linux/dma-mapping.h:95
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_dma_map
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
In drivers/virtio/virtio_ring.c (ffffffff81aa5b2e)
Location: include/linux/dma-mapping.h:95
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_dma_mapping_error
  - drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:vring_map_one_sg
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81b20afb)
Location: include/linux/dma-mapping.h:95
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81b42c31)
Location: include/linux/dma-mapping.h:95
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/usb/core/hcd.c (ffffffff81d3bb42)
Location: include/linux/dma-mapping.h:95
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81d5f82b)
Location: include/linux/dma-mapping.h:95
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/host/xhci.c (ffffffff81d9134f)
Location: include/linux/dma-mapping.h:95
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81da354e)
Location: include/linux/dma-mapping.h:95
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_align_td
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81db3fed)
Location: include/linux/dma-mapping.h:95
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
```
In net/core/page_pool.c (ffffffff81f435b5)
Location: include/linux/dma-mapping.h:95
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_dma_map
```
```
In net/xdp/xsk_buff_pool.c (ffffffff82141e36)
Location: include/linux/dma-mapping.h:95
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_dma_map
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
In mm/hmm.c (ffff80001037aa08)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_dma_map
  - mm/hmm.c:hmm_range_dma_map
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffff80001072e450)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/dma/bcm2835-dma.c (ffff800010804834)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_probe
```
```
In drivers/dma/mv_xor.c (ffff800010807c74)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mv_xor.c:mv_xor_channel_add
```
```
In drivers/soc/fsl/qbman/qman.c (ffff800010816454)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/qman.c:qman_init_fq
```
```
In drivers/virtio/virtio_ring.c (ffff80001082548c)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed
```
```
In drivers/tty/serial/8250/8250_dma.c (ffff80001088bb14)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/tty/serial/msm_serial.c (ffff8000108a3a14)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:msm_handle_tx
```
```
In drivers/iommu/io-pgtable-arm.c (ffff8000108cb484)
Location: include/linux/dma-mapping.h:433
Inline: True
```
```
In drivers/iommu/rockchip-iommu.c (ffff8000108d93b0)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_map
```
```
In drivers/net/ethernet/broadcom/bgmac.c (ffff8000109e3690)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_start_xmit
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_start_xmit
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109eb7a8)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
```
```
In drivers/usb/core/hcd.c (ffff800010a1c9cc)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffff800010a41824)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/host/xhci-ring.c (ffff800010a7f8dc)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffff800010a8b9d4)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
```
In drivers/firmware/qcom_scm-64.c (ffff800010b4fa20)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/firmware/qcom_scm-64.c:qcom_scm_call
```
```
In net/core/page_pool.c (ffff800010c0cf90)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
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
In arch/arm/mm/dma-mapping.c (c031b468)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - arch/arm/mm/dma-mapping.c:arm_dma_map_sg
```
```
In mm/hmm.c (c0565fdc)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_dma_map
  - mm/hmm.c:hmm_range_dma_map
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (c08b7ce0)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/dma/mv_xor.c (c0925a34)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mv_xor.c:mv_chan_xor_self_test
  - drivers/dma/mv_xor.c:mv_chan_xor_self_test
```
```
In drivers/virtio/virtio_ring.c (c0941f7c)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
```
```
In drivers/tty/serial/8250/8250_dma.c (c0989468)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/tty/serial/msm_serial.c (c099ccc8)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:msm_handle_tx
```
```
In drivers/iommu/io-pgtable-arm.c (c09c0008)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/iommu/io-pgtable-arm.c:__arm_lpae_alloc_pages
```
```
In drivers/iommu/omap-iommu.c (c09c4730)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/iommu/omap-iommu.c:omap_iommu_attach_dev
  - drivers/iommu/omap-iommu.c:iopte_alloc
```
```
In drivers/iommu/rockchip-iommu.c (c09c6db4)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_map
```
```
In drivers/iommu/tegra-smmu.c (c09c88fc)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/iommu/tegra-smmu.c:tegra_smmu_map
  - drivers/iommu/tegra-smmu.c:tegra_smmu_attach_dev
```
```
In drivers/iommu/exynos-iommu.c (c09ca7a4)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/iommu/exynos-iommu.c:exynos_iommu_map
  - drivers/iommu/exynos-iommu.c:exynos_iommu_domain_alloc
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0acdb7c)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
```
```
In drivers/net/ethernet/ti/davinci_cpdma.c (c0ad736c)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_chan_submit_si
```
```
In drivers/usb/core/hcd.c (c0af5994)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (c0b13fe8)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/host/xhci-ring.c (c0b52cc4)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (c0b5de28)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
```
In drivers/usb/musb/musb_gadget.c (0)
Location: include/linux/dma-mapping.h:433
Inline: True
```
```
In drivers/usb/gadget/udc/core.c (c0b73eac)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/usb/gadget/udc/core.c:usb_gadget_map_request_by_dev
```
```
In drivers/i2c/busses/i2c-imx.c (c0b9a9c0)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_dma_xfer
```
```
In drivers/mmc/host/sdhci.c (c0c24c94)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci.c:sdhci_setup_host
```
```
In drivers/firmware/qcom_scm-32.c (c0c362cc)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/firmware/qcom_scm-32.c:qcom_scm_call
```
```
In drivers/firmware/tegra/ivc.c (c0c439ec)
Location: include/linux/dma-mapping.h:433
Inline: True
```
```
In net/core/page_pool.c (c0d24cb0)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
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
In mm/hmm.c (c00000000046f5c0)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_dma_map
  - mm/hmm.c:hmm_range_dma_map
```
```
In drivers/virtio/virtio_ring.c (c0000000008cfb34)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
```
```
In drivers/tty/serial/8250/8250_dma.c (c000000000934410)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/tpm/tpm_ibmvtpm.c (c000000000969160)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_probe
  - drivers/char/tpm/tpm_ibmvtpm.c:ibmvtpm_interrupt
```
```
In drivers/usb/core/hcd.c (c000000000ad7f60)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (c000000000b02544)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/host/xhci-ring.c (c000000000b586f8)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (c000000000b67960)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
```
In net/core/page_pool.c (c000000000cf7c70)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
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
In mm/hmm.c (ffffffe000251c06)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_dma_map
  - mm/hmm.c:hmm_range_dma_map
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffe0004e8bb4)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/virtio/virtio_ring.c (ffffffe00051a4ae)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffe000555490)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/usb/core/hcd.c (ffffffe0006416b8)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffe00065d85c)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/host/xhci-ring.c (ffffffe00069630e)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffe0006a0746)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
```
In drivers/mmc/host/mmc_spi.c (ffffffe00071a870)
Location: include/linux/dma-mapping.h:433
Inline: True
```
```
In net/core/page_pool.c (ffffffe000789a10)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
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
In mm/hmm.c (ffffffff812cdcb1)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_dma_map
  - mm/hmm.c:hmm_range_dma_map
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815a56ff)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/virtio/virtio_ring.c (ffffffff816223c8)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81675fbb)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81692ba0)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/nvme/host/pci.c (ffffffff8174f637)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_queue_rq
  - drivers/nvme/host/pci.c:nvme_map_data
  - drivers/nvme/host/pci.c:nvme_map_data
```
```
In drivers/usb/core/hcd.c (ffffffff817a5e11)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff817c3299)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817f8f5e)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In net/core/page_pool.c (ffffffff81906fab)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
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
In mm/hmm.c (ffffffff812beb21)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_dma_map
  - mm/hmm.c:hmm_range_dma_map
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8159489f)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/virtio/virtio_ring.c (ffffffff81616a18)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8165509b)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81670590)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/nvme/host/pci.c (ffffffff8172f4d7)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_queue_rq
  - drivers/nvme/host/pci.c:nvme_map_data
  - drivers/nvme/host/pci.c:nvme_map_data
```
```
In drivers/usb/core/hcd.c (ffffffff81798341)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817be0fe)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817c91fa)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
```
In net/core/page_pool.c (ffffffff818c0dbb)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
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
In mm/hmm.c (ffffffff812cbac1)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_dma_map
  - mm/hmm.c:hmm_range_dma_map
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815a5c8f)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/virtio/virtio_ring.c (ffffffff81650368)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816a438b)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816c0e10)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/usb/core/hcd.c (ffffffff817e28b1)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff817ffd39)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81835a2e)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81840b2a)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
```
In drivers/i2c/busses/i2c-amd-mp2-plat.c (ffffffff81868f9c)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_xfer
```
```
In net/core/page_pool.c (ffffffff81957fdb)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
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
In mm/hmm.c (ffffffff812dc821)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_dma_map
  - mm/hmm.c:hmm_range_dma_map
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815c008f)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/virtio/virtio_ring.c (ffffffff8166a9f8)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816be81b)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816db3e0)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/usb/core/hcd.c (ffffffff817fd601)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81819e49)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8184fd64)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8185affa)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
```
In net/core/page_pool.c (ffffffff8197a0dd)
Location: include/linux/dma-mapping.h:433
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
</details>
</li>
</ul>

## Differences
