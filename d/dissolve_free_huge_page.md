# Function: <code>dissolve_free_huge_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811dc6d5)
Location: mm/hugetlb.c:1415
Inline: True
Inline callers:
  - mm/hugetlb.c:dissolve_free_huge_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811fa93a)
Location: mm/hugetlb.c:1442
Inline: True
Inline callers:
  - mm/hugetlb.c:dissolve_free_huge_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8120b3b0)
Location: mm/hugetlb.c:1444
Inline: True
Inline callers:
  - mm/hugetlb.c:dissolve_free_huge_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dissolve_free_huge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81216900)
Location: mm/hugetlb.c:1462
Inline: False
Direct callers:
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
```
**Symbols:**

```
ffffffff81216900-ffffffff81216a70: dissolve_free_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dissolve_free_huge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812315b0)
Location: mm/hugetlb.c:1468
Inline: False
Direct callers:
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
```
**Symbols:**

```
ffffffff812315b0-ffffffff81231720: dissolve_free_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dissolve_free_huge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812544c0)
Location: mm/hugetlb.c:1485
Inline: False
Direct callers:
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:me_huge_page
```
**Symbols:**

```
ffffffff812544c0-ffffffff8125462a: dissolve_free_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dissolve_free_huge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812688a0)
Location: mm/hugetlb.c:1486
Inline: False
Direct callers:
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:me_huge_page
```
**Symbols:**

```
ffffffff812688a0-ffffffff81268a0e: dissolve_free_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int dissolve_free_huge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81283970)
Location: mm/hugetlb.c:1521
Inline: True
Direct callers:
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:me_huge_page
```
**Symbols:**

```
ffffffff81283970-ffffffff81283acd: dissolve_free_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int dissolve_free_huge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81293510)
Location: mm/hugetlb.c:1601
Inline: True
Direct callers:
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
```
**Symbols:**

```
ffffffff81293510-ffffffff8129366d: dissolve_free_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dissolve_free_huge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffff812c6acf)
Location: mm/hugetlb.c:1846
Inline: True
Inline callers:
  - mm/hugetlb.c:dissolve_free_huge_pages
Direct callers:
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:me_huge_page
```
**Symbols:**

```
ffffffff812c4da0-ffffffff812c4f0d: dissolve_free_huge_page.part.0 (STB_LOCAL)
ffffffff812c6a40-ffffffff812c6a7a: dissolve_free_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dissolve_free_huge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d2580)
Location: mm/hugetlb.c:1794
Inline: False
Direct callers:
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:me_huge_page
```
**Symbols:**

```
ffffffff812d2580-ffffffff812d274b: dissolve_free_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dissolve_free_huge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d8fc0)
Location: mm/hugetlb.c:1743
Inline: False
Direct callers:
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:me_huge_page
```
**Symbols:**

```
ffffffff812d8fc0-ffffffff812d919b: dissolve_free_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dissolve_free_huge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:1952
Inline: False
Direct callers:
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/memory-failure.c:__page_handle_poison
```
**Symbols:**

```
ffffffff81cbf6ee-ffffffff81cbf725: dissolve_free_huge_page.cold (STB_LOCAL)
ffffffff8131f9d0-ffffffff8131fc61: dissolve_free_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dissolve_free_huge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:2064
Inline: False
Direct callers:
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/memory-failure.c:__page_handle_poison
```
**Symbols:**

```
ffffffff81e71a84-ffffffff81e71ac1: dissolve_free_huge_page.cold (STB_LOCAL)
ffffffff8138c570-ffffffff8138c971: dissolve_free_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int dissolve_free_huge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:2277
Inline: False
Direct callers:
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/memory-failure.c:__page_handle_poison
```
**Symbols:**

```
ffffffff82066565-ffffffff8206659b: dissolve_free_huge_page.cold (STB_LOCAL)
ffffffff8140b050-ffffffff8140b292: dissolve_free_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int dissolve_free_huge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:2304
Inline: False
Direct callers:
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/memory-failure.c:__page_handle_poison
```
**Symbols:**

```
ffffffff820e5d34-ffffffff820e5d6a: dissolve_free_huge_page.cold (STB_LOCAL)
ffffffff8143e670-ffffffff8143e8ec: dissolve_free_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int dissolve_free_huge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:2415
Inline: False
Direct callers:
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/memory-failure.c:__page_handle_poison
```
**Symbols:**

```
ffffffff821c2dd6-ffffffff821c2e0b: dissolve_free_huge_page.cold (STB_LOCAL)
ffffffff81478180-ffffffff81478404: dissolve_free_huge_page (STB_GLOBAL)
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
int dissolve_free_huge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffff800010331548)
Location: mm/hugetlb.c:1601
Inline: True
Direct callers:
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
```
**Symbols:**

```
ffff800010331548-ffff800010331794: dissolve_free_huge_page (STB_GLOBAL)
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
int dissolve_free_huge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (c00000000040a330)
Location: mm/hugetlb.c:1601
Inline: True
Direct callers:
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
```
**Symbols:**

```
c00000000040a330-c00000000040a618: dissolve_free_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int dissolve_free_huge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffe00022e634)
Location: mm/hugetlb.c:1601
Inline: True
Direct callers:
  - mm/hugetlb.c:dissolve_free_huge_pages
```
**Symbols:**

```
ffffffe00022e634-ffffffe00022e7be: dissolve_free_huge_page (STB_GLOBAL)
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
int dissolve_free_huge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8128baf0)
Location: mm/hugetlb.c:1601
Inline: True
Direct callers:
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
```
**Symbols:**

```
ffffffff8128baf0-ffffffff8128bc4d: dissolve_free_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int dissolve_free_huge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8127d920)
Location: mm/hugetlb.c:1601
Inline: True
Direct callers:
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
```
**Symbols:**

```
ffffffff8127d920-ffffffff8127da7d: dissolve_free_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int dissolve_free_huge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81289900)
Location: mm/hugetlb.c:1601
Inline: True
Direct callers:
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
```
**Symbols:**

```
ffffffff81289900-ffffffff81289a5d: dissolve_free_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int dissolve_free_huge_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812996e0)
Location: mm/hugetlb.c:1601
Inline: True
Direct callers:
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
```
**Symbols:**

```
ffffffff812996e0-ffffffff81299841: dissolve_free_huge_page (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
