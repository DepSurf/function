# Function: <code>dma_alloc_attrs</code>

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
In mm/dmapool.c (ffffffff811d9680)
Location: include/asm-generic/dma-mapping-common.h:245
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81509611)
Location: include/asm-generic/dma-mapping-common.h:245
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/virtio_console.c (ffffffff81516f5a)
Location: include/asm-generic/dma-mapping-common.h:245
Inline: True
```
```
In drivers/base/dma-mapping.c (ffffffff8155daaf)
Location: include/asm-generic/dma-mapping-common.h:245
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dmam_alloc_noncoherent
  - drivers/base/dma-mapping.c:dmam_alloc_coherent
```
```
In drivers/usb/core/buffer.c (ffffffff8161794b)
Location: include/asm-generic/dma-mapping-common.h:245
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8162a7b8)
Location: include/asm-generic/dma-mapping-common.h:245
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8162e63e)
Location: include/asm-generic/dma-mapping-common.h:245
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81637b2d)
Location: include/asm-generic/dma-mapping-common.h:245
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff816414d3)
Location: include/asm-generic/dma-mapping-common.h:245
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_init
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8164a154)
Location: include/asm-generic/dma-mapping-common.h:245
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81655214)
Location: include/asm-generic/dma-mapping-common.h:245
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
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
In mm/dmapool.c (ffffffff811f783c)
Location: include/linux/dma-mapping.h:404
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In drivers/virtio/virtio_ring.c (ffffffff8150f40e)
Location: include/linux/dma-mapping.h:404
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8155b5b4)
Location: include/linux/dma-mapping.h:404
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/virtio_console.c (ffffffff81569c0a)
Location: include/linux/dma-mapping.h:404
Inline: True
```
```
In drivers/base/dma-mapping.c (ffffffff815b1cf3)
Location: include/linux/dma-mapping.h:404
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dmam_alloc_noncoherent
  - drivers/base/dma-mapping.c:dmam_alloc_coherent
```
```
In drivers/usb/core/buffer.c (ffffffff81677a14)
Location: include/linux/dma-mapping.h:404
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8168a6f2)
Location: include/linux/dma-mapping.h:404
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8169883a)
Location: include/linux/dma-mapping.h:404
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff816a1ff9)
Location: include/linux/dma-mapping.h:404
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_init
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816aabb4)
Location: include/linux/dma-mapping.h:404
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816b6a0b)
Location: include/linux/dma-mapping.h:404
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
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
In mm/dmapool.c (ffffffff812081ec)
Location: include/linux/dma-mapping.h:456
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In drivers/virtio/virtio_ring.c (ffffffff8153b55e)
Location: include/linux/dma-mapping.h:456
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81587d5e)
Location: include/linux/dma-mapping.h:456
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/virtio_console.c (ffffffff8159649a)
Location: include/linux/dma-mapping.h:456
Inline: True
```
```
In drivers/base/dma-mapping.c (ffffffff815e11e3)
Location: include/linux/dma-mapping.h:456
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dmam_alloc_noncoherent
  - drivers/base/dma-mapping.c:dmam_alloc_coherent
```
```
In drivers/usb/core/buffer.c (ffffffff816a56f4)
Location: include/linux/dma-mapping.h:456
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
```
```
In drivers/usb/dwc2/hcd.c (ffffffff816b8827)
Location: include/linux/dma-mapping.h:456
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff816c6d6a)
Location: include/linux/dma-mapping.h:456
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff816d0c79)
Location: include/linux/dma-mapping.h:456
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_init
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816d8cf4)
Location: include/linux/dma-mapping.h:456
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816e4cdd)
Location: include/linux/dma-mapping.h:456
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
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
In mm/dmapool.c (ffffffff812138e0)
Location: include/linux/dma-mapping.h:499
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff814d2be8)
Location: include/linux/dma-mapping.h:499
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
```
```
In drivers/virtio/virtio_ring.c (ffffffff8154edbe)
Location: include/linux/dma-mapping.h:499
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8159c1e7)
Location: include/linux/dma-mapping.h:499
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/virtio_console.c (ffffffff815aa276)
Location: include/linux/dma-mapping.h:499
Inline: True
```
```
In drivers/base/dma-mapping.c (ffffffff815f5dae)
Location: include/linux/dma-mapping.h:499
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dmam_alloc_attrs
  - drivers/base/dma-mapping.c:dmam_alloc_coherent
