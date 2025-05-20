# Function: <code>alloc_surplus_huge_page</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct page *alloc_surplus_huge_page(struct hstate *h, gfp_t gfp_mask, int nid, nodemask_t *nmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81252e00)
Location: mm/hugetlb.c:1549
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_huge_page
```
**Symbols:**

```
ffffffff81252e00-ffffffff81252f29: alloc_surplus_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct page *alloc_surplus_huge_page(struct hstate *h, gfp_t gfp_mask, int nid, nodemask_t *nmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81266f70)
Location: mm/hugetlb.c:1549
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_huge_page
```
**Symbols:**

```
ffffffff81266f70-ffffffff81267099: alloc_surplus_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct page *alloc_surplus_huge_page(struct hstate *h, gfp_t gfp_mask, int nid, nodemask_t *nmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81282c30)
Location: mm/hugetlb.c:1591
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_huge_page
```
**Symbols:**

```
ffffffff81282c30-ffffffff81282d69: alloc_surplus_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct page *alloc_surplus_huge_page(struct hstate *h, gfp_t gfp_mask, int nid, nodemask_t *nmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81292750)
Location: mm/hugetlb.c:1671
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_huge_page
```
**Symbols:**

```
ffffffff81292750-ffffffff8129288c: alloc_surplus_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *alloc_surplus_huge_page(struct hstate *h, gfp_t gfp_mask, int nid, nodemask_t *nmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812c5a60)
Location: mm/hugetlb.c:1916
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:gather_surplus_pages
```
**Symbols:**

```
ffffffff812c5a60-ffffffff812c5b9c: alloc_surplus_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *alloc_surplus_huge_page(struct hstate *h, gfp_t gfp_mask, int nid, nodemask_t *nmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d16b0)
Location: mm/hugetlb.c:1885
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:gather_surplus_pages
```
**Symbols:**

```
ffffffff812d16b0-ffffffff812d17e9: alloc_surplus_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page *alloc_surplus_huge_page(struct hstate *h, gfp_t gfp_mask, int nid, nodemask_t *nmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d81c0)
Location: mm/hugetlb.c:1832
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:gather_surplus_pages
```
**Symbols:**

```
ffffffff812d81c0-ffffffff812d82fc: alloc_surplus_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct page *alloc_surplus_huge_page(struct hstate *h, gfp_t gfp_mask, int nid, nodemask_t *nmask, bool zero_ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:2060
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:gather_surplus_pages
```
**Symbols:**

```
ffffffff8131e010-ffffffff8131e135: alloc_surplus_huge_page (STB_LOCAL)
ffffffff81cbf524-ffffffff81cbf557: alloc_surplus_huge_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct page *alloc_surplus_huge_page(struct hstate *h, gfp_t gfp_mask, int nid, nodemask_t *nmask, bool zero_ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:2172
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:gather_surplus_pages
```
**Symbols:**

```
ffffffff8138a0f0-ffffffff8138a208: alloc_surplus_huge_page (STB_LOCAL)
ffffffff81e71845-ffffffff81e71873: alloc_surplus_huge_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct page *alloc_surplus_huge_page(struct hstate *h, gfp_t gfp_mask, int nid, nodemask_t *nmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81409220)
Location: mm/hugetlb.c:2382
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:gather_surplus_pages
```
**Symbols:**

```
ffffffff81409220-ffffffff81409319: alloc_surplus_huge_page (STB_LOCAL)
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
struct page *alloc_surplus_huge_page(struct hstate *h, gfp_t gfp_mask, int nid, nodemask_t *nmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffff80001032ffa8)
Location: mm/hugetlb.c:1671
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_huge_page
```
**Symbols:**

```
ffff80001032ffa8-ffff80001033018c: alloc_surplus_huge_page (STB_LOCAL)
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
struct page *alloc_surplus_huge_page(struct hstate *h, gfp_t gfp_mask, int nid, nodemask_t *nmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (c000000000408a20)
Location: mm/hugetlb.c:1671
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_huge_page
```
**Symbols:**

```
c000000000408a20-c000000000408cbc: alloc_surplus_huge_page (STB_LOCAL)
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
In mm/hugetlb.c (ffffffe00022d2c6)
Location: mm/hugetlb.c:1671
Inline: True
Direct callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_huge_page
```
**Symbols:**

```
ffffffe00022d2c6-ffffffe00022d452: alloc_surplus_huge_page.constprop.0 (STB_LOCAL)
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
struct page *alloc_surplus_huge_page(struct hstate *h, gfp_t gfp_mask, int nid, nodemask_t *nmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8128ad30)
Location: mm/hugetlb.c:1671
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_huge_page
```
**Symbols:**

```
ffffffff8128ad30-ffffffff8128ae6c: alloc_surplus_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct page *alloc_surplus_huge_page(struct hstate *h, gfp_t gfp_mask, int nid, nodemask_t *nmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8127cb60)
Location: mm/hugetlb.c:1671
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_huge_page
```
**Symbols:**

```
ffffffff8127cb60-ffffffff8127cc9c: alloc_surplus_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct page *alloc_surplus_huge_page(struct hstate *h, gfp_t gfp_mask, int nid, nodemask_t *nmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81288b40)
Location: mm/hugetlb.c:1671
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_huge_page
```
**Symbols:**

```
ffffffff81288b40-ffffffff81288c7c: alloc_surplus_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct page *alloc_surplus_huge_page(struct hstate *h, gfp_t gfp_mask, int nid, nodemask_t *nmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812988f0)
Location: mm/hugetlb.c:1671
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_huge_page
```
**Symbols:**

```
ffffffff812988f0-ffffffff81298a24: alloc_surplus_huge_page (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool zero_ref</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool zero_ref</code>
</li>
</ul>
</details>
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
