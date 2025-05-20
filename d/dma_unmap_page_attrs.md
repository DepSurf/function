# Function: <code>dma_unmap_page_attrs</code>

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
In drivers/dma/dmaengine.c (ffffffff81539ec6)
Location: include/linux/dma-mapping.h:263
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
```
In drivers/virtio/virtio_ring.c (ffffffff8153bc18)
Location: include/linux/dma-mapping.h:263
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff815a1896)
Location: include/linux/dma-mapping.h:263
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
```
```
In drivers/usb/core/hcd.c (0)
Location: include/linux/dma-mapping.h:263
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
In drivers/dma/dmaengine.c (ffffffff8154d741)
Location: include/linux/dma-mapping.h:306
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap_put
  - drivers/dma/dmaengine.c:dmaengine_unmap_put
  - drivers/dma/dmaengine.c:dmaengine_unmap_put
```
```
In drivers/virtio/virtio_ring.c (ffffffff8154f55e)
Location: include/linux/dma-mapping.h:306
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff815b515d)
Location: include/linux/dma-mapping.h:306
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
```
```
In drivers/usb/core/hcd.c (0)
Location: include/linux/dma-mapping.h:306
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
In drivers/dma/dmaengine.c (ffffffff815b0db4)
Location: include/linux/dma-mapping.h:304
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
```
In drivers/virtio/virtio_ring.c (ffffffff815b2d1e)
Location: include/linux/dma-mapping.h:304
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8161bdfd)
Location: include/linux/dma-mapping.h:304
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
```
```
In drivers/usb/core/hcd.c (0)
Location: include/linux/dma-mapping.h:304
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
In drivers/dma/dmaengine.c (ffffffff815e9201)
Location: include/linux/dma-mapping.h:304
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
```
In drivers/virtio/virtio_ring.c (ffffffff815eb23e)
Location: include/linux/dma-mapping.h:304
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81655aaa)
Location: include/linux/dma-mapping.h:304
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
```
```
In drivers/usb/core/hcd.c (0)
Location: include/linux/dma-mapping.h:304
Inline: True
```
```
In net/core/page_pool.c (ffffffff818bd835)
Location: include/linux/dma-mapping.h:304
Inline: True
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
In drivers/dma/dmaengine.c (ffffffff816036c0)
Location: include/linux/dma-mapping.h:296
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
```
In drivers/virtio/virtio_ring.c (ffffffff81605796)
Location: include/linux/dma-mapping.h:296
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81658dac)
Location: include/linux/dma-mapping.h:296
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81673cca)
Location: include/linux/dma-mapping.h:296
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
```
```
In drivers/usb/core/hcd.c (ffffffff8177e15f)
Location: include/linux/dma-mapping.h:296
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff817a10b5)
Location: include/linux/dma-mapping.h:296
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817a4e53)
Location: include/linux/dma-mapping.h:296
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817cd872)
Location: include/linux/dma-mapping.h:296
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817dab51)
Location: include/linux/dma-mapping.h:296
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In net/core/page_pool.c (ffffffff818e4d7d)
Location: include/linux/dma-mapping.h:296
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hmm.c (ffffffff812c3528)
Location: include/linux/dma-mapping.h:298
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_dma_unmap
  - mm/hmm.c:hmm_range_dma_map
```
```
In drivers/dma/dmaengine.c (ffffffff81635ef3)
Location: include/linux/dma-mapping.h:298
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
```
In drivers/virtio/virtio_ring.c (ffffffff8163a96f)
Location: include/linux/dma-mapping.h:298
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
  - drivers/virtio/virtio_ring.c:detach_buf_packed
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8168e2a0)
Location: include/linux/dma-mapping.h:298
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816a9a98)
Location: include/linux/dma-mapping.h:298
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
```
```
In drivers/usb/core/hcd.c (ffffffff817bc6df)
Location: include/linux/dma-mapping.h:298
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff817e0003)
Location: include/linux/dma-mapping.h:298
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817e4073)
Location: include/linux/dma-mapping.h:298
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8180d8e0)
Location: include/linux/dma-mapping.h:298
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8181a922)
Location: include/linux/dma-mapping.h:298
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
```
In net/core/page_pool.c (ffffffff81934227)
Location: include/linux/dma-mapping.h:298
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_clean_page
```
**Symbols:**

```
ffffffff8181b4dc-ffffffff8181b521: dma_unmap_page_attrs.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hmm.c (ffffffff812d5557)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_dma_unmap
  - mm/hmm.c:hmm_range_dma_map
