# Function: <code>pci_free_irq_vectors</code>

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
void pci_free_irq_vectors(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814a1f60)
Location: drivers/pci/msi.c:1219
Inline: False
```
**Symbols:**

```
ffffffff814a1f60-ffffffff814a1f7d: pci_free_irq_vectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pci_free_irq_vectors(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814c3bb0)
Location: drivers/pci/msi.c:1253
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
```
**Symbols:**

```
ffffffff814c3bb0-ffffffff814c3bcd: pci_free_irq_vectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pci_free_irq_vectors(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814cd870)
Location: drivers/pci/msi.c:1197
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
```
**Symbols:**

```
ffffffff814cd870-ffffffff814cd88d: pci_free_irq_vectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pci_free_irq_vectors(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8150ddb0)
Location: drivers/pci/msi.c:1197
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
```
**Symbols:**

```
ffffffff8150ddb0-ffffffff8150ddcd: pci_free_irq_vectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pci_free_irq_vectors(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81542c90)
Location: drivers/pci/msi.c:1196
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
```
**Symbols:**

```
ffffffff81542c90-ffffffff81542cad: pci_free_irq_vectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pci_free_irq_vectors(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8155a040)
Location: drivers/pci/msi.c:1216
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
```
**Symbols:**

```
ffffffff8155a040-ffffffff8155a05d: pci_free_irq_vectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pci_free_irq_vectors(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8158a130)
Location: drivers/pci/msi.c:1245
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
```
**Symbols:**

```
ffffffff8158a130-ffffffff8158a14f: pci_free_irq_vectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pci_free_irq_vectors(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff815ab420)
Location: drivers/pci/msi.c:1246
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
```
**Symbols:**

```
ffffffff815ab420-ffffffff815ab43f: pci_free_irq_vectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pci_free_irq_vectors(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81654c10)
Location: drivers/pci/msi.c:1246
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_enable
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_setup_msix
```
**Symbols:**

```
ffffffff81654c10-ffffffff81654c31: pci_free_irq_vectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pci_free_irq_vectors(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8165e1b0)
Location: drivers/pci/msi.c:1266
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_enable
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_setup_msix
```
**Symbols:**

```
ffffffff8165e1b0-ffffffff8165e1d1: pci_free_irq_vectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pci_free_irq_vectors(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81640530)
Location: drivers/pci/msi.c:1272
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_enable
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
```
**Symbols:**

```
ffffffff81640530-ffffffff81640551: pci_free_irq_vectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pci_free_irq_vectors(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff816b1880)
Location: drivers/pci/msi.c:1180
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_enable
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
```
**Symbols:**

```
ffffffff816b1880-ffffffff816b18a1: pci_free_irq_vectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void pci_free_irq_vectors(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/msi.c (ffffffff817d4eac)
Location: drivers/pci/msi/msi.c:1051
Inline: True
Inline callers:
  - drivers/pci/msi/msi.c:pcim_msi_release
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_enable
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
```
**Symbols:**

```
ffffffff817d4e20-ffffffff817d4e9a: pci_free_irq_vectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pci_free_irq_vectors(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/api.c (ffffffff818f4840)
Location: drivers/pci/msi/api.c:426
Inline: False
Direct callers:
  - drivers/pci/msi/msi.c:pcim_msi_release
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_shutdown
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_remove
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
  - drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
```
**Symbols:**

```
ffffffff818f4840-ffffffff818f48ad: pci_free_irq_vectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pci_free_irq_vectors(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/api.c (ffffffff81937c70)
Location: drivers/pci/msi/api.c:426
Inline: False
Direct callers:
  - drivers/pci/msi/msi.c:pcim_msi_release
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_shutdown
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_remove
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
  - drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff81937c70-ffffffff81937cdd: pci_free_irq_vectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pci_free_irq_vectors(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/api.c (ffffffff81980ad0)
Location: drivers/pci/msi/api.c:426
Inline: False
Direct callers:
  - drivers/pci/msi/msi.c:pcim_msi_release
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_shutdown
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_remove
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
  - drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec
  - drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff81980ad0-ffffffff81980b3d: pci_free_irq_vectors (STB_GLOBAL)
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
void pci_free_irq_vectors(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffff800010714bc0)
Location: drivers/pci/msi.c:1246
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
```
**Symbols:**

```
ffff800010714bc0-ffff800010714bf4: pci_free_irq_vectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pci_free_irq_vectors(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (c089ff08)
Location: drivers/pci/msi.c:1246
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
```
**Symbols:**

```
c089ff08-c089ff30: pci_free_irq_vectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pci_free_irq_vectors(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (c000000000885310)
Location: drivers/pci/msi.c:1246
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
```
**Symbols:**

```
c000000000885310-c000000000885350: pci_free_irq_vectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pci_free_irq_vectors(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffe0004ded0c)
Location: drivers/pci/msi.c:1246
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
```
**Symbols:**

```
ffffffe0004ded0c-ffffffe0004ded40: pci_free_irq_vectors (STB_GLOBAL)
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
void pci_free_irq_vectors(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8159ebf0)
Location: drivers/pci/msi.c:1246
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/nvme/host/pci.c:nvme_dev_disable
  - drivers/nvme/host/pci.c:nvme_setup_io_queues
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
```
**Symbols:**

```
ffffffff8159ebf0-ffffffff8159ec0f: pci_free_irq_vectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pci_free_irq_vectors(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8158dd80)
Location: drivers/pci/msi.c:1246
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/nvme/host/pci.c:nvme_dev_disable
  - drivers/nvme/host/pci.c:nvme_setup_io_queues
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
```
**Symbols:**

```
ffffffff8158dd80-ffffffff8158dd9f: pci_free_irq_vectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pci_free_irq_vectors(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8159f170)
Location: drivers/pci/msi.c:1246
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
```
**Symbols:**

```
ffffffff8159f170-ffffffff8159f18f: pci_free_irq_vectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pci_free_irq_vectors(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff815b95a0)
Location: drivers/pci/msi.c:1246
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
```
**Symbols:**

```
ffffffff815b95a0-ffffffff815b95bf: pci_free_irq_vectors (STB_GLOBAL)
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
