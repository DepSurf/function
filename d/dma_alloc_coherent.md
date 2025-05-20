# Function: <code>dma_alloc_coherent</code>

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
Location: include/asm-generic/dma-mapping-common.h:286
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81509611)
Location: include/asm-generic/dma-mapping-common.h:286
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/virtio_console.c (ffffffff81516f5a)
Location: include/asm-generic/dma-mapping-common.h:286
Inline: True
```
```
In drivers/base/dma-mapping.c (ffffffff8155dcb2)
Location: include/asm-generic/dma-mapping-common.h:286
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dmam_alloc_coherent
```
```
In drivers/usb/core/buffer.c (ffffffff8161794b)
Location: include/asm-generic/dma-mapping-common.h:286
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8162a7b8)
Location: include/asm-generic/dma-mapping-common.h:286
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8162e63e)
Location: include/asm-generic/dma-mapping-common.h:286
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81637b2d)
Location: include/asm-generic/dma-mapping-common.h:286
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff816414d3)
Location: include/asm-generic/dma-mapping-common.h:286
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_init
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8164a154)
Location: include/asm-generic/dma-mapping-common.h:286
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81655214)
Location: include/asm-generic/dma-mapping-common.h:286
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
Location: include/linux/dma-mapping.h:445
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In drivers/virtio/virtio_ring.c (ffffffff8150f40e)
Location: include/linux/dma-mapping.h:445
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8155b5b4)
Location: include/linux/dma-mapping.h:445
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/virtio_console.c (ffffffff81569c0a)
Location: include/linux/dma-mapping.h:445
Inline: True
```
```
In drivers/base/dma-mapping.c (ffffffff815b1ef3)
Location: include/linux/dma-mapping.h:445
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dmam_alloc_coherent
```
```
In drivers/usb/core/buffer.c (ffffffff81677a14)
Location: include/linux/dma-mapping.h:445
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8168a6f2)
Location: include/linux/dma-mapping.h:445
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8169883a)
Location: include/linux/dma-mapping.h:445
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff816a1ff9)
Location: include/linux/dma-mapping.h:445
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_init
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816aabb4)
Location: include/linux/dma-mapping.h:445
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816b6a0b)
Location: include/linux/dma-mapping.h:445
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
Location: include/linux/dma-mapping.h:497
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In drivers/virtio/virtio_ring.c (ffffffff8153b55e)
Location: include/linux/dma-mapping.h:497
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81587d5e)
Location: include/linux/dma-mapping.h:497
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/virtio_console.c (ffffffff8159649a)
Location: include/linux/dma-mapping.h:497
Inline: True
```
```
In drivers/base/dma-mapping.c (ffffffff815e0f43)
Location: include/linux/dma-mapping.h:497
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dmam_alloc_coherent
```
```
In drivers/usb/core/buffer.c (ffffffff816a56f4)
Location: include/linux/dma-mapping.h:497
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
```
```
In drivers/usb/dwc2/hcd.c (ffffffff816b8827)
Location: include/linux/dma-mapping.h:497
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff816c6d6a)
Location: include/linux/dma-mapping.h:497
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff816d0c79)
Location: include/linux/dma-mapping.h:497
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_init
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816d8cf4)
Location: include/linux/dma-mapping.h:497
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816e4cdd)
Location: include/linux/dma-mapping.h:497
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
Location: include/linux/dma-mapping.h:540
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff814d2be8)
Location: include/linux/dma-mapping.h:540
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
```
```
In drivers/virtio/virtio_ring.c (ffffffff8154edbe)
Location: include/linux/dma-mapping.h:540
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8159c1e7)
Location: include/linux/dma-mapping.h:540
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/virtio_console.c (ffffffff815aa276)
Location: include/linux/dma-mapping.h:540
Inline: True
```
```
In drivers/base/dma-mapping.c (ffffffff815f6033)
Location: include/linux/dma-mapping.h:540
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dmam_alloc_coherent
```
```
In drivers/usb/core/buffer.c (ffffffff816baa81)
Location: include/linux/dma-mapping.h:540
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
```
```
In drivers/usb/dwc2/hcd.c (ffffffff816ccb84)
Location: include/linux/dma-mapping.h:540
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff816db53c)
Location: include/linux/dma-mapping.h:540
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff816e52bd)
Location: include/linux/dma-mapping.h:540
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_init
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816ed1b4)
Location: include/linux/dma-mapping.h:540
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816f8c33)
Location: include/linux/dma-mapping.h:540
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
Location: include/linux/dma-mapping.h:549
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff81512fe8)
Location: include/linux/dma-mapping.h:549
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
```
```
In drivers/virtio/virtio_ring.c (ffffffff815b255e)
Location: include/linux/dma-mapping.h:549
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816014ed)
Location: include/linux/dma-mapping.h:549
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/virtio_console.c (ffffffff81610bea)
Location: include/linux/dma-mapping.h:549
Inline: True
```
```
In drivers/base/dma-mapping.c (ffffffff8165df53)
Location: include/linux/dma-mapping.h:549
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dmam_alloc_coherent
```
```
In drivers/usb/core/buffer.c (ffffffff81726441)
Location: include/linux/dma-mapping.h:549
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81739101)
Location: include/linux/dma-mapping.h:549
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81747c6c)
Location: include/linux/dma-mapping.h:549
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81751add)
Location: include/linux/dma-mapping.h:549
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_init
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81759998)
Location: include/linux/dma-mapping.h:549
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81765802)
Location: include/linux/dma-mapping.h:549
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
Location: include/linux/dma-mapping.h:549
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
In kernel/dma/mapping.c (ffffffff8110c9c6)
Location: include/linux/dma-mapping.h:553
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dmam_alloc_coherent
```
```
In mm/dmapool.c (ffffffff8125129c)
Location: include/linux/dma-mapping.h:553
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff81548394)
Location: include/linux/dma-mapping.h:553
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
```
```
In drivers/virtio/virtio_ring.c (ffffffff815ea95d)
Location: include/linux/dma-mapping.h:553
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8163a77f)
Location: include/linux/dma-mapping.h:553
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/virtio_console.c (ffffffff8164a79d)
Location: include/linux/dma-mapping.h:553
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:alloc_buf
```
```
In drivers/usb/core/buffer.c (ffffffff81765214)
Location: include/linux/dma-mapping.h:553
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81779197)
Location: include/linux/dma-mapping.h:553
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81788454)
Location: include/linux/dma-mapping.h:553
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff817915ab)
Location: include/linux/dma-mapping.h:553
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_init
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81799f40)
Location: include/linux/dma-mapping.h:553
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817a5b45)
Location: include/linux/dma-mapping.h:553
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_erst
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817b34ed)
Location: include/linux/dma-mapping.h:553
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
```
In drivers/i2c/busses/i2c-amd-platdrv.c (ffffffff817dd53a)
Location: include/linux/dma-mapping.h:553
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-amd-platdrv.c:i2c_amd_xfer
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
In mm/dmapool.c (ffffffff812656ba)
Location: include/linux/dma-mapping.h:633
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff8155e596)
Location: include/linux/dma-mapping.h:633
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
```
```
In drivers/virtio/virtio_ring.c (ffffffff81604df5)
Location: include/linux/dma-mapping.h:633
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff8160cc24)
Location: include/linux/dma-mapping.h:633
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81658a8e)
Location: include/linux/dma-mapping.h:633
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/virtio_console.c (ffffffff81668965)
Location: include/linux/dma-mapping.h:633
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:alloc_buf
```
```
In drivers/usb/core/buffer.c (ffffffff8178985f)
Location: include/linux/dma-mapping.h:633
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8179efd5)
Location: include/linux/dma-mapping.h:633
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817b1627)
Location: include/linux/dma-mapping.h:633
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff817b7d1c)
Location: include/linux/dma-mapping.h:633
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_init
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817c03c8)
Location: include/linux/dma-mapping.h:633
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817cbc36)
Location: include/linux/dma-mapping.h:633
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_erst
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817d9aa4)
Location: include/linux/dma-mapping.h:633
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
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
In mm/dmapool.c (ffffffff8128062c)
Location: include/linux/dma-mapping.h:636
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff8158e9d8)
Location: include/linux/dma-mapping.h:636
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
```
```
In drivers/virtio/virtio_ring.c (ffffffff81637735)
Location: include/linux/dma-mapping.h:636
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff816418c6)
Location: include/linux/dma-mapping.h:636
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8168df6e)
Location: include/linux/dma-mapping.h:636
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/virtio_console.c (ffffffff8169f64f)
Location: include/linux/dma-mapping.h:636
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:alloc_buf
```
```
In drivers/usb/core/buffer.c (ffffffff817c7cc1)
Location: include/linux/dma-mapping.h:636
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
```
```
In drivers/usb/dwc2/hcd.c (ffffffff817ddb78)
Location: include/linux/dma-mapping.h:636
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817f1e6f)
Location: include/linux/dma-mapping.h:636
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff817f6712)
Location: include/linux/dma-mapping.h:636
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_init
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817ff87c)
Location: include/linux/dma-mapping.h:636
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8180c006)
Location: include/linux/dma-mapping.h:636
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_erst
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8181a397)
Location: include/linux/dma-mapping.h:636
Inline: True
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
In mm/dmapool.c (ffffffff8129005c)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff815b05f8)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
```
```
In drivers/virtio/virtio_ring.c (ffffffff81659515)
Location: include/linux/dma-mapping.h:641
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff81662ed6)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816b04be)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/virtio_console.c (ffffffff816c23df)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:alloc_buf
```
```
In drivers/usb/core/buffer.c (ffffffff817f87e8)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8180ea9b)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81822d5f)
Location: include/linux/dma-mapping.h:641
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81827572)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_init
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff818306dc)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8183d006)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_erst
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8184b732)
Location: include/linux/dma-mapping.h:641
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff818f3ba3)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
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
In mm/dmapool.c (ffffffff812c2be1)
Location: include/linux/dma-mapping.h:727
Inline: True
Inline callers:
  - mm/dmapool.c:pool_alloc_page
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff81659913)
Location: include/linux/dma-mapping.h:727
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
```
```
In drivers/virtio/virtio_ring.c (ffffffff8170a390)
Location: include/linux/dma-mapping.h:727
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff81713406)
Location: include/linux/dma-mapping.h:727
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8176399f)
Location: include/linux/dma-mapping.h:727
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/virtio_console.c (ffffffff81774b6f)
Location: include/linux/dma-mapping.h:727
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:alloc_buf
```
```
In drivers/usb/core/buffer.c (ffffffff818c8930)
Location: include/linux/dma-mapping.h:727
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818df73b)
Location: include/linux/dma-mapping.h:727
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818ee06f)
Location: include/linux/dma-mapping.h:727
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff818fa275)
Location: include/linux/dma-mapping.h:727
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_init
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81901a0a)
Location: include/linux/dma-mapping.h:727
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8190fab4)
Location: include/linux/dma-mapping.h:727
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_erst
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8191e172)
Location: include/linux/dma-mapping.h:727
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819ca393)
Location: include/linux/dma-mapping.h:727
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
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
In mm/dmapool.c (ffffffff812ce9b1)
Location: include/linux/dma-mapping.h:392
Inline: True
Inline callers:
  - mm/dmapool.c:pool_alloc_page
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff81679cf3)
Location: include/linux/dma-mapping.h:392
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
```
```
In drivers/virtio/virtio_ring.c (ffffffff817278c0)
Location: include/linux/dma-mapping.h:392
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff817302f6)
Location: include/linux/dma-mapping.h:392
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8177e9a5)
Location: include/linux/dma-mapping.h:392
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/virtio_console.c (ffffffff8178f8e8)
Location: include/linux/dma-mapping.h:392
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:alloc_buf
```
```
In drivers/usb/core/buffer.c (ffffffff818d3a80)
Location: include/linux/dma-mapping.h:392
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818e959b)
Location: include/linux/dma-mapping.h:392
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818f6f8f)
Location: include/linux/dma-mapping.h:392
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81902db5)
Location: include/linux/dma-mapping.h:392
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_init
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8190a2d6)
Location: include/linux/dma-mapping.h:392
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81917614)
Location: include/linux/dma-mapping.h:392
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_erst
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff819255c7)
Location: include/linux/dma-mapping.h:392
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819c9813)
Location: include/linux/dma-mapping.h:392
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
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
In mm/dmapool.c (ffffffff812d5773)
Location: include/linux/dma-mapping.h:435
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff8165c851)
Location: include/linux/dma-mapping.h:435
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
```
```
In drivers/virtio/virtio_ring.c (ffffffff8170b400)
Location: include/linux/dma-mapping.h:435
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff81713e96)
Location: include/linux/dma-mapping.h:435
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff817622f5)
Location: include/linux/dma-mapping.h:435
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/virtio_console.c (ffffffff8177245b)
Location: include/linux/dma-mapping.h:435
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:alloc_buf
```
```
In drivers/usb/core/buffer.c (ffffffff818b6fe3)
Location: include/linux/dma-mapping.h:435
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818cb07d)
Location: include/linux/dma-mapping.h:435
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818da57f)
Location: include/linux/dma-mapping.h:435
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff818e5f05)
Location: include/linux/dma-mapping.h:435
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_init
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff818ee87f)
Location: include/linux/dma-mapping.h:435
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffff818faaa5)
Location: include/linux/dma-mapping.h:435
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_erst
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81908cc7)
Location: include/linux/dma-mapping.h:435
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819ae823)
Location: include/linux/dma-mapping.h:435
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
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
In mm/dmapool.c (ffffffff8131b599)
Location: include/linux/dma-mapping.h:415
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff816cef42)
Location: include/linux/dma-mapping.h:415
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
```
```
In drivers/virtio/virtio_ring.c (ffffffff81787480)
Location: include/linux/dma-mapping.h:415
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff817908d2)
Location: include/linux/dma-mapping.h:415
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff817e63ae)
Location: include/linux/dma-mapping.h:415
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/virtio_console.c (ffffffff817f852b)
Location: include/linux/dma-mapping.h:415
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:alloc_buf
```
```
In drivers/usb/core/buffer.c (ffffffff8194cac3)
Location: include/linux/dma-mapping.h:415
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81964370)
Location: include/linux/dma-mapping.h:415
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8197592f)
Location: include/linux/dma-mapping.h:415
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff819822c0)
Location: include/linux/dma-mapping.h:415
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_init
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8198b05f)
Location: include/linux/dma-mapping.h:415
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8199985c)
Location: include/linux/dma-mapping.h:415
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_erst
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff819a9547)
Location: include/linux/dma-mapping.h:415
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81a5cdf3)
Location: include/linux/dma-mapping.h:415
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
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
In mm/dmapool.c (ffffffff81386da4)
Location: include/linux/dma-mapping.h:415
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff817f7bdc)
Location: include/linux/dma-mapping.h:415
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
```
```
In drivers/virtio/virtio_ring.c (ffffffff818be5fd)
Location: include/linux/dma-mapping.h:415
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff818c97b3)
Location: include/linux/dma-mapping.h:415
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81925947)
Location: include/linux/dma-mapping.h:415
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/virtio_console.c (ffffffff81936e6a)
Location: include/linux/dma-mapping.h:415
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:alloc_buf
```
```
In drivers/usb/core/buffer.c (ffffffff81aa5647)
Location: include/linux/dma-mapping.h:415
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81abe86c)
Location: include/linux/dma-mapping.h:415
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81ad13b6)
Location: include/linux/dma-mapping.h:415
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81adf2d6)
Location: include/linux/dma-mapping.h:415
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_init
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81ae6917)
Location: include/linux/dma-mapping.h:415
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81af6854)
Location: include/linux/dma-mapping.h:415
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_erst
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81b0760f)
Location: include/linux/dma-mapping.h:415
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81bcce8b)
Location: include/linux/dma-mapping.h:415
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
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
In mm/dmapool.c (ffffffff81404c72)
Location: include/linux/dma-mapping.h:420
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff819236ec)
Location: include/linux/dma-mapping.h:420
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
```
```
In drivers/virtio/virtio_ring.c (ffffffff81a0d77d)
Location: include/linux/dma-mapping.h:420
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff81a1a696)
Location: include/linux/dma-mapping.h:420
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81a82377)
Location: include/linux/dma-mapping.h:420
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/virtio_console.c (ffffffff81a96d2a)
Location: include/linux/dma-mapping.h:420
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:alloc_buf
```
```
In drivers/usb/core/buffer.c (ffffffff81c2c0a7)
Location: include/linux/dma-mapping.h:420
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81c47fd3)
Location: include/linux/dma-mapping.h:420
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81c5bbf6)
Location: include/linux/dma-mapping.h:420
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81c6a832)
Location: include/linux/dma-mapping.h:420
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_init
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81c726cc)
Location: include/linux/dma-mapping.h:420
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81c841ed)
Location: include/linux/dma-mapping.h:420
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_erst
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81c96edf)
Location: include/linux/dma-mapping.h:420
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81d7768b)
Location: include/linux/dma-mapping.h:420
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
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
In mm/dmapool.c (ffffffff814381d9)
Location: include/linux/dma-mapping.h:421
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff819672fc)
Location: include/linux/dma-mapping.h:421
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
```
```
In drivers/virtio/virtio_ring.c (ffffffff81a566c3)
Location: include/linux/dma-mapping.h:421
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff81a63516)
Location: include/linux/dma-mapping.h:421
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81acd977)
Location: include/linux/dma-mapping.h:421
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/virtio_console.c (ffffffff81ae2538)
Location: include/linux/dma-mapping.h:421
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:alloc_buf
```
```
In drivers/usb/core/buffer.c (ffffffff81c93283)
Location: include/linux/dma-mapping.h:421
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_alloc_pages
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81caf5b3)
Location: include/linux/dma-mapping.h:421
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81cc34a6)
Location: include/linux/dma-mapping.h:421
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81cd1c1c)
Location: include/linux/dma-mapping.h:421
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_init
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81cd9cbc)
Location: include/linux/dma-mapping.h:421
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81ceaeed)
Location: include/linux/dma-mapping.h:421
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_erst
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81cfe1ef)
Location: include/linux/dma-mapping.h:421
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81de55db)
Location: include/linux/dma-mapping.h:421
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
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
In mm/dmapool.c (ffffffff81471b55)
Location: include/linux/dma-mapping.h:428
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff819b0a2c)
Location: include/linux/dma-mapping.h:428
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
```
```
In drivers/virtio/virtio_ring.c (ffffffff81aa77e3)
Location: include/linux/dma-mapping.h:428
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff81ab5d36)
Location: include/linux/dma-mapping.h:428
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81b20a47)
Location: include/linux/dma-mapping.h:428
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/virtio_console.c (ffffffff81b35928)
Location: include/linux/dma-mapping.h:428
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:alloc_buf
```
```
In drivers/usb/core/buffer.c (ffffffff81d47d33)
Location: include/linux/dma-mapping.h:428
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_alloc_pages
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81d64297)
Location: include/linux/dma-mapping.h:428
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81d783a6)
Location: include/linux/dma-mapping.h:428
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81d86bdc)
Location: include/linux/dma-mapping.h:428
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_init
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81d8eccc)
Location: include/linux/dma-mapping.h:428
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81da06bb)
Location: include/linux/dma-mapping.h:428
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_interrupter
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81db3b2d)
Location: include/linux/dma-mapping.h:428
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81e9b9ab)
Location: include/linux/dma-mapping.h:428
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
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
In mm/dmapool.c (ffff80001032d414)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffff80001071c57c)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
```
```
In drivers/pci/controller/pcie-iproc-msi.c (ffff80001072619c)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_init
```
```
In drivers/video/fbdev/amba-clcd.c (ffff80001075bfa4)
Location: include/linux/dma-mapping.h:641
Inline: True
```
```
In drivers/dma/mv_xor_v2.c (ffff80001080916c)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_probe
```
```
In drivers/dma/mxs-dma.c (ffff800010809f00)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/dma/mxs-dma.c:mxs_dma_alloc_chan_resources
```
```
In drivers/virtio/virtio_ring.c (ffff800010821d28)
Location: include/linux/dma-mapping.h:641
Inline: True
```
```
In drivers/xen/grant-table.c (ffff80001082cc68)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/tty/serial/8250/8250_dma.c (ffff80001088ba84)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/tty/serial/amba-pl011.c (ffff800010894aa8)
Location: include/linux/dma-mapping.h:641
Inline: True
```
```
In drivers/char/virtio_console.c (ffff8000108b4618)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:alloc_buf
```
```
In drivers/net/ethernet/broadcom/bgmac.c (ffff8000109e4370)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_enet_probe
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_enet_probe
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e9154)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_init
```
```
In drivers/usb/core/buffer.c (ffff800010a29530)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
```
```
In drivers/usb/dwc2/hcd.c (ffff800010a4752c)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-hcd.c (ffff800010a54ed4)
Location: include/linux/dma-mapping.h:641
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (ffff800010a62510)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_init
```
```
In drivers/usb/host/uhci-hcd.c (ffff800010a6b5f8)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffff800010a7ae18)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_erst
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
```
In drivers/usb/host/xhci-dbgcap.c (ffff800010a8aae8)
Location: include/linux/dma-mapping.h:641
Inline: True
```
```
In drivers/firmware/raspberrypi.c (ffff800010b4e5b4)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/firmware/raspberrypi.c:rpi_firmware_property_list
```
```
In drivers/firmware/qcom_scm.c (ffff800010b4ede0)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/firmware/qcom_scm.c:qcom_scm_assign_mem
  - drivers/firmware/qcom_scm.c:qcom_scm_pas_init_image
