# Function: <code>unmap_hugepage_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void unmap_hugepage_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct page *ref_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811ddb20)
Location: mm/hugetlb.c:3275
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_cow
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff811ddb20-ffffffff811ddbb6: unmap_hugepage_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void unmap_hugepage_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct page *ref_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811fbdf0)
Location: mm/hugetlb.c:3290
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_cow
  - fs/hugetlbfs/inode.c:hugetlb_vmdelete_list
```
**Symbols:**

```
ffffffff811fbdf0-ffffffff811fbe86: unmap_hugepage_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void unmap_hugepage_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct page *ref_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8120c8a0)
Location: mm/hugetlb.c:3401
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_cow
  - fs/hugetlbfs/inode.c:hugetlb_vmdelete_list
```
**Symbols:**

```
ffffffff8120c8a0-ffffffff8120c936: unmap_hugepage_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void unmap_hugepage_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct page *ref_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81218210)
Location: mm/hugetlb.c:3385
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_cow
  - fs/hugetlbfs/inode.c:hugetlb_vmdelete_list
```
**Symbols:**

```
ffffffff81218210-ffffffff812182a6: unmap_hugepage_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void unmap_hugepage_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct page *ref_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81233090)
Location: mm/hugetlb.c:3406
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_cow
  - fs/hugetlbfs/inode.c:hugetlb_vmdelete_list
```
**Symbols:**

```
ffffffff81233090-ffffffff81233126: unmap_hugepage_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void unmap_hugepage_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct page *ref_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812560a0)
Location: mm/hugetlb.c:3436
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_cow
  - fs/hugetlbfs/inode.c:hugetlb_vmdelete_list
```
**Symbols:**

```
ffffffff812560a0-ffffffff81256136: unmap_hugepage_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void unmap_hugepage_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct page *ref_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8126a540)
Location: mm/hugetlb.c:3454
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_cow
  - fs/hugetlbfs/inode.c:hugetlb_vmdelete_list
```
**Symbols:**

```
ffffffff8126a540-ffffffff8126a607: unmap_hugepage_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void unmap_hugepage_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct page *ref_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81285670)
Location: mm/hugetlb.c:3524
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_cow
  - fs/hugetlbfs/inode.c:hugetlb_vmdelete_list
```
**Symbols:**

```
ffffffff81285670-ffffffff81285738: unmap_hugepage_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void unmap_hugepage_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct page *ref_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81295230)
Location: mm/hugetlb.c:3641
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_cow
  - fs/hugetlbfs/inode.c:hugetlb_vmdelete_list
```
**Symbols:**

```
ffffffff81295230-ffffffff812952f8: unmap_hugepage_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void unmap_hugepage_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct page *ref_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812c8830)
Location: mm/hugetlb.c:4063
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlb_vmdelete_list
```
**Symbols:**

```
ffffffff812c8830-ffffffff812c8915: unmap_hugepage_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void unmap_hugepage_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct page *ref_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d43d0)
Location: mm/hugetlb.c:4033
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlb_vmdelete_list
```
**Symbols:**

```
ffffffff812d43d0-ffffffff812d4498: unmap_hugepage_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void unmap_hugepage_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct page *ref_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812db2b0)
Location: mm/hugetlb.c:4261
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_cow
  - fs/hugetlbfs/inode.c:hugetlb_vmdelete_list
```
**Symbols:**

```
ffffffff812db2b0-ffffffff812db33a: unmap_hugepage_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void unmap_hugepage_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct page *ref_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff813224c0)
Location: mm/hugetlb.c:4566
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_cow
  - fs/hugetlbfs/inode.c:hugetlb_vmdelete_list
```
**Symbols:**

```
ffffffff813224c0-ffffffff8132254a: unmap_hugepage_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void unmap_hugepage_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct page *ref_page, zap_flags_t zap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8138f9a0)
Location: mm/hugetlb.c:5146
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_wp
  - fs/hugetlbfs/inode.c:hugetlb_vmdelete_list
