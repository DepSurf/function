# Function: <code>dma_free_attrs</code>

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
In mm/dmapool.c (ffffffff811d991a)
Location: include/asm-generic/dma-mapping-common.h:267
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81509900)
Location: include/asm-generic/dma-mapping-common.h:267
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
```
In drivers/char/virtio_console.c (ffffffff81516a35)
Location: include/asm-generic/dma-mapping-common.h:267
Inline: True
```
```
In drivers/base/dma-mapping.c (ffffffff8155db9a)
Location: include/asm-generic/dma-mapping-common.h:267
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dmam_coherent_release
  - drivers/base/dma-mapping.c:dmam_noncoherent_release
```
```
In drivers/usb/core/buffer.c (ffffffff81617a76)
Location: include/asm-generic/dma-mapping-common.h:267
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8162a191)
Location: include/asm-generic/dma-mapping-common.h:267
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8162e53f)
Location: include/asm-generic/dma-mapping-common.h:267
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81634ca3)
Location: include/asm-generic/dma-mapping-common.h:267
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81641285)
Location: include/asm-generic/dma-mapping-common.h:267
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81649763)
Location: include/asm-generic/dma-mapping-common.h:267
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81655383)
Location: include/asm-generic/dma-mapping-common.h:267
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_free_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
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
In mm/dmapool.c (ffffffff811f7af0)
Location: include/linux/dma-mapping.h:426
Inline: True
```
```
In drivers/virtio/virtio_ring.c (ffffffff8150f28d)
Location: include/linux/dma-mapping.h:426
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8155b964)
Location: include/linux/dma-mapping.h:426
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/virtio_console.c (ffffffff815696ce)
Location: include/linux/dma-mapping.h:426
Inline: True
```
```
In drivers/base/dma-mapping.c (ffffffff815b2062)
Location: include/linux/dma-mapping.h:426
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dmam_noncoherent_release
  - drivers/base/dma-mapping.c:dmam_coherent_release
```
```
In drivers/usb/core/buffer.c (ffffffff81677b46)
Location: include/linux/dma-mapping.h:426
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8168a090)
Location: include/linux/dma-mapping.h:426
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8169511f)
Location: include/linux/dma-mapping.h:426
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff816a1d95)
Location: include/linux/dma-mapping.h:426
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816aa1d3)
Location: include/linux/dma-mapping.h:426
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816b72b3)
Location: include/linux/dma-mapping.h:426
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_free_stream_info
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
In mm/dmapool.c (ffffffff812084a0)
Location: include/linux/dma-mapping.h:478
Inline: True
```
```
In drivers/virtio/virtio_ring.c (ffffffff8153b3dd)
Location: include/linux/dma-mapping.h:478
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81588126)
Location: include/linux/dma-mapping.h:478
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/virtio_console.c (ffffffff81595e0e)
Location: include/linux/dma-mapping.h:478
Inline: True
```
```
In drivers/base/dma-mapping.c (ffffffff815e1352)
Location: include/linux/dma-mapping.h:478
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dmam_noncoherent_release
  - drivers/base/dma-mapping.c:dmam_coherent_release
```
```
In drivers/usb/core/buffer.c (ffffffff816a5826)
Location: include/linux/dma-mapping.h:478
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
```
```
In drivers/usb/dwc2/hcd.c (ffffffff816b81ff)
Location: include/linux/dma-mapping.h:478
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff816c36af)
Location: include/linux/dma-mapping.h:478
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff816d0a15)
Location: include/linux/dma-mapping.h:478
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816d8323)
Location: include/linux/dma-mapping.h:478
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816e555a)
Location: include/linux/dma-mapping.h:478
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_free_stream_info
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
In mm/dmapool.c (ffffffff81213b69)
Location: include/linux/dma-mapping.h:521
Inline: True
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff814d2b28)
Location: include/linux/dma-mapping.h:521
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space
```
```
In drivers/virtio/virtio_ring.c (ffffffff8154ec69)
Location: include/linux/dma-mapping.h:521
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8159c589)
Location: include/linux/dma-mapping.h:521
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/virtio_console.c (ffffffff815a9bf3)
Location: include/linux/dma-mapping.h:521
Inline: True
```
```
In drivers/base/dma-mapping.c (ffffffff815f60f5)
Location: include/linux/dma-mapping.h:521
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dmam_release
```
```
In drivers/usb/core/buffer.c (ffffffff816babab)
Location: include/linux/dma-mapping.h:521
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
```
```
In drivers/usb/dwc2/hcd.c (ffffffff816cc4ea)
Location: include/linux/dma-mapping.h:521
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff816d7994)
Location: include/linux/dma-mapping.h:521
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff816e509d)
Location: include/linux/dma-mapping.h:521
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816ec83f)
Location: include/linux/dma-mapping.h:521
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816f9481)
Location: include/linux/dma-mapping.h:521
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
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
In mm/dmapool.c (ffffffff8122e6f9)
Location: include/linux/dma-mapping.h:530
Inline: True
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff81512f28)
Location: include/linux/dma-mapping.h:530
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space
```
```
In drivers/virtio/virtio_ring.c (ffffffff815b2409)
Location: include/linux/dma-mapping.h:530
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8160187c)
Location: include/linux/dma-mapping.h:530
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/virtio_console.c (ffffffff8161051c)
Location: include/linux/dma-mapping.h:530
Inline: True
```
```
In drivers/base/dma-mapping.c (ffffffff8165e016)
Location: include/linux/dma-mapping.h:530
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dmam_release
```
```
In drivers/usb/core/buffer.c (ffffffff8172656b)
Location: include/linux/dma-mapping.h:530
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81738a6d)
Location: include/linux/dma-mapping.h:530
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817440c4)
Location: include/linux/dma-mapping.h:530
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff817518c7)
Location: include/linux/dma-mapping.h:530
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8175902f)
Location: include/linux/dma-mapping.h:530
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81765f78)
Location: include/linux/dma-mapping.h:530
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_free_erst
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81772c92)
Location: include/linux/dma-mapping.h:530
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
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
In kernel/dma/mapping.c (ffffffff8110cad5)
Location: include/linux/dma-mapping.h:534
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dmam_release
```
```
In mm/dmapool.c (ffffffff81251572)
Location: include/linux/dma-mapping.h:534
Inline: True
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff815482b7)
Location: include/linux/dma-mapping.h:534
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space
```
```
In drivers/virtio/virtio_ring.c (ffffffff815ea84a)
Location: include/linux/dma-mapping.h:534
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8163ab36)
Location: include/linux/dma-mapping.h:534
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/virtio_console.c (ffffffff8164a019)
Location: include/linux/dma-mapping.h:534
Inline: True
```
```
In drivers/usb/core/buffer.c (ffffffff8176536f)
Location: include/linux/dma-mapping.h:534
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81778ab0)
Location: include/linux/dma-mapping.h:534
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81784634)
Location: include/linux/dma-mapping.h:534
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff8179138c)
Location: include/linux/dma-mapping.h:534
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8179986c)
Location: include/linux/dma-mapping.h:534
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817a6b0b)
Location: include/linux/dma-mapping.h:534
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_free_erst
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817b3231)
Location: include/linux/dma-mapping.h:534
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
```
```
In drivers/i2c/busses/i2c-amd-platdrv.c (ffffffff817dd617)
Location: include/linux/dma-mapping.h:534
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-amd-platdrv.c:i2c_amd_xfer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dma_free_attrs(struct device *dev, size_t size, void *cpu_addr, dma_addr_t dma_handle, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81117f50)
Location: kernel/dma/mapping.c:276
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dmam_release
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_free_erst
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
```
**Symbols:**

