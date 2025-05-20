# Function: <code>pci_disable_msi</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_msi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814551b0)
Location: drivers/pci/msi.c:901
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/pcie/portdrv_core.c:cleanup_service_irqs
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_run
```
**Symbols:**

```
ffffffff814551b0-ffffffff814551e7: pci_disable_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_msi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814a1de0)
Location: drivers/pci/msi.c:915
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/pcie/portdrv_core.c:cleanup_service_irqs
  - drivers/pci/msi.c:pci_free_irq_vectors
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
```
**Symbols:**

```
ffffffff814a1de0-ffffffff814a1e17: pci_disable_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_msi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814c3a30)
Location: drivers/pci/msi.c:929
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/pcie/portdrv_core.c:cleanup_service_irqs
  - drivers/pci/msi.c:pci_free_irq_vectors
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
```
**Symbols:**

```
ffffffff814c3a30-ffffffff814c3a67: pci_disable_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_msi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814cd750)
Location: drivers/pci/msi.c:905
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/msi.c:pci_free_irq_vectors
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
```
**Symbols:**

```
ffffffff814cd750-ffffffff814cd86b: pci_disable_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_msi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8150dc90)
Location: drivers/pci/msi.c:905
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/msi.c:pci_free_irq_vectors
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
```
**Symbols:**

```
ffffffff8150dc90-ffffffff8150ddab: pci_disable_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_msi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81542b70)
Location: drivers/pci/msi.c:905
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/pci/msi.c:pci_free_irq_vectors
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
```
**Symbols:**

```
ffffffff81542b70-ffffffff81542c8e: pci_disable_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_msi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81559f20)
Location: drivers/pci/msi.c:904
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/pci/msi.c:pci_free_irq_vectors
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
```
**Symbols:**

```
ffffffff81559f20-ffffffff8155a03e: pci_disable_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_msi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8158a000)
Location: drivers/pci/msi.c:939
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/pci/msi.c:pci_free_irq_vectors
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
```
**Symbols:**

```
ffffffff8158a000-ffffffff8158a124: pci_disable_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_msi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff815ab2f0)
Location: drivers/pci/msi.c:940
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/pci/msi.c:pci_free_irq_vectors
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
```
**Symbols:**

```
ffffffff815ab2f0-ffffffff815ab414: pci_disable_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_msi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff816541d0)
Location: drivers/pci/msi.c:940
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/pci/msi.c:pci_free_irq_vectors
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
```
**Symbols:**

```
ffffffff816541d0-ffffffff8165430b: pci_disable_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_msi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8165e070)
Location: drivers/pci/msi.c:964
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/msi.c:pci_free_irq_vectors
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
```
**Symbols:**

```
ffffffff8165e070-ffffffff8165e1ab: pci_disable_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_msi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81640410)
Location: drivers/pci/msi.c:972
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/msi.c:pci_free_irq_vectors
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
```
**Symbols:**

```
ffffffff81640410-ffffffff81640530: pci_disable_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_msi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff816b09a0)
Location: drivers/pci/msi.c:880
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/msi.c:pci_free_irq_vectors
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
```
**Symbols:**

```
ffffffff816b09a0-ffffffff816b0abb: pci_disable_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_disable_msi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/msi/msi.c (ffffffff817d4eff)
Location: drivers/pci/msi/msi.c:756
Inline: True
Inline callers:
  - drivers/pci/msi/msi.c:pcim_msi_release
Direct callers:
  - drivers/pci/msi/msi.c:pcim_msi_release
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
```
**Symbols:**

```
ffffffff817d43c0-ffffffff817d4518: pci_disable_msi.part.0 (STB_LOCAL)
ffffffff817d4520-ffffffff817d4559: pci_disable_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_msi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/api.c (ffffffff818f4854)
Location: drivers/pci/msi/api.c:51
Inline: True
Inline callers:
  - drivers/pci/msi/api.c:pci_free_irq_vectors
  - drivers/pci/msi/api.c:pci_free_irq_vectors
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
```
**Symbols:**

```
ffffffff818f4440-ffffffff818f44b1: pci_disable_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_msi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/api.c (ffffffff81937c84)
Location: drivers/pci/msi/api.c:51
Inline: True
Inline callers:
  - drivers/pci/msi/api.c:pci_free_irq_vectors
  - drivers/pci/msi/api.c:pci_free_irq_vectors
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
```
**Symbols:**

```
ffffffff81937870-ffffffff819378e1: pci_disable_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_msi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/api.c (ffffffff81980ae4)
Location: drivers/pci/msi/api.c:51
Inline: True
Inline callers:
  - drivers/pci/msi/api.c:pci_free_irq_vectors
  - drivers/pci/msi/api.c:pci_free_irq_vectors
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
```
**Symbols:**

```
ffffffff819806d0-ffffffff81980741: pci_disable_msi (STB_GLOBAL)
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
void pci_disable_msi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffff800010714a88)
Location: drivers/pci/msi.c:940
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/pci/msi.c:pci_free_irq_vectors
```
**Symbols:**

```
ffff800010714a88-ffff800010714bbc: pci_disable_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_msi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (c089f45c)
Location: drivers/pci/msi.c:940
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/msi.c:pci_free_irq_vectors
```
**Symbols:**

```
c089f45c-c089f594: pci_disable_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_msi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (c0000000008844c0)
Location: drivers/pci/msi.c:940
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/msi.c:pci_free_irq_vectors
```
**Symbols:**

```
c0000000008844c0-c00000000088465c: pci_disable_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_msi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffe0004de42e)
Location: drivers/pci/msi.c:940
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/pci/msi.c:pci_free_irq_vectors
```
**Symbols:**

```
ffffffe0004de42e-ffffffe0004de522: pci_disable_msi (STB_GLOBAL)
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
void pci_disable_msi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8159eac0)
Location: drivers/pci/msi.c:940
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/pci/msi.c:pci_free_irq_vectors
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
```
**Symbols:**

```
ffffffff8159eac0-ffffffff8159ebe4: pci_disable_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_msi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8158dc50)
Location: drivers/pci/msi.c:940
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/pci/msi.c:pci_free_irq_vectors
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
```
**Symbols:**

```
ffffffff8158dc50-ffffffff8158dd74: pci_disable_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_msi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8159f040)
Location: drivers/pci/msi.c:940
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/pci/msi.c:pci_free_irq_vectors
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
```
**Symbols:**

```
ffffffff8159f040-ffffffff8159f164: pci_disable_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_msi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff815b9470)
Location: drivers/pci/msi.c:940
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/pci/msi.c:pci_free_irq_vectors
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
```
**Symbols:**

```
ffffffff815b9470-ffffffff815b9594: pci_disable_msi (STB_GLOBAL)
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
