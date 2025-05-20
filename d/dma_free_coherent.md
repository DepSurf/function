# Function: <code>dma_free_coherent</code>

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
Location: include/asm-generic/dma-mapping-common.h:292
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81509900)
Location: include/asm-generic/dma-mapping-common.h:292
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
```
In drivers/char/virtio_console.c (ffffffff81516a35)
Location: include/asm-generic/dma-mapping-common.h:292
Inline: True
```
```
In drivers/base/dma-mapping.c (ffffffff8155dd72)
Location: include/asm-generic/dma-mapping-common.h:292
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dmam_coherent_release
```
```
In drivers/usb/core/buffer.c (ffffffff81617a76)
Location: include/asm-generic/dma-mapping-common.h:292
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8162a191)
Location: include/asm-generic/dma-mapping-common.h:292
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8162e53f)
Location: include/asm-generic/dma-mapping-common.h:292
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81634ca3)
Location: include/asm-generic/dma-mapping-common.h:292
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81641285)
Location: include/asm-generic/dma-mapping-common.h:292
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81649763)
Location: include/asm-generic/dma-mapping-common.h:292
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81655383)
Location: include/asm-generic/dma-mapping-common.h:292
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
Location: include/linux/dma-mapping.h:451
Inline: True
```
```
In drivers/virtio/virtio_ring.c (ffffffff8150f28d)
Location: include/linux/dma-mapping.h:451
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8155b964)
Location: include/linux/dma-mapping.h:451
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/virtio_console.c (ffffffff815696ce)
Location: include/linux/dma-mapping.h:451
Inline: True
```
```
In drivers/base/dma-mapping.c (ffffffff815b1fc2)
Location: include/linux/dma-mapping.h:451
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dmam_coherent_release
```
```
In drivers/usb/core/buffer.c (ffffffff81677b46)
Location: include/linux/dma-mapping.h:451
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8168a090)
Location: include/linux/dma-mapping.h:451
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8169511f)
Location: include/linux/dma-mapping.h:451
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff816a1d95)
Location: include/linux/dma-mapping.h:451
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816aa1d3)
Location: include/linux/dma-mapping.h:451
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816b72b3)
Location: include/linux/dma-mapping.h:451
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
Location: include/linux/dma-mapping.h:503
Inline: True
```
```
In drivers/virtio/virtio_ring.c (ffffffff8153b3dd)
Location: include/linux/dma-mapping.h:503
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81588126)
Location: include/linux/dma-mapping.h:503
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/virtio_console.c (ffffffff81595e0e)
Location: include/linux/dma-mapping.h:503
Inline: True
```
```
In drivers/base/dma-mapping.c (ffffffff815e12b2)
Location: include/linux/dma-mapping.h:503
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dmam_coherent_release
```
```
In drivers/usb/core/buffer.c (ffffffff816a5826)
Location: include/linux/dma-mapping.h:503
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
```
```
In drivers/usb/dwc2/hcd.c (ffffffff816b81ff)
Location: include/linux/dma-mapping.h:503
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff816c36af)
Location: include/linux/dma-mapping.h:503
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff816d0a15)
Location: include/linux/dma-mapping.h:503
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816d8323)
Location: include/linux/dma-mapping.h:503
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816e555a)
Location: include/linux/dma-mapping.h:503
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
Location: include/linux/dma-mapping.h:546
Inline: True
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff814d2b28)
Location: include/linux/dma-mapping.h:546
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space
```
```
In drivers/virtio/virtio_ring.c (ffffffff8154ec69)
Location: include/linux/dma-mapping.h:546
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8159c589)
Location: include/linux/dma-mapping.h:546
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/virtio_console.c (ffffffff815a9bf3)
Location: include/linux/dma-mapping.h:546
Inline: True
```
```
In drivers/base/dma-mapping.c (ffffffff815f5ea9)
Location: include/linux/dma-mapping.h:546
Inline: True
```
```
In drivers/usb/core/buffer.c (ffffffff816babab)
Location: include/linux/dma-mapping.h:546
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
```
```
In drivers/usb/dwc2/hcd.c (ffffffff816cc4ea)
Location: include/linux/dma-mapping.h:546
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff816d7994)
Location: include/linux/dma-mapping.h:546
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff816e509d)
Location: include/linux/dma-mapping.h:546
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816ec83f)
Location: include/linux/dma-mapping.h:546
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816f9481)
Location: include/linux/dma-mapping.h:546
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
Location: include/linux/dma-mapping.h:555
Inline: True
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff81512f28)
Location: include/linux/dma-mapping.h:555
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space
```
```
In drivers/virtio/virtio_ring.c (ffffffff815b2409)
Location: include/linux/dma-mapping.h:555
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8160187c)
Location: include/linux/dma-mapping.h:555
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/virtio_console.c (ffffffff8161051c)
Location: include/linux/dma-mapping.h:555
Inline: True
```
```
In drivers/base/dma-mapping.c (ffffffff8165de69)
Location: include/linux/dma-mapping.h:555
Inline: True
```
```
In drivers/usb/core/buffer.c (ffffffff8172656b)
Location: include/linux/dma-mapping.h:555
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81738a6d)
Location: include/linux/dma-mapping.h:555
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817440c4)
Location: include/linux/dma-mapping.h:555
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff817518c7)
Location: include/linux/dma-mapping.h:555
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8175902f)
Location: include/linux/dma-mapping.h:555
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81765f78)
Location: include/linux/dma-mapping.h:555
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
Location: include/linux/dma-mapping.h:555
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
In kernel/dma/mapping.c (ffffffff8110c8e1)
Location: include/linux/dma-mapping.h:559
Inline: True
```
```
In mm/dmapool.c (ffffffff81251572)
Location: include/linux/dma-mapping.h:559
Inline: True
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff815482b7)
Location: include/linux/dma-mapping.h:559
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space
```
```
In drivers/virtio/virtio_ring.c (ffffffff815ea84a)
Location: include/linux/dma-mapping.h:559
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8163ab36)
Location: include/linux/dma-mapping.h:559
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/virtio_console.c (ffffffff8164a019)
Location: include/linux/dma-mapping.h:559
Inline: True
```
```
In drivers/usb/core/buffer.c (ffffffff8176536f)
Location: include/linux/dma-mapping.h:559
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81778ab0)
Location: include/linux/dma-mapping.h:559
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81784634)
Location: include/linux/dma-mapping.h:559
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff8179138c)
Location: include/linux/dma-mapping.h:559
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8179986c)
Location: include/linux/dma-mapping.h:559
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817a6b0b)
Location: include/linux/dma-mapping.h:559
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
Location: include/linux/dma-mapping.h:559
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
```
```
In drivers/i2c/busses/i2c-amd-platdrv.c (ffffffff817dd617)
Location: include/linux/dma-mapping.h:559
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
In kernel/dma/mapping.c (ffffffff811181bf)
Location: include/linux/dma-mapping.h:641
Inline: True
```
```
In mm/dmapool.c (ffffffff81265979)
Location: include/linux/dma-mapping.h:641
Inline: True
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff8155e4e0)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space
```
```
In drivers/virtio/virtio_ring.c (ffffffff81604e95)
Location: include/linux/dma-mapping.h:641
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff8160c6d0)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81658d42)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/virtio_console.c (ffffffff81668242)
Location: include/linux/dma-mapping.h:641
Inline: True
```
```
In drivers/usb/core/buffer.c (ffffffff8178991b)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8179ea4d)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817a9c30)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff817b7b5f)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817bfa9b)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817cc469)
Location: include/linux/dma-mapping.h:641
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
In drivers/usb/host/xhci-dbgcap.c (ffffffff817d9868)
Location: include/linux/dma-mapping.h:641
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
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
In kernel/dma/mapping.c (ffffffff81122540)
Location: include/linux/dma-mapping.h:644
Inline: True
```
```
In mm/dmapool.c (ffffffff8128094d)
Location: include/linux/dma-mapping.h:644
Inline: True
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff8158e91a)
Location: include/linux/dma-mapping.h:644
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space
```
```
In drivers/virtio/virtio_ring.c (ffffffff816377d5)
Location: include/linux/dma-mapping.h:644
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff8164182c)
Location: include/linux/dma-mapping.h:644
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8168e232)
Location: include/linux/dma-mapping.h:644
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/virtio_console.c (ffffffff8169dcb8)
Location: include/linux/dma-mapping.h:644
Inline: True
```
```
In drivers/usb/core/buffer.c (ffffffff817c7d4c)
Location: include/linux/dma-mapping.h:644
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
```
```
In drivers/usb/dwc2/hcd.c (ffffffff817dd644)
Location: include/linux/dma-mapping.h:644
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817e8dd0)
Location: include/linux/dma-mapping.h:644
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff817f6450)
Location: include/linux/dma-mapping.h:644
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817ff34b)
Location: include/linux/dma-mapping.h:644
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8180c646)
Location: include/linux/dma-mapping.h:644
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
In drivers/usb/host/xhci-dbgcap.c (ffffffff8181a1ce)
Location: include/linux/dma-mapping.h:644
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
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
In kernel/dma/mapping.c (ffffffff8112eb40)
Location: include/linux/dma-mapping.h:649
Inline: True
```
```
In mm/dmapool.c (ffffffff8129037d)
Location: include/linux/dma-mapping.h:649
Inline: True
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff815b053a)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space
```
```
In drivers/virtio/virtio_ring.c (ffffffff816595b5)
Location: include/linux/dma-mapping.h:649
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff816629cc)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816b0802)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/virtio_console.c (ffffffff816c0a28)
Location: include/linux/dma-mapping.h:649
Inline: True
```
```
In drivers/usb/core/buffer.c (ffffffff817f8883)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8180e574)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81819c90)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff818272b0)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff818301ab)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8183d638)
Location: include/linux/dma-mapping.h:649
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
In drivers/usb/host/xhci-dbgcap.c (ffffffff8184b56e)
Location: include/linux/dma-mapping.h:649
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff818f3775)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_release_carveout
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
In kernel/dma/mapping.c (ffffffff8113d4b0)
Location: include/linux/dma-mapping.h:735
Inline: True
```
```
In mm/dmapool.c (ffffffff812c300d)
Location: include/linux/dma-mapping.h:735
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_destroy
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff81659856)
Location: include/linux/dma-mapping.h:735
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space
```
```
In drivers/virtio/virtio_ring.c (ffffffff8170a214)
Location: include/linux/dma-mapping.h:735
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff8171212c)
Location: include/linux/dma-mapping.h:735
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81763be2)
Location: include/linux/dma-mapping.h:735
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/virtio_console.c (ffffffff817744ab)
Location: include/linux/dma-mapping.h:735
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:free_buf
```
```
In drivers/usb/core/buffer.c (ffffffff818c89eb)
Location: include/linux/dma-mapping.h:735
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818df203)
Location: include/linux/dma-mapping.h:735
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818ea240)
Location: include/linux/dma-mapping.h:735
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff818f9fc3)
Location: include/linux/dma-mapping.h:735
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81901d2b)
Location: include/linux/dma-mapping.h:735
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:release_uhci
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8190f46c)
Location: include/linux/dma-mapping.h:735
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8191dede)
Location: include/linux/dma-mapping.h:735
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819c90a5)
Location: include/linux/dma-mapping.h:735
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_release_carveout
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
In kernel/dma/mapping.c (ffffffff81137d40)
Location: include/linux/dma-mapping.h:400
Inline: True
```
```
In mm/dmapool.c (ffffffff812cedda)
Location: include/linux/dma-mapping.h:400
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_destroy
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff81679c43)
Location: include/linux/dma-mapping.h:400
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space
```
```
In drivers/virtio/virtio_ring.c (ffffffff81727744)
Location: include/linux/dma-mapping.h:400
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff8172eebc)
Location: include/linux/dma-mapping.h:400
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8177ebb2)
Location: include/linux/dma-mapping.h:400
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/virtio_console.c (ffffffff8178f20b)
Location: include/linux/dma-mapping.h:400
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:free_buf
```
```
In drivers/usb/core/buffer.c (ffffffff818d3b3b)
Location: include/linux/dma-mapping.h:400
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818e9063)
Location: include/linux/dma-mapping.h:400
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818f3130)
Location: include/linux/dma-mapping.h:400
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81902b03)
Location: include/linux/dma-mapping.h:400
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8190a5f7)
Location: include/linux/dma-mapping.h:400
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:release_uhci
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81916fcc)
Location: include/linux/dma-mapping.h:400
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81925db1)
Location: include/linux/dma-mapping.h:400
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
  - drivers/usb/host/xhci-dbgcap.c:dbc_ring_free
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819c8c45)
Location: include/linux/dma-mapping.h:400
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_release_carveout
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
In kernel/dma/mapping.c (ffffffff81138d70)
Location: include/linux/dma-mapping.h:442
Inline: True
```
```
In mm/dmapool.c (ffffffff812d59fa)
Location: include/linux/dma-mapping.h:442
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_destroy
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff8165c792)
Location: include/linux/dma-mapping.h:442
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space
```
```
In drivers/virtio/virtio_ring.c (ffffffff8170b384)
Location: include/linux/dma-mapping.h:442
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff8171290c)
Location: include/linux/dma-mapping.h:442
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81762512)
Location: include/linux/dma-mapping.h:442
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/virtio_console.c (ffffffff81771ff8)
Location: include/linux/dma-mapping.h:442
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:free_buf
```
```
In drivers/usb/core/buffer.c (ffffffff818b709b)
Location: include/linux/dma-mapping.h:442
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818cab43)
Location: include/linux/dma-mapping.h:442
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818d68f0)
Location: include/linux/dma-mapping.h:442
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff818e5c46)
Location: include/linux/dma-mapping.h:442
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff818ee756)
Location: include/linux/dma-mapping.h:442
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffff818fa44c)
Location: include/linux/dma-mapping.h:442
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff819094a1)
Location: include/linux/dma-mapping.h:442
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
  - drivers/usb/host/xhci-dbgcap.c:dbc_ring_free
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819adb95)
Location: include/linux/dma-mapping.h:442
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_release_carveout
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
In kernel/dma/mapping.c (ffffffff8115b680)
Location: include/linux/dma-mapping.h:422
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dmam_free_coherent
```
```
In mm/dmapool.c (ffffffff8131b84a)
Location: include/linux/dma-mapping.h:422
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_destroy
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff816cee62)
Location: include/linux/dma-mapping.h:422
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space
```
```
In drivers/virtio/virtio_ring.c (ffffffff81787404)
Location: include/linux/dma-mapping.h:422
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff8178f44c)
Location: include/linux/dma-mapping.h:422
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff817e65e2)
Location: include/linux/dma-mapping.h:422
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/virtio_console.c (ffffffff817f7d95)
Location: include/linux/dma-mapping.h:422
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:free_buf
```
```
In drivers/usb/core/buffer.c (ffffffff8194cb7b)
Location: include/linux/dma-mapping.h:422
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81963d09)
Location: include/linux/dma-mapping.h:422
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81971660)
Location: include/linux/dma-mapping.h:422
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81981fe6)
Location: include/linux/dma-mapping.h:422
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8198af2b)
Location: include/linux/dma-mapping.h:422
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffff819991cc)
Location: include/linux/dma-mapping.h:422
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff819a9423)
Location: include/linux/dma-mapping.h:422
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ring_free
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81a5c0f5)
Location: include/linux/dma-mapping.h:422
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_release_carveout
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
In kernel/dma/mapping.c (ffffffff811850ef)
Location: include/linux/dma-mapping.h:422
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dmam_free_coherent
```
```
In mm/dmapool.c (ffffffff81387070)
Location: include/linux/dma-mapping.h:422
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_destroy
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff817f7acc)
Location: include/linux/dma-mapping.h:422
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space
```
```
In drivers/virtio/virtio_ring.c (ffffffff818be405)
Location: include/linux/dma-mapping.h:422
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff818c7737)
Location: include/linux/dma-mapping.h:422
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81925b52)
Location: include/linux/dma-mapping.h:422
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/virtio_console.c (ffffffff81936b12)
Location: include/linux/dma-mapping.h:422
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:free_buf
```
```
In drivers/usb/core/buffer.c (ffffffff81aa575f)
Location: include/linux/dma-mapping.h:422
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81abe21d)
Location: include/linux/dma-mapping.h:422
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81acc4f0)
Location: include/linux/dma-mapping.h:422
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81adead7)
Location: include/linux/dma-mapping.h:422
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81ae5c77)
Location: include/linux/dma-mapping.h:422
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81af61f0)
Location: include/linux/dma-mapping.h:422
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81b074b2)
Location: include/linux/dma-mapping.h:422
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ring_free
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81bcc0a5)
Location: include/linux/dma-mapping.h:422
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_release_carveout
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
In kernel/dma/mapping.c (ffffffff811c089f)
Location: include/linux/dma-mapping.h:427
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dmam_free_coherent
```
```
In mm/dmapool.c (ffffffff81404fcd)
Location: include/linux/dma-mapping.h:427
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_destroy
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff819235cc)
Location: include/linux/dma-mapping.h:427
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space
```
```
In drivers/virtio/virtio_ring.c (ffffffff81a0d4a5)
Location: include/linux/dma-mapping.h:427
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff81a182a7)
Location: include/linux/dma-mapping.h:427
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81a82592)
Location: include/linux/dma-mapping.h:427
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/virtio_console.c (ffffffff81a969b2)
Location: include/linux/dma-mapping.h:427
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:free_buf
```
```
In drivers/usb/core/buffer.c (ffffffff81c2c1cf)
Location: include/linux/dma-mapping.h:427
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81c4798d)
Location: include/linux/dma-mapping.h:427
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81c56c70)
Location: include/linux/dma-mapping.h:427
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81c69fe7)
Location: include/linux/dma-mapping.h:427
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81c719bf)
Location: include/linux/dma-mapping.h:427
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81c83b80)
Location: include/linux/dma-mapping.h:427
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81c9753e)
Location: include/linux/dma-mapping.h:427
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_mem_cleanup
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_mem_cleanup
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_mem_cleanup
  - drivers/usb/host/xhci-dbgcap.c:dbc_ring_free
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81d75c95)
Location: include/linux/dma-mapping.h:427
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_release_carveout
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
In kernel/dma/mapping.c (ffffffff811d338f)
Location: include/linux/dma-mapping.h:428
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dmam_free_coherent
```
```
In mm/dmapool.c (ffffffff81438004)
Location: include/linux/dma-mapping.h:428
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_destroy
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff819671dc)
Location: include/linux/dma-mapping.h:428
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space
```
```
In drivers/virtio/virtio_ring.c (ffffffff81a563ab)
Location: include/linux/dma-mapping.h:428
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff81a61335)
Location: include/linux/dma-mapping.h:428
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81acdb92)
Location: include/linux/dma-mapping.h:428
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/virtio_console.c (ffffffff81ae21c7)
Location: include/linux/dma-mapping.h:428
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:free_buf
```
```
In drivers/usb/core/buffer.c (ffffffff81c9334d)
Location: include/linux/dma-mapping.h:428
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free_pages
  - drivers/usb/core/buffer.c:hcd_buffer_free
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81caef6d)
Location: include/linux/dma-mapping.h:428
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81cbe310)
Location: include/linux/dma-mapping.h:428
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81cd13f7)
Location: include/linux/dma-mapping.h:428
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81cd8f8f)
Location: include/linux/dma-mapping.h:428
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81cea84e)
Location: include/linux/dma-mapping.h:428
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81cfe85e)
Location: include/linux/dma-mapping.h:428
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_mem_cleanup
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_mem_cleanup
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_mem_cleanup
  - drivers/usb/host/xhci-dbgcap.c:dbc_ring_free
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81de3bd5)
Location: include/linux/dma-mapping.h:428
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_release_carveout
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
In kernel/dma/mapping.c (ffffffff811e800f)
Location: include/linux/dma-mapping.h:435
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dmam_free_coherent
```
```
In mm/dmapool.c (ffffffff81471964)
Location: include/linux/dma-mapping.h:435
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_destroy
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff819b090c)
Location: include/linux/dma-mapping.h:435
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space
```
```
In drivers/virtio/virtio_ring.c (ffffffff81aa74cb)
Location: include/linux/dma-mapping.h:435
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff81ab3b65)
Location: include/linux/dma-mapping.h:435
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81b20c62)
Location: include/linux/dma-mapping.h:435
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/virtio_console.c (ffffffff81b355b7)
Location: include/linux/dma-mapping.h:435
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:free_buf
```
```
In drivers/usb/core/buffer.c (ffffffff81d47dfd)
Location: include/linux/dma-mapping.h:435
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free_pages
  - drivers/usb/core/buffer.c:hcd_buffer_free
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81d63c1d)
Location: include/linux/dma-mapping.h:435
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81d73080)
Location: include/linux/dma-mapping.h:435
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81d863b7)
Location: include/linux/dma-mapping.h:435
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81d8df9f)
Location: include/linux/dma-mapping.h:435
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81da0241)
Location: include/linux/dma-mapping.h:435
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_free_interrupter
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81db47f8)
Location: include/linux/dma-mapping.h:435
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_mem_cleanup
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_mem_cleanup
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_mem_cleanup
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_mem_cleanup
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_mem_cleanup
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_mem_cleanup
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81e99cc5)
Location: include/linux/dma-mapping.h:435
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_release_carveout
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
In kernel/dma/mapping.c (0)
Location: include/linux/dma-mapping.h:649
Inline: True
```
```
In mm/dmapool.c (ffff80001032ce58)
Location: include/linux/dma-mapping.h:649
Inline: True
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffff80001071c4d0)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space
```
```
In drivers/pci/controller/pcie-iproc-msi.c (ffff8000107267b0)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_exit
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_init
```
```
In drivers/video/fbdev/amba-clcd.c (ffff80001075b6c8)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/video/fbdev/amba-clcd.c:clcdfb_of_dma_remove
```
```
In drivers/dma/mv_xor.c (ffff8000108081d8)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_xor_probe
  - drivers/dma/mv_xor.c:mv_xor_channel_add
```
```
In drivers/dma/mv_xor_v2.c (ffff800010808410)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_remove
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_probe
```
```
In drivers/dma/mxs-dma.c (ffff800010809c98)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/dma/mxs-dma.c:mxs_dma_free_chan_resources
  - drivers/dma/mxs-dma.c:mxs_dma_alloc_chan_resources
```
```
In drivers/virtio/virtio_ring.c (ffff800010821df0)
Location: include/linux/dma-mapping.h:649
Inline: True
```
```
In drivers/xen/grant-table.c (ffff80001082cbe0)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
```
```
In drivers/tty/serial/8250/8250_dma.c (ffff80001088bcf0)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/tty/serial/amba-pl011.c (ffff800010896220)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
```
```
In drivers/char/virtio_console.c (ffff8000108b387c)
Location: include/linux/dma-mapping.h:649
Inline: True
```
```
In drivers/net/ethernet/broadcom/bgmac.c (ffff8000109e2668)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_free
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_free
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e91ac)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_init
```
```
In drivers/usb/core/buffer.c (ffff800010a29630)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
```
```
In drivers/usb/dwc2/hcd.c (ffff800010a470c0)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
```
```
In drivers/usb/host/ehci-hcd.c (ffff800010a52f00)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
```
```
In drivers/usb/host/ohci-hcd.c (ffff800010a621fc)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
```
```
In drivers/usb/host/uhci-hcd.c (ffff800010a6a6e0)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffff800010a7b5ac)
Location: include/linux/dma-mapping.h:649
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
In drivers/usb/host/xhci-dbgcap.c (ffff800010a8a984)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
```
```
In drivers/firmware/raspberrypi.c (ffff800010b4e684)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/firmware/raspberrypi.c:rpi_firmware_property_list
```
```
In drivers/firmware/qcom_scm.c (ffff800010b4eef0)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/firmware/qcom_scm.c:qcom_scm_assign_mem
  - drivers/firmware/qcom_scm.c:qcom_scm_pas_init_image
```
```
In drivers/remoteproc/remoteproc_core.c (ffff800010b7f4ac)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_release_carveout
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
In kernel/dma/mapping.c (c03e1378)
Location: include/linux/dma-mapping.h:649
Inline: True
```
```
In mm/dmapool.c (c0543248)
Location: include/linux/dma-mapping.h:649
Inline: True
```
```
In drivers/pci/endpoint/pci-epf-core.c (c08a57bc)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space
```
```
In drivers/video/fbdev/amba-clcd.c (c08de4d4)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/video/fbdev/amba-clcd.c:clcdfb_of_dma_remove
```
```
In drivers/dma/mv_xor.c (c092604c)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_xor_probe
  - drivers/dma/mv_xor.c:mv_xor_channel_add
```
```
In drivers/dma/mxs-dma.c (c09269f0)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/dma/mxs-dma.c:mxs_dma_free_chan_resources
  - drivers/dma/mxs-dma.c:mxs_dma_alloc_chan_resources
```
```
In drivers/virtio/virtio_ring.c (c093f8d4)
Location: include/linux/dma-mapping.h:649
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (c09896b4)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/tty/serial/amba-pl011.c (c09923a8)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
```
```
In drivers/char/virtio_console.c (c09ad6e0)
Location: include/linux/dma-mapping.h:649
Inline: True
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0aca3e0)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_init
```
```
In drivers/net/ethernet/ti/davinci_cpdma.c (c0ad6960)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_desc_pool_destroy
```
```
In drivers/usb/core/buffer.c (c0aff590)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
```
```
In drivers/usb/dwc2/hcd.c (c0b197c0)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
```
```
In drivers/usb/host/ehci-hcd.c (c0b25e2c)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
```
```
In drivers/usb/host/ohci-hcd.c (c0b353b0)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
```
```
In drivers/usb/host/uhci-hcd.c (c0b3c40c)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (c0b4ee40)
Location: include/linux/dma-mapping.h:649
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
In drivers/usb/host/xhci-dbgcap.c (c0b5d61c)
Location: include/linux/dma-mapping.h:649
Inline: True
```
```
In drivers/mmc/host/sdhci.c (c0c254b0)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci.c:sdhci_remove_host
  - drivers/mmc/host/sdhci.c:sdhci_cleanup_host
  - drivers/mmc/host/sdhci.c:sdhci_setup_host
  - drivers/mmc/host/sdhci.c:sdhci_setup_host
```
```
In drivers/firmware/qcom_scm.c (c0c357ec)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/firmware/qcom_scm.c:qcom_scm_assign_mem
  - drivers/firmware/qcom_scm.c:qcom_scm_pas_init_image
```
```
In drivers/firmware/tegra/bpmp.c (c0c42274)
Location: include/linux/dma-mapping.h:649
Inline: True
```
```
In drivers/firmware/tegra/bpmp-debugfs.c (c0c430c8)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/firmware/tegra/bpmp-debugfs.c:tegra_bpmp_init_debugfs
  - drivers/firmware/tegra/bpmp-debugfs.c:debugfs_store
  - drivers/firmware/tegra/bpmp-debugfs.c:debugfs_store
  - drivers/firmware/tegra/bpmp-debugfs.c:debugfs_show
  - drivers/firmware/tegra/bpmp-debugfs.c:debugfs_show
```
```
In drivers/staging/emxx_udc/emxx_udc.c (c0c5b554)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_drv_remove
```
```
In drivers/remoteproc/remoteproc_core.c (c0c62c84)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_release_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
```
```
In sound/core/memalloc.c (c0c9bf00)
Location: include/linux/dma-mapping.h:649
Inline: True
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
In kernel/dma/mapping.c (c0000000001f40e4)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dmam_free_coherent
```
```
In mm/dmapool.c (c000000000404ff0)
Location: include/linux/dma-mapping.h:649
Inline: True
```
```
In drivers/pci/endpoint/pci-epf-core.c (c00000000088ca08)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space
```
```
In drivers/virtio/virtio_ring.c (c0000000008cb9a0)
Location: include/linux/dma-mapping.h:649
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (c000000000934730)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/virtio_console.c (c00000000094bcd8)
Location: include/linux/dma-mapping.h:649
Inline: True
```
```
In drivers/usb/core/buffer.c (c000000000ae5b8c)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
```
```
In drivers/usb/dwc2/hcd.c (c000000000b0b9a8)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
```
```
In drivers/usb/host/ehci-hcd.c (c000000000b1ccf8)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
```
```
In drivers/usb/host/ohci-hcd.c (c000000000b31b60)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
```
```
In drivers/usb/host/uhci-hcd.c (c000000000b3c684)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (c000000000b532a4)
Location: include/linux/dma-mapping.h:649
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
In drivers/usb/host/xhci-dbgcap.c (c000000000b65f28)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
```
```
In drivers/remoteproc/remoteproc_core.c (c000000000c5b68c)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_release_carveout
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
In kernel/dma/mapping.c (ffffffe00012630a)
Location: include/linux/dma-mapping.h:649
Inline: True
```
```
In mm/dmapool.c (ffffffe00022bac2)
Location: include/linux/dma-mapping.h:649
Inline: True
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffe0004e31ae)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space
```
```
In drivers/virtio/virtio_ring.c (ffffffe000518942)
Location: include/linux/dma-mapping.h:649
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffe00055561a)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/usb/core/buffer.c (ffffffe00064b03e)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
```
```
In drivers/usb/dwc2/hcd.c (ffffffe000663aa2)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
```
```
In drivers/usb/host/ehci-hcd.c (ffffffe00066faa8)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
```
```
In drivers/usb/host/ohci-hcd.c (ffffffe00067d452)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
```
```
In drivers/usb/host/uhci-hcd.c (ffffffe000685708)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffe000692b06)
Location: include/linux/dma-mapping.h:649
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
In drivers/usb/host/xhci-dbgcap.c (ffffffe00069f576)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
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
In kernel/dma/mapping.c (ffffffff81127120)
Location: include/linux/dma-mapping.h:649
Inline: True
```
```
In mm/dmapool.c (ffffffff8128895d)
Location: include/linux/dma-mapping.h:649
Inline: True
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff815a3cfa)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space
```
```
In drivers/virtio/virtio_ring.c (ffffffff8161f455)
Location: include/linux/dma-mapping.h:649
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff8162883c)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81676272)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/virtio_console.c (ffffffff81686478)
Location: include/linux/dma-mapping.h:649
Inline: True
```
```
In drivers/nvme/host/pci.c (ffffffff81751139)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_reset_work
  - drivers/nvme/host/pci.c:nvme_alloc_host_mem
  - drivers/nvme/host/pci.c:nvme_free_host_mem
  - drivers/nvme/host/pci.c:nvme_alloc_queue
  - drivers/nvme/host/pci.c:nvme_free_queue
  - drivers/nvme/host/pci.c:nvme_free_queue
  - drivers/nvme/host/pci.c:nvme_dbbuf_dma_free
  - drivers/nvme/host/pci.c:nvme_dbbuf_dma_free
```
```
In drivers/usb/core/buffer.c (ffffffff817b0c63)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
```
```
In drivers/usb/dwc2/hcd.c (ffffffff817c6954)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817d2070)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff817df690)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817e858b)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817f59e8)
Location: include/linux/dma-mapping.h:649
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
In drivers/remoteproc/remoteproc_core.c (ffffffff81894aa5)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_release_carveout
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
In kernel/dma/mapping.c (ffffffff81119b80)
Location: include/linux/dma-mapping.h:649
Inline: True
```
```
In mm/dmapool.c (ffffffff8127a7ad)
Location: include/linux/dma-mapping.h:649
Inline: True
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff81592e9a)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space
```
```
In drivers/virtio/virtio_ring.c (ffffffff81613a2a)
Location: include/linux/dma-mapping.h:649
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81655352)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/nvme/host/pci.c (ffffffff81730fd9)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_reset_work
  - drivers/nvme/host/pci.c:nvme_alloc_host_mem
  - drivers/nvme/host/pci.c:nvme_free_host_mem
  - drivers/nvme/host/pci.c:nvme_alloc_queue
  - drivers/nvme/host/pci.c:nvme_free_queue
  - drivers/nvme/host/pci.c:nvme_free_queue
  - drivers/nvme/host/pci.c:nvme_dbbuf_dma_free
  - drivers/nvme/host/pci.c:nvme_dbbuf_dma_free
```
```
In drivers/usb/core/buffer.c (ffffffff817a2693)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817bab88)
Location: include/linux/dma-mapping.h:649
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
In drivers/usb/host/xhci-dbgcap.c (ffffffff817c8abe)
Location: include/linux/dma-mapping.h:649
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
In kernel/dma/mapping.c (ffffffff81125010)
Location: include/linux/dma-mapping.h:649
Inline: True
```
```
In mm/dmapool.c (ffffffff8128676d)
Location: include/linux/dma-mapping.h:649
Inline: True
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff815a428a)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space
```
```
In drivers/virtio/virtio_ring.c (ffffffff8164d3f5)
Location: include/linux/dma-mapping.h:649
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff8165680c)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816a4642)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/usb/core/buffer.c (ffffffff817ed703)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818033f4)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8180eb10)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff8181c130)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8182502b)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffff818324b8)
Location: include/linux/dma-mapping.h:649
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
In drivers/usb/host/xhci-dbgcap.c (ffffffff818403ee)
Location: include/linux/dma-mapping.h:649
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
In kernel/dma/mapping.c (ffffffff81131650)
Location: include/linux/dma-mapping.h:649
Inline: True
```
```
In mm/dmapool.c (ffffffff8129655d)
Location: include/linux/dma-mapping.h:649
Inline: True
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff815be68a)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_free_space
```
```
In drivers/virtio/virtio_ring.c (ffffffff81667a85)
Location: include/linux/dma-mapping.h:649
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff81670dec)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816beae6)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/virtio_console.c (ffffffff816cedc8)
Location: include/linux/dma-mapping.h:649
Inline: True
```
```
In drivers/usb/core/buffer.c (ffffffff81807943)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8181d504)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818295e0)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_mem_cleanup
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81837010)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_stop
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8183dce9)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8184c698)
Location: include/linux/dma-mapping.h:649
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
In drivers/usb/host/xhci-dbgcap.c (ffffffff8185a8be)
Location: include/linux/dma-mapping.h:649
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81905205)
Location: include/linux/dma-mapping.h:649
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_release_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
```
</details>
</li>
</ul>

## Differences