```
ffffffff81117f50-ffffffff81117fa4: dma_free_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void dma_free_attrs(struct device *dev, size_t size, void *cpu_addr, dma_addr_t dma_handle, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/mapping.c (0)
Location: kernel/dma/mapping.c:293
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dmam_release
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_free_erst
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
```
**Symbols:**

```
ffffffff81122888-ffffffff811228a3: dma_free_attrs.cold (STB_LOCAL)
ffffffff811222a0-ffffffff8112234f: dma_free_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dma_free_attrs(struct device *dev, size_t size, void *cpu_addr, dma_addr_t dma_handle, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8112e910)
Location: kernel/dma/mapping.c:321
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dmam_release
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_free_erst
  - drivers/remoteproc/remoteproc_core.c:rproc_release_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
```
**Symbols:**

```
ffffffff8112e910-ffffffff8112e95c: dma_free_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dma_free_attrs(struct device *dev, size_t size, void *cpu_addr, dma_addr_t dma_handle, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8113d2a0)
Location: kernel/dma/mapping.c:292
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dmam_release
  - mm/dmapool.c:dma_pool_destroy
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/char/virtio_console.c:free_buf
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:release_uhci
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
  - drivers/remoteproc/remoteproc_core.c:rproc_release_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
```
**Symbols:**

