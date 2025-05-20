# Function: <code>pci_irq_vector</code>

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
int pci_irq_vector(struct pci_dev *dev, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814a0120)
Location: drivers/pci/msi.c:1231
Inline: False
```
**Symbols:**

```
ffffffff814a0120-ffffffff814a0215: pci_irq_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pci_irq_vector(struct pci_dev *dev, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814c1ca0)
Location: drivers/pci/msi.c:1265
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
```
**Symbols:**

```
ffffffff814c1ca0-ffffffff814c1d95: pci_irq_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_irq_vector(struct pci_dev *dev, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814cc1c0)
Location: drivers/pci/msi.c:1209
Inline: False
Direct callers:
  - drivers/pci/irq.c:pci_free_irq
  - drivers/pci/irq.c:pci_request_irq
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
```
**Symbols:**

```
ffffffff814cc1c0-ffffffff814cc23c: pci_irq_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_irq_vector(struct pci_dev *dev, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8150c6f0)
Location: drivers/pci/msi.c:1209
Inline: False
Direct callers:
  - drivers/pci/irq.c:pci_free_irq
  - drivers/pci/irq.c:pci_request_irq
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
```
**Symbols:**

```
ffffffff8150c6f0-ffffffff8150c76c: pci_irq_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_irq_vector(struct pci_dev *dev, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81541490)
Location: drivers/pci/msi.c:1208
Inline: False
Direct callers:
  - drivers/pci/irq.c:pci_free_irq
  - drivers/pci/irq.c:pci_request_irq
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
```
**Symbols:**

```
ffffffff81541490-ffffffff8154150c: pci_irq_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_irq_vector(struct pci_dev *dev, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff815587f0)
Location: drivers/pci/msi.c:1228
Inline: False
Direct callers:
  - drivers/pci/irq.c:pci_free_irq
  - drivers/pci/irq.c:pci_request_irq
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
```
**Symbols:**

```
ffffffff815587f0-ffffffff8155886c: pci_irq_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pci_irq_vector(struct pci_dev *dev, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81588920)
Location: drivers/pci/msi.c:1257
Inline: False
Direct callers:
  - drivers/pci/irq.c:pci_free_irq
  - drivers/pci/irq.c:pci_request_irq
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
```
**Symbols:**

```
ffffffff81588920-ffffffff8158899c: pci_irq_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int pci_irq_vector(struct pci_dev *dev, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff815aa6b0)
Location: drivers/pci/msi.c:1258
Inline: True
Direct callers:
  - drivers/pci/irq.c:pci_free_irq
  - drivers/pci/irq.c:pci_request_irq
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
```
**Symbols:**

```
ffffffff815aa6b0-ffffffff815aa72c: pci_irq_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_irq_vector(struct pci_dev *dev, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81653140)
Location: drivers/pci/msi.c:1258
Inline: False
Direct callers:
  - drivers/pci/irq.c:pci_free_irq
  - drivers/pci/irq.c:pci_request_irq
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_setup_msix
  - drivers/usb/host/xhci.c:xhci_setup_msix
```
**Symbols:**

```
ffffffff81653140-ffffffff816531bc: pci_irq_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pci_irq_vector(struct pci_dev *dev, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8165ce70)
Location: drivers/pci/msi.c:1278
Inline: False
Direct callers:
  - drivers/pci/irq.c:pci_free_irq
  - drivers/pci/irq.c:pci_request_irq
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_setup_msix
  - drivers/usb/host/xhci.c:xhci_setup_msix
