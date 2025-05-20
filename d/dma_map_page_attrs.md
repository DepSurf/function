# Function: <code>dma_map_page_attrs</code>

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
In drivers/virtio/virtio_ring.c (ffffffff8153b2d9)
Location: include/linux/dma-mapping.h:246
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff815a1bd3)
Location: include/linux/dma-mapping.h:246
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/usb/core/hcd.c (ffffffff8169adb7)
Location: include/linux/dma-mapping.h:246
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
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
In drivers/virtio/virtio_ring.c (ffffffff8154eb62)
Location: include/linux/dma-mapping.h:289
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff815b57ba)
Location: include/linux/dma-mapping.h:289
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
```
```
In drivers/usb/core/hcd.c (ffffffff816b0178)
Location: include/linux/dma-mapping.h:289
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
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
In drivers/virtio/virtio_ring.c (ffffffff815b2312)
Location: include/linux/dma-mapping.h:288
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8161c807)
Location: include/linux/dma-mapping.h:288
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
```
```
In drivers/usb/core/hcd.c (ffffffff8171b6da)
Location: include/linux/dma-mapping.h:288
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
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
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff81549524)
Location: include/linux/dma-mapping.h:288
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/virtio/virtio_ring.c (ffffffff815ea772)
Location: include/linux/dma-mapping.h:288
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816565ae)
Location: include/linux/dma-mapping.h:288
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
```
```
In drivers/usb/core/hcd.c (ffffffff8175a4f1)
Location: include/linux/dma-mapping.h:288
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In net/core/page_pool.c (ffffffff818bd72e)
Location: include/linux/dma-mapping.h:288
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
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8155fc26)
Location: include/linux/dma-mapping.h:279
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/virtio/virtio_ring.c (ffffffff81604d51)
Location: include/linux/dma-mapping.h:279
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81658b14)
Location: include/linux/dma-mapping.h:279
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81674418)
Location: include/linux/dma-mapping.h:279
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
```
```
In drivers/usb/core/hcd.c (ffffffff8177ea42)
Location: include/linux/dma-mapping.h:279
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8179ae98)
Location: include/linux/dma-mapping.h:279
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817a4a94)
Location: include/linux/dma-mapping.h:279
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817cf5b5)
Location: include/linux/dma-mapping.h:279
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817da8d8)
Location: include/linux/dma-mapping.h:279
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
```
In net/core/page_pool.c (ffffffff818e4b0a)
Location: include/linux/dma-mapping.h:279
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
In mm/hmm.c (ffffffff812c367a)
Location: include/linux/dma-mapping.h:281
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_dma_map
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8158fee9)
Location: include/linux/dma-mapping.h:281
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/virtio/virtio_ring.c (ffffffff81637673)
Location: include/linux/dma-mapping.h:281
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8168dffb)
Location: include/linux/dma-mapping.h:281
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816aa3e7)
Location: include/linux/dma-mapping.h:281
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/usb/core/hcd.c (ffffffff817bcfc9)
Location: include/linux/dma-mapping.h:281
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff817da020)
Location: include/linux/dma-mapping.h:281
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817e3cd8)
Location: include/linux/dma-mapping.h:281
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8180fa31)
Location: include/linux/dma-mapping.h:281
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8181b001)
Location: include/linux/dma-mapping.h:281
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
```
In net/core/page_pool.c (ffffffff8193430e)
Location: include/linux/dma-mapping.h:281
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
In mm/hmm.c (ffffffff812d56a9)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_dma_map
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815b1f09)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/virtio/virtio_ring.c (ffffffff816593ea)
Location: include/linux/dma-mapping.h:274
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816b068e)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816cd127)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/usb/core/hcd.c (ffffffff817eda06)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8180b0fd)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81814ac6)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81840e7e)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8184bd00)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
```
In net/core/page_pool.c (ffffffff81966f44)
Location: include/linux/dma-mapping.h:274
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
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8165b4e9)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/virtio/virtio_ring.c (ffffffff8170b610)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81763a3c)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81781f96)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_setup_scratch_page
```
```
In drivers/usb/core/hcd.c (ffffffff818bcf77)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818da78c)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_alloc_split_dma_aligned_buf
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818e6957)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81911b7c)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-ring.c:xhci_align_td
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8191eb27)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
```
In net/core/page_pool.c (ffffffff81a3a664)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ba996f)
Location: include/linux/dma-mapping.h:274
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
dma_addr_t dma_map_page_attrs(struct device *dev, struct page *page, size_t offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81137f30)
Location: kernel/dma/mapping.c:140
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/char/agp/intel-gtt.c:intel_gtt_setup_scratch_page
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
**Symbols:**

```
ffffffff81137f30-ffffffff81137f7e: dma_map_page_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
dma_addr_t dma_map_page_attrs(struct device *dev, struct page *page, size_t offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81138ff0)
Location: kernel/dma/mapping.c:142
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - net/core/page_pool.c:page_pool_dma_map
```
**Symbols:**

```
ffffffff81138ff0-ffffffff8113903e: dma_map_page_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
dma_addr_t dma_map_page_attrs(struct device *dev, struct page *page, size_t offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8115be80)
Location: kernel/dma/mapping.c:142
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - net/core/page_pool.c:page_pool_dma_map
```
**Symbols:**

