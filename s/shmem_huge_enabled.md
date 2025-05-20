# Function: <code>shmem_huge_enabled</code>

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
bool shmem_huge_enabled(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811c44a0)
Location: mm/shmem.c:4005
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffffffff811c44a0-ffffffff811c4546: shmem_huge_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool shmem_huge_enabled(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811d45a0)
Location: mm/shmem.c:3899
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffffffff811d45a0-ffffffff811d463b: shmem_huge_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool shmem_huge_enabled(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811dd250)
Location: mm/shmem.c:4064
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffffffff811dd250-ffffffff811dd2e7: shmem_huge_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool shmem_huge_enabled(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811f2cd0)
Location: mm/shmem.c:4109
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffffffff811f2cd0-ffffffff811f2d67: shmem_huge_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool shmem_huge_enabled(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81213ee0)
Location: mm/shmem.c:3825
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
**Symbols:**

```
ffffffff81213ee0-ffffffff81213f77: shmem_huge_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool shmem_huge_enabled(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81226ea0)
Location: mm/shmem.c:3811
Inline: False
Direct callers:
  - mm/huge_memory.c:transparent_hugepage_enabled
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffffffff81226ea0-ffffffff81226f37: shmem_huge_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool shmem_huge_enabled(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81236a00)
Location: mm/shmem.c:3888
Inline: False
Direct callers:
  - mm/huge_memory.c:transparent_hugepage_enabled
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffffffff81236a00-ffffffff81236abc: shmem_huge_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool shmem_huge_enabled(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81244c40)
Location: mm/shmem.c:4009
Inline: False
Direct callers:
  - mm/huge_memory.c:transparent_hugepage_enabled
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
**Symbols:**

```
ffffffff81244c40-ffffffff81244cfc: shmem_huge_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool shmem_huge_enabled(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81272900)
Location: mm/shmem.c:3972
Inline: False
Direct callers:
  - mm/huge_memory.c:transparent_hugepage_enabled
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
**Symbols:**

```
ffffffff81272900-ffffffff812729be: shmem_huge_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool shmem_huge_enabled(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8127cda0)
Location: mm/shmem.c:4079
Inline: False
Direct callers:
  - mm/shmem.c:shmem_zero_setup
  - mm/shmem.c:shmem_mmap
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:transparent_hugepage_enabled
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
**Symbols:**

```
ffffffff8127cda0-ffffffff8127ce5e: shmem_huge_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool shmem_huge_enabled(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81281f40)
Location: mm/shmem.c:4024
Inline: False
Direct callers:
  - mm/shmem.c:shmem_zero_setup
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:transparent_hugepage_active
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
**Symbols:**

```
ffffffff81281f40-ffffffff81281ffd: shmem_huge_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812bf89b)
Location: include/linux/shmem_fs.h:91
Inline: True
Inline callers:
  - mm/shmem.c:shmem_zero_setup
```
```
In mm/huge_memory.c (ffffffff813461fa)
Location: include/linux/shmem_fs.h:91
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:transparent_hugepage_active
```
```
In mm/khugepaged.c (ffffffff8134fd9e)
Location: include/linux/shmem_fs.h:91
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff813bbd3d)
Location: include/linux/shmem_fs.h:91
Inline: True
Inline callers:
  - mm/huge_memory.c:transparent_hugepage_active
```
```
In mm/khugepaged.c (ffffffff813c7fb7)
Location: include/linux/shmem_fs.h:91
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8143e28d)
Location: include/linux/shmem_fs.h:97
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_vma_check
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
bool shmem_huge_enabled(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffff8000102d7350)
Location: mm/shmem.c:4009
Inline: False
Direct callers:
  - mm/huge_memory.c:transparent_hugepage_enabled
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffff8000102d7350-ffff8000102d7428: shmem_huge_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool shmem_huge_enabled(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c000000000397520)
Location: mm/shmem.c:4009
Inline: False
Direct callers:
  - mm/huge_memory.c:transparent_hugepage_enabled
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
**Symbols:**

```
c000000000397520-c000000000397628: shmem_huge_enabled (STB_GLOBAL)
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
bool shmem_huge_enabled(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8123d290)
Location: mm/shmem.c:4009
Inline: False
Direct callers:
  - mm/huge_memory.c:transparent_hugepage_enabled
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
**Symbols:**

```
ffffffff8123d290-ffffffff8123d34c: shmem_huge_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool shmem_huge_enabled(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81230290)
Location: mm/shmem.c:4009
Inline: False
Direct callers:
  - mm/huge_memory.c:transparent_hugepage_enabled
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
**Symbols:**

```
ffffffff81230290-ffffffff8123034c: shmem_huge_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool shmem_huge_enabled(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8123b030)
Location: mm/shmem.c:4009
Inline: False
Direct callers:
  - mm/huge_memory.c:transparent_hugepage_enabled
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
**Symbols:**

```
ffffffff8123b030-ffffffff8123b0ec: shmem_huge_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool shmem_huge_enabled(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8124a740)
Location: mm/shmem.c:4009
Inline: False
Direct callers:
  - mm/huge_memory.c:transparent_hugepage_enabled
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffffffff8124a740-ffffffff8124a7fc: shmem_huge_enabled (STB_GLOBAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
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