```
```
In drivers/dma/dmaengine.c (ffffffff81657c13)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
```
In drivers/virtio/virtio_ring.c (ffffffff8165ce2f)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
  - drivers/virtio/virtio_ring.c:detach_buf_packed
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816b0870)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816cc7d8)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
```
```
In drivers/usb/core/hcd.c (ffffffff817eceff)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81810ef3)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81814f33)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8183e9d0)
Location: include/linux/dma-mapping.h:291
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8184bfa2)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
```
In net/core/page_pool.c (ffffffff81966e5a)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_clean_page
```
**Symbols:**

```
ffffffff8184c8e6-ffffffff8184c92b: dma_unmap_page_attrs.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dma/dmaengine.c (ffffffff81707353)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
```
In drivers/virtio/virtio_ring.c (ffffffff8170a8c6)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
  - drivers/virtio/virtio_ring.c:detach_buf_packed
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81763c50)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81781078)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
```
```
In drivers/usb/core/hcd.c (ffffffff818bc21f)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff818e1725)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_xfercomp_isoc_split_in
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818e6ae1)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81910f2e)
Location: include/linux/dma-mapping.h:291
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8191e806)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
```
In net/core/page_pool.c (ffffffff81a3a8ea)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release_page
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ba9835)
Location: include/linux/dma-mapping.h:291
Inline: True
```
**Symbols:**

```
ffffffff8191f405-ffffffff8191f44a: dma_unmap_page_attrs.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dma_unmap_page_attrs(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81137f80)
Location: kernel/dma/mapping.c:163
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/virtio/virtio_ring.c:detach_buf_packed
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_xfercomp_isoc_split_in
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
  - drivers/usb/host/xhci.c:xhci_unmap_urb_for_dma
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
  - net/core/page_pool.c:page_pool_release_page
  - net/xdp/xsk_buff_pool.c:__xp_dma_unmap
```
**Symbols:**

```
ffffffff81137f80-ffffffff8113812f: dma_unmap_page_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dma_unmap_page_attrs(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81139040)
Location: kernel/dma/mapping.c:165
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/virtio/virtio_ring.c:detach_buf_packed
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_xfercomp_isoc_split_in
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
  - drivers/usb/host/xhci.c:xhci_unmap_urb_for_dma
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
  - net/core/page_pool.c:page_pool_release_page
  - net/xdp/xsk_buff_pool.c:__xp_dma_unmap
```
**Symbols:**

```
ffffffff81139040-ffffffff811391f5: dma_unmap_page_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dma_unmap_page_attrs(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8115bed0)
Location: kernel/dma/mapping.c:165
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/virtio/virtio_ring.c:detach_buf_packed
  - drivers/virtio/virtio_ring.c:vring_unmap_one_split
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_xfercomp_isoc_split_in
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
  - drivers/usb/host/xhci.c:xhci_unmap_urb_for_dma
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
  - net/core/page_pool.c:page_pool_release_page
  - net/xdp/xsk_buff_pool.c:__xp_dma_unmap
```
**Symbols:**

```
ffffffff8115bed0-ffffffff8115c088: dma_unmap_page_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dma_unmap_page_attrs(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81185b30)
Location: kernel/dma/mapping.c:165
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/virtio/virtio_ring.c:vring_unmap_one_split
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_xfercomp_isoc_split_in
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
  - drivers/usb/host/xhci.c:xhci_unmap_urb_for_dma
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
  - net/core/page_pool.c:page_pool_release_page
  - net/xdp/xsk_buff_pool.c:__xp_dma_unmap
```
**Symbols:**

```
ffffffff81185b30-ffffffff81185d1f: dma_unmap_page_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dma_unmap_page_attrs(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811c1500)
Location: kernel/dma/mapping.c:167
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/virtio/virtio_ring.c:vring_unmap_one_split
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_xfercomp_isoc_split_in
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
  - drivers/usb/host/xhci.c:xhci_unmap_urb_for_dma
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
  - net/core/page_pool.c:page_pool_release_page
  - net/xdp/xsk_buff_pool.c:__xp_dma_unmap
```
**Symbols:**

```
ffffffff811c1500-ffffffff811c16ef: dma_unmap_page_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dma_unmap_page_attrs(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811d3f80)
Location: kernel/dma/mapping.c:171
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/virtio/virtio_ring.c:vring_unmap_one_split
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_xfercomp_isoc_split_in
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
  - drivers/usb/host/xhci.c:xhci_unmap_urb_for_dma
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
  - net/core/page_pool.c:page_pool_release_page
  - net/xdp/xsk_buff_pool.c:__xp_dma_unmap
