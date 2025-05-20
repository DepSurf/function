# Function: <code>pci_enable_msi</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_enable_msi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814cd5f0)
Location: drivers/pci/msi.c:1073
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
```
**Symbols:**

```
ffffffff814cd5f0-ffffffff814cd616: pci_enable_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_enable_msi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8150db30)
Location: drivers/pci/msi.c:1073
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
```
**Symbols:**

```
ffffffff8150db30-ffffffff8150db56: pci_enable_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_enable_msi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81542a20)
Location: drivers/pci/msi.c:1072
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
```
**Symbols:**

```
ffffffff81542a20-ffffffff81542a46: pci_enable_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_enable_msi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81559df0)
Location: drivers/pci/msi.c:1078
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
```
**Symbols:**

```
ffffffff81559df0-ffffffff81559e16: pci_enable_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pci_enable_msi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81589e90)
Location: drivers/pci/msi.c:1106
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
```
**Symbols:**

```
ffffffff81589e90-ffffffff81589eb6: pci_enable_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pci_enable_msi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff815ab2c0)
Location: drivers/pci/msi.c:1107
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
```
**Symbols:**

```
ffffffff815ab2c0-ffffffff815ab2e6: pci_enable_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_enable_msi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff816541a0)
Location: drivers/pci/msi.c:1107
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
```
**Symbols:**

```
ffffffff816541a0-ffffffff816541c6: pci_enable_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pci_enable_msi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8165e5f0)
Location: drivers/pci/msi.c:1131
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
```
**Symbols:**

```
ffffffff8165e5f0-ffffffff8165e616: pci_enable_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pci_enable_msi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81640a10)
Location: drivers/pci/msi.c:1137
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
```
**Symbols:**

```
ffffffff81640a10-ffffffff81640a33: pci_enable_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pci_enable_msi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff816b0e70)
Location: drivers/pci/msi.c:1045
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
```
**Symbols:**

```
ffffffff816b0e70-ffffffff816b0e93: pci_enable_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pci_enable_msi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/msi.c (ffffffff817d4390)
Location: drivers/pci/msi/msi.c:912
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
```
**Symbols:**

```
ffffffff817d4390-ffffffff817d43bf: pci_enable_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_enable_msi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/api.c (ffffffff818f40e0)
Location: drivers/pci/msi/api.c:30
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
```
**Symbols:**

```
ffffffff818f40e0-ffffffff818f410f: pci_enable_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_enable_msi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/api.c (ffffffff81937510)
Location: drivers/pci/msi/api.c:30
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
```
**Symbols:**

```
ffffffff81937510-ffffffff8193753f: pci_enable_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_enable_msi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/api.c (ffffffff81980370)
Location: drivers/pci/msi/api.c:30
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
```
**Symbols:**

```
ffffffff81980370-ffffffff8198039f: pci_enable_msi (STB_GLOBAL)
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
int pci_enable_msi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffff800010714a48)
Location: drivers/pci/msi.c:1107
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
```
**Symbols:**

```
ffff800010714a48-ffff800010714a88: pci_enable_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_enable_msi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (c089f430)
Location: drivers/pci/msi.c:1107
Inline: False
```
**Symbols:**

```
c089f430-c089f45c: pci_enable_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_enable_msi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (c000000000884470)
Location: drivers/pci/msi.c:1107
Inline: False
```
**Symbols:**

```
c000000000884470-c0000000008844bc: pci_enable_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_enable_msi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffe0004de3f2)
Location: drivers/pci/msi.c:1107
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
```
**Symbols:**

```
ffffffe0004de3f2-ffffffe0004de42e: pci_enable_msi (STB_GLOBAL)
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
int pci_enable_msi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8159ea90)
Location: drivers/pci/msi.c:1107
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
```
**Symbols:**

```
ffffffff8159ea90-ffffffff8159eab6: pci_enable_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pci_enable_msi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8158dc20)
Location: drivers/pci/msi.c:1107
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
```
**Symbols:**

```
ffffffff8158dc20-ffffffff8158dc46: pci_enable_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pci_enable_msi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8159f010)
Location: drivers/pci/msi.c:1107
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
```
**Symbols:**

```
ffffffff8159f010-ffffffff8159f036: pci_enable_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pci_enable_msi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff815b9440)
Location: drivers/pci/msi.c:1107
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
```
**Symbols:**

```
ffffffff815b9440-ffffffff815b9466: pci_enable_msi (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
