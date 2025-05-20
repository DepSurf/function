# Function: <code>tce_build</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tce_build(struct iommu_table *tbl, long unsigned int index, unsigned int npages, long unsigned int uaddr, int direction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tce_64.c (ffffffff81068110)
Location: arch/x86/kernel/tce_64.c:49
Inline: False
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:iommu_alloc
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
```
**Symbols:**

```
ffffffff81068110-ffffffff810681ed: tce_build (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tce_build(struct iommu_table *tbl, long unsigned int index, unsigned int npages, long unsigned int uaddr, int direction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tce_64.c (ffffffff81067e60)
Location: arch/x86/kernel/tce_64.c:49
Inline: False
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:iommu_alloc
```
**Symbols:**

```
ffffffff81067e60-ffffffff81067f2c: tce_build (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tce_build(struct iommu_table *tbl, long unsigned int index, unsigned int npages, long unsigned int uaddr, int direction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tce_64.c (ffffffff8106bab0)
Location: arch/x86/kernel/tce_64.c:49
Inline: False
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:iommu_alloc
```
**Symbols:**

```
ffffffff8106bab0-ffffffff8106bb7c: tce_build (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tce_build(struct iommu_table *tbl, long unsigned int index, unsigned int npages, long unsigned int uaddr, int direction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tce_64.c (ffffffff8106ae70)
Location: arch/x86/kernel/tce_64.c:49
Inline: False
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:iommu_alloc
```
**Symbols:**

```
ffffffff8106ae70-ffffffff8106af3c: tce_build (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tce_build(struct iommu_table *tbl, long unsigned int index, unsigned int npages, long unsigned int uaddr, int direction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tce_64.c (ffffffff8106f770)
Location: arch/x86/kernel/tce_64.c:49
Inline: False
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:iommu_alloc
```
**Symbols:**

```
ffffffff8106f770-ffffffff8106f83c: tce_build (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tce_build(struct iommu_table *tbl, long unsigned int index, unsigned int npages, long unsigned int uaddr, int direction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tce_64.c (ffffffff81072630)
Location: arch/x86/kernel/tce_64.c:49
Inline: False
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:iommu_alloc
```
**Symbols:**

```
ffffffff81072630-ffffffff8107270b: tce_build (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tce_build(struct iommu_table *tbl, long unsigned int index, unsigned int npages, long unsigned int uaddr, int direction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tce_64.c (ffffffff81078680)
Location: arch/x86/kernel/tce_64.c:49
Inline: False
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:iommu_alloc
```
**Symbols:**

```
ffffffff81078680-ffffffff8107875b: tce_build (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tce_build(struct iommu_table *tbl, long unsigned int index, unsigned int npages, long unsigned int uaddr, int direction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tce_64.c (ffffffff8107c1f0)
Location: arch/x86/kernel/tce_64.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:iommu_alloc
```
**Symbols:**

```
ffffffff8107c1f0-ffffffff8107c2c6: tce_build (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tce_build(struct iommu_table *tbl, long unsigned int index, unsigned int npages, long unsigned int uaddr, int direction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tce_64.c (ffffffff8107d2e0)
Location: arch/x86/kernel/tce_64.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:iommu_alloc
```
**Symbols:**

```
ffffffff8107d2e0-ffffffff8107d3b6: tce_build (STB_GLOBAL)
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
void tce_build(struct iommu_table *tbl, long unsigned int index, unsigned int npages, long unsigned int uaddr, int direction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tce_64.c (ffffffff8107c2e0)
Location: arch/x86/kernel/tce_64.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:iommu_alloc
```
**Symbols:**

```
ffffffff8107c2e0-ffffffff8107c3b6: tce_build (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tce_build(struct iommu_table *tbl, long unsigned int index, unsigned int npages, long unsigned int uaddr, int direction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tce_64.c (ffffffff8106ba10)
Location: arch/x86/kernel/tce_64.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:iommu_alloc
```
**Symbols:**

```
ffffffff8106ba10-ffffffff8106bad5: tce_build (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tce_build(struct iommu_table *tbl, long unsigned int index, unsigned int npages, long unsigned int uaddr, int direction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tce_64.c (ffffffff8107c290)
Location: arch/x86/kernel/tce_64.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:iommu_alloc
```
**Symbols:**

```
ffffffff8107c290-ffffffff8107c366: tce_build (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tce_build(struct iommu_table *tbl, long unsigned int index, unsigned int npages, long unsigned int uaddr, int direction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tce_64.c (ffffffff8107e390)
Location: arch/x86/kernel/tce_64.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:iommu_alloc
```
**Symbols:**

```
ffffffff8107e390-ffffffff8107e466: tce_build (STB_GLOBAL)
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