```
**Symbols:**

```
ffffffff811d3f80-ffffffff811d416f: dma_unmap_page_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void dma_unmap_page_attrs(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/mapping.c (0)
Location: kernel/dma/mapping.c:171
Inline: False
Direct callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/virtio/virtio_ring.c:vring_unmap_extra_packed
  - drivers/virtio/virtio_ring.c:vring_unmap_one_split
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_xfercomp_isoc_split_in
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
  - drivers/usb/host/xhci.c:xhci_unmap_urb_for_dma
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
  - net/core/page_pool.c:page_pool_return_page
  - net/xdp/xsk_buff_pool.c:__xp_dma_unmap
```
**Symbols:**

```
ffffffff821b4749-ffffffff821b4787: dma_unmap_page_attrs.cold (STB_LOCAL)
ffffffff811e8fc0-ffffffff811e91dc: dma_unmap_page_attrs (STB_GLOBAL)
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
In mm/hmm.c (ffff80001037a930)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_dma_unmap
  - mm/hmm.c:hmm_range_dma_map
```
```
In drivers/dma/dmaengine.c (ffff8000107fce5c)
Location: include/linux/dma-mapping.h:291
Inline: True
```
```
In drivers/dma/bcm2835-dma.c (ffff800010804284)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_free
```
```
In drivers/dma/mv_xor.c (ffff800010807444)
Location: include/linux/dma-mapping.h:291
Inline: True
Direct callers:
  - drivers/dma/mv_xor.c:mv_xor_probe
  - drivers/dma/mv_xor.c:mv_xor_probe
```
```
In drivers/virtio/virtio_ring.c (ffff800010822fcc)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
  - drivers/virtio/virtio_ring.c:detach_buf_packed
```
```
In drivers/tty/serial/8250/8250_dma.c (ffff80001088bd3c)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
```
In drivers/tty/serial/msm_serial.c (ffff8000108a3b7c)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:msm_handle_tx
  - drivers/tty/serial/msm_serial.c:msm_complete_rx_dma
  - drivers/tty/serial/msm_serial.c:msm_complete_tx_dma
  - drivers/tty/serial/msm_serial.c:msm_stop_dma
```
```
In drivers/iommu/io-pgtable-arm.c (ffff8000108cb574)
Location: include/linux/dma-mapping.h:291
Inline: True
```
```
In drivers/iommu/rockchip-iommu.c (ffff8000108d80dc)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_domain_free
  - drivers/iommu/rockchip-iommu.c:rk_iommu_domain_free
```
```
In drivers/net/ethernet/broadcom/bgmac.c (ffff8000109e397c)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_start_xmit
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_start_xmit
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_poll
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_cleanup
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_cleanup
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_rx_read
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e655c)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_free_buffers
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_napi
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
```
```
In drivers/usb/core/hcd.c (ffff800010a1bf70)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
```
In drivers/usb/dwc2/hcd_intr.c (ffff800010a49f78)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffff800010a4e148)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
```
```
In drivers/usb/host/xhci-ring.c (ffff800010a7c47c)
Location: include/linux/dma-mapping.h:291
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (ffff800010a8bd10)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/firmware/qcom_scm-64.c (ffff800010b4f8a4)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/firmware/qcom_scm-64.c:qcom_scm_call
```
```
In net/core/page_pool.c (ffff800010c0c900)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_clean_page
```
**Symbols:**

```
ffff800010807444-ffff800010807484: dma_unmap_page_attrs.constprop.0 (STB_LOCAL)
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
In mm/hmm.c (c0565e7c)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_dma_unmap
  - mm/hmm.c:hmm_range_dma_map
```
```
In drivers/dma/dmaengine.c (c091f528)
Location: include/linux/dma-mapping.h:291
Inline: True
```
```
In drivers/dma/mv_xor.c (c092516c)
Location: include/linux/dma-mapping.h:291
Inline: True
Direct callers:
  - drivers/dma/mv_xor.c:mv_xor_probe
  - drivers/dma/mv_xor.c:mv_xor_probe
```
```
In drivers/virtio/virtio_ring.c (c0940b7c)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
  - drivers/virtio/virtio_ring.c:detach_buf_packed
