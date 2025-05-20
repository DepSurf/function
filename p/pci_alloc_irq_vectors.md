# Function: <code>pci_alloc_irq_vectors</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pci_alloc_irq_vectors(struct pci_dev *dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814a15a0)
Location: drivers/pci/msi.c:1185
Inline: False
```
**Symbols:**

```
ffffffff814a15a0-ffffffff814a162a: pci_alloc_irq_vectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff8153f476)
Location: include/linux/pci.h:1390
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
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
In drivers/pci/pcie/portdrv_core.c (ffffffff814c101d)
Location: include/linux/pci.h:1395
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/usb/host/xhci.c (ffffffff816f0304)
Location: include/linux/pci.h:1395
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
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
In drivers/pci/pcie/portdrv_core.c (ffffffff8150144d)
Location: include/linux/pci.h:1420
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/usb/host/xhci.c (ffffffff8175c4c4)
Location: include/linux/pci.h:1420
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
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
In drivers/pci/pcie/portdrv_core.c (ffffffff815303a3)
Location: include/linux/pci.h:1418
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/usb/host/xhci.c (ffffffff8179cec4)
Location: include/linux/pci.h:1418
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
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
In drivers/pci/pcie/portdrv_core.c (ffffffff81547863)
Location: include/linux/pci.h:1452
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/usb/host/xhci.c (ffffffff817c32a4)
Location: include/linux/pci.h:1452
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
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
In drivers/pci/pcie/portdrv_core.c (ffffffff81577965)
Location: include/linux/pci.h:1521
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/usb/host/xhci.c (ffffffff818024ef)
Location: include/linux/pci.h:1521
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
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
In drivers/pci/pcie/portdrv_core.c (ffffffff815990e5)
Location: include/linux/pci.h:1776
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816b3b62)
Location: include/linux/pci.h:1776
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817d8ef1)
Location: include/linux/pci.h:1776
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
```
```
In drivers/usb/host/xhci.c (ffffffff8183135c)
Location: include/linux/pci.h:1776
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
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
In drivers/pci/pcie/portdrv_core.c (ffffffff81638c99)
Location: include/linux/pci.h:1799
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81766aad)
Location: include/linux/pci.h:1799
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff818a67bb)
Location: include/linux/pci.h:1799
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_enable
```
```
In drivers/usb/host/xhci.c (ffffffff8190381e)
Location: include/linux/pci.h:1799
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_setup_msix
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
In drivers/pci/pcie/portdrv_core.c (ffffffff8165f7a9)
Location: include/linux/pci.h:1807
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff817819ed)
Location: include/linux/pci.h:1807
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff818b56ab)
Location: include/linux/pci.h:1807
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_enable
```
```
In drivers/usb/core/hcd-pci.c (ffffffff818dcccc)
Location: include/linux/pci.h:1807
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci.c (ffffffff8190bd8e)
Location: include/linux/pci.h:1807
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_setup_msix
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
In drivers/pci/pcie/portdrv_core.c (ffffffff81641b99)
Location: include/linux/pci.h:1823
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81765350)
Location: include/linux/pci.h:1823
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff81898b4c)
Location: include/linux/pci.h:1823
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_enable
```
```
In drivers/usb/core/hcd-pci.c (ffffffff818c003c)
Location: include/linux/pci.h:1823
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci.c (ffffffff818ef349)
Location: include/linux/pci.h:1823
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
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
In drivers/pci/pcie/portdrv_core.c (ffffffff816b2821)
Location: include/linux/pci.h:1886
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff817e9a8d)
Location: include/linux/pci.h:1886
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff8192c55c)
Location: include/linux/pci.h:1886
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_enable
```
```
In drivers/usb/core/hcd-pci.c (ffffffff819566c1)
Location: include/linux/pci.h:1886
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci.c (ffffffff8198bf09)
Location: include/linux/pci.h:1886
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
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
In drivers/pci/pcie/portdrv_core.c (ffffffff817d617d)
Location: include/linux/pci.h:1905
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81929434)
Location: include/linux/pci.h:1905
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff81a82b93)
Location: include/linux/pci.h:1905
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_enable
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81ab027b)
Location: include/linux/pci.h:1905
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci.c (ffffffff81ae80f0)
Location: include/linux/pci.h:1905
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_alloc_irq_vectors(struct pci_dev *dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/api.c (ffffffff818f43c0)
Location: drivers/pci/msi/api.c:234
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
  - drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/tty/serial/8250/8250_mid.c:dnv_setup
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
**Symbols:**

```
ffffffff818f43c0-ffffffff818f43e2: pci_alloc_irq_vectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_alloc_irq_vectors(struct pci_dev *dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/api.c (ffffffff819377f0)
Location: drivers/pci/msi/api.c:234
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
  - drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/tty/serial/8250/8250_mid.c:dnv_setup
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff819377f0-ffffffff81937812: pci_alloc_irq_vectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_alloc_irq_vectors(struct pci_dev *dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/api.c (ffffffff81980650)
Location: drivers/pci/msi/api.c:234
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
  - drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec
  - drivers/tty/serial/8250/8250_mid.c:dnv_setup
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff81980650-ffffffff81980672: pci_alloc_irq_vectors (STB_GLOBAL)
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
In drivers/pci/pcie/portdrv_core.c (ffff8000107007ac)
Location: include/linux/pci.h:1776
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/tty/serial/8250/8250_pci.c (ffff80001088f6cc)
Location: include/linux/pci.h:1776
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
```
```
In drivers/usb/host/xhci.c (ffff800010a6d864)
Location: include/linux/pci.h:1776
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
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
In drivers/pci/pcie/portdrv_core.c (c0898528)
Location: include/linux/pci.h:1776
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/tty/serial/8250/8250_pci.c (c098c8a4)
Location: include/linux/pci.h:1776
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
```
```
In drivers/usb/host/xhci.c (c0b41ef4)
Location: include/linux/pci.h:1776
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
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
In drivers/tty/serial/8250/8250_pci.c (c000000000937ba4)
Location: include/linux/pci.h:1776
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (c000000000ab8ea0)
Location: include/linux/pci.h:1776
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
```
```
In drivers/usb/host/xhci.c (c000000000b41910)
Location: include/linux/pci.h:1776
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
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
In drivers/pci/pcie/portdrv_core.c (ffffffe0004cf736)
Location: include/linux/pci.h:1776
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffe00055935a)
Location: include/linux/pci.h:1776
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
```
```
In drivers/usb/host/xhci.c (ffffffe000686cf2)
Location: include/linux/pci.h:1776
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
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
In drivers/pci/pcie/portdrv_core.c (ffffffff8158cf75)
Location: include/linux/pci.h:1776
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816795c2)
Location: include/linux/pci.h:1776
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
```
```
In drivers/nvme/host/pci.c (ffffffff81750a47)
Location: include/linux/pci.h:1776
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_reset_work
```
```
In drivers/usb/host/xhci.c (ffffffff817e973c)
Location: include/linux/pci.h:1776
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
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
In drivers/pci/pcie/portdrv_core.c (ffffffff8157bab5)
Location: include/linux/pci.h:1776
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816586b2)
Location: include/linux/pci.h:1776
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
```
```
In drivers/nvme/host/pci.c (ffffffff817308e7)
Location: include/linux/pci.h:1776
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_reset_work
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff81782fa1)
Location: include/linux/pci.h:1776
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
```
```
In drivers/usb/host/xhci.c (ffffffff817ae84c)
Location: include/linux/pci.h:1776
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
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
In drivers/pci/pcie/portdrv_core.c (ffffffff8158ce35)
Location: include/linux/pci.h:1776
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816a79a2)
Location: include/linux/pci.h:1776
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817cdd71)
Location: include/linux/pci.h:1776
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
```
```
In drivers/usb/host/xhci.c (ffffffff818261dc)
Location: include/linux/pci.h:1776
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
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
In drivers/pci/pcie/portdrv_core.c (ffffffff815a72e5)
Location: include/linux/pci.h:1776
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816c1e02)
Location: include/linux/pci.h:1776
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817e8011)
Location: include/linux/pci.h:1776
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
```
```
In drivers/usb/host/xhci.c (ffffffff818400bc)
Location: include/linux/pci.h:1776
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
