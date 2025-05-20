# Function: <code>dma_unmap_single_attrs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81509a5e)
Location: include/asm-generic/dma-mapping-common.h:30
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
```
In drivers/usb/core/hcd.c (ffffffff8160cc16)
Location: include/asm-generic/dma-mapping-common.h:30
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff8162b2d0)
Location: include/asm-generic/dma-mapping-common.h:30
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state_abn
  - drivers/usb/dwc2/hcd_intr.c:dwc2_update_urb_state
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xacterr_intr
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
**Symbols:**

```
ffffffff8162b2d0-ffffffff8162b309: dma_unmap_single_attrs.constprop.18 (STB_LOCAL)
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
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/dma-mapping.h:188
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8155b9e3)
Location: include/linux/dma-mapping.h:188
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
```
In drivers/usb/core/hcd.c (ffffffff8166c83a)
Location: include/linux/dma-mapping.h:188
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8168f628)
Location: include/linux/dma-mapping.h:188
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
```
```
In drivers/usb/host/xhci-ring.c (ffffffff816b86a9)
Location: include/linux/dma-mapping.h:188
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_unmap_td_bounce_buffer
  - drivers/usb/host/xhci-ring.c:xhci_unmap_td_bounce_buffer
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
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/dma-mapping.h:199
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff815881c9)
Location: include/linux/dma-mapping.h:199
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
```
In drivers/usb/core/hcd.c (ffffffff8169a53a)
Location: include/linux/dma-mapping.h:199
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff816bd6d7)
Location: include/linux/dma-mapping.h:199
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
```
```
In drivers/usb/host/xhci-ring.c (ffffffff816e64d4)
Location: include/linux/dma-mapping.h:199
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
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/dma-mapping.h:242
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8159c616)
Location: include/linux/dma-mapping.h:242
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
```
In drivers/usb/core/hcd.c (ffffffff816af7af)
Location: include/linux/dma-mapping.h:242
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff816d1730)
Location: include/linux/dma-mapping.h:242
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
```
```
In drivers/usb/host/xhci-ring.c (ffffffff816fa251)
Location: include/linux/dma-mapping.h:242
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
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/dma-mapping.h:244
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8160190f)
Location: include/linux/dma-mapping.h:244
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
```
In drivers/usb/core/hcd.c (ffffffff8171ae0f)
Location: include/linux/dma-mapping.h:244
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8173ddb0)
Location: include/linux/dma-mapping.h:244
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81766c91)
Location: include/linux/dma-mapping.h:244
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81773fc0)
Location: include/linux/dma-mapping.h:244
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
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
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/dma-mapping.h:244
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8163abf0)
Location: include/linux/dma-mapping.h:244
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
```
In drivers/usb/core/hcd.c (ffffffff81759aef)
Location: include/linux/dma-mapping.h:244
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff8177ae90)
Location: include/linux/dma-mapping.h:244
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8177e736)
Location: include/linux/dma-mapping.h:244
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817a78c9)
Location: include/linux/dma-mapping.h:244
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817b4615)
Location: include/linux/dma-mapping.h:244
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
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
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/dma-mapping.h:582
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81658dac)
Location: include/linux/dma-mapping.h:582
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
```
In drivers/usb/core/hcd.c (ffffffff8177e15f)
Location: include/linux/dma-mapping.h:582
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff817a10b5)
Location: include/linux/dma-mapping.h:582
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817a4e53)
Location: include/linux/dma-mapping.h:582
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817cd872)
Location: include/linux/dma-mapping.h:582
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817dab51)
Location: include/linux/dma-mapping.h:582
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
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
In drivers/virtio/virtio_ring.c (ffffffff8163a96f)
Location: include/linux/dma-mapping.h:585
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8168e2a0)
Location: include/linux/dma-mapping.h:585
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
```
In drivers/usb/core/hcd.c (ffffffff817bc6df)
Location: include/linux/dma-mapping.h:585
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff817e0003)
Location: include/linux/dma-mapping.h:585
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817e4073)
Location: include/linux/dma-mapping.h:585
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8180d8e0)
Location: include/linux/dma-mapping.h:585
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8181b7d0)
Location: include/linux/dma-mapping.h:585
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
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
In drivers/virtio/virtio_ring.c (ffffffff8165ce2f)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816b0870)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
```
In drivers/usb/core/hcd.c (ffffffff817eceff)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81810ef3)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81814f33)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8183e9d0)
Location: include/linux/dma-mapping.h:592
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8184c93d)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
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
In drivers/virtio/virtio_ring.c (ffffffff8170a8c6)
Location: include/linux/dma-mapping.h:597
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81763c50)
Location: include/linux/dma-mapping.h:597
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
```
In drivers/usb/core/hcd.c (ffffffff818bc21f)
Location: include/linux/dma-mapping.h:597
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff818e1725)
Location: include/linux/dma-mapping.h:597
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_xfercomp_isoc_split_in
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818e6ae1)
Location: include/linux/dma-mapping.h:597
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81910f2e)
Location: include/linux/dma-mapping.h:597
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8191f4c2)
Location: include/linux/dma-mapping.h:597
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
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
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8167b89f)
Location: include/linux/dma-mapping.h:283
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
```
```
In drivers/virtio/virtio_ring.c (ffffffff81727310)
Location: include/linux/dma-mapping.h:283
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8177ec1b)
Location: include/linux/dma-mapping.h:283
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
```
In drivers/usb/core/hcd.c (ffffffff818c8f16)
Location: include/linux/dma-mapping.h:283
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff818eafea)
Location: include/linux/dma-mapping.h:283
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_xfercomp_isoc_split_in
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818efbec)
Location: include/linux/dma-mapping.h:283
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
```
```
In drivers/usb/host/xhci.c (ffffffff8190c8b8)
Location: include/linux/dma-mapping.h:283
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_unmap_urb_for_dma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8191868a)
Location: include/linux/dma-mapping.h:283
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81c22688)
Location: include/linux/dma-mapping.h:283
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
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
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8165e720)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8176257b)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
```
In drivers/usb/core/hcd.c (ffffffff818ac4c6)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff818ce93b)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_xfercomp_isoc_split_in
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818d339e)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
```
```
In drivers/usb/host/xhci.c (ffffffff818efde0)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_unmap_urb_for_dma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff818fb9a7)
Location: include/linux/dma-mapping.h:326
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81c1487f)
Location: include/linux/dma-mapping.h:326
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
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
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff816d12a0)
Location: include/linux/dma-mapping.h:334
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
```
```
In drivers/virtio/virtio_ring.c (ffffffff8178703b)
Location: include/linux/dma-mapping.h:334
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
  - drivers/virtio/virtio_ring.c:vring_unmap_one_split
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff817e664b)
Location: include/linux/dma-mapping.h:334
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
```
In drivers/usb/core/hcd.c (ffffffff81941516)
Location: include/linux/dma-mapping.h:334
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81968608)
Location: include/linux/dma-mapping.h:334
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_xfercomp_isoc_split_in
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8196deb8)
Location: include/linux/dma-mapping.h:334
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
```
```
In drivers/usb/host/xhci.c (ffffffff8198c9f0)
Location: include/linux/dma-mapping.h:334
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_unmap_urb_for_dma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8199a827)
Location: include/linux/dma-mapping.h:334
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81d21d71)
Location: include/linux/dma-mapping.h:334
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
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
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff817fa2ff)
Location: include/linux/dma-mapping.h:334
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
```
```
In drivers/virtio/virtio_ring.c (ffffffff818bd109)
Location: include/linux/dma-mapping.h:334
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_unmap_one_split
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81925bbb)
Location: include/linux/dma-mapping.h:334
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
```
In drivers/usb/core/hcd.c (ffffffff81a99d37)
Location: include/linux/dma-mapping.h:334
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81ac27b4)
Location: include/linux/dma-mapping.h:334
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_xfercomp_isoc_split_in
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81ac84bb)
Location: include/linux/dma-mapping.h:334
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
```
```
In drivers/usb/host/xhci.c (ffffffff81ae8c7d)
Location: include/linux/dma-mapping.h:334
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_unmap_urb_for_dma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81af7938)
Location: include/linux/dma-mapping.h:334
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81eedb23)
Location: include/linux/dma-mapping.h:334
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
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
In drivers/virtio/virtio_ring.c (ffffffff81a0bf29)
Location: include/linux/dma-mapping.h:339
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_unmap_one_split
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81a825fb)
Location: include/linux/dma-mapping.h:339
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
```
In drivers/usb/core/hcd.c (ffffffff81c1e273)
Location: include/linux/dma-mapping.h:339
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81c4c664)
Location: include/linux/dma-mapping.h:339
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_xfercomp_isoc_split_in
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81c5284b)
Location: include/linux/dma-mapping.h:339
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
```
```
In drivers/usb/host/xhci.c (ffffffff81c74e7d)
Location: include/linux/dma-mapping.h:339
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_unmap_urb_for_dma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81c855f8)
Location: include/linux/dma-mapping.h:339
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81c97cac)
Location: include/linux/dma-mapping.h:339
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
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
In drivers/virtio/virtio_ring.c (ffffffff81a54e48)
Location: include/linux/dma-mapping.h:340
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_unmap_one_split
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81acdbfb)
Location: include/linux/dma-mapping.h:340
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
```
In drivers/usb/core/hcd.c (ffffffff81c85163)
Location: include/linux/dma-mapping.h:340
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81cb3cd4)
Location: include/linux/dma-mapping.h:340
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_xfercomp_isoc_split_in
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81cb9e0b)
Location: include/linux/dma-mapping.h:340
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
```
```
In drivers/usb/host/xhci.c (ffffffff81cdbf9d)
Location: include/linux/dma-mapping.h:340
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_unmap_urb_for_dma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81cec068)
Location: include/linux/dma-mapping.h:340
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81cfefde)
Location: include/linux/dma-mapping.h:340
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
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
In drivers/virtio/virtio_ring.c (ffffffff81aa61dd)
Location: include/linux/dma-mapping.h:345
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81b20ccb)
Location: include/linux/dma-mapping.h:345
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
```
In drivers/usb/core/hcd.c (ffffffff81d39b63)
Location: include/linux/dma-mapping.h:345
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81d68a04)
Location: include/linux/dma-mapping.h:345
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_xfercomp_isoc_split_in
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81d6eb7b)
Location: include/linux/dma-mapping.h:345
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
```
```
In drivers/usb/host/xhci.c (ffffffff81d90fbd)
Location: include/linux/dma-mapping.h:345
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_unmap_urb_for_dma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81da1689)
Location: include/linux/dma-mapping.h:345
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81db40de)
Location: include/linux/dma-mapping.h:345
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
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
In drivers/dma/mv_xor.c (ffff8000108081ec)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_xor_probe
  - drivers/dma/mv_xor.c:mv_xor_probe
