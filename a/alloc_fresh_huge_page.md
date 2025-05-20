# Function: <code>alloc_fresh_huge_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int alloc_fresh_huge_page(struct hstate *h, nodemask_t *nodes_allowed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811db170)
Location: mm/hugetlb.c:1351
Inline: False
Direct callers:
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
**Symbols:**

```
ffffffff811db170-ffffffff811db21c: alloc_fresh_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int alloc_fresh_huge_page(struct hstate *h, nodemask_t *nodes_allowed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811f93b0)
Location: mm/hugetlb.c:1378
Inline: False
Direct callers:
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
**Symbols:**

```
ffffffff811f93b0-ffffffff811f9465: alloc_fresh_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int alloc_fresh_huge_page(struct hstate *h, nodemask_t *nodes_allowed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8120a6e0)
Location: mm/hugetlb.c:1378
Inline: False
Direct callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
**Symbols:**

```
ffffffff8120a6e0-ffffffff8120a79a: alloc_fresh_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int alloc_fresh_huge_page(struct hstate *h, nodemask_t *nodes_allowed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81215a70)
Location: mm/hugetlb.c:1396
Inline: False
Direct callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
**Symbols:**

```
ffffffff81215a70-ffffffff81215b1b: alloc_fresh_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int alloc_fresh_huge_page(struct hstate *h, nodemask_t *nodes_allowed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812306a0)
Location: mm/hugetlb.c:1402
Inline: False
Direct callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
**Symbols:**

```
ffffffff812306a0-ffffffff8123074b: alloc_fresh_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct page *alloc_fresh_huge_page(struct hstate *h, gfp_t gfp_mask, int nid, nodemask_t *nmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812524e0)
Location: mm/hugetlb.c:1397
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:alloc_huge_page_node
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
```
**Symbols:**

```
ffffffff812524e0-ffffffff8125284d: alloc_fresh_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct page *alloc_fresh_huge_page(struct hstate *h, gfp_t gfp_mask, int nid, nodemask_t *nmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81266740)
Location: mm/hugetlb.c:1398
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:alloc_huge_page_node
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
```
**Symbols:**

```
ffffffff81266740-ffffffff81266ab0: alloc_fresh_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct page *alloc_fresh_huge_page(struct hstate *h, gfp_t gfp_mask, int nid, nodemask_t *nmask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81281a10)
Location: mm/hugetlb.c:1429
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:alloc_huge_page_node
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
```
**Symbols:**

```
ffffffff81281a10-ffffffff81281da4: alloc_fresh_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct page *alloc_fresh_huge_page(struct hstate *h, gfp_t gfp_mask, int nid, nodemask_t *nmask, nodemask_t *node_alloc_noretry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81291420)
Location: mm/hugetlb.c:1506
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:alloc_huge_page_node
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
```
**Symbols:**

```
ffffffff81291420-ffffffff8129181a: alloc_fresh_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *alloc_fresh_huge_page(struct hstate *h, gfp_t gfp_mask, int nid, nodemask_t *nmask, nodemask_t *node_alloc_noretry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812c4880)
Location: mm/hugetlb.c:1751
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:alloc_huge_page_node
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
```
**Symbols:**

```
ffffffff812c4880-ffffffff812c49be: alloc_fresh_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *alloc_fresh_huge_page(struct hstate *h, gfp_t gfp_mask, int nid, nodemask_t *nmask, nodemask_t *node_alloc_noretry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d0520)
Location: mm/hugetlb.c:1699
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
```
**Symbols:**

```
ffffffff812d0520-ffffffff812d065e: alloc_fresh_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page *alloc_fresh_huge_page(struct hstate *h, gfp_t gfp_mask, int nid, nodemask_t *nmask, nodemask_t *node_alloc_noretry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d7430)
Location: mm/hugetlb.c:1654
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
```
**Symbols:**

