# Function: <code>set_max_huge_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int set_max_huge_pages(struct hstate *h, long unsigned int count, nodemask_t *nodes_allowed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811dbae0)
Location: mm/hugetlb.c:2141
Inline: False
Direct callers:
  - mm/hugetlb.c:nr_hugepages_store_common
  - mm/hugetlb.c:hugetlb_sysctl_handler_common
```
**Symbols:**

```
ffffffff811dbae0-ffffffff811dc017: set_max_huge_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int set_max_huge_pages(struct hstate *h, long unsigned int count, nodemask_t *nodes_allowed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811f9d50)
Location: mm/hugetlb.c:2188
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_sysctl_handler_common
  - mm/hugetlb.c:nr_hugepages_store_common
```
**Symbols:**

```
ffffffff811f9d50-ffffffff811fa2b7: set_max_huge_pages (STB_LOCAL)
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
In mm/hugetlb.c (ffffffff8120a82c)
Location: mm/hugetlb.c:2294
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81215ba4)
Location: mm/hugetlb.c:2272
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812307d7)
Location: mm/hugetlb.c:2280
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81252fa3)
Location: mm/hugetlb.c:2285
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81267a13)
Location: mm/hugetlb.c:2279
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8128215a)
Location: mm/hugetlb.c:2322
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81291bde)
Location: mm/hugetlb.c:2424
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int set_max_huge_pages(struct hstate *h, long unsigned int count, int nid, nodemask_t *nodes_allowed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812c5040)
Location: mm/hugetlb.c:2707
Inline: False
Direct callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
```
**Symbols:**

```
ffffffff812c5040-ffffffff812c52f7: set_max_huge_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int set_max_huge_pages(struct hstate *h, long unsigned int count, int nid, nodemask_t *nodes_allowed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d0c40)
Location: mm/hugetlb.c:2660
Inline: False
Direct callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
```
**Symbols:**

```
ffffffff812d0c40-ffffffff812d0f04: set_max_huge_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int set_max_huge_pages(struct hstate *h, long unsigned int count, int nid, nodemask_t *nodes_allowed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d7970)
Location: mm/hugetlb.c:2805
Inline: False
Direct callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
```
**Symbols:**

```
ffffffff812d7970-ffffffff812d7cea: set_max_huge_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int set_max_huge_pages(struct hstate *h, long unsigned int count, int nid, nodemask_t *nodes_allowed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8131e260)
Location: mm/hugetlb.c:3088
Inline: False
Direct callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
```
**Symbols:**

```
ffffffff8131e260-ffffffff8131e6f5: set_max_huge_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int set_max_huge_pages(struct hstate *h, long unsigned int count, int nid, nodemask_t *nodes_allowed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8138a390)
Location: mm/hugetlb.c:3267
Inline: False
Direct callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
```
**Symbols:**

```
ffffffff8138a390-ffffffff8138a84d: set_max_huge_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int set_max_huge_pages(struct hstate *h, long unsigned int count, int nid, nodemask_t *nodes_allowed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:3431
Inline: False
Direct callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
```
**Symbols:**

```
ffffffff81409d40-ffffffff8140a296: set_max_huge_pages (STB_LOCAL)
ffffffff82066455-ffffffff8206648b: set_max_huge_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int set_max_huge_pages(struct hstate *h, long unsigned int count, int nid, nodemask_t *nodes_allowed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:3462
Inline: False
Direct callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
```
**Symbols:**

```
ffffffff8143d3b0-ffffffff8143d8f1: set_max_huge_pages (STB_LOCAL)
ffffffff820e5c0a-ffffffff820e5c40: set_max_huge_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int set_max_huge_pages(struct hstate *h, long unsigned int count, int nid, nodemask_t *nodes_allowed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:3691
Inline: False
Direct callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
```
**Symbols:**

```
ffffffff81475300-ffffffff814758b1: set_max_huge_pages (STB_LOCAL)
ffffffff821c2b09-ffffffff821c2b3f: set_max_huge_pages.cold (STB_LOCAL)
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
int set_max_huge_pages(struct hstate *h, long unsigned int count, int nid, nodemask_t *nodes_allowed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffff80001032f968)
Location: mm/hugetlb.c:2424
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_sysctl_handler_common
  - mm/hugetlb.c:nr_hugepages_store_common
```
**Symbols:**

```
ffff80001032f968-ffff80001032fc8c: set_max_huge_pages (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (c0000000004082ac)
Location: mm/hugetlb.c:2424
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
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
In mm/hugetlb.c (ffffffe00022dd1c)
Location: mm/hugetlb.c:2424
Inline: True
Direct callers:
  - mm/hugetlb.c:hugetlb_sysctl_handler
  - mm/hugetlb.c:nr_hugepages_store
```
**Symbols:**

```
ffffffe00022dd1c-ffffffe00022df6a: set_max_huge_pages.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8128a1be)
Location: mm/hugetlb.c:2424
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8127bfee)
Location: mm/hugetlb.c:2424
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81287fce)
Location: mm/hugetlb.c:2424
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8129840e)
Location: mm/hugetlb.c:2424
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
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
</ul>