```
```
In drivers/virtio/virtio_ring.c (ffff800010822fcc)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
```
```
In drivers/tty/serial/8250/8250_dma.c (ffff80001088bd3c)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
```
In drivers/tty/serial/msm_serial.c (ffff8000108a3b7c)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:msm_handle_tx
  - drivers/tty/serial/msm_serial.c:msm_complete_rx_dma
  - drivers/tty/serial/msm_serial.c:msm_complete_tx_dma
  - drivers/tty/serial/msm_serial.c:msm_stop_dma
```
```
In drivers/iommu/io-pgtable-arm.c (ffff8000108cb574)
Location: include/linux/dma-mapping.h:592
Inline: True
```
```
In drivers/iommu/rockchip-iommu.c (ffff8000108d80dc)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_domain_free
  - drivers/iommu/rockchip-iommu.c:rk_iommu_domain_free
```
```
In drivers/net/ethernet/broadcom/bgmac.c (ffff8000109e397c)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_start_xmit
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_cleanup
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_rx_read
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e655c)
Location: include/linux/dma-mapping.h:592
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
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
```
In drivers/usb/dwc2/hcd_intr.c (ffff800010a49f78)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffff800010a4e148)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
```
```
In drivers/usb/host/xhci-ring.c (ffff800010a7c47c)
Location: include/linux/dma-mapping.h:592
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (ffff800010a8bd10)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/firmware/qcom_scm-64.c (ffff800010b4f8a4)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/firmware/qcom_scm-64.c:qcom_scm_call
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
In drivers/dma/mv_xor.c (c0926068)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_xor_probe
  - drivers/dma/mv_xor.c:mv_xor_probe
