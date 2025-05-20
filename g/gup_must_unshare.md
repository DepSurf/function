# Function: <code>gup_must_unshare</code>

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
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8133a7c4)
Location: include/linux/mm.h:3054
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_pte_range
  - mm/gup.c:follow_page_pte
```
```
In mm/hugetlb.c (ffffffff8139364d)
Location: include/linux/mm.h:3054
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/huge_memory.c (ffffffff813bcba9)
Location: include/linux/mm.h:3054
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813b22ae)
Location: include/linux/mm.h:3208
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_pte_range
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/hugetlb.c (ffffffff81411dbe)
Location: include/linux/mm.h:3208
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/huge_memory.c (ffffffff8143f1a4)
Location: include/linux/mm.h:3208
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool gup_must_unshare(struct vm_area_struct *vma, unsigned int flags, struct page *page);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813e39f0)
Location: mm/internal.h:969
Inline: True
Direct callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_pte_range
  - mm/gup.c:follow_page_pte
```
```
In mm/hugetlb.c (ffffffff81445409)
Location: mm/internal.h:969
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/huge_memory.c (ffffffff8147496b)
Location: mm/internal.h:969
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
```
**Symbols:**

```
ffffffff813e39f0-ffffffff813e3b0a: gup_must_unshare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool gup_must_unshare(struct vm_area_struct *vma, unsigned int flags, struct page *page);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8140e270)
Location: mm/internal.h:1059
Inline: True
Direct callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_pte_range
  - mm/gup.c:follow_page_pte
```
```
In mm/hugetlb.c (ffffffff8147b69b)
Location: mm/internal.h:1059
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_follow_page_mask
```
```
In mm/huge_memory.c (ffffffff814a3fee)
Location: mm/internal.h:1059
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
```
**Symbols:**

```
ffffffff8140e270-ffffffff8140e37e: gup_must_unshare (STB_LOCAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
