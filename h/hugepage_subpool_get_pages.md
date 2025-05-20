# Function: <code>hugepage_subpool_get_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int hugepage_subpool_get_pages(struct hugepage_subpool *spool, long int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811d9a00)
Location: mm/hugetlb.c:129
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
```
**Symbols:**

```
ffffffff811d9a00-ffffffff811d9a78: hugepage_subpool_get_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int hugepage_subpool_get_pages(struct hugepage_subpool *spool, long int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811f7bf0)
Location: mm/hugetlb.c:129
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
```
**Symbols:**

```
ffffffff811f7bf0-ffffffff811f7c71: hugepage_subpool_get_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int hugepage_subpool_get_pages(struct hugepage_subpool *spool, long int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812085a0)
Location: mm/hugetlb.c:129
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
```
**Symbols:**

```
ffffffff812085a0-ffffffff81208621: hugepage_subpool_get_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffff81217a49)
Location: mm/hugetlb.c:131
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
Direct callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
```
**Symbols:**

```
ffffffff81214b20-ffffffff81214b98: hugepage_subpool_get_pages.part.34 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffff812327a2)
Location: mm/hugetlb.c:132
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
Direct callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
```
**Symbols:**

```
ffffffff8122f6b0-ffffffff8122f728: hugepage_subpool_get_pages.part.42 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffff812557f0)
Location: mm/hugetlb.c:131
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
Direct callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
```
**Symbols:**

```
ffffffff81252850-ffffffff812528c8: hugepage_subpool_get_pages.part.48 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffff81269bd0)
Location: mm/hugetlb.c:131
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
Direct callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
```
**Symbols:**

```
ffffffff81266ab0-ffffffff81266b28: hugepage_subpool_get_pages.part.48 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffff81284d1c)
Location: mm/hugetlb.c:133
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
Direct callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
```
**Symbols:**

```
ffffffff81281980-ffffffff81281a01: hugepage_subpool_get_pages.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffff812948bc)
Location: mm/hugetlb.c:134
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
Direct callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
```
**Symbols:**

```
ffffffff81291390-ffffffff81291411: hugepage_subpool_get_pages.part.0 (STB_LOCAL)
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
In mm/hugetlb.c (ffffffff812c7d4f)
Location: mm/hugetlb.c:140
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
Direct callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
```
**Symbols:**

```
ffffffff812c46a0-ffffffff812c4721: hugepage_subpool_get_pages.part.0 (STB_LOCAL)
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
In mm/hugetlb.c (ffffffff812d38b5)
Location: mm/hugetlb.c:157
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
Direct callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
```
**Symbols:**

```
ffffffff812d0350-ffffffff812d03d1: hugepage_subpool_get_pages.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffff812da807)
Location: mm/hugetlb.c:154
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
Direct callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
```
**Symbols:**

```
ffffffff812d71b0-ffffffff812d7238: hugepage_subpool_get_pages.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffff813217aa)
Location: mm/hugetlb.c:156
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
Direct callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
```
**Symbols:**

```
ffffffff8131d060-ffffffff8131d0e8: hugepage_subpool_get_pages.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffff8138e7af)
Location: mm/hugetlb.c:170
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
Direct callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
```
**Symbols:**

```
ffffffff813880e0-ffffffff81388190: hugepage_subpool_get_pages.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffff8140d21e)
Location: mm/hugetlb.c:170
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
Direct callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
```
**Symbols:**

```
ffffffff81406360-ffffffff81406410: hugepage_subpool_get_pages.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffff81440666)
Location: mm/hugetlb.c:170
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
Direct callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
```
**Symbols:**

```
ffffffff81439a40-ffffffff81439af0: hugepage_subpool_get_pages.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffff8147a6ee)
Location: mm/hugetlb.c:172
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
Direct callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
```
**Symbols:**

```
ffffffff81473540-ffffffff814735f0: hugepage_subpool_get_pages.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffff8000103331d4)
Location: mm/hugetlb.c:134
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
Direct callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
```
**Symbols:**

```
ffff80001032ee40-ffff80001032ef3c: hugepage_subpool_get_pages.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (c000000000410000)
Location: mm/hugetlb.c:134
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
Direct callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
```
**Symbols:**

```
c000000000407b40-c000000000407c80: hugepage_subpool_get_pages.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffe00022f7d8)
Location: mm/hugetlb.c:134
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
Direct callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
```
**Symbols:**

```
ffffffe00022c4bc-ffffffe00022c568: hugepage_subpool_get_pages.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffff8128ce9c)
Location: mm/hugetlb.c:134
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
Direct callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
```
**Symbols:**

```
ffffffff81289970-ffffffff812899f1: hugepage_subpool_get_pages.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffff8127ecac)
Location: mm/hugetlb.c:134
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
Direct callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
```
**Symbols:**

```
ffffffff8127b7a0-ffffffff8127b821: hugepage_subpool_get_pages.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffff8128acac)
Location: mm/hugetlb.c:134
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
Direct callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
```
**Symbols:**

```
ffffffff81287780-ffffffff81287801: hugepage_subpool_get_pages.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffff8129aaa0)
Location: mm/hugetlb.c:134
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
Direct callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
```
**Symbols:**

```
ffffffff81297340-ffffffff812973bf: hugepage_subpool_get_pages.part.0 (STB_LOCAL)
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
</ul>