```
```
In drivers/usb/core/buffer.c (ffffffff816baa81)
Location: include/linux/dma-mapping.h:499
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
```
```
In drivers/usb/dwc2/hcd.c (ffffffff816ccb84)
Location: include/linux/dma-mapping.h:499
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff816db53c)
Location: include/linux/dma-mapping.h:499
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff816e52bd)
Location: include/linux/dma-mapping.h:499
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_init
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816ed1b4)
Location: include/linux/dma-mapping.h:499
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816f8c33)
Location: include/linux/dma-mapping.h:499
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
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
In mm/dmapool.c (ffffffff8122e460)
Location: include/linux/dma-mapping.h:508
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff81512fe8)
Location: include/linux/dma-mapping.h:508
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
```
```
In drivers/virtio/virtio_ring.c (ffffffff815b255e)
Location: include/linux/dma-mapping.h:508
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816014ed)
Location: include/linux/dma-mapping.h:508
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/virtio_console.c (ffffffff81610bea)
Location: include/linux/dma-mapping.h:508
Inline: True
```
```
In drivers/base/dma-mapping.c (ffffffff8165dd6e)
Location: include/linux/dma-mapping.h:508
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dmam_alloc_attrs
  - drivers/base/dma-mapping.c:dmam_alloc_coherent
```
```
In drivers/usb/core/buffer.c (ffffffff81726441)
Location: include/linux/dma-mapping.h:508
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81739101)
Location: include/linux/dma-mapping.h:508
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81747c6c)
Location: include/linux/dma-mapping.h:508
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81751add)
Location: include/linux/dma-mapping.h:508
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_init
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81759998)
Location: include/linux/dma-mapping.h:508
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81765802)
Location: include/linux/dma-mapping.h:508
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_erst
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81772f48)
Location: include/linux/dma-mapping.h:508
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
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
In kernel/dma/mapping.c (ffffffff8110c7ae)
Location: include/linux/dma-mapping.h:508
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dmam_alloc_attrs
  - kernel/dma/mapping.c:dmam_alloc_coherent
```
```
In mm/dmapool.c (ffffffff812512a4)
Location: include/linux/dma-mapping.h:508
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff81548398)
Location: include/linux/dma-mapping.h:508
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
```
```
In drivers/virtio/virtio_ring.c (ffffffff815ea961)
Location: include/linux/dma-mapping.h:508
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8163a783)
Location: include/linux/dma-mapping.h:508
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/virtio_console.c (ffffffff8164a7a1)
Location: include/linux/dma-mapping.h:508
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:alloc_buf
```
```
In drivers/usb/core/buffer.c (ffffffff81765218)
Location: include/linux/dma-mapping.h:508
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8177919b)
Location: include/linux/dma-mapping.h:508
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81788458)
Location: include/linux/dma-mapping.h:508
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff817915af)
Location: include/linux/dma-mapping.h:508
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_init
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81799f44)
Location: include/linux/dma-mapping.h:508
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817a5b49)
Location: include/linux/dma-mapping.h:508
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_erst
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817b34f1)
Location: include/linux/dma-mapping.h:508
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
```
In drivers/i2c/busses/i2c-amd-platdrv.c (ffffffff817dd53e)
Location: include/linux/dma-mapping.h:508
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
void *dma_alloc_attrs(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t flag, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81117dc0)
Location: kernel/dma/mapping.c:247
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dmam_alloc_attrs
  - mm/dmapool.c:dma_pool_alloc
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/char/virtio_console.c:alloc_buf
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_erst
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
**Symbols:**

```
ffffffff81117dc0-ffffffff81117e8a: dma_alloc_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *dma_alloc_attrs(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t flag, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81122120)
Location: kernel/dma/mapping.c:267
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dmam_alloc_attrs
  - mm/dmapool.c:dma_pool_alloc
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/char/virtio_console.c:alloc_buf
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_erst
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
**Symbols:**

```
ffffffff81122120-ffffffff811221ec: dma_alloc_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *dma_alloc_attrs(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t flag, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8112e800)
Location: kernel/dma/mapping.c:295
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dmam_alloc_attrs
  - mm/dmapool.c:dma_pool_alloc
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/char/virtio_console.c:alloc_buf
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_erst
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
```
**Symbols:**