```
```
In drivers/remoteproc/remoteproc_core.c (ffff800010b7f940)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
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
In mm/dmapool.c (c0542f1c)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In drivers/pci/endpoint/pci-epf-core.c (c08a585c)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
```
```
In drivers/video/fbdev/amba-clcd.c (c08ded50)
Location: include/linux/dma-mapping.h:641
Inline: True
```
```
In drivers/dma/mxs-dma.c (c0926cd0)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/dma/mxs-dma.c:mxs_dma_alloc_chan_resources
```
```
In drivers/soc/tegra/fuse/fuse-tegra20.c (c093a9bc)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/soc/tegra/fuse/fuse-tegra20.c:tegra20_fuse_probe
```
```
In drivers/virtio/virtio_ring.c (c093f864)
Location: include/linux/dma-mapping.h:641
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (c09893a0)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/tty/serial/amba-pl011.c (c0990a40)
Location: include/linux/dma-mapping.h:641
Inline: True
```
```
In drivers/char/virtio_console.c (c09af2b8)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:alloc_buf
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0aca388)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_init
```
```
In drivers/net/ethernet/ti/davinci_cpdma.c (c0ad7820)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_ctlr_create
```
```
In drivers/usb/core/buffer.c (c0aff4d4)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
```
```
In drivers/usb/dwc2/hcd.c (c0b19df8)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-hcd.c (c0b2ebd0)
Location: include/linux/dma-mapping.h:641
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (c0b355dc)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_init
```
```
In drivers/usb/host/uhci-hcd.c (c0b3e570)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (c0b4e718)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_erst
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
```
In drivers/usb/host/xhci-dbgcap.c (c0b5d7b8)
Location: include/linux/dma-mapping.h:641
Inline: True
```
```
In drivers/mmc/host/sdhci.c (c0c24a6c)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci.c:sdhci_setup_host
```
```
In drivers/firmware/qcom_scm.c (c0c356a8)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/firmware/qcom_scm.c:qcom_scm_assign_mem
  - drivers/firmware/qcom_scm.c:qcom_scm_pas_init_image
```
```
In drivers/firmware/tegra/bpmp.c (c0c421c8)
Location: include/linux/dma-mapping.h:641
Inline: True
```
```
In drivers/firmware/tegra/bpmp-debugfs.c (c0c42ffc)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/firmware/tegra/bpmp-debugfs.c:tegra_bpmp_init_debugfs
  - drivers/firmware/tegra/bpmp-debugfs.c:debugfs_store
  - drivers/firmware/tegra/bpmp-debugfs.c:debugfs_store
  - drivers/firmware/tegra/bpmp-debugfs.c:debugfs_show
  - drivers/firmware/tegra/bpmp-debugfs.c:debugfs_show
```
```
In drivers/staging/emxx_udc/emxx_udc.c (c0c5d34c)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_ep_queue
```
```
In drivers/remoteproc/remoteproc_core.c (c0c630c0)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
```
```
In sound/core/memalloc.c (c0c9bd5c)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - sound/core/memalloc.c:snd_dma_alloc_pages
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
In mm/dmapool.c (c000000000404a68)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In drivers/pci/endpoint/pci-epf-core.c (c00000000088cad0)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
```
```
In drivers/virtio/virtio_ring.c (c0000000008cb920)
Location: include/linux/dma-mapping.h:641
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (c000000000934390)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/virtio_console.c (c00000000094e714)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:alloc_buf
```
```
In drivers/usb/core/buffer.c (c000000000ae5a64)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
```
```
In drivers/usb/dwc2/hcd.c (c000000000b0bff4)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-hcd.c (c000000000b28e7c)
Location: include/linux/dma-mapping.h:641
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (c000000000b32080)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_init
```
```
In drivers/usb/host/uhci-hcd.c (c000000000b3ce20)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (c000000000b52ab8)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_erst
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
```
In drivers/usb/host/xhci-dbgcap.c (c000000000b663a4)
Location: include/linux/dma-mapping.h:641
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (c000000000c5c3d8)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
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
In mm/dmapool.c (ffffffe00022b7ca)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffe0004e323c)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
```
```
In drivers/virtio/virtio_ring.c (ffffffe0005188c6)
Location: include/linux/dma-mapping.h:641
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffe00055541e)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/dma-mapping.h:641
Inline: True
```
```
In drivers/usb/core/buffer.c (ffffffe00064af44)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
```
```
In drivers/usb/dwc2/hcd.c (ffffffe000663fbe)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-hcd.c (ffffffe00067470c)
Location: include/linux/dma-mapping.h:641
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (ffffffe00067d766)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_init
```
```
In drivers/usb/host/uhci-hcd.c (ffffffe00068580a)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffe000692444)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_erst
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffe00069ff96)
Location: include/linux/dma-mapping.h:641
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
In mm/dmapool.c (ffffffff8128863c)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff815a3db8)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
```
```
In drivers/virtio/virtio_ring.c (ffffffff8161f3b5)
Location: include/linux/dma-mapping.h:641
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff81628d46)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81675f2e)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/virtio_console.c (ffffffff81687e2f)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:alloc_buf
```
```
In drivers/nvme/host/pci.c (ffffffff817510f7)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_reset_work
  - drivers/nvme/host/pci.c:nvme_reset_work
  - drivers/nvme/host/pci.c:nvme_alloc_host_mem
  - drivers/nvme/host/pci.c:nvme_alloc_queue
  - drivers/nvme/host/pci.c:nvme_alloc_queue
