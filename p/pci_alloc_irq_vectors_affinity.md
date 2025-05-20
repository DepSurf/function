# Function: <code>pci_alloc_irq_vectors_affinity</code>

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
<summary>In <code>4.10</code>: ✅</summary>

```c
int pci_alloc_irq_vectors_affinity(struct pci_dev *dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags, const struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814c3120)
Location: drivers/pci/msi.c:1199
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
**Symbols:**

```
ffffffff814c3120-ffffffff814c3274: pci_alloc_irq_vectors_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_alloc_irq_vectors_affinity(struct pci_dev *dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags, const struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814cd620)
Location: drivers/pci/msi.c:1151
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
```
**Symbols:**

```
ffffffff814cd620-ffffffff814cd74c: pci_alloc_irq_vectors_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_alloc_irq_vectors_affinity(struct pci_dev *dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags, const struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8150db60)
Location: drivers/pci/msi.c:1151
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
```
**Symbols:**

```
ffffffff8150db60-ffffffff8150dc8c: pci_alloc_irq_vectors_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_alloc_irq_vectors_affinity(struct pci_dev *dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags, const struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81542a50)
Location: drivers/pci/msi.c:1150
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
```
**Symbols:**

```
ffffffff81542a50-ffffffff81542b67: pci_alloc_irq_vectors_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_alloc_irq_vectors_affinity(struct pci_dev *dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags, const struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81559e20)
Location: drivers/pci/msi.c:1166
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
```
**Symbols:**

```
ffffffff81559e20-ffffffff81559f14: pci_alloc_irq_vectors_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pci_alloc_irq_vectors_affinity(struct pci_dev *dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags, struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/msi.c (0)
Location: drivers/pci/msi.c:1188
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
**Symbols:**

```
ffffffff8158a99e-ffffffff8158a9b4: pci_alloc_irq_vectors_affinity.cold (STB_LOCAL)
ffffffff81589ec0-ffffffff81589ffb: pci_alloc_irq_vectors_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pci_alloc_irq_vectors_affinity(struct pci_dev *dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags, struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff815aba70)
Location: drivers/pci/msi.c:1189
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
**Symbols:**

```
ffffffff815aba70-ffffffff815abba3: pci_alloc_irq_vectors_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_alloc_irq_vectors_affinity(struct pci_dev *dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags, struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81654960)
Location: drivers/pci/msi.c:1189
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_enable
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_setup_msix
```
**Symbols:**

```
ffffffff81654960-ffffffff81654a93: pci_alloc_irq_vectors_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pci_alloc_irq_vectors_affinity(struct pci_dev *dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags, struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8165e620)
Location: drivers/pci/msi.c:1213
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_enable
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_setup_msix
```
**Symbols:**

```
ffffffff8165e620-ffffffff8165e725: pci_alloc_irq_vectors_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pci_alloc_irq_vectors_affinity(struct pci_dev *dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags, struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81640a40)
Location: drivers/pci/msi.c:1219
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_enable
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
**Symbols:**

```
ffffffff81640a40-ffffffff81640b45: pci_alloc_irq_vectors_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pci_alloc_irq_vectors_affinity(struct pci_dev *dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags, struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/msi.c (0)
Location: drivers/pci/msi.c:1127
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_enable
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
**Symbols:**

```
ffffffff81ce5bc8-ffffffff81ce5be6: pci_alloc_irq_vectors_affinity.cold (STB_LOCAL)
ffffffff816b14c0-ffffffff816b1741: pci_alloc_irq_vectors_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pci_alloc_irq_vectors_affinity(struct pci_dev *dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags, struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/msi.c (ffffffff817d4b50)
Location: drivers/pci/msi/msi.c:998
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_enable
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
**Symbols:**

```
ffffffff817d4b50-ffffffff817d4c6b: pci_alloc_irq_vectors_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_alloc_irq_vectors_affinity(struct pci_dev *dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags, struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/api.c (ffffffff818f4290)
Location: drivers/pci/msi/api.c:254
Inline: False
Direct callers:
  - drivers/pci/msi/api.c:pci_alloc_irq_vectors
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
```
**Symbols:**

```
ffffffff818f4290-ffffffff818f43ab: pci_alloc_irq_vectors_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_alloc_irq_vectors_affinity(struct pci_dev *dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags, struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/api.c (ffffffff819376c0)
Location: drivers/pci/msi/api.c:254
Inline: False
Direct callers:
  - drivers/pci/msi/api.c:pci_alloc_irq_vectors
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
```
**Symbols:**

```
ffffffff819376c0-ffffffff819377db: pci_alloc_irq_vectors_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_alloc_irq_vectors_affinity(struct pci_dev *dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags, struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/api.c (ffffffff81980520)
Location: drivers/pci/msi/api.c:254
Inline: False
Direct callers:
  - drivers/pci/msi/api.c:pci_alloc_irq_vectors
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
```
**Symbols:**

```
ffffffff81980520-ffffffff8198063b: pci_alloc_irq_vectors_affinity (STB_GLOBAL)
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
int pci_alloc_irq_vectors_affinity(struct pci_dev *dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags, struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffff800010715400)
Location: drivers/pci/msi.c:1189
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
**Symbols:**

```
ffff800010715400-ffff800010715554: pci_alloc_irq_vectors_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_alloc_irq_vectors_affinity(struct pci_dev *dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags, struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (c089fc78)
Location: drivers/pci/msi.c:1189
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
**Symbols:**

```
c089fc78-c089fdd8: pci_alloc_irq_vectors_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_alloc_irq_vectors_affinity(struct pci_dev *dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags, struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (c000000000884f90)
Location: drivers/pci/msi.c:1189
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
**Symbols:**

```
c000000000884f90-c000000000885180: pci_alloc_irq_vectors_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_alloc_irq_vectors_affinity(struct pci_dev *dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags, struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffe0004deb32)
Location: drivers/pci/msi.c:1189
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
**Symbols:**

```
ffffffe0004deb32-ffffffe0004dec22: pci_alloc_irq_vectors_affinity (STB_GLOBAL)
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
int pci_alloc_irq_vectors_affinity(struct pci_dev *dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags, struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8159f240)
Location: drivers/pci/msi.c:1189
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/nvme/host/pci.c:nvme_reset_work
  - drivers/nvme/host/pci.c:nvme_setup_io_queues
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
**Symbols:**

```
ffffffff8159f240-ffffffff8159f373: pci_alloc_irq_vectors_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pci_alloc_irq_vectors_affinity(struct pci_dev *dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags, struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8158e3d0)
Location: drivers/pci/msi.c:1189
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/nvme/host/pci.c:nvme_reset_work
  - drivers/nvme/host/pci.c:nvme_setup_io_queues
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
**Symbols:**

```
ffffffff8158e3d0-ffffffff8158e503: pci_alloc_irq_vectors_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pci_alloc_irq_vectors_affinity(struct pci_dev *dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags, struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8159f7c0)
Location: drivers/pci/msi.c:1189
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
**Symbols:**

```
ffffffff8159f7c0-ffffffff8159f8f3: pci_alloc_irq_vectors_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pci_alloc_irq_vectors_affinity(struct pci_dev *dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags, struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff815b9bf0)
Location: drivers/pci/msi.c:1189
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
**Symbols:**

```
ffffffff815b9bf0-ffffffff815b9d23: pci_alloc_irq_vectors_affinity (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const struct irq_affinity *affd</code> ➡️ <code>struct irq_affinity *affd</code>
</li>
</ul>
</details>
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
