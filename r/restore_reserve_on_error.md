# Function: <code>restore_reserve_on_error</code>

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
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void restore_reserve_on_error(struct hstate *h, struct vm_area_struct *vma, long unsigned int address, struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81209830)
Location: mm/hugetlb.c:1956
Inline: True
Direct callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
```
**Symbols:**

```
ffffffff81209830-ffffffff8120989e: restore_reserve_on_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void restore_reserve_on_error(struct hstate *h, struct vm_area_struct *vma, long unsigned int address, struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812150c0)
Location: mm/hugetlb.c:1936
Inline: True
Direct callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
**Symbols:**

```
ffffffff812150c0-ffffffff8121512f: restore_reserve_on_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void restore_reserve_on_error(struct hstate *h, struct vm_area_struct *vma, long unsigned int address, struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8122f980)
Location: mm/hugetlb.c:1942
Inline: True
Direct callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
**Symbols:**

```
ffffffff8122f980-ffffffff8122f9ef: restore_reserve_on_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void restore_reserve_on_error(struct hstate *h, struct vm_area_struct *vma, long unsigned int address, struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81253de0)
Location: mm/hugetlb.c:1958
Inline: True
Direct callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
**Symbols:**

```
ffffffff81253de0-ffffffff81253e4e: restore_reserve_on_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void restore_reserve_on_error(struct hstate *h, struct vm_area_struct *vma, long unsigned int address, struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812681c0)
Location: mm/hugetlb.c:1958
Inline: True
Direct callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
**Symbols:**

```
ffffffff812681c0-ffffffff8126822e: restore_reserve_on_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void restore_reserve_on_error(struct hstate *h, struct vm_area_struct *vma, long unsigned int address, struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81282bc0)
Location: mm/hugetlb.c:2001
Inline: True
Direct callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
**Symbols:**

```
ffffffff81282bc0-ffffffff81282c27: restore_reserve_on_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void restore_reserve_on_error(struct hstate *h, struct vm_area_struct *vma, long unsigned int address, struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812926e0)
Location: mm/hugetlb.c:2081
Inline: True
Direct callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
**Symbols:**

```
ffffffff812926e0-ffffffff81292747: restore_reserve_on_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffff812c93dd)
Location: mm/hugetlb.c:2337
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
Direct callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
**Symbols:**

```
ffffffff812c59f0-ffffffff812c5a5c: restore_reserve_on_error.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffff812d4ffc)
Location: mm/hugetlb.c:2287
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
Direct callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
**Symbols:**

```
ffffffff812d1640-ffffffff812d16ac: restore_reserve_on_error.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void restore_reserve_on_error(struct hstate *h, struct vm_area_struct *vma, long unsigned int address, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d9390)
Location: mm/hugetlb.c:2262
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff812d9390-ffffffff812d94da: restore_reserve_on_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void restore_reserve_on_error(struct hstate *h, struct vm_area_struct *vma, long unsigned int address, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8131fe70)
Location: mm/hugetlb.c:2522
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff8131fe70-ffffffff8131ff20: restore_reserve_on_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void restore_reserve_on_error(struct hstate *h, struct vm_area_struct *vma, long unsigned int address, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8138cbd0)
Location: mm/hugetlb.c:2634
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff8138cbd0-ffffffff8138ccab: restore_reserve_on_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void restore_reserve_on_error(struct hstate *h, struct vm_area_struct *vma, long unsigned int address, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8140b600)
Location: mm/hugetlb.c:2818
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff8140b600-ffffffff8140b6db: restore_reserve_on_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void restore_reserve_on_error(struct hstate *h, struct vm_area_struct *vma, long unsigned int address, struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8143ec50)
Location: mm/hugetlb.c:2847
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff8143ec50-ffffffff8143ed2b: restore_reserve_on_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void restore_reserve_on_error(struct hstate *h, struct vm_area_struct *vma, long unsigned int address, struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81478680)
Location: mm/hugetlb.c:2946
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff81478680-ffffffff8147875b: restore_reserve_on_error (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void restore_reserve_on_error(struct hstate *h, struct vm_area_struct *vma, long unsigned int address, struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffff800010330d28)
Location: mm/hugetlb.c:2081
Inline: True
Direct callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
**Symbols:**

```
ffff800010330d28-ffff800010330dcc: restore_reserve_on_error (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void restore_reserve_on_error(struct hstate *h, struct vm_area_struct *vma, long unsigned int address, struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (c000000000407ee0)
Location: mm/hugetlb.c:2081
Inline: True
Direct callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
**Symbols:**

```
c000000000407ee0-c000000000407fc8: restore_reserve_on_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void restore_reserve_on_error(struct hstate *h, struct vm_area_struct *vma, long unsigned int address, struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffe00022d244)
Location: mm/hugetlb.c:2081
Inline: True
Direct callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
**Symbols:**

```
ffffffe00022d244-ffffffe00022d2c6: restore_reserve_on_error (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void restore_reserve_on_error(struct hstate *h, struct vm_area_struct *vma, long unsigned int address, struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8128acc0)
Location: mm/hugetlb.c:2081
Inline: True
Direct callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
**Symbols:**

```
ffffffff8128acc0-ffffffff8128ad27: restore_reserve_on_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void restore_reserve_on_error(struct hstate *h, struct vm_area_struct *vma, long unsigned int address, struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8127caf0)
Location: mm/hugetlb.c:2081
Inline: True
Direct callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
**Symbols:**

```
ffffffff8127caf0-ffffffff8127cb57: restore_reserve_on_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void restore_reserve_on_error(struct hstate *h, struct vm_area_struct *vma, long unsigned int address, struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81288ad0)
Location: mm/hugetlb.c:2081
Inline: True
Direct callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
**Symbols:**

```
ffffffff81288ad0-ffffffff81288b37: restore_reserve_on_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void restore_reserve_on_error(struct hstate *h, struct vm_area_struct *vma, long unsigned int address, struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812976d0)
Location: mm/hugetlb.c:2081
Inline: True
Direct callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
**Symbols:**

```
ffffffff812976d0-ffffffff81297737: restore_reserve_on_error (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio *folio</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *page</code>
</li>
</ul>
</details>
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