```
ffffffff8113d2a0-ffffffff8113d2f5: dma_free_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dma_free_attrs(struct device *dev, size_t size, void *cpu_addr, dma_addr_t dma_handle, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81137980)
Location: kernel/dma/mapping.c:451
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dmam_release
  - mm/dmapool.c:dma_pool_destroy
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/char/virtio_console.c:free_buf
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:release_uhci
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
  - drivers/usb/host/xhci-dbgcap.c:dbc_ring_free
  - drivers/remoteproc/remoteproc_core.c:rproc_release_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
```
**Symbols:**

```
ffffffff81137980-ffffffff811379d5: dma_free_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dma_free_attrs(struct device *dev, size_t size, void *cpu_addr, dma_addr_t dma_handle, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81138770)
Location: kernel/dma/mapping.c:453
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dmam_release
  - mm/dmapool.c:dma_pool_destroy
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/char/virtio_console.c:free_buf
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
  - drivers/usb/host/xhci-dbgcap.c:dbc_ring_free
  - drivers/remoteproc/remoteproc_core.c:rproc_release_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
```
**Symbols:**

```
ffffffff81138770-ffffffff811387c5: dma_free_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dma_free_attrs(struct device *dev, size_t size, void *cpu_addr, dma_addr_t dma_handle, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8115b5d0)
Location: kernel/dma/mapping.c:518
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dmam_free_coherent
  - kernel/dma/mapping.c:dmam_release
  - mm/dmapool.c:dma_pool_destroy
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/char/virtio_console.c:free_buf
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-dbgcap.c:dbc_ring_free
  - drivers/remoteproc/remoteproc_core.c:rproc_release_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
```
**Symbols:**

```
ffffffff8115b5d0-ffffffff8115b625: dma_free_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dma_free_attrs(struct device *dev, size_t size, void *cpu_addr, dma_addr_t dma_handle, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81185000)
Location: kernel/dma/mapping.c:512
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dmam_free_coherent
  - kernel/dma/mapping.c:dmam_release
  - mm/dmapool.c:dma_pool_destroy
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/char/virtio_console.c:free_buf
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-dbgcap.c:dbc_ring_free
  - drivers/remoteproc/remoteproc_core.c:rproc_release_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
```
**Symbols:**

```
ffffffff81185000-ffffffff8118507c: dma_free_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dma_free_attrs(struct device *dev, size_t size, void *cpu_addr, dma_addr_t dma_handle, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811c0780)
Location: kernel/dma/mapping.c:527
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dmam_free_coherent
  - kernel/dma/mapping.c:dmam_release
  - mm/dmapool.c:dma_pool_destroy
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/char/virtio_console.c:free_buf
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_mem_cleanup
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_mem_cleanup
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_mem_cleanup
  - drivers/usb/host/xhci-dbgcap.c:dbc_ring_free
  - drivers/remoteproc/remoteproc_core.c:rproc_release_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
```
**Symbols:**

```
ffffffff811c0780-ffffffff811c080f: dma_free_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dma_free_attrs(struct device *dev, size_t size, void *cpu_addr, dma_addr_t dma_handle, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811d3270)
Location: kernel/dma/mapping.c:531
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dmam_free_coherent
  - kernel/dma/mapping.c:dmam_release
  - mm/dmapool.c:dma_pool_destroy
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/char/virtio_console.c:free_buf
  - drivers/usb/core/buffer.c:hcd_buffer_free_pages
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_mem_cleanup
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_mem_cleanup
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_mem_cleanup
  - drivers/usb/host/xhci-dbgcap.c:dbc_ring_free
  - drivers/remoteproc/remoteproc_core.c:rproc_release_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
```
**Symbols:**

