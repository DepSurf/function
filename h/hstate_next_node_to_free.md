# Function: <code>hstate_next_node_to_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffff811daae0)
Location: mm/hugetlb.c:981
Inline: True
Direct callers:
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:set_max_huge_pages
```
**Symbols:**

```
ffffffff811daae0-ffffffff811dab24: hstate_next_node_to_free.isra.42 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffff811f8c60)
Location: mm/hugetlb.c:1001
Inline: True
Direct callers:
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:free_pool_huge_page
```
**Symbols:**

```
ffffffff811f8c60-ffffffff811f8ca0: hstate_next_node_to_free.isra.42 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffff81209670)
Location: mm/hugetlb.c:1001
Inline: True
Direct callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:free_pool_huge_page
```
**Symbols:**

```
ffffffff81209670-ffffffff812096b0: hstate_next_node_to_free.isra.46 (STB_LOCAL)
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
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:1021
Inline: True
```
**Symbols:**

```
ffffffff81214f00-ffffffff81214f40: hstate_next_node_to_free.isra.52 (STB_LOCAL)
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
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:1022
Inline: True
```
**Symbols:**

```
ffffffff8122f940-ffffffff8122f980: hstate_next_node_to_free.isra.61 (STB_LOCAL)
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
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:1014
Inline: True
```
**Symbols:**

```
ffffffff81251e20-ffffffff81251e62: hstate_next_node_to_free.isra.67 (STB_LOCAL)
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
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:1014
Inline: True
```
**Symbols:**

```
ffffffff81266220-ffffffff81266262: hstate_next_node_to_free.isra.66 (STB_LOCAL)
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
In mm/hugetlb.c (ffffffff8128237a)
Location: mm/hugetlb.c:1024
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:free_pool_huge_page
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
In mm/hugetlb.c (ffffffff81291e81)
Location: mm/hugetlb.c:1025
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:free_pool_huge_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812c52b2)
Location: mm/hugetlb.c:1190
Inline: True
Inline callers:
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:free_pool_huge_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d0eb6)
Location: mm/hugetlb.c:1215
Inline: True
Inline callers:
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:free_pool_huge_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d7c85)
Location: mm/hugetlb.c:1225
Inline: True
Inline callers:
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:remove_pool_huge_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8131e59c)
Location: mm/hugetlb.c:1239
Inline: True
Inline callers:
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:remove_pool_huge_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81389df6)
Location: mm/hugetlb.c:1287
Inline: True
Inline callers:
  - mm/hugetlb.c:demote_store
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:remove_pool_huge_page
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8140ab76)
Location: mm/hugetlb.c:1451
Inline: True
Inline callers:
  - mm/hugetlb.c:demote_store
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:remove_pool_huge_page
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8143e226)
Location: mm/hugetlb.c:1448
Inline: True
Inline callers:
  - mm/hugetlb.c:demote_store
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:remove_pool_huge_page
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81477eb6)
Location: mm/hugetlb.c:1486
Inline: True
Inline callers:
  - mm/hugetlb.c:demote_store
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:remove_pool_hugetlb_folio
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
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:1025
Inline: True
```
**Symbols:**

```
ffff80001032e0c0-ffff80001032e140: hstate_next_node_to_free.isra.0 (STB_LOCAL)
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
In mm/hugetlb.c (c00000000040866c)
Location: mm/hugetlb.c:1025
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:free_pool_huge_page
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
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:1025
Inline: True
```
**Symbols:**

```
ffffffe00022bfb8-ffffffe00022c024: hstate_next_node_to_free.isra.0 (STB_LOCAL)
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
In mm/hugetlb.c (ffffffff8128a461)
Location: mm/hugetlb.c:1025
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:free_pool_huge_page
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
In mm/hugetlb.c (ffffffff8127c291)
Location: mm/hugetlb.c:1025
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:free_pool_huge_page
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
In mm/hugetlb.c (ffffffff81288271)
Location: mm/hugetlb.c:1025
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:free_pool_huge_page
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
In mm/hugetlb.c (ffffffff81298699)
Location: mm/hugetlb.c:1025
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:free_pool_huge_page
```
</details>
</li>
</ul>

## Differences
