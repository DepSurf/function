# Function: <code>iommu_range_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int iommu_range_alloc(struct device *dev, struct iommu_table *tbl, unsigned int npages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff810674e0)
Location: arch/x86/kernel/pci-calgary_64.c:227
Inline: False
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:iommu_alloc
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
```
**Symbols:**

```
ffffffff810674e0-ffffffff8106762c: iommu_range_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int iommu_range_alloc(struct device *dev, struct iommu_table *tbl, unsigned int npages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff81067260)
Location: arch/x86/kernel/pci-calgary_64.c:227
Inline: False
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:iommu_alloc
```
**Symbols:**

```
ffffffff81067260-ffffffff8106738c: iommu_range_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int iommu_range_alloc(struct device *dev, struct iommu_table *tbl, unsigned int npages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8106aeb0)
Location: arch/x86/kernel/pci-calgary_64.c:227
Inline: False
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:iommu_alloc
```
**Symbols:**

```
ffffffff8106aeb0-ffffffff8106afdc: iommu_range_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int iommu_range_alloc(struct device *dev, struct iommu_table *tbl, unsigned int npages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8106a320)
Location: arch/x86/kernel/pci-calgary_64.c:229
Inline: False
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:iommu_alloc
```
**Symbols:**

```
ffffffff8106a320-ffffffff8106a429: iommu_range_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int iommu_range_alloc(struct device *dev, struct iommu_table *tbl, unsigned int npages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8106ec30)
Location: arch/x86/kernel/pci-calgary_64.c:229
Inline: False
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:iommu_alloc
```
**Symbols:**

```
ffffffff8106ec30-ffffffff8106ed3f: iommu_range_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
long unsigned int iommu_range_alloc(struct device *dev, struct iommu_table *tbl, unsigned int npages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: arch/x86/kernel/pci-calgary_64.c:230
Inline: False
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:iommu_alloc
```
**Symbols:**

```
ffffffff81071b00-ffffffff81071bff: iommu_range_alloc (STB_LOCAL)
ffffffff810722cd-ffffffff81072300: iommu_range_alloc.cold.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
long unsigned int iommu_range_alloc(struct device *dev, struct iommu_table *tbl, unsigned int npages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: arch/x86/kernel/pci-calgary_64.c:226
Inline: False
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:iommu_alloc
```
**Symbols:**

```
ffffffff81077b20-ffffffff81077c22: iommu_range_alloc (STB_LOCAL)
ffffffff81078327-ffffffff81078358: iommu_range_alloc.cold.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
long unsigned int iommu_range_alloc(struct device *dev, struct iommu_table *tbl, unsigned int npages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: arch/x86/kernel/pci-calgary_64.c:214
Inline: False
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:iommu_alloc
```
**Symbols:**

```
ffffffff8107b690-ffffffff8107b799: iommu_range_alloc (STB_LOCAL)
ffffffff8107beaa-ffffffff8107bee2: iommu_range_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
long unsigned int iommu_range_alloc(struct device *dev, struct iommu_table *tbl, unsigned int npages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: arch/x86/kernel/pci-calgary_64.c:214
Inline: False
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:iommu_alloc
```
**Symbols:**

```
ffffffff8107c780-ffffffff8107c889: iommu_range_alloc (STB_LOCAL)
ffffffff8107cf9a-ffffffff8107cfd2: iommu_range_alloc.cold (STB_LOCAL)
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
long unsigned int iommu_range_alloc(struct device *dev, struct iommu_table *tbl, long unsigned int npages, long unsigned int *handle, long unsigned int mask, unsigned int align_order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/iommu.c (c000000000051300)
Location: arch/powerpc/kernel/iommu.c:163
Inline: False
Direct callers:
  - arch/powerpc/kernel/iommu.c:ppc_iommu_map_sg
  - arch/powerpc/kernel/iommu.c:iommu_alloc
```
**Symbols:**

```
c000000000051300-c000000000051704: iommu_range_alloc (STB_LOCAL)
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
long unsigned int iommu_range_alloc(struct device *dev, struct iommu_table *tbl, unsigned int npages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: arch/x86/kernel/pci-calgary_64.c:214
Inline: False
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:iommu_alloc
```
**Symbols:**

```
ffffffff8107b780-ffffffff8107b889: iommu_range_alloc (STB_LOCAL)
ffffffff8107bf9a-ffffffff8107bfd2: iommu_range_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
long unsigned int iommu_range_alloc(struct device *dev, struct iommu_table *tbl, unsigned int npages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: arch/x86/kernel/pci-calgary_64.c:214
Inline: False
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:iommu_alloc
```
**Symbols:**

```
ffffffff8106aeb0-ffffffff8106afb9: iommu_range_alloc (STB_LOCAL)
ffffffff8106b6ca-ffffffff8106b702: iommu_range_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
long unsigned int iommu_range_alloc(struct device *dev, struct iommu_table *tbl, unsigned int npages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: arch/x86/kernel/pci-calgary_64.c:214
Inline: False
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:iommu_alloc
```
**Symbols:**

```
ffffffff8107b730-ffffffff8107b839: iommu_range_alloc (STB_LOCAL)
ffffffff8107bf4a-ffffffff8107bf82: iommu_range_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
long unsigned int iommu_range_alloc(struct device *dev, struct iommu_table *tbl, unsigned int npages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: arch/x86/kernel/pci-calgary_64.c:214
Inline: False
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:iommu_alloc
```
**Symbols:**

```
ffffffff8107d830-ffffffff8107d939: iommu_range_alloc (STB_LOCAL)
ffffffff8107e04a-ffffffff8107e082: iommu_range_alloc.cold (STB_LOCAL)
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
<code>long unsigned int *handle</code>
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
<b>Param type changed. </b>
<code>unsigned int npages</code> ➡️ <code>long unsigned int npages</code>
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
