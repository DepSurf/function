# Function: <code>shmem_is_huge</code>

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
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool shmem_is_huge(struct vm_area_struct *vma, struct inode *inode, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812bcfb0)
Location: mm/shmem.c:476
Inline: True
Direct callers:
  - mm/shmem.c:shmem_zero_setup
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getattr
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:transparent_hugepage_active
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
**Symbols:**

```
ffffffff812bcfb0-ffffffff812bd058: shmem_is_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool shmem_is_huge(struct vm_area_struct *vma, struct inode *inode, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/shmem.c (ffffffff81318faf)
Location: mm/shmem.c:474
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getattr
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getattr
  - mm/huge_memory.c:transparent_hugepage_active
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
**Symbols:**

```
ffffffff81315c80-ffffffff81315d43: shmem_is_huge.part.0 (STB_LOCAL)
ffffffff8131c1a0-ffffffff8131c1da: shmem_is_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool shmem_is_huge(struct vm_area_struct *vma, struct inode *inode, long unsigned int index, bool shmem_huge_force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/shmem.c (ffffffff8138d0f0)
Location: mm/shmem.c:471
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_getattr
Direct callers:
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_getattr
  - mm/huge_memory.c:hugepage_vma_check
```
**Symbols:**

```
ffffffff81389d90-ffffffff81389e4d: shmem_is_huge.part.0 (STB_LOCAL)
ffffffff8138fd60-ffffffff8138fda6: shmem_is_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool shmem_is_huge(struct inode *inode, long unsigned int index, bool shmem_huge_force, struct mm_struct *mm, long unsigned int vm_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/shmem.c (ffffffff813bf937)
Location: mm/shmem.c:472
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_getattr
Direct callers:
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_getattr
  - mm/huge_memory.c:hugepage_vma_check
```
**Symbols:**

```
ffffffff813bbf50-ffffffff813bc029: shmem_is_huge.part.0 (STB_LOCAL)
ffffffff813c26b0-ffffffff813c26fc: shmem_is_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool shmem_is_huge(struct inode *inode, long unsigned int index, bool shmem_huge_force, struct mm_struct *mm, long unsigned int vm_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/shmem.c (ffffffff813ea970)
Location: mm/shmem.c:538
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_getattr
Direct callers:
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_getattr
  - mm/huge_memory.c:__thp_vma_allowable_orders
```
**Symbols:**

```
ffffffff813e6b40-ffffffff813e6c19: shmem_is_huge.part.0 (STB_LOCAL)
ffffffff813ed350-ffffffff813ed39c: shmem_is_huge (STB_GLOBAL)
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool shmem_huge_force</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mm_struct *mm</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int vm_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>struct vm_area_struct *vma</code>
</li>
<li>
<b>Param reordered. </b>
<code>vma, inode, index, shmem_huge_force</code> ➡️ <code>inode, index, shmem_huge_force, mm, vm_flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