```
ffffffff8115be80-ffffffff8115bece: dma_map_page_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
dma_addr_t dma_map_page_attrs(struct device *dev, struct page *page, size_t offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81185a90)
Location: kernel/dma/mapping.c:142
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - net/core/page_pool.c:page_pool_dma_map
  - net/xdp/xsk_buff_pool.c:xp_dma_map
```
**Symbols:**

```
ffffffff81185a90-ffffffff81185b26: dma_map_page_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
dma_addr_t dma_map_page_attrs(struct device *dev, struct page *page, size_t offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811c1450)
Location: kernel/dma/mapping.c:143
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - net/core/page_pool.c:page_pool_dma_map
  - net/xdp/xsk_buff_pool.c:xp_dma_map
```
**Symbols:**

```
ffffffff811c1450-ffffffff811c14e6: dma_map_page_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
dma_addr_t dma_map_page_attrs(struct device *dev, struct page *page, size_t offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811d3ed0)
Location: kernel/dma/mapping.c:147
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - net/core/page_pool.c:page_pool_dma_map
  - net/xdp/xsk_buff_pool.c:xp_dma_map
```
**Symbols:**

```
ffffffff811d3ed0-ffffffff811d3f66: dma_map_page_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
dma_addr_t dma_map_page_attrs(struct device *dev, struct page *page, size_t offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811e8b70)
Location: kernel/dma/mapping.c:147
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_map_one_sg
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - net/core/page_pool.c:page_pool_dma_map
  - net/xdp/xsk_buff_pool.c:xp_dma_map
```
**Symbols:**

```
ffffffff811e8b70-ffffffff811e8c06: dma_map_page_attrs (STB_GLOBAL)
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
In mm/hmm.c (ffff80001037aa94)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_dma_map
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffff80001072e420)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/dma/bcm2835-dma.c (ffff800010804810)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_probe
```
```
In drivers/dma/mv_xor.c (ffff800010807484)
Location: include/linux/dma-mapping.h:274
Inline: True
Direct callers:
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mv_xor.c:mv_xor_channel_add
```
```
In drivers/soc/fsl/qbman/qman.c (ffff800010816430)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/qman.c:qman_init_fq
```
```
In drivers/virtio/virtio_ring.c (ffff800010821c08)
Location: include/linux/dma-mapping.h:274
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffff80001088baec)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/tty/serial/msm_serial.c (ffff8000108a39e4)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:msm_handle_tx
```
```
In drivers/iommu/io-pgtable-arm.c (ffff8000108cb45c)
Location: include/linux/dma-mapping.h:274
Inline: True
```
```
In drivers/iommu/rockchip-iommu.c (ffff8000108d9374)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_map
```
```
In drivers/net/ethernet/broadcom/bgmac.c (ffff8000109e3664)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_start_xmit
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_start_xmit
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109eb774)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
```
```
In drivers/usb/core/hcd.c (ffff800010a1c99c)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffff800010a417fc)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffff800010a4dc6c)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/xhci-ring.c (ffff800010a7f89c)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffff800010a8b9b4)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
```
In drivers/firmware/qcom_scm-64.c (ffff800010b4f9f8)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/firmware/qcom_scm-64.c:qcom_scm_call
```
```
In net/core/page_pool.c (ffff800010c0cf64)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
**Symbols:**

```
ffff800010807484-ffff8000108074b0: dma_map_page_attrs.constprop.0 (STB_LOCAL)
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
In mm/hmm.c (c05660e4)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_dma_map
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (c08b7ca4)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/dma/mv_xor.c (c09251c4)
Location: include/linux/dma-mapping.h:274
Inline: True
Direct callers:
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mv_xor.c:mv_chan_xor_self_test
  - drivers/dma/mv_xor.c:mv_chan_xor_self_test
```
```
In drivers/virtio/virtio_ring.c (c093f710)
Location: include/linux/dma-mapping.h:274
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (c098943c)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/tty/serial/msm_serial.c (c099cc80)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:msm_handle_tx
```
```
In drivers/iommu/io-pgtable-arm.c (c09bffb0)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/iommu/io-pgtable-arm.c:__arm_lpae_alloc_pages
```
```
In drivers/iommu/omap-iommu.c (c09c47f8)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/iommu/omap-iommu.c:omap_iommu_attach_dev
  - drivers/iommu/omap-iommu.c:iopte_alloc
```
```
In drivers/iommu/rockchip-iommu.c (c09c6d84)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_map
```
```
In drivers/iommu/tegra-smmu.c (c09c889c)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/iommu/tegra-smmu.c:tegra_smmu_map
  - drivers/iommu/tegra-smmu.c:tegra_smmu_attach_dev
```
```
In drivers/iommu/exynos-iommu.c (c09ca758)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/iommu/exynos-iommu.c:exynos_iommu_map
  - drivers/iommu/exynos-iommu.c:exynos_iommu_domain_alloc
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0acdb48)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
```
```
In drivers/net/ethernet/ti/davinci_cpdma.c (c0ad7194)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_chan_submit_si
```
```
In drivers/usb/core/hcd.c (c0af5960)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (c0b13fbc)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/dwc2/hcd_ddma.c (c0b1fd7c)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/xhci-ring.c (c0b52c78)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (c0b5dde0)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
```
In drivers/usb/gadget/udc/core.c (c0b73e10)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/usb/gadget/udc/core.c:usb_gadget_map_request_by_dev
```
```
In drivers/i2c/busses/i2c-imx.c (c0b9a978)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_dma_xfer
```
```
In drivers/mmc/host/sdhci.c (c0c24c68)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci.c:sdhci_setup_host
```
```
In drivers/firmware/qcom_scm-32.c (c0c36274)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/firmware/qcom_scm-32.c:qcom_scm_call
```
```
In drivers/firmware/tegra/ivc.c (c0c43974)
Location: include/linux/dma-mapping.h:274
Inline: True
```
```
In drivers/staging/emxx_udc/emxx_udc.c (c0c5c240)
Location: include/linux/dma-mapping.h:274
Inline: True
```
```
In net/core/page_pool.c (c0d24c68)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
**Symbols:**