```
ffffffff8112e800-ffffffff8112e853: dma_alloc_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *dma_alloc_attrs(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t flag, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8113d190)
Location: kernel/dma/mapping.c:266
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dmam_alloc_attrs
  - mm/dmapool.c:pool_alloc_page
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/char/virtio_console.c:alloc_buf
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_erst
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
```
**Symbols:**

```
ffffffff8113d190-ffffffff8113d1e3: dma_alloc_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *dma_alloc_attrs(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t flag, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81137880)
Location: kernel/dma/mapping.c:425
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dmam_alloc_attrs
  - mm/dmapool.c:pool_alloc_page
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/char/virtio_console.c:alloc_buf
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_erst
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
```
**Symbols:**

```
ffffffff81137880-ffffffff811378cf: dma_alloc_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *dma_alloc_attrs(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t flag, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81138670)
Location: kernel/dma/mapping.c:427
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dmam_alloc_attrs
  - mm/dmapool.c:dma_pool_alloc
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/char/virtio_console.c:alloc_buf
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_erst
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
```
**Symbols:**

```
ffffffff81138670-ffffffff811386bf: dma_alloc_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *dma_alloc_attrs(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t flag, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8115b4c0)
Location: kernel/dma/mapping.c:492
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dmam_alloc_attrs
  - mm/dmapool.c:dma_pool_alloc
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/char/virtio_console.c:alloc_buf
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_erst
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
```
**Symbols:**

```
ffffffff8115b4c0-ffffffff8115b50f: dma_alloc_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *dma_alloc_attrs(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t flag, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81184ec0)
Location: kernel/dma/mapping.c:486
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dmam_alloc_attrs
  - mm/dmapool.c:dma_pool_alloc
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/char/virtio_console.c:alloc_buf
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_erst
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
```
**Symbols:**

```
ffffffff81184ec0-ffffffff81184f37: dma_alloc_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *dma_alloc_attrs(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t flag, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811c05e0)
Location: kernel/dma/mapping.c:493
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dmam_alloc_attrs
  - mm/dmapool.c:dma_pool_alloc
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/char/virtio_console.c:alloc_buf
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_erst
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
```
**Symbols:**

```
ffffffff811c05e0-ffffffff811c0693: dma_alloc_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *dma_alloc_attrs(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t flag, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811d30c0)
Location: kernel/dma/mapping.c:497
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dmam_alloc_attrs
  - mm/dmapool.c:dma_pool_alloc
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/char/virtio_console.c:alloc_buf
  - drivers/usb/core/buffer.c:hcd_buffer_alloc_pages
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_erst
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
```
**Symbols:**

```
ffffffff811d30c0-ffffffff811d318c: dma_alloc_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *dma_alloc_attrs(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t flag, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811e7d40)
Location: kernel/dma/mapping.c:497
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dmam_alloc_attrs
  - mm/dmapool.c:dma_pool_alloc
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/char/virtio_console.c:alloc_buf
  - drivers/usb/core/buffer.c:hcd_buffer_alloc_pages
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_interrupter
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
```
**Symbols:**

```
ffffffff811e7d40-ffffffff811e7e0c: dma_alloc_attrs (STB_GLOBAL)
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
void *dma_alloc_attrs(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t flag, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffff800010193ad8)
Location: kernel/dma/mapping.c:295
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dmam_alloc_attrs
  - mm/dmapool.c:dma_pool_alloc
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_init
  - drivers/video/fbdev/mx3fb.c:__set_par
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_probe
  - drivers/dma/mxs-dma.c:mxs_dma_alloc_chan_resources
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/char/virtio_console.c:alloc_buf
  - drivers/iommu/qcom_iommu.c:qcom_iommu_device_probe
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_enet_probe
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_enet_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_init
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_erst
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/firmware/raspberrypi.c:rpi_firmware_property_list
  - drivers/firmware/qcom_scm.c:qcom_scm_assign_mem
  - drivers/firmware/qcom_scm.c:qcom_scm_pas_init_image
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
```
**Symbols:**