```
```
In drivers/usb/core/buffer.c (ffffffff817b0bc8)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
```
```
In drivers/usb/dwc2/hcd.c (ffffffff817c6e7b)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817db13f)
Location: include/linux/dma-mapping.h:641
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff817df952)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_init
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817e8abc)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817f53b6)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_erst
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81894ed3)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
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
In mm/dmapool.c (ffffffff8127a48c)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff81592f58)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
```
```
In drivers/virtio/virtio_ring.c (ffffffff816139d4)
Location: include/linux/dma-mapping.h:641
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8165500e)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/dma-mapping.h:641
Inline: True
```
```
In drivers/nvme/host/pci.c (ffffffff81730f97)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_reset_work
  - drivers/nvme/host/pci.c:nvme_reset_work
  - drivers/nvme/host/pci.c:nvme_alloc_host_mem
  - drivers/nvme/host/pci.c:nvme_alloc_queue
  - drivers/nvme/host/pci.c:nvme_alloc_queue
```
```
In drivers/usb/core/buffer.c (ffffffff817a25f8)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817ba556)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_erst
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817c8c82)
Location: include/linux/dma-mapping.h:641
Inline: True
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
In mm/dmapool.c (ffffffff8128644c)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff815a4348)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
```
```
In drivers/virtio/virtio_ring.c (ffffffff8164d355)
Location: include/linux/dma-mapping.h:641
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff81656d16)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816a42fe)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/dma-mapping.h:641
Inline: True
```
```
In drivers/usb/core/buffer.c (ffffffff817ed668)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8180391b)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81817bdf)
Location: include/linux/dma-mapping.h:641
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff8181c3f2)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_init
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8182555c)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81831e86)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_erst
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff818405b2)
Location: include/linux/dma-mapping.h:641
Inline: True
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
In mm/dmapool.c (ffffffff81296240)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff815be748)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
```
```
In drivers/virtio/virtio_ring.c (ffffffff816679e5)
Location: include/linux/dma-mapping.h:641
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff816712f6)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816be78e)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/virtio_console.c (ffffffff816d070f)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:alloc_buf
```
```
In drivers/usb/core/buffer.c (ffffffff818078a8)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8181da2b)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81831bcf)
Location: include/linux/dma-mapping.h:641
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff818372d2)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_init
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8183eedc)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8184c066)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_erst
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8185aa82)
Location: include/linux/dma-mapping.h:641
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81905633)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
```
</details>
</li>
</ul>

## Differences
