# Function: <code>pci_disable_msix</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_msix(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814552f0)
Location: drivers/pci/msi.c:1002
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/pcie/portdrv_core.c:cleanup_service_irqs
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/virtio/virtio_pci_common.c:vp_free_vectors
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_run
```
**Symbols:**

```
ffffffff814552f0-ffffffff81455327: pci_disable_msix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_msix(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814a1f20)
Location: drivers/pci/msi.c:1015
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:cleanup_service_irqs
  - drivers/pci/msi.c:pci_free_irq_vectors
  - drivers/virtio/virtio_pci_common.c:vp_free_vectors
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
```
**Symbols:**

```
ffffffff814a1f20-ffffffff814a1f57: pci_disable_msix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_msix(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814c3b70)
Location: drivers/pci/msi.c:1035
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/pcie/portdrv_core.c:cleanup_service_irqs
  - drivers/pci/msi.c:pci_free_irq_vectors
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_setup_msix
```
**Symbols:**

```
ffffffff814c3b70-ffffffff814c3ba7: pci_disable_msix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_msix(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814cd1e0)
Location: drivers/pci/msi.c:995
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/msi.c:pci_free_irq_vectors
```
**Symbols:**

```
ffffffff814cd1e0-ffffffff814cd2fa: pci_disable_msix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_msix(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8150d720)
Location: drivers/pci/msi.c:995
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/msi.c:pci_free_irq_vectors
```
**Symbols:**

```
ffffffff8150d720-ffffffff8150d83a: pci_disable_msix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_msix(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81542610)
Location: drivers/pci/msi.c:995
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/msi.c:pci_free_irq_vectors
```
**Symbols:**

```
ffffffff81542610-ffffffff8154272a: pci_disable_msix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_msix(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff815599c0)
Location: drivers/pci/msi.c:993
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/msi.c:pci_free_irq_vectors
```
**Symbols:**

```
ffffffff815599c0-ffffffff81559ad7: pci_disable_msix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_msix(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81589a80)
Location: drivers/pci/msi.c:1028
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/msi.c:pci_free_irq_vectors
```
**Symbols:**

```
ffffffff81589a80-ffffffff81589ba5: pci_disable_msix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_msix(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff815aaeb0)
Location: drivers/pci/msi.c:1029
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/msi.c:pci_free_irq_vectors
```
**Symbols:**

```
ffffffff815aaeb0-ffffffff815aafd5: pci_disable_msix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_msix(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81654ae0)
Location: drivers/pci/msi.c:1029
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/msi.c:pci_free_irq_vectors
```
**Symbols:**

```
ffffffff81654ae0-ffffffff81654c03: pci_disable_msix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_msix(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8165d8c0)
Location: drivers/pci/msi.c:1053
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/msi.c:pci_free_irq_vectors
```
**Symbols:**

```
ffffffff8165d8c0-ffffffff8165d9e3: pci_disable_msix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_msix(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81640250)
Location: drivers/pci/msi.c:1059
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/msi.c:pci_free_irq_vectors
```
**Symbols:**

```
ffffffff81640250-ffffffff81640373: pci_disable_msix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_msix(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff816b1750)
Location: drivers/pci/msi.c:967
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/msi.c:pci_free_irq_vectors
```
**Symbols:**

```
ffffffff816b1750-ffffffff816b1875: pci_disable_msix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_disable_msix(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/msi/msi.c (ffffffff817d4eac)
Location: drivers/pci/msi/msi.c:845
Inline: True
Inline callers:
  - drivers/pci/msi/msi.c:pcim_msi_release
Direct callers:
  - drivers/pci/msi/msi.c:pcim_msi_release
```
**Symbols:**

```
ffffffff817d4c70-ffffffff817d4dde: pci_disable_msix.part.0 (STB_LOCAL)
ffffffff817d4de0-ffffffff817d4e19: pci_disable_msix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_msix(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/api.c (ffffffff818f4580)
Location: drivers/pci/msi/api.c:194
Inline: True
Direct callers:
  - drivers/pci/msi/api.c:pci_free_irq_vectors
```
**Symbols:**

```
ffffffff818f4580-ffffffff818f45f1: pci_disable_msix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_msix(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/api.c (ffffffff819379b0)
Location: drivers/pci/msi/api.c:194
Inline: True
Direct callers:
  - drivers/pci/msi/api.c:pci_free_irq_vectors
```
**Symbols:**

```
ffffffff819379b0-ffffffff81937a21: pci_disable_msix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_msix(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/api.c (ffffffff81980810)
Location: drivers/pci/msi/api.c:194
Inline: True
Direct callers:
  - drivers/pci/msi/api.c:pci_free_irq_vectors
```
**Symbols:**

```
ffffffff81980810-ffffffff81980881: pci_disable_msix (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_msix(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffff8000107145e8)
Location: drivers/pci/msi.c:1029
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/msi.c:pci_free_irq_vectors
```
**Symbols:**

```
ffff8000107145e8-ffff800010714730: pci_disable_msix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_msix(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (c089fdd8)
Location: drivers/pci/msi.c:1029
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/msi.c:pci_free_irq_vectors
```
**Symbols:**

```
c089fdd8-c089ff08: pci_disable_msix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_msix(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (c000000000885180)
Location: drivers/pci/msi.c:1029
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/msi.c:pci_free_irq_vectors
```
**Symbols:**

```
c000000000885180-c00000000088530c: pci_disable_msix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_msix(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffe0004dec22)
Location: drivers/pci/msi.c:1029
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/msi.c:pci_free_irq_vectors
```
**Symbols:**

```
ffffffe0004dec22-ffffffe0004ded0c: pci_disable_msix (STB_GLOBAL)
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
void pci_disable_msix(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8159e680)
Location: drivers/pci/msi.c:1029
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/msi.c:pci_free_irq_vectors
```
**Symbols:**

```
ffffffff8159e680-ffffffff8159e7a5: pci_disable_msix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_msix(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8158d810)
Location: drivers/pci/msi.c:1029
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/msi.c:pci_free_irq_vectors
```
**Symbols:**

```
ffffffff8158d810-ffffffff8158d935: pci_disable_msix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_msix(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8159ec00)
Location: drivers/pci/msi.c:1029
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/msi.c:pci_free_irq_vectors
```
**Symbols:**

```
ffffffff8159ec00-ffffffff8159ed25: pci_disable_msix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_msix(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff815b9030)
Location: drivers/pci/msi.c:1029
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/msi.c:pci_free_irq_vectors
```
**Symbols:**

```
ffffffff815b9030-ffffffff815b9155: pci_disable_msix (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
