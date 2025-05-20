# Function: <code>prep_compound_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void prep_compound_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81192940)
Location: mm/page_alloc.c:465
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
Direct callers:
  - mm/hugetlb.c:hugetlb_init
```
**Symbols:**

```
ffffffff81192940-ffffffff81192991: prep_compound_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void prep_compound_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811a9952)
Location: mm/page_alloc.c:572
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff811a8090-ffffffff811a80f6: prep_compound_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void prep_compound_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811b9eb0)
Location: mm/page_alloc.c:577
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff811b8460-ffffffff811b84c6: prep_compound_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void prep_compound_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811c240d)
Location: mm/page_alloc.c:593
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff811c02b0-ffffffff811c0317: prep_compound_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void prep_compound_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811d6dbe)
Location: mm/page_alloc.c:608
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff811d4d90-ffffffff811d4df7: prep_compound_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void prep_compound_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811f86e1)
Location: mm/page_alloc.c:569
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
Direct callers:
  - mm/hugetlb.c:hugetlb_init
```
**Symbols:**

```
ffffffff811f61b0-ffffffff811f6216: prep_compound_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void prep_compound_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8120ad14)
Location: mm/page_alloc.c:614
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
Direct callers:
  - mm/hugetlb.c:hugetlb_init
```
**Symbols:**

```
ffffffff81208480-ffffffff812084e6: prep_compound_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void prep_compound_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8126d42b)
Location: mm/page_alloc.c:676
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
Direct callers:
  - mm/hugetlb.c:hugetlb_init
```
**Symbols:**

```
ffffffff8126e870-ffffffff8126e8d6: prep_compound_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void prep_compound_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8127bf6b)
Location: mm/page_alloc.c:664
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
Direct callers:
  - mm/hugetlb.c:hugetlb_init
```
**Symbols:**

```
ffffffff8127d6b0-ffffffff8127d716: prep_compound_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void prep_compound_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812af690)
Location: mm/page_alloc.c:658
Inline: False
Direct callers:
  - mm/page_alloc.c:prep_new_page
  - mm/hugetlb.c:gather_bootmem_prealloc
```
**Symbols:**

```
ffffffff812af690-ffffffff812af734: prep_compound_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void prep_compound_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812bb2c0)
Location: mm/page_alloc.c:658
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
  - mm/hugetlb.c:gather_bootmem_prealloc
```
**Symbols:**

```
ffffffff812bb2c0-ffffffff812bb36d: prep_compound_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void prep_compound_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812c0410)
Location: mm/page_alloc.c:680
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff812c0410-ffffffff812c04c0: prep_compound_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void prep_compound_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:731
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff81cbd3b0-ffffffff81cbd3ec: prep_compound_page.cold (STB_LOCAL)
ffffffff813031a0-ffffffff81303265: prep_compound_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void prep_compound_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:735
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
  - mm/hugetlb.c:demote_free_huge_page
```
**Symbols:**

```
ffffffff81e6f24a-ffffffff81e6f2a5: prep_compound_page.cold (STB_LOCAL)
ffffffff8136ab70-ffffffff8136ac23: prep_compound_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void prep_compound_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:794
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
  - mm/hugetlb.c:demote_free_huge_page
```
**Symbols:**

```
ffffffff820650cd-ffffffff82065128: prep_compound_page.cold (STB_LOCAL)
ffffffff813e6ec0-ffffffff813e6f88: prep_compound_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void prep_compound_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:610
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
  - mm/hugetlb.c:demote_free_hugetlb_folio
```
**Symbols:**

```
ffffffff820e486d-ffffffff820e48a9: prep_compound_page.cold (STB_LOCAL)
ffffffff8141c020-ffffffff8141c0dd: prep_compound_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void prep_compound_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:580
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
  - mm/hugetlb.c:demote_free_hugetlb_folio
```
**Symbols:**

```
ffffffff821c1518-ffffffff821c1552: prep_compound_page.cold (STB_LOCAL)
ffffffff81448b90-ffffffff81448c52: prep_compound_page (STB_GLOBAL)
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
void prep_compound_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff8000103134f0)
Location: mm/page_alloc.c:664
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
Direct callers:
  - mm/hugetlb.c:hugetlb_init
```
**Symbols:**

```
ffff800010314fd0-ffff800010315064: prep_compound_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void prep_compound_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c052e384)
Location: mm/page_alloc.c:664
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
```
**Symbols:**

```
c052f908-c052f97c: prep_compound_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void prep_compound_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003e5144)
Location: mm/page_alloc.c:664
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
Direct callers:
  - mm/hugetlb.c:hugetlb_init
```
**Symbols:**

```
c0000000003e6cf0-c0000000003e6d78: prep_compound_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void prep_compound_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe00021a89e)
Location: mm/page_alloc.c:664
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
Direct callers:
  - mm/hugetlb.c:hugetlb_init
```
**Symbols:**

```
ffffffe00021ba9a-ffffffe00021bb10: prep_compound_page (STB_GLOBAL)
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
void prep_compound_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812745bb)
Location: mm/page_alloc.c:664
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
Direct callers:
  - mm/hugetlb.c:hugetlb_init
```
**Symbols:**

```
ffffffff81275d00-ffffffff81275d66: prep_compound_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void prep_compound_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8126652b)
Location: mm/page_alloc.c:664
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
Direct callers:
  - mm/hugetlb.c:hugetlb_init
```
**Symbols:**

```
ffffffff81267c50-ffffffff81267cb6: prep_compound_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void prep_compound_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8127235b)
Location: mm/page_alloc.c:664
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
Direct callers:
  - mm/hugetlb.c:hugetlb_init
```
**Symbols:**

```
ffffffff81273aa0-ffffffff81273b06: prep_compound_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void prep_compound_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8128218b)
Location: mm/page_alloc.c:664
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
Direct callers:
  - mm/hugetlb.c:hugetlb_init
```
**Symbols:**

```
ffffffff812835a0-ffffffff81283606: prep_compound_page (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