```
c09251c4-c092523c: dma_map_page_attrs.constprop.0 (STB_LOCAL)
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
In mm/hmm.c (c00000000046f65c)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_dma_map
```
```
In drivers/virtio/virtio_ring.c (c0000000008cb800)
Location: include/linux/dma-mapping.h:274
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (c000000000934570)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/tpm/tpm_ibmvtpm.c (c00000000096911c)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_probe
  - drivers/char/tpm/tpm_ibmvtpm.c:ibmvtpm_interrupt
```
```
In drivers/usb/core/hcd.c (c000000000ad7f30)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (c000000000b02820)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/dwc2/hcd_ddma.c (c000000000b15478)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/xhci-ring.c (c000000000b583d8)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (c000000000b67928)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
```
In net/core/page_pool.c (c000000000cf7c34)
Location: include/linux/dma-mapping.h:274
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
In mm/hmm.c (ffffffe000251c0a)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_dma_map
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffe0004e8b96)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/virtio/virtio_ring.c (ffffffe0005187f0)
Location: include/linux/dma-mapping.h:274
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffe000555468)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/usb/core/hcd.c (ffffffe00064169e)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffe00065d82e)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffe00066a6b4)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/xhci-ring.c (ffffffe0006962d2)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffe0006a0722)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
```
In drivers/mmc/host/mmc_spi.c (ffffffe00071a84c)
Location: include/linux/dma-mapping.h:274
Inline: True
```
```
In net/core/page_pool.c (ffffffe0007899f0)
Location: include/linux/dma-mapping.h:274
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
In mm/hmm.c (ffffffff812cdc89)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_dma_map
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815a56c9)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/virtio/virtio_ring.c (ffffffff8161f28a)
Location: include/linux/dma-mapping.h:274
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816760fe)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81692b77)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/nvme/host/pci.c (ffffffff8174f5d3)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_queue_rq
  - drivers/nvme/host/pci.c:nvme_map_data
  - drivers/nvme/host/pci.c:nvme_map_data
```
```
In drivers/usb/core/hcd.c (ffffffff817a5de6)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff817c34dd)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817ccea6)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817f922e)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In net/core/page_pool.c (ffffffff81906f14)
Location: include/linux/dma-mapping.h:274
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
In mm/hmm.c (ffffffff812beaf9)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_dma_map
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff81594869)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/virtio/virtio_ring.c (ffffffff816138aa)
Location: include/linux/dma-mapping.h:274
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816551de)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81670567)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/nvme/host/pci.c (ffffffff8172f473)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_queue_rq
  - drivers/nvme/host/pci.c:nvme_map_data
  - drivers/nvme/host/pci.c:nvme_map_data
```
```
In drivers/usb/core/hcd.c (ffffffff81798316)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817be3ce)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817c9250)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
```
In net/core/page_pool.c (ffffffff818c0d24)
Location: include/linux/dma-mapping.h:274
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
In mm/hmm.c (ffffffff812cba99)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_dma_map
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815a5c59)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/virtio/virtio_ring.c (ffffffff8164d22a)
Location: include/linux/dma-mapping.h:274
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816a44ce)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816c0de7)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/usb/core/hcd.c (ffffffff817e2886)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff817fff7d)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81809946)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81835cfe)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81840b80)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
```
In drivers/i2c/busses/i2c-amd-mp2-plat.c (ffffffff81868ff9)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_xfer
```
```
In net/core/page_pool.c (ffffffff81957f44)
Location: include/linux/dma-mapping.h:274
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
In mm/hmm.c (ffffffff812dc7f9)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_dma_map
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815c0059)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/virtio/virtio_ring.c (ffffffff816678ba)
Location: include/linux/dma-mapping.h:274
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816be95e)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816db3b7)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/usb/core/hcd.c (ffffffff817fd5d6)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8181a08d)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81823a56)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81850034)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8185b050)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
```
In net/core/page_pool.c (ffffffff8197a034)
Location: include/linux/dma-mapping.h:274
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