```
ffffffff811d3270-ffffffff811d32ff: dma_free_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dma_free_attrs(struct device *dev, size_t size, void *cpu_addr, dma_addr_t dma_handle, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811e7ef0)
Location: kernel/dma/mapping.c:531
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dmam_free_coherent
  - kernel/dma/mapping.c:dmam_release
  - mm/dmapool.c:dma_pool_destroy
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/char/virtio_console.c:free_buf
  - drivers/usb/core/buffer.c:hcd_buffer_free_pages
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_free_interrupter
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_mem_cleanup
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_mem_cleanup
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_mem_cleanup
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_mem_cleanup
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_mem_cleanup
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_mem_cleanup
  - drivers/remoteproc/remoteproc_core.c:rproc_release_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
```
**Symbols:**

```
ffffffff811e7ef0-ffffffff811e7f7f: dma_free_attrs (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void dma_free_attrs(struct device *dev, size_t size, void *cpu_addr, dma_addr_t dma_handle, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffff800010193c80)
Location: kernel/dma/mapping.c:321
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dmam_release
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_exit
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_init
  - drivers/video/fbdev/amba-clcd.c:clcdfb_of_dma_remove
  - drivers/video/fbdev/mx3fb.c:mx3fb_unmap_video_memory
  - drivers/dma/mv_xor.c:mv_xor_probe
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_remove
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_probe
  - drivers/dma/mxs-dma.c:mxs_dma_free_chan_resources
  - drivers/dma/mxs-dma.c:mxs_dma_alloc_chan_resources
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
  - drivers/iommu/qcom_iommu.c:qcom_iommu_device_probe
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_free
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_free
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_init
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_free_erst
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
  - drivers/firmware/raspberrypi.c:rpi_firmware_property_list
  - drivers/firmware/qcom_scm.c:qcom_scm_assign_mem
  - drivers/firmware/qcom_scm.c:qcom_scm_pas_init_image
  - drivers/remoteproc/remoteproc_core.c:rproc_release_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
```
**Symbols:**

```
ffff800010193c80-ffff800010193d60: dma_free_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dma_free_attrs(struct device *dev, size_t size, void *cpu_addr, dma_addr_t dma_handle, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (c03e1004)
Location: kernel/dma/mapping.c:321
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dmam_release
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_msi_teardown
  - drivers/video/fbdev/amba-clcd.c:clcdfb_of_dma_remove
  - drivers/video/fbdev/mx3fb.c:mx3fb_unmap_video_memory
  - drivers/dma/mv_xor.c:mv_xor_probe
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mxs-dma.c:mxs_dma_free_chan_resources
  - drivers/dma/mxs-dma.c:mxs_dma_alloc_chan_resources
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
  - drivers/iommu/qcom_iommu.c:qcom_iommu_device_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_init
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_desc_pool_destroy
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_free_erst
  - drivers/mmc/host/sdhci.c:sdhci_remove_host
  - drivers/mmc/host/sdhci.c:sdhci_cleanup_host
  - drivers/mmc/host/sdhci.c:sdhci_setup_host
  - drivers/mmc/host/sdhci.c:sdhci_setup_host
  - drivers/firmware/qcom_scm.c:qcom_scm_assign_mem
  - drivers/firmware/qcom_scm.c:qcom_scm_pas_init_image
  - drivers/firmware/tegra/bpmp-debugfs.c:tegra_bpmp_init_debugfs
  - drivers/firmware/tegra/bpmp-debugfs.c:tegra_bpmp_init_debugfs
  - drivers/firmware/tegra/bpmp-debugfs.c:tegra_bpmp_init_debugfs
  - drivers/firmware/tegra/bpmp-debugfs.c:debugfs_store
  - drivers/firmware/tegra/bpmp-debugfs.c:debugfs_store
  - drivers/firmware/tegra/bpmp-debugfs.c:debugfs_store
  - drivers/firmware/tegra/bpmp-debugfs.c:debugfs_store
  - drivers/firmware/tegra/bpmp-debugfs.c:debugfs_store
  - drivers/firmware/tegra/bpmp-debugfs.c:debugfs_show
  - drivers/firmware/tegra/bpmp-debugfs.c:debugfs_show
  - drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_drv_remove
  - drivers/remoteproc/remoteproc_core.c:rproc_release_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
  - sound/soc/fsl/imx-pcm-fiq.c:imx_pcm_fiq_free
```
**Symbols:**

