# Function: <code>iommu_area_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int iommu_area_alloc(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, long unsigned int shift, long unsigned int boundary_size, long unsigned int align_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iommu-helper.c (ffffffff81413170)
Location: lib/iommu-helper.c:19
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_alloc
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_alloc
  - lib/iommu-common.c:iommu_tbl_range_alloc
  - drivers/iommu/amd_iommu.c:dma_ops_area_alloc
```
**Symbols:**

```
ffffffff81413170-ffffffff814131f3: iommu_area_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int iommu_area_alloc(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, long unsigned int shift, long unsigned int boundary_size, long unsigned int align_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iommu-helper.c (ffffffff8145ae70)
Location: lib/iommu-helper.c:19
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_alloc
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_alloc
  - lib/iommu-common.c:iommu_tbl_range_alloc
```
**Symbols:**

```
ffffffff8145ae70-ffffffff8145af12: iommu_area_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int iommu_area_alloc(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, long unsigned int shift, long unsigned int boundary_size, long unsigned int align_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iommu-helper.c (ffffffff81479960)
Location: lib/iommu-helper.c:19
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_alloc
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_alloc
  - lib/iommu-common.c:iommu_tbl_range_alloc
```
**Symbols:**

```
ffffffff81479960-ffffffff81479a02: iommu_area_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int iommu_area_alloc(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, long unsigned int shift, long unsigned int boundary_size, long unsigned int align_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iommu-helper.c (ffffffff81482cc0)
Location: lib/iommu-helper.c:19
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_alloc
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_alloc
  - lib/iommu-common.c:iommu_tbl_range_alloc
```
**Symbols:**

```
ffffffff81482cc0-ffffffff81482d5f: iommu_area_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int iommu_area_alloc(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, long unsigned int shift, long unsigned int boundary_size, long unsigned int align_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iommu-helper.c (ffffffff814bed00)
Location: lib/iommu-helper.c:20
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_alloc
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_alloc
  - lib/iommu-common.c:iommu_tbl_range_alloc
```
**Symbols:**

```
ffffffff814bed00-ffffffff814bed9f: iommu_area_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int iommu_area_alloc(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, long unsigned int shift, long unsigned int boundary_size, long unsigned int align_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iommu-helper.c (ffffffff814eff00)
Location: lib/iommu-helper.c:9
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_alloc
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_alloc
```
**Symbols:**

```
ffffffff814eff00-ffffffff814effb0: iommu_area_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int iommu_area_alloc(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, long unsigned int shift, long unsigned int boundary_size, long unsigned int align_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iommu-helper.c (ffffffff81503e20)
Location: lib/iommu-helper.c:9
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_alloc
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_alloc
```
**Symbols:**

```
ffffffff81503e20-ffffffff81503ed0: iommu_area_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int iommu_area_alloc(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, long unsigned int shift, long unsigned int boundary_size, long unsigned int align_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iommu-helper.c (ffffffff81531f90)
Location: lib/iommu-helper.c:9
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_alloc
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_alloc
```
**Symbols:**

```
ffffffff81531f90-ffffffff81532045: iommu_area_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int iommu_area_alloc(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, long unsigned int shift, long unsigned int boundary_size, long unsigned int align_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iommu-helper.c (ffffffff81552dd0)
Location: lib/iommu-helper.c:9
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_alloc
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_alloc
```
**Symbols:**

```
ffffffff81552dd0-ffffffff81552e85: iommu_area_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int iommu_area_alloc(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, long unsigned int shift, long unsigned int boundary_size, long unsigned int align_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iommu-helper.c (ffffffff815dc1b0)
Location: lib/iommu-helper.c:9
Inline: False
```
**Symbols:**

```
ffffffff815dc1b0-ffffffff815dc25f: iommu_area_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int iommu_area_alloc(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, long unsigned int shift, long unsigned int boundary_size, long unsigned int align_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iommu-helper.c (ffffffff815f9e50)
Location: lib/iommu-helper.c:9
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
```
**Symbols:**

```
ffffffff815f9e50-ffffffff815f9eff: iommu_area_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int iommu_area_alloc(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, long unsigned int shift, long unsigned int boundary_size, long unsigned int align_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iommu-helper.c (ffffffff815dca30)
Location: lib/iommu-helper.c:9
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
```
**Symbols:**

```
ffffffff815dca30-ffffffff815dcadf: iommu_area_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int iommu_area_alloc(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, long unsigned int shift, long unsigned int boundary_size, long unsigned int align_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iommu-helper.c (ffffffff81648390)
Location: lib/iommu-helper.c:9
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
```
**Symbols:**

```
ffffffff81648390-ffffffff8164843f: iommu_area_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int iommu_area_alloc(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, long unsigned int shift, long unsigned int boundary_size, long unsigned int align_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iommu-helper.c (ffffffff8175e770)
Location: lib/iommu-helper.c:9
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
```
**Symbols:**

```
ffffffff8175e770-ffffffff8175e82b: iommu_area_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int iommu_area_alloc(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, long unsigned int shift, long unsigned int boundary_size, long unsigned int align_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iommu-helper.c (ffffffff8188bf90)
Location: lib/iommu-helper.c:9
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
```
**Symbols:**

```
ffffffff8188bf90-ffffffff8188c04b: iommu_area_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int iommu_area_alloc(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, long unsigned int shift, long unsigned int boundary_size, long unsigned int align_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iommu-helper.c (ffffffff818ce400)
Location: lib/iommu-helper.c:9
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
```
**Symbols:**

```
ffffffff818ce400-ffffffff818ce4bb: iommu_area_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int iommu_area_alloc(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, long unsigned int shift, long unsigned int boundary_size, long unsigned int align_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iommu-helper.c (ffffffff819201b0)
Location: lib/iommu-helper.c:9
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
```
**Symbols:**

```
ffffffff819201b0-ffffffff8192026b: iommu_area_alloc (STB_GLOBAL)
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
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int iommu_area_alloc(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, long unsigned int shift, long unsigned int boundary_size, long unsigned int align_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iommu-helper.c (c000000000811940)
Location: lib/iommu-helper.c:9
Inline: False
Direct callers:
  - arch/powerpc/kernel/iommu.c:iommu_range_alloc
  - arch/powerpc/kernel/iommu.c:iommu_range_alloc
```
**Symbols:**

```
c000000000811940-c000000000811aa8: iommu_area_alloc (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
long unsigned int iommu_area_alloc(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, long unsigned int shift, long unsigned int boundary_size, long unsigned int align_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iommu-helper.c (ffffffff8154b3b0)
Location: lib/iommu-helper.c:9
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_alloc
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_alloc
```
**Symbols:**

```
ffffffff8154b3b0-ffffffff8154b465: iommu_area_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int iommu_area_alloc(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, long unsigned int shift, long unsigned int boundary_size, long unsigned int align_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iommu-helper.c (ffffffff8153b690)
Location: lib/iommu-helper.c:9
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_alloc
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_alloc
```
**Symbols:**

```
ffffffff8153b690-ffffffff8153b745: iommu_area_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int iommu_area_alloc(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, long unsigned int shift, long unsigned int boundary_size, long unsigned int align_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iommu-helper.c (ffffffff815470f0)
Location: lib/iommu-helper.c:9
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_alloc
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_alloc
```
**Symbols:**

```
ffffffff815470f0-ffffffff815471a5: iommu_area_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int iommu_area_alloc(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, long unsigned int shift, long unsigned int boundary_size, long unsigned int align_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iommu-helper.c (ffffffff81560f40)
Location: lib/iommu-helper.c:9
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
  - arch/x86/kernel/amd_gart_64.c:alloc_iommu
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_alloc
  - arch/x86/kernel/pci-calgary_64.c:iommu_range_alloc
```
**Symbols:**

```
ffffffff81560f40-ffffffff81560ff5: iommu_area_alloc (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