```
ffff800010193ad8-ffff800010193bc4: dma_alloc_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *dma_alloc_attrs(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t flag, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (c03e0e2c)
Location: kernel/dma/mapping.c:295
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dmam_alloc_attrs
  - mm/dmapool.c:dma_pool_alloc
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_probe
  - drivers/video/fbdev/mx3fb.c:__set_par
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mxs-dma.c:mxs_dma_alloc_chan_resources
  - drivers/soc/tegra/fuse/fuse-tegra20.c:tegra20_fuse_probe
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/char/virtio_console.c:alloc_buf
  - drivers/iommu/qcom_iommu.c:qcom_iommu_device_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_init
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_ctlr_create
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_erst
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/mmc/host/sdhci.c:sdhci_setup_host
  - drivers/firmware/qcom_scm.c:qcom_scm_assign_mem
  - drivers/firmware/qcom_scm.c:qcom_scm_pas_init_image
  - drivers/firmware/tegra/bpmp-debugfs.c:tegra_bpmp_init_debugfs
  - drivers/firmware/tegra/bpmp-debugfs.c:debugfs_store
  - drivers/firmware/tegra/bpmp-debugfs.c:debugfs_store
  - drivers/firmware/tegra/bpmp-debugfs.c:debugfs_show
  - drivers/firmware/tegra/bpmp-debugfs.c:debugfs_show
  - drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_ep_queue
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
  - sound/core/memalloc.c:snd_dma_alloc_pages
  - sound/soc/fsl/imx-pcm-fiq.c:imx_pcm_preallocate_dma_buffer
```
**Symbols:**

```
c03e0e2c-c03e0f58: dma_alloc_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *dma_alloc_attrs(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t flag, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (c0000000001f3d30)
Location: kernel/dma/mapping.c:295
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dmam_alloc_attrs
  - mm/dmapool.c:dma_pool_alloc
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/char/virtio_console.c:alloc_buf
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_erst
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
```
**Symbols:**

```
c0000000001f3d30-c0000000001f3e54: dma_alloc_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *dma_alloc_attrs(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t flag, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffe000125ed4)
Location: kernel/dma/mapping.c:295
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dmam_alloc_attrs
  - mm/dmapool.c:dma_pool_alloc
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_erst
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
**Symbols:**

```
ffffffe000125ed4-ffffffe000125f66: dma_alloc_attrs (STB_GLOBAL)
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
void *dma_alloc_attrs(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t flag, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81126de0)
Location: kernel/dma/mapping.c:295
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dmam_alloc_attrs
  - mm/dmapool.c:dma_pool_alloc
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/char/virtio_console.c:alloc_buf
  - drivers/nvme/host/pci.c:nvme_reset_work
  - drivers/nvme/host/pci.c:nvme_reset_work
  - drivers/nvme/host/pci.c:nvme_alloc_host_mem
  - drivers/nvme/host/pci.c:nvme_alloc_host_mem
  - drivers/nvme/host/pci.c:nvme_alloc_queue
  - drivers/nvme/host/pci.c:nvme_alloc_queue
  - drivers/nvme/host/pci.c:nvme_alloc_queue
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_erst
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
```
**Symbols:**

```
ffffffff81126de0-ffffffff81126e33: dma_alloc_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *dma_alloc_attrs(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t flag, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81119840)
Location: kernel/dma/mapping.c:295
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dmam_alloc_attrs
  - mm/dmapool.c:dma_pool_alloc
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/nvme/host/pci.c:nvme_reset_work
  - drivers/nvme/host/pci.c:nvme_reset_work
  - drivers/nvme/host/pci.c:nvme_alloc_host_mem
  - drivers/nvme/host/pci.c:nvme_alloc_host_mem
  - drivers/nvme/host/pci.c:nvme_alloc_queue
  - drivers/nvme/host/pci.c:nvme_alloc_queue
  - drivers/nvme/host/pci.c:nvme_alloc_queue
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_erst
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
**Symbols:**

```
ffffffff81119840-ffffffff81119893: dma_alloc_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *dma_alloc_attrs(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t flag, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81124cd0)
Location: kernel/dma/mapping.c:295
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dmam_alloc_attrs
  - mm/dmapool.c:dma_pool_alloc
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_erst
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
**Symbols:**

```
ffffffff81124cd0-ffffffff81124d23: dma_alloc_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *dma_alloc_attrs(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t flag, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81131310)
Location: kernel/dma/mapping.c:295
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dmam_alloc_attrs
  - mm/dmapool.c:dma_pool_alloc
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/char/virtio_console.c:alloc_buf
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_erst
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
```
**Symbols:**

```
ffffffff81131310-ffffffff81131363: dma_alloc_attrs (STB_GLOBAL)
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
