# Function: <code>iommu_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
dma_addr_t iommu_alloc(struct device *dev, struct iommu_table *tbl, void *vaddr, unsigned int npages, int direction);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff81067630)
Location: arch/x86/kernel/pci-calgary_64.c:267
Inline: False
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
```
**Symbols:**

```
ffffffff81067630-ffffffff810676b4: iommu_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
dma_addr_t iommu_alloc(struct device *dev, struct iommu_table *tbl, void *vaddr, unsigned int npages, int direction);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff81067390)
Location: arch/x86/kernel/pci-calgary_64.c:267
Inline: False
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_page
```
**Symbols:**

```
ffffffff81067390-ffffffff81067419: iommu_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
dma_addr_t iommu_alloc(struct device *dev, struct iommu_table *tbl, void *vaddr, unsigned int npages, int direction);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8106afe0)
Location: arch/x86/kernel/pci-calgary_64.c:267
Inline: False
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_page
```
**Symbols:**

```
ffffffff8106afe0-ffffffff8106b069: iommu_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
dma_addr_t iommu_alloc(struct device *dev, struct iommu_table *tbl, void *vaddr, unsigned int npages, int direction);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8106a430)
Location: arch/x86/kernel/pci-calgary_64.c:269
Inline: False
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_page
```
**Symbols:**

```
ffffffff8106a430-ffffffff8106a4b9: iommu_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
dma_addr_t iommu_alloc(struct device *dev, struct iommu_table *tbl, void *vaddr, unsigned int npages, int direction);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8106ed40)
Location: arch/x86/kernel/pci-calgary_64.c:269
Inline: False
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_page
```
**Symbols:**

```
ffffffff8106ed40-ffffffff8106edc9: iommu_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
dma_addr_t iommu_alloc(struct device *dev, struct iommu_table *tbl, void *vaddr, unsigned int npages, int direction);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: arch/x86/kernel/pci-calgary_64.c:270
Inline: False
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_page
```
**Symbols:**

```
ffffffff81071c00-ffffffff81071c69: iommu_alloc (STB_LOCAL)
ffffffff81072300-ffffffff8107231a: iommu_alloc.cold.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
dma_addr_t iommu_alloc(struct device *dev, struct iommu_table *tbl, void *vaddr, unsigned int npages, int direction);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: arch/x86/kernel/pci-calgary_64.c:266
Inline: False
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_page
```
**Symbols:**

```
ffffffff81077c30-ffffffff81077ca7: iommu_alloc (STB_LOCAL)
ffffffff81078358-ffffffff81078372: iommu_alloc.cold.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
dma_addr_t iommu_alloc(struct device *dev, struct iommu_table *tbl, void *vaddr, unsigned int npages, int direction);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: arch/x86/kernel/pci-calgary_64.c:254
Inline: False
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_page
```
**Symbols:**

```
ffffffff8107b7a0-ffffffff8107b80a: iommu_alloc (STB_LOCAL)
ffffffff8107bee2-ffffffff8107befd: iommu_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
dma_addr_t iommu_alloc(struct device *dev, struct iommu_table *tbl, void *vaddr, unsigned int npages, int direction);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: arch/x86/kernel/pci-calgary_64.c:254
Inline: False
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_page
```
**Symbols:**

```
ffffffff8107c890-ffffffff8107c8fa: iommu_alloc (STB_LOCAL)
ffffffff8107cfd2-ffffffff8107cfed: iommu_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
dma_addr_t iommu_alloc(struct device *dev, struct iommu_table *tbl, void *page, unsigned int npages, enum dma_data_direction direction, long unsigned int mask, unsigned int align_order, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/iommu.c (c000000000051a60)
Location: arch/powerpc/kernel/iommu.c:293
Inline: False
Direct callers:
  - arch/powerpc/kernel/iommu.c:iommu_alloc_coherent
  - arch/powerpc/kernel/iommu.c:iommu_map_page
  - arch/powerpc/kernel/iommu.c:iommu_map_page
```
**Symbols:**

```
c000000000051a60-c000000000051b88: iommu_alloc (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
dma_addr_t iommu_alloc(struct device *dev, struct iommu_table *tbl, void *vaddr, unsigned int npages, int direction);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: arch/x86/kernel/pci-calgary_64.c:254
Inline: False
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_page
```
**Symbols:**

```
ffffffff8107b890-ffffffff8107b8fa: iommu_alloc (STB_LOCAL)
ffffffff8107bfd2-ffffffff8107bfed: iommu_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
dma_addr_t iommu_alloc(struct device *dev, struct iommu_table *tbl, void *vaddr, unsigned int npages, int direction);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: arch/x86/kernel/pci-calgary_64.c:254
Inline: False
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_page
```
**Symbols:**

```
ffffffff8106afc0-ffffffff8106b02a: iommu_alloc (STB_LOCAL)
ffffffff8106b702-ffffffff8106b71d: iommu_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
dma_addr_t iommu_alloc(struct device *dev, struct iommu_table *tbl, void *vaddr, unsigned int npages, int direction);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: arch/x86/kernel/pci-calgary_64.c:254
Inline: False
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_page
```
**Symbols:**

```
ffffffff8107b840-ffffffff8107b8aa: iommu_alloc (STB_LOCAL)
ffffffff8107bf82-ffffffff8107bf9d: iommu_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
dma_addr_t iommu_alloc(struct device *dev, struct iommu_table *tbl, void *vaddr, unsigned int npages, int direction);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: arch/x86/kernel/pci-calgary_64.c:254
Inline: False
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_page
```
**Symbols:**

```
ffffffff8107d940-ffffffff8107d9aa: iommu_alloc (STB_LOCAL)
ffffffff8107e082-ffffffff8107e09d: iommu_alloc.cold (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>ppc64el</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *page</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int mask</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int align_order</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int attrs</code>
</li>
<li>
<b>Param removed. </b>
<code>void *vaddr</code>
</li>
<li>
<b>Param type changed. </b>
<code>int direction</code> ➡️ <code>enum dma_data_direction direction</code>
</li>
</ul>
</details>
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
