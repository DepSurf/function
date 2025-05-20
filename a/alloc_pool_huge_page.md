# Function: <code>alloc_pool_huge_page</code>

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
int alloc_pool_huge_page(struct hstate *h, nodemask_t *nodes_allowed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81252d10)
Location: mm/hugetlb.c:1421
Inline: False
Direct callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
**Symbols:**

```
ffffffff81252d10-ffffffff81252df5: alloc_pool_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int alloc_pool_huge_page(struct hstate *h, nodemask_t *nodes_allowed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812670a0)
Location: mm/hugetlb.c:1422
Inline: False
Direct callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
**Symbols:**

```
ffffffff812670a0-ffffffff81267185: alloc_pool_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int alloc_pool_huge_page(struct hstate *h, nodemask_t *nodes_allowed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81282010)
Location: mm/hugetlb.c:1453
Inline: False
Direct callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
**Symbols:**

```
ffffffff81282010-ffffffff8128210b: alloc_pool_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int alloc_pool_huge_page(struct hstate *h, nodemask_t *nodes_allowed, nodemask_t *node_alloc_noretry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81291a80)
Location: mm/hugetlb.c:1531
Inline: False
Direct callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
**Symbols:**

```
ffffffff81291a80-ffffffff81291b87: alloc_pool_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int alloc_pool_huge_page(struct hstate *h, nodemask_t *nodes_allowed, nodemask_t *node_alloc_noretry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812c4f10)
Location: mm/hugetlb.c:1776
Inline: False
Direct callers:
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
**Symbols:**

```
ffffffff812c4f10-ffffffff812c5039: alloc_pool_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int alloc_pool_huge_page(struct hstate *h, nodemask_t *nodes_allowed, nodemask_t *node_alloc_noretry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d0b10)
Location: mm/hugetlb.c:1724
Inline: False
Direct callers:
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
**Symbols:**

```
ffffffff812d0b10-ffffffff812d0c36: alloc_pool_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int alloc_pool_huge_page(struct hstate *h, nodemask_t *nodes_allowed, nodemask_t *node_alloc_noretry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d74e0)
Location: mm/hugetlb.c:1679
Inline: False
Direct callers:
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
**Symbols:**

```
ffffffff812d74e0-ffffffff812d7600: alloc_pool_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int alloc_pool_huge_page(struct hstate *h, nodemask_t *nodes_allowed, nodemask_t *node_alloc_noretry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8131e140)
Location: mm/hugetlb.c:1884
Inline: False
Direct callers:
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
**Symbols:**

```
ffffffff8131e140-ffffffff8131e260: alloc_pool_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int alloc_pool_huge_page(struct hstate *h, nodemask_t *nodes_allowed, nodemask_t *node_alloc_noretry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8138a210)
Location: mm/hugetlb.c:1996
Inline: False
Direct callers:
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
**Symbols:**

```
ffffffff8138a210-ffffffff8138a387: alloc_pool_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int alloc_pool_huge_page(struct hstate *h, nodemask_t *nodes_allowed, nodemask_t *node_alloc_noretry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81409c10)
Location: mm/hugetlb.c:2210
Inline: False
Direct callers:
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
**Symbols:**

```
ffffffff81409c10-ffffffff81409d2c: alloc_pool_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int alloc_pool_huge_page(struct hstate *h, nodemask_t *nodes_allowed, nodemask_t *node_alloc_noretry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8143d280)
Location: mm/hugetlb.c:2237
Inline: False
Direct callers:
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
**Symbols:**

```
ffffffff8143d280-ffffffff8143d39c: alloc_pool_huge_page (STB_LOCAL)
```
</details>
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
int alloc_pool_huge_page(struct hstate *h, nodemask_t *nodes_allowed, nodemask_t *node_alloc_noretry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffff80001032f640)
Location: mm/hugetlb.c:1531
Inline: False
Direct callers:
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
**Symbols:**

```
ffff80001032f640-ffff80001032f760: alloc_pool_huge_page (STB_LOCAL)
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
int alloc_pool_huge_page(struct hstate *h, nodemask_t *nodes_allowed, nodemask_t *node_alloc_noretry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (c000000000407fd0)
Location: mm/hugetlb.c:1531
Inline: False
Direct callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
**Symbols:**

```
c000000000407fd0-c00000000040820c: alloc_pool_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int alloc_pool_huge_page(struct hstate *h, nodemask_t *nodes_allowed, nodemask_t *node_alloc_noretry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffe00022d452)
Location: mm/hugetlb.c:1531
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
**Symbols:**

```
ffffffe00022d452-ffffffe00022d4fc: alloc_pool_huge_page (STB_LOCAL)
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
int alloc_pool_huge_page(struct hstate *h, nodemask_t *nodes_allowed, nodemask_t *node_alloc_noretry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8128a060)
Location: mm/hugetlb.c:1531
Inline: False
Direct callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
**Symbols:**

```
ffffffff8128a060-ffffffff8128a167: alloc_pool_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int alloc_pool_huge_page(struct hstate *h, nodemask_t *nodes_allowed, nodemask_t *node_alloc_noretry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8127be90)
Location: mm/hugetlb.c:1531
Inline: False
Direct callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
**Symbols:**

```
ffffffff8127be90-ffffffff8127bf97: alloc_pool_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int alloc_pool_huge_page(struct hstate *h, nodemask_t *nodes_allowed, nodemask_t *node_alloc_noretry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81287e70)
Location: mm/hugetlb.c:1531
Inline: False
Direct callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
**Symbols:**

```
ffffffff81287e70-ffffffff81287f77: alloc_pool_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int alloc_pool_huge_page(struct hstate *h, nodemask_t *nodes_allowed, nodemask_t *node_alloc_noretry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812982b0)
Location: mm/hugetlb.c:1531
Inline: False
Direct callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
**Symbols:**

```
ffffffff812982b0-ffffffff812983b7: alloc_pool_huge_page (STB_LOCAL)
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
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
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