```
**Symbols:**

```
ffffffff8165ce70-ffffffff8165ceec: pci_irq_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pci_irq_vector(struct pci_dev *dev, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8163f410)
Location: drivers/pci/msi.c:1284
Inline: False
Direct callers:
  - drivers/pci/irq.c:pci_free_irq
  - drivers/pci/irq.c:pci_request_irq
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
```
**Symbols:**

```
ffffffff8163f410-ffffffff8163f48c: pci_irq_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pci_irq_vector(struct pci_dev *dev, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff816b0340)
Location: drivers/pci/msi.c:1199
Inline: False
Direct callers:
  - drivers/pci/irq.c:pci_free_irq
  - drivers/pci/irq.c:pci_request_irq
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
```
**Symbols:**

```
ffffffff816b0340-ffffffff816b03b5: pci_irq_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int pci_irq_vector(struct pci_dev *dev, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/msi.c (ffffffff817d3d8e)
Location: drivers/pci/msi/msi.c:1070
Inline: True
Inline callers:
  - drivers/pci/msi/msi.c:pci_irq_get_affinity
  - drivers/pci/msi/msi.c:pci_irq_get_affinity
Direct callers:
  - drivers/pci/irq.c:pci_free_irq
  - drivers/pci/irq.c:pci_request_irq
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
```
**Symbols:**

```
ffffffff817d3d20-ffffffff817d3d7c: pci_irq_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int pci_irq_vector(struct pci_dev *dev, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/api.c (ffffffff818f478e)
Location: drivers/pci/msi/api.c:313
Inline: True
Inline callers:
  - drivers/pci/msi/api.c:pci_irq_get_affinity
  - drivers/pci/msi/api.c:pci_irq_get_affinity
Direct callers:
  - drivers/pci/irq.c:pci_free_irq
  - drivers/pci/irq.c:pci_request_irq
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
  - drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec
  - drivers/virtio/virtio_pci_modern.c:vp_modern_disable_vq_and_reset
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/tty/serial/8250/8250_mid.c:dnv_setup
  - drivers/tty/serial/8250/8250_mid.c:dnv_setup
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
```
**Symbols:**

```
ffffffff818f4610-ffffffff818f4678: pci_irq_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int pci_irq_vector(struct pci_dev *dev, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/api.c (ffffffff81937bbe)
Location: drivers/pci/msi/api.c:313
Inline: True
Inline callers:
  - drivers/pci/msi/api.c:pci_irq_get_affinity
  - drivers/pci/msi/api.c:pci_irq_get_affinity
Direct callers:
  - drivers/pci/irq.c:pci_free_irq
  - drivers/pci/irq.c:pci_request_irq
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
  - drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec
  - drivers/virtio/virtio_pci_modern.c:vp_modern_disable_vq_and_reset
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/tty/serial/8250/8250_mid.c:dnv_setup
  - drivers/tty/serial/8250/8250_mid.c:dnv_setup
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff81937a40-ffffffff81937aa8: pci_irq_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int pci_irq_vector(struct pci_dev *dev, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/api.c (ffffffff81980a1e)
Location: drivers/pci/msi/api.c:313
Inline: True
Inline callers:
  - drivers/pci/msi/api.c:pci_irq_get_affinity
  - drivers/pci/msi/api.c:pci_irq_get_affinity
Direct callers:
  - drivers/pci/irq.c:pci_free_irq
  - drivers/pci/irq.c:pci_request_irq
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
  - drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec
  - drivers/virtio/virtio_pci_modern.c:vp_modern_disable_vq_and_reset
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
  - drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/tty/serial/8250/8250_mid.c:dnv_setup
  - drivers/tty/serial/8250/8250_mid.c:dnv_setup
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff819808a0-ffffffff81980908: pci_irq_vector (STB_GLOBAL)
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
int pci_irq_vector(struct pci_dev *dev, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffff800010713748)
Location: drivers/pci/msi.c:1258
Inline: False
Direct callers:
  - drivers/pci/irq.c:pci_free_irq
  - drivers/pci/irq.c:pci_request_irq
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
```
**Symbols:**

```
ffff800010713748-ffff800010713808: pci_irq_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_irq_vector(struct pci_dev *dev, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (c089e2e4)
Location: drivers/pci/msi.c:1258
Inline: False
Direct callers:
  - drivers/pci/irq.c:pci_free_irq
  - drivers/pci/irq.c:pci_request_irq
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
```
**Symbols:**

```
c089e2e4-c089e41c: pci_irq_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_irq_vector(struct pci_dev *dev, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (c000000000883020)
Location: drivers/pci/msi.c:1258
Inline: False
Direct callers:
  - drivers/pci/irq.c:pci_free_irq
  - drivers/pci/irq.c:pci_request_irq
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
```
**Symbols:**

```
c000000000883020-c0000000008830d4: pci_irq_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_irq_vector(struct pci_dev *dev, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffe0004dd512)
Location: drivers/pci/msi.c:1258
Inline: False
Direct callers:
  - drivers/pci/irq.c:pci_free_irq
  - drivers/pci/irq.c:pci_request_irq
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
```
**Symbols:**

```
ffffffe0004dd512-ffffffe0004dd5aa: pci_irq_vector (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int pci_irq_vector(struct pci_dev *dev, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8159de80)
Location: drivers/pci/msi.c:1258
Inline: True
Direct callers:
  - drivers/pci/irq.c:pci_free_irq
  - drivers/pci/irq.c:pci_request_irq
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/nvme/host/pci.c:nvme_poll_irqdisable
  - drivers/nvme/host/pci.c:nvme_poll_irqdisable
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
```
**Symbols:**

```
ffffffff8159de80-ffffffff8159defc: pci_irq_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int pci_irq_vector(struct pci_dev *dev, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8158d010)
Location: drivers/pci/msi.c:1258
Inline: True
Direct callers:
  - drivers/pci/irq.c:pci_free_irq
  - drivers/pci/irq.c:pci_request_irq
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/nvme/host/pci.c:nvme_poll_irqdisable
  - drivers/nvme/host/pci.c:nvme_poll_irqdisable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
```
**Symbols:**

```
ffffffff8158d010-ffffffff8158d08c: pci_irq_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int pci_irq_vector(struct pci_dev *dev, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8159e400)
Location: drivers/pci/msi.c:1258
Inline: True
Direct callers:
  - drivers/pci/irq.c:pci_free_irq
  - drivers/pci/irq.c:pci_request_irq
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
```
**Symbols:**

```
ffffffff8159e400-ffffffff8159e47c: pci_irq_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int pci_irq_vector(struct pci_dev *dev, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff815b8830)
Location: drivers/pci/msi.c:1258
Inline: True
Direct callers:
  - drivers/pci/irq.c:pci_free_irq
  - drivers/pci/irq.c:pci_request_irq
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
```
**Symbols:**

```
ffffffff815b8830-ffffffff815b88ac: pci_irq_vector (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
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