```
ffffffff812d7430-ffffffff812d74dd: alloc_fresh_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct page *alloc_fresh_huge_page(struct hstate *h, gfp_t gfp_mask, int nid, nodemask_t *nmask, nodemask_t *node_alloc_noretry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:1845
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
```
**Symbols:**

```
ffffffff8131ded0-ffffffff8131e00e: alloc_fresh_huge_page (STB_LOCAL)
ffffffff81cbf4ed-ffffffff81cbf524: alloc_fresh_huge_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct page *alloc_fresh_huge_page(struct hstate *h, gfp_t gfp_mask, int nid, nodemask_t *nmask, nodemask_t *node_alloc_noretry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:1957
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
```
**Symbols:**

```
ffffffff81389750-ffffffff8138987f: alloc_fresh_huge_page (STB_LOCAL)
ffffffff81e716fa-ffffffff81e71731: alloc_fresh_huge_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
struct page *alloc_fresh_huge_page(struct hstate *h, gfp_t gfp_mask, int nid, nodemask_t *nmask, nodemask_t *node_alloc_noretry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffff80001032f480)
Location: mm/hugetlb.c:1506
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:alloc_huge_page_node
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
```
**Symbols:**

```
ffff80001032f480-ffff80001032f63c: alloc_fresh_huge_page (STB_LOCAL)
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
struct page *alloc_fresh_huge_page(struct hstate *h, gfp_t gfp_mask, int nid, nodemask_t *nmask, nodemask_t *node_alloc_noretry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (c000000000407570)
Location: mm/hugetlb.c:1506
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:alloc_huge_page_node
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
```
**Symbols:**

```
c000000000407570-c000000000407b40: alloc_fresh_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct page *alloc_fresh_huge_page(struct hstate *h, gfp_t gfp_mask, int nid, nodemask_t *nmask, nodemask_t *node_alloc_noretry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffe00022c568)
Location: mm/hugetlb.c:1506
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page_node
  - mm/hugetlb.c:alloc_pool_huge_page
```
**Symbols:**

```
ffffffe00022c568-ffffffe00022c986: alloc_fresh_huge_page (STB_LOCAL)
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
struct page *alloc_fresh_huge_page(struct hstate *h, gfp_t gfp_mask, int nid, nodemask_t *nmask, nodemask_t *node_alloc_noretry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81289a00)
Location: mm/hugetlb.c:1506
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:alloc_huge_page_node
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
```
**Symbols:**

```
ffffffff81289a00-ffffffff81289dfa: alloc_fresh_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct page *alloc_fresh_huge_page(struct hstate *h, gfp_t gfp_mask, int nid, nodemask_t *nmask, nodemask_t *node_alloc_noretry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8127b830)
Location: mm/hugetlb.c:1506
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:alloc_huge_page_node
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
```
**Symbols:**

```
ffffffff8127b830-ffffffff8127bc2a: alloc_fresh_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct page *alloc_fresh_huge_page(struct hstate *h, gfp_t gfp_mask, int nid, nodemask_t *nmask, nodemask_t *node_alloc_noretry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81287810)
Location: mm/hugetlb.c:1506
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:alloc_huge_page_node
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
```
**Symbols:**

```
ffffffff81287810-ffffffff81287c0a: alloc_fresh_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct page *alloc_fresh_huge_page(struct hstate *h, gfp_t gfp_mask, int nid, nodemask_t *nmask, nodemask_t *node_alloc_noretry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81297db0)
Location: mm/hugetlb.c:1506
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:alloc_huge_page_node
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
```
**Symbols:**

```
ffffffff81297db0-ffffffff812981a0: alloc_fresh_huge_page (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>gfp_t gfp_mask</code>
</li>
<li>
<b>Param added. </b>
<code>int nid</code>
</li>
<li>
<b>Param added. </b>
<code>nodemask_t *nmask</code>
</li>
<li>
<b>Param removed. </b>
<code>nodemask_t *nodes_allowed</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>struct page *</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>nodemask_t *node_alloc_noretry</code>
</li>
</ul>
</details>
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
