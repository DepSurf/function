# Function: <code>alloc_irq_table</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct irq_remap_table *alloc_irq_table(u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816679d0)
Location: drivers/iommu/amd_iommu.c:3659
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
```
**Symbols:**

```
ffffffff816679d0-ffffffff81667c05: alloc_irq_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct irq_remap_table *alloc_irq_table(u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81685ef0)
Location: drivers/iommu/amd_iommu.c:3724
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
```
**Symbols:**

```
ffffffff81685ef0-ffffffff81686123: alloc_irq_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct irq_remap_table *alloc_irq_table(u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816bd650)
Location: drivers/iommu/amd_iommu.c:3705
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
```
**Symbols:**

```
ffffffff816bd650-ffffffff816bd87f: alloc_irq_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct irq_remap_table *alloc_irq_table(u16 devid, struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816e06e0)
Location: drivers/iommu/amd_iommu.c:3754
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/amd_iommu.c:alloc_irq_index
```
**Symbols:**

```
ffffffff816e06e0-ffffffff816e08ff: alloc_irq_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct irq_remap_table *alloc_irq_table(u16 devid, struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81798280)
Location: drivers/iommu/amd/iommu.c:3170
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/iommu.c:alloc_irq_index
```
**Symbols:**

```
ffffffff81798280-ffffffff81798453: alloc_irq_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct irq_remap_table *alloc_irq_table(u16 devid, struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817a6910)
Location: drivers/iommu/amd/iommu.c:3261
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/iommu.c:alloc_irq_index
```
**Symbols:**

```
ffffffff817a6910-ffffffff817a6ae3: alloc_irq_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct irq_remap_table *alloc_irq_table(u16 devid, struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81788350)
Location: drivers/iommu/amd/iommu.c:2627
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/iommu.c:alloc_irq_index
```
**Symbols:**

```
ffffffff81788350-ffffffff81788576: alloc_irq_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct irq_remap_table *alloc_irq_table(u16 devid, struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:2695
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/iommu.c:alloc_irq_index
```
**Symbols:**

```
ffffffff8180fc40-ffffffff8180fea2: alloc_irq_table (STB_LOCAL)
ffffffff81cfe216-ffffffff81cfe22a: alloc_irq_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct irq_remap_table *alloc_irq_table(u16 devid, struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff8194ef70)
Location: drivers/iommu/amd/iommu.c:2721
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/iommu.c:alloc_irq_index
```
**Symbols:**

```
ffffffff8194ef70-ffffffff8194f1c0: alloc_irq_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct irq_remap_table *alloc_irq_table(struct amd_iommu *iommu, u16 devid, struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81ab40e0)
Location: drivers/iommu/amd/iommu.c:2896
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/iommu.c:alloc_irq_index
```
**Symbols:**

```
ffffffff81ab40e0-ffffffff81ab42fc: alloc_irq_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct irq_remap_table *alloc_irq_table(struct amd_iommu *iommu, u16 devid, struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b01bb0)
Location: drivers/iommu/amd/iommu.c:2942
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/iommu.c:alloc_irq_index
```
**Symbols:**

```
ffffffff81b01bb0-ffffffff81b01dfd: alloc_irq_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct irq_remap_table *alloc_irq_table(struct amd_iommu *iommu, u16 devid, struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b55520)
Location: drivers/iommu/amd/iommu.c:2981
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/iommu.c:alloc_irq_index
```
**Symbols:**

```
ffffffff81b55520-ffffffff81b5576d: alloc_irq_table (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct irq_remap_table *alloc_irq_table(u16 devid, struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a6130)
Location: drivers/iommu/amd_iommu.c:3754
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/amd_iommu.c:alloc_irq_index
```
**Symbols:**

```
ffffffff816a6130-ffffffff816a634f: alloc_irq_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct irq_remap_table *alloc_irq_table(u16 devid, struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81683b20)
Location: drivers/iommu/amd_iommu.c:3754
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/amd_iommu.c:alloc_irq_index
```
**Symbols:**

```
ffffffff81683b20-ffffffff81683d3f: alloc_irq_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct irq_remap_table *alloc_irq_table(u16 devid, struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816d43a0)
Location: drivers/iommu/amd_iommu.c:3754
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/amd_iommu.c:alloc_irq_index
```
**Symbols:**

```
ffffffff816d43a0-ffffffff816d45bf: alloc_irq_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct irq_remap_table *alloc_irq_table(u16 devid, struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816eeaa0)
Location: drivers/iommu/amd_iommu.c:3754
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/amd_iommu.c:alloc_irq_index
```
**Symbols:**

```
ffffffff816eeaa0-ffffffff816eecbf: alloc_irq_table (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct pci_dev *pdev</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct amd_iommu *iommu</code>
</li>
<li>
<b>Param reordered. </b>
<code>devid, pdev</code> ➡️ <code>iommu, devid, pdev</code>
</li>
</ul>
</details>
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