```
c03e1004-c03e10e4: dma_free_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dma_free_attrs(struct device *dev, size_t size, void *cpu_addr, dma_addr_t dma_handle, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (c0000000001f3f60)
Location: kernel/dma/mapping.c:321
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dmam_free_coherent
  - kernel/dma/mapping.c:dmam_release
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_free_erst
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
  - drivers/remoteproc/remoteproc_core.c:rproc_release_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
```
**Symbols:**

```
c0000000001f3f60-c0000000001f4064: dma_free_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dma_free_attrs(struct device *dev, size_t size, void *cpu_addr, dma_addr_t dma_handle, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffe000126004)
Location: kernel/dma/mapping.c:321
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dmam_release
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_free_erst
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
```
**Symbols:**

```
ffffffe000126004-ffffffe0001260e6: dma_free_attrs (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void dma_free_attrs(struct device *dev, size_t size, void *cpu_addr, dma_addr_t dma_handle, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81126ef0)
Location: kernel/dma/mapping.c:321
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dmam_release
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/nvme/host/pci.c:nvme_reset_work
  - drivers/nvme/host/pci.c:nvme_alloc_host_mem
  - drivers/nvme/host/pci.c:nvme_alloc_host_mem
  - drivers/nvme/host/pci.c:nvme_free_host_mem
  - drivers/nvme/host/pci.c:nvme_free_host_mem
  - drivers/nvme/host/pci.c:nvme_alloc_queue
  - drivers/nvme/host/pci.c:nvme_free_queue
  - drivers/nvme/host/pci.c:nvme_free_queue
  - drivers/nvme/host/pci.c:nvme_dbbuf_dma_free
  - drivers/nvme/host/pci.c:nvme_dbbuf_dma_free
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_free_erst
  - drivers/remoteproc/remoteproc_core.c:rproc_release_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
```
**Symbols:**

```
ffffffff81126ef0-ffffffff81126f3c: dma_free_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dma_free_attrs(struct device *dev, size_t size, void *cpu_addr, dma_addr_t dma_handle, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81119950)
Location: kernel/dma/mapping.c:321
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dmam_release
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/nvme/host/pci.c:nvme_reset_work
  - drivers/nvme/host/pci.c:nvme_alloc_host_mem
  - drivers/nvme/host/pci.c:nvme_alloc_host_mem
  - drivers/nvme/host/pci.c:nvme_free_host_mem
  - drivers/nvme/host/pci.c:nvme_free_host_mem
  - drivers/nvme/host/pci.c:nvme_alloc_queue
  - drivers/nvme/host/pci.c:nvme_free_queue
  - drivers/nvme/host/pci.c:nvme_free_queue
  - drivers/nvme/host/pci.c:nvme_dbbuf_dma_free
  - drivers/nvme/host/pci.c:nvme_dbbuf_dma_free
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_free_erst
```
**Symbols:**

```
ffffffff81119950-ffffffff8111999d: dma_free_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dma_free_attrs(struct device *dev, size_t size, void *cpu_addr, dma_addr_t dma_handle, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81124de0)
Location: kernel/dma/mapping.c:321
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dmam_release
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_free_erst
```
**Symbols:**

```
ffffffff81124de0-ffffffff81124e2c: dma_free_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dma_free_attrs(struct device *dev, size_t size, void *cpu_addr, dma_addr_t dma_handle, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81131420)
Location: kernel/dma/mapping.c:321
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dmam_release
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_free_erst
  - drivers/remoteproc/remoteproc_core.c:rproc_release_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
```
**Symbols:**

```
ffffffff81131420-ffffffff8113146c: dma_free_attrs (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