```
```
In drivers/tty/serial/8250/8250_dma.c (c098970c)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
```
In drivers/tty/serial/msm_serial.c (c099ce28)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:msm_handle_tx
  - drivers/tty/serial/msm_serial.c:msm_complete_rx_dma
  - drivers/tty/serial/msm_serial.c:msm_complete_tx_dma
  - drivers/tty/serial/msm_serial.c:msm_stop_dma
```
```
In drivers/iommu/io-pgtable-arm.c (c09c0654)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/iommu/io-pgtable-arm.c:__arm_lpae_free_pages
  - drivers/iommu/io-pgtable-arm.c:__arm_lpae_alloc_pages
```
```
In drivers/iommu/omap-iommu.c (c09c3f58)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/iommu/omap-iommu.c:omap_iommu_detach
  - drivers/iommu/omap-iommu.c:iopte_alloc
```
```
In drivers/iommu/rockchip-iommu.c (c09c66b8)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_domain_free
  - drivers/iommu/rockchip-iommu.c:rk_iommu_domain_free
```
```
In drivers/iommu/tegra-smmu.c (c09c8a7c)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/iommu/tegra-smmu.c:tegra_smmu_unmap
  - drivers/iommu/tegra-smmu.c:tegra_smmu_map
  - drivers/iommu/tegra-smmu.c:tegra_smmu_detach_dev
  - drivers/iommu/tegra-smmu.c:tegra_smmu_attach_dev
```
```
In drivers/iommu/exynos-iommu.c (c09c9d34)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/iommu/exynos-iommu.c:exynos_iommu_domain_free
  - drivers/iommu/exynos-iommu.c:exynos_iommu_domain_free
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0ac9614)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_free_buffers
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_napi
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
```
```
In drivers/net/ethernet/ti/davinci_cpdma.c (0)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/davinci_cpdma.c:__cpdma_chan_free
```
```
In drivers/usb/core/hcd.c (c0af3cac)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
```
In drivers/usb/dwc2/hcd_intr.c (c0b1c394)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
```
In drivers/usb/dwc2/hcd_ddma.c (c0b201f4)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
```
```
In drivers/usb/host/xhci-ring.c (c0b50580)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_unmap_td_bounce_buffer
  - drivers/usb/host/xhci-ring.c:xhci_unmap_td_bounce_buffer
```
```
In drivers/usb/host/xhci-dbgcap.c (c0b5e134)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
```
In drivers/usb/gadget/udc/core.c (c0b73ccc)
Location: include/linux/dma-mapping.h:291
Inline: True
```
```
In drivers/i2c/busses/i2c-imx.c (c0b9c428)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_dma_callback
Direct callers:
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_dma_xfer
```
```
In drivers/firmware/qcom_scm-32.c (c0c36458)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/firmware/qcom_scm-32.c:qcom_scm_call
```
```
In drivers/firmware/tegra/ivc.c (c0c432ec)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/firmware/tegra/ivc.c:tegra_ivc_cleanup
  - drivers/firmware/tegra/ivc.c:tegra_ivc_cleanup
```
```
In drivers/staging/emxx_udc/emxx_udc.c (c0c5c0b4)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_dma_unmap_single
```
```
In net/core/page_pool.c (c0d24ae4)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_clean_page
```
**Symbols:**

```
c092516c-c09251c4: dma_unmap_page_attrs.constprop.0 (STB_LOCAL)
c0b5dcc0-c0b5dd24: dma_unmap_page_attrs.constprop.0 (STB_LOCAL)
c0b9a868-c0b9a8cc: dma_unmap_page_attrs.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hmm.c (c00000000046f364)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_dma_unmap
  - mm/hmm.c:hmm_range_dma_map
```
```
In drivers/dma/dmaengine.c (c0000000008c9218)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap_put
  - drivers/dma/dmaengine.c:dmaengine_unmap_put
  - drivers/dma/dmaengine.c:dmaengine_unmap_put
```
```
In drivers/virtio/virtio_ring.c (c0000000008d08cc)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
  - drivers/virtio/virtio_ring.c:detach_buf_packed
```
```
In drivers/tty/serial/8250/8250_dma.c (c00000000093479c)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
```
In drivers/char/tpm/tpm_ibmvtpm.c (c00000000096923c)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_probe
  - drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_remove
  - drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_remove
```
```
In drivers/usb/core/hcd.c (c000000000ad5c1c)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
```
In drivers/usb/dwc2/hcd_intr.c (c000000000b0feb4)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
```
In drivers/usb/dwc2/hcd_ddma.c (c000000000b15a7c)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
```
```
In drivers/usb/host/xhci-ring.c (c000000000b54f60)
Location: include/linux/dma-mapping.h:291
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (c000000000b66144)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
```
In net/core/page_pool.c (c000000000cf7ad4)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_clean_page
```
**Symbols:**

```
c000000000b681fc-c000000000b68268: dma_unmap_page_attrs.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hmm.c (ffffffe000251da6)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_dma_unmap
  - mm/hmm.c:hmm_range_dma_map
```
```
In drivers/dma/dmaengine.c (ffffffe0005173e2)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap_put
  - drivers/dma/dmaengine.c:dmaengine_unmap_put
  - drivers/dma/dmaengine.c:dmaengine_unmap_put
