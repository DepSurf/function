# Function: <code>adjust_range_if_pmd_sharing_possible</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void adjust_range_if_pmd_sharing_possible(struct vm_area_struct *vma, long unsigned int *start, long unsigned int *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81269e40)
Location: mm/hugetlb.c:4624
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
```
**Symbols:**

```
ffffffff81269e40-ffffffff81269eab: adjust_range_if_pmd_sharing_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void adjust_range_if_pmd_sharing_possible(struct vm_area_struct *vma, long unsigned int *start, long unsigned int *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81284f70)
Location: mm/hugetlb.c:4729
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
```
**Symbols:**

```
ffffffff81284f70-ffffffff81284fdb: adjust_range_if_pmd_sharing_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void adjust_range_if_pmd_sharing_possible(struct vm_area_struct *vma, long unsigned int *start, long unsigned int *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81294b10)
Location: mm/hugetlb.c:4846
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
```
**Symbols:**

```
ffffffff81294b10-ffffffff81294b7b: adjust_range_if_pmd_sharing_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void adjust_range_if_pmd_sharing_possible(struct vm_area_struct *vma, long unsigned int *start, long unsigned int *end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812c963a)
Location: mm/hugetlb.c:5334
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
Direct callers:
  - mm/rmap.c:try_to_unmap_one
```
**Symbols:**

```
ffffffff812c80e0-ffffffff812c8126: adjust_range_if_pmd_sharing_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void adjust_range_if_pmd_sharing_possible(struct vm_area_struct *vma, long unsigned int *start, long unsigned int *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d3ca0)
Location: mm/hugetlb.c:5337
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
```
**Symbols:**

```
ffffffff812d3ca0-ffffffff812d3d0b: adjust_range_if_pmd_sharing_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void adjust_range_if_pmd_sharing_possible(struct vm_area_struct *vma, long unsigned int *start, long unsigned int *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812dabe0)
Location: mm/hugetlb.c:5615
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
```
**Symbols:**

```
ffffffff812dabe0-ffffffff812dac48: adjust_range_if_pmd_sharing_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void adjust_range_if_pmd_sharing_possible(struct vm_area_struct *vma, long unsigned int *start, long unsigned int *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81321bf0)
Location: mm/hugetlb.c:5952
Inline: False
Direct callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
```
**Symbols:**

```
ffffffff81321bf0-ffffffff81321c58: adjust_range_if_pmd_sharing_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void adjust_range_if_pmd_sharing_possible(struct vm_area_struct *vma, long unsigned int *start, long unsigned int *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8138ed20)
Location: mm/hugetlb.c:6678
Inline: False
Direct callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
```
**Symbols:**

```
ffffffff8138ed20-ffffffff8138ed99: adjust_range_if_pmd_sharing_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void adjust_range_if_pmd_sharing_possible(struct vm_area_struct *vma, long unsigned int *start, long unsigned int *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8140d800)
Location: mm/hugetlb.c:7024
Inline: False
Direct callers:
  - mm/memory.c:zap_page_range_single
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
```
**Symbols:**

```
ffffffff8140d800-ffffffff8140d879: adjust_range_if_pmd_sharing_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void adjust_range_if_pmd_sharing_possible(struct vm_area_struct *vma, long unsigned int *start, long unsigned int *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81440bb0)
Location: mm/hugetlb.c:7119
Inline: False
Direct callers:
  - mm/memory.c:zap_page_range_single
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
```
**Symbols:**

```
ffffffff81440bb0-ffffffff81440c29: adjust_range_if_pmd_sharing_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void adjust_range_if_pmd_sharing_possible(struct vm_area_struct *vma, long unsigned int *start, long unsigned int *end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8147999e)
Location: mm/hugetlb.c:7256
Inline: True
Inline callers:
  - mm/hugetlb.c:__hugetlb_zap_begin
Direct callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
```
**Symbols:**

```
ffffffff8147ace0-ffffffff8147ad59: adjust_range_if_pmd_sharing_possible (STB_GLOBAL)
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
void adjust_range_if_pmd_sharing_possible(struct vm_area_struct *vma, long unsigned int *start, long unsigned int *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffff8000103334b8)
Location: mm/hugetlb.c:4846
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
```
**Symbols:**

```
ffff8000103334b8-ffff800010333564: adjust_range_if_pmd_sharing_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/rmap.c (0)
Location: include/linux/hugetlb.h:161
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void adjust_range_if_pmd_sharing_possible(struct vm_area_struct *vma, long unsigned int *start, long unsigned int *end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (c000000000410380)
Location: mm/hugetlb.c:4968
Inline: True
Direct callers:
  - mm/rmap.c:try_to_unmap_one
```
**Symbols:**

```
c000000000410380-c00000000041038c: adjust_range_if_pmd_sharing_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void adjust_range_if_pmd_sharing_possible(struct vm_area_struct *vma, long unsigned int *start, long unsigned int *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffe00022fa2a)
Location: mm/hugetlb.c:4846
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
```
**Symbols:**

```
ffffffe00022fa2a-ffffffe00022faae: adjust_range_if_pmd_sharing_possible (STB_GLOBAL)
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
void adjust_range_if_pmd_sharing_possible(struct vm_area_struct *vma, long unsigned int *start, long unsigned int *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8128d0f0)
Location: mm/hugetlb.c:4846
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
```
**Symbols:**

```
ffffffff8128d0f0-ffffffff8128d15b: adjust_range_if_pmd_sharing_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void adjust_range_if_pmd_sharing_possible(struct vm_area_struct *vma, long unsigned int *start, long unsigned int *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8127ef00)
Location: mm/hugetlb.c:4846
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
```
**Symbols:**

```
ffffffff8127ef00-ffffffff8127ef6b: adjust_range_if_pmd_sharing_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void adjust_range_if_pmd_sharing_possible(struct vm_area_struct *vma, long unsigned int *start, long unsigned int *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8128af00)
Location: mm/hugetlb.c:4846
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
```
**Symbols:**

```
ffffffff8128af00-ffffffff8128af6b: adjust_range_if_pmd_sharing_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void adjust_range_if_pmd_sharing_possible(struct vm_area_struct *vma, long unsigned int *start, long unsigned int *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8129ad20)
Location: mm/hugetlb.c:4846
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
```
**Symbols:**

```
ffffffff8129ad20-ffffffff8129ad8b: adjust_range_if_pmd_sharing_possible (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