```
```
In drivers/virtio/virtio_ring.c (c0940b60)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
```
```
In drivers/tty/serial/8250/8250_dma.c (c098970c)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
```
In drivers/tty/serial/msm_serial.c (c099ce28)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:msm_handle_tx
  - drivers/tty/serial/msm_serial.c:msm_complete_rx_dma
  - drivers/tty/serial/msm_serial.c:msm_complete_tx_dma
  - drivers/tty/serial/msm_serial.c:msm_stop_dma
```
```
In drivers/iommu/io-pgtable-arm.c (c09c0654)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/iommu/io-pgtable-arm.c:__arm_lpae_free_pages
  - drivers/iommu/io-pgtable-arm.c:__arm_lpae_alloc_pages
```
```
In drivers/iommu/omap-iommu.c (c09c3f58)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/iommu/omap-iommu.c:omap_iommu_detach
  - drivers/iommu/omap-iommu.c:iopte_alloc
```
```
In drivers/iommu/rockchip-iommu.c (c09c66b8)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_domain_free
  - drivers/iommu/rockchip-iommu.c:rk_iommu_domain_free
```
```
In drivers/iommu/exynos-iommu.c (c09c9d34)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/iommu/exynos-iommu.c:exynos_iommu_domain_free
  - drivers/iommu/exynos-iommu.c:exynos_iommu_domain_free
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0ac9614)
Location: include/linux/dma-mapping.h:592
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
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/davinci_cpdma.c:__cpdma_chan_free
```
```
In drivers/usb/core/hcd.c (c0af3cac)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
```
In drivers/usb/dwc2/hcd_intr.c (c0b1c394)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
```
In drivers/usb/dwc2/hcd_ddma.c (c0b201f4)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
```
```
In drivers/usb/host/xhci-ring.c (c0b50580)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_unmap_td_bounce_buffer
  - drivers/usb/host/xhci-ring.c:xhci_unmap_td_bounce_buffer
```
```
In drivers/usb/host/xhci-dbgcap.c (c0b5e09c)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/usb/gadget/udc/core.c (c0b73ccc)
Location: include/linux/dma-mapping.h:592
Inline: True
```
```
In drivers/i2c/busses/i2c-imx.c (c0b9ab5c)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_dma_xfer
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_dma_callback
```
```
In drivers/firmware/qcom_scm-32.c (c0c36458)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/firmware/qcom_scm-32.c:qcom_scm_call
```
```
In drivers/firmware/tegra/ivc.c (c0c432ec)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/firmware/tegra/ivc.c:tegra_ivc_cleanup
  - drivers/firmware/tegra/ivc.c:tegra_ivc_cleanup
```
```
In drivers/staging/emxx_udc/emxx_udc.c (c0c5c0b4)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_dma_unmap_single
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
In drivers/virtio/virtio_ring.c (c0000000008d08b4)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
```
```
In drivers/tty/serial/8250/8250_dma.c (c00000000093479c)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
```
In drivers/char/tpm/tpm_ibmvtpm.c (c00000000096923c)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_probe
  - drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_remove
  - drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_remove