```
```
In drivers/virtio/virtio_ring.c (ffffffe000519912)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
  - drivers/virtio/virtio_ring.c:detach_buf_packed
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffe00055565a)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
```
In drivers/usb/core/hcd.c (ffffffe000640172)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffe000666e3c)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffe00066ab22)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
```
```
In drivers/usb/host/xhci-ring.c (ffffffe00069400e)
Location: include/linux/dma-mapping.h:291
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffe00069f6fc)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
```
In drivers/mmc/host/mmc_spi.c (ffffffe00071b1a4)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/mmc/host/mmc_spi.c:mmc_spi_remove
  - drivers/mmc/host/mmc_spi.c:mmc_spi_remove
```
```
In net/core/page_pool.c (ffffffe0007898b2)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_clean_page
```
**Symbols:**

```
ffffffe0006a0c8a-ffffffe0006a0cbc: dma_unmap_page_attrs.constprop.0 (STB_LOCAL)
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
In mm/hmm.c (ffffffff812cdb37)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_dma_unmap
  - mm/hmm.c:hmm_range_dma_map
```
```
In drivers/dma/dmaengine.c (ffffffff8161dab3)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
```
In drivers/virtio/virtio_ring.c (ffffffff81622ccf)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
  - drivers/virtio/virtio_ring.c:detach_buf_packed
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816762e0)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81692228)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
```
```
In drivers/nvme/host/pci.c (ffffffff8174e641)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_pci_complete_rq
  - drivers/nvme/host/pci.c:nvme_unmap_data
```
```
In drivers/usb/core/hcd.c (ffffffff817a52df)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff817c92d3)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817cd313)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817f6d80)
Location: include/linux/dma-mapping.h:291
Inline: True
```
```
In net/core/page_pool.c (ffffffff81906e2a)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_clean_page
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hmm.c (ffffffff812be9a7)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_dma_unmap
  - mm/hmm.c:hmm_range_dma_map
```
```
In drivers/dma/dmaengine.c (ffffffff816121a3)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
```
In drivers/virtio/virtio_ring.c (ffffffff8161731f)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
  - drivers/virtio/virtio_ring.c:detach_buf_packed
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816553c0)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8166fc18)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
```
```
In drivers/nvme/host/pci.c (ffffffff8172e4e1)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_pci_complete_rq
  - drivers/nvme/host/pci.c:nvme_unmap_data
```
```
In drivers/usb/core/hcd.c (ffffffff81796def)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817bbf20)
Location: include/linux/dma-mapping.h:291
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817c94f2)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
```
In net/core/page_pool.c (ffffffff818c0c3a)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_clean_page
```
**Symbols:**

```
ffffffff817c9e36-ffffffff817c9e7b: dma_unmap_page_attrs.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hmm.c (ffffffff812cb947)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_dma_unmap
  - mm/hmm.c:hmm_range_dma_map
```
```
In drivers/dma/dmaengine.c (ffffffff8164ba53)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
```
In drivers/virtio/virtio_ring.c (ffffffff81650c6f)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
  - drivers/virtio/virtio_ring.c:detach_buf_packed
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816a46b0)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816c0498)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
```
```
In drivers/usb/core/hcd.c (ffffffff817e1d7f)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81805d73)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81809db3)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81833850)
Location: include/linux/dma-mapping.h:291
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81840e22)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
```
In drivers/i2c/busses/i2c-amd-mp2-plat.c (ffffffff8186893b)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_check_cmd_completion
```
```
In net/core/page_pool.c (ffffffff81957e5a)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_clean_page
```
**Symbols:**

```
ffffffff81841766-ffffffff818417ab: dma_unmap_page_attrs.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hmm.c (ffffffff812dc6a7)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_dma_unmap
  - mm/hmm.c:hmm_range_dma_map
```
```
In drivers/dma/dmaengine.c (ffffffff81665ff3)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
```
```
In drivers/virtio/virtio_ring.c (ffffffff8166b2ff)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
  - drivers/virtio/virtio_ring.c:detach_buf_packed
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816beb68)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816daa68)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
```
```
In drivers/usb/core/hcd.c (ffffffff817fc06f)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff8181fe83)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81823ec3)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8184db20)
Location: include/linux/dma-mapping.h:291
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8185b312)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
```
In net/core/page_pool.c (ffffffff81979f48)
Location: include/linux/dma-mapping.h:291
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_clean_page
```
**Symbols:**

```
ffffffff8185bcc6-ffffffff8185bd0b: dma_unmap_page_attrs.constprop.0 (STB_LOCAL)
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
