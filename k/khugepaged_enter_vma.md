# Function: <code>khugepaged_enter_vma</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
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
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void khugepaged_enter_vma(struct vm_area_struct *vma, long unsigned int vm_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff813c7842)
Location: mm/khugepaged.c:508
Inline: True
Inline callers:
  - mm/khugepaged.c:hugepage_madvise
  - mm/khugepaged.c:hugepage_madvise
Direct callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
```
**Symbols:**

```
ffffffff813c78c0-ffffffff813c794a: khugepaged_enter_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void khugepaged_enter_vma(struct vm_area_struct *vma, long unsigned int vm_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8144b800)
Location: mm/khugepaged.c:450
Inline: True
Direct callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:vma_merge
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:hugepage_madvise
```
**Symbols:**

```
ffffffff8144b800-ffffffff8144b884: khugepaged_enter_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void khugepaged_enter_vma(struct vm_area_struct *vma, long unsigned int vm_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff81481080)
Location: mm/khugepaged.c:451
Inline: True
Direct callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:vma_merge
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:hugepage_madvise
```
**Symbols:**

```
ffffffff81481080-ffffffff81481104: khugepaged_enter_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void khugepaged_enter_vma(struct vm_area_struct *vma, long unsigned int vm_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff814b0070)
Location: mm/khugepaged.c:445
Inline: True
Direct callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:vma_merge
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:hugepage_madvise
```
**Symbols:**

```
ffffffff814b0070-ffffffff814b015a: khugepaged_enter_vma (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