```
**Symbols:**

```
ffffffff8138f9a0-ffffffff8138fa57: unmap_hugepage_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void unmap_hugepage_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct page *ref_page, zap_flags_t zap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81410280)
Location: mm/hugetlb.c:5393
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_wp
  - fs/hugetlbfs/inode.c:hugetlb_vmdelete_list
  - fs/hugetlbfs/inode.c:hugetlb_unmap_file_folio
  - fs/hugetlbfs/inode.c:hugetlb_unmap_file_folio
```
**Symbols:**

```
ffffffff81410280-ffffffff814103f2: unmap_hugepage_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void unmap_hugepage_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct page *ref_page, zap_flags_t zap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81443650)
Location: mm/hugetlb.c:5479
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_wp
  - fs/hugetlbfs/inode.c:hugetlb_vmdelete_list
  - fs/hugetlbfs/inode.c:hugetlb_unmap_file_folio
  - fs/hugetlbfs/inode.c:hugetlb_unmap_file_folio
```
**Symbols:**

```
ffffffff81443650-ffffffff814437b4: unmap_hugepage_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void unmap_hugepage_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct page *ref_page, zap_flags_t zap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8147d6d0)
Location: mm/hugetlb.c:5746
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_wp
  - fs/hugetlbfs/inode.c:hugetlb_vmdelete_list
  - fs/hugetlbfs/inode.c:hugetlb_unmap_file_folio
  - fs/hugetlbfs/inode.c:hugetlb_unmap_file_folio
```
**Symbols:**

```
ffffffff8147d6d0-ffffffff8147d832: unmap_hugepage_range (STB_GLOBAL)
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
void unmap_hugepage_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct page *ref_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffff800010333f38)
Location: mm/hugetlb.c:3641
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_cow
  - fs/hugetlbfs/inode.c:hugetlb_vmdelete_list
```
**Symbols:**

```
ffff800010333f38-ffff800010333fe4: unmap_hugepage_range (STB_GLOBAL)
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
void unmap_hugepage_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct page *ref_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (c00000000040cba0)
Location: mm/hugetlb.c:3641
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_cow
  - fs/hugetlbfs/inode.c:hugetlb_vmdelete_list
```
**Symbols:**

```
c00000000040cba0-c00000000040cc60: unmap_hugepage_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void unmap_hugepage_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct page *ref_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffe00023005e)
Location: mm/hugetlb.c:3641
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_cow
  - fs/hugetlbfs/inode.c:hugetlb_vmdelete_list
```
**Symbols:**

```
ffffffe00023005e-ffffffe0002300e8: unmap_hugepage_range (STB_GLOBAL)
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
void unmap_hugepage_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct page *ref_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8128d810)
Location: mm/hugetlb.c:3641
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_cow
  - fs/hugetlbfs/inode.c:hugetlb_vmdelete_list
```
**Symbols:**

```
ffffffff8128d810-ffffffff8128d8d8: unmap_hugepage_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void unmap_hugepage_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct page *ref_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8127f5a0)
Location: mm/hugetlb.c:3641
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_cow
  - fs/hugetlbfs/inode.c:hugetlb_vmdelete_list
```
**Symbols:**

```
ffffffff8127f5a0-ffffffff8127f668: unmap_hugepage_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void unmap_hugepage_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct page *ref_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8128b620)
Location: mm/hugetlb.c:3641
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_cow
  - fs/hugetlbfs/inode.c:hugetlb_vmdelete_list
```
**Symbols:**

```
ffffffff8128b620-ffffffff8128b6e8: unmap_hugepage_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void unmap_hugepage_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct page *ref_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8129b430)
Location: mm/hugetlb.c:3641
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_cow
  - fs/hugetlbfs/inode.c:hugetlb_vmdelete_list
```
**Symbols:**

```
ffffffff8129b430-ffffffff8129b4f8: unmap_hugepage_range (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>zap_flags_t zap_flags</code>
</li>
</ul>
</details>
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