```
```
In drivers/usb/core/hcd.c (c000000000ad5c1c)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
```
In drivers/usb/dwc2/hcd_intr.c (c000000000b0feb4)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
```
In drivers/usb/dwc2/hcd_ddma.c (c000000000b15a7c)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
```
```
In drivers/usb/host/xhci-ring.c (c000000000b54f60)
Location: include/linux/dma-mapping.h:592
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (c000000000b67d20)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
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
In drivers/virtio/virtio_ring.c (ffffffe000519912)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffe00055565a)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
```
In drivers/usb/core/hcd.c (ffffffe000640172)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffe000666e3c)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffe00066ab22)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
```
```
In drivers/usb/host/xhci-ring.c (ffffffe00069400e)
Location: include/linux/dma-mapping.h:592
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffe0006a09ea)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/mmc/host/mmc_spi.c (ffffffe00071b1a4)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/mmc/host/mmc_spi.c:mmc_spi_remove
  - drivers/mmc/host/mmc_spi.c:mmc_spi_remove
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
In drivers/virtio/virtio_ring.c (ffffffff81622ccf)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816762e0)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
```
In drivers/usb/core/hcd.c (ffffffff817a52df)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff817c92d3)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817cd313)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817f6d80)
Location: include/linux/dma-mapping.h:592
Inline: True
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
In drivers/virtio/virtio_ring.c (ffffffff8161731f)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816553c0)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
```
In drivers/usb/core/hcd.c (ffffffff81796def)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817bbf20)
Location: include/linux/dma-mapping.h:592
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817c9e8d)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
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
In drivers/virtio/virtio_ring.c (ffffffff81650c6f)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816a46b0)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
```
In drivers/usb/core/hcd.c (ffffffff817e1d7f)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81805d73)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81809db3)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81833850)
Location: include/linux/dma-mapping.h:592
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff818417bd)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/i2c/busses/i2c-amd-mp2-plat.c (ffffffff8186893b)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_check_cmd_completion
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
In drivers/virtio/virtio_ring.c (ffffffff8166b2ff)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816beb68)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
```
```
In drivers/usb/core/hcd.c (ffffffff817fc06f)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff8181fe83)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81823ec3)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8184db20)
Location: include/linux/dma-mapping.h:592
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8185bd1d)
Location: include/linux/dma-mapping.h:592
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
</details>
</li>
</ul>

## Differences
