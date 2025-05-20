# Function: <code>next_node_allowed</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int next_node_allowed(int nid, nodemask_t *nodes_allowed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811d9b00)
Location: mm/hugetlb.c:939
Inline: False
```
**Symbols:**

```
ffffffff811d9b00-ffffffff811d9b53: next_node_allowed (STB_LOCAL)
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
In mm/hugetlb.c (ffffffff811f8c80)
Location: mm/hugetlb.c:961
Inline: True
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
In mm/hugetlb.c (ffffffff81209690)
Location: mm/hugetlb.c:961
Inline: True
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
In mm/hugetlb.c (ffffffff81214f20)
Location: mm/hugetlb.c:981
Inline: True
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
In mm/hugetlb.c (ffffffff8122f960)
Location: mm/hugetlb.c:982
Inline: True
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
In mm/hugetlb.c (ffffffff81251e57)
Location: mm/hugetlb.c:974
Inline: True
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
In mm/hugetlb.c (ffffffff81266257)
Location: mm/hugetlb.c:974
Inline: True
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
In mm/hugetlb.c (ffffffff81282385)
Location: mm/hugetlb.c:984
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:get_valid_node_allowed
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
In mm/hugetlb.c (ffffffff81291e86)
Location: mm/hugetlb.c:985
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:get_valid_node_allowed
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
In mm/hugetlb.c (ffffffff812c5133)
Location: mm/hugetlb.c:1150
Inline: True
Inline callers:
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
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
In mm/hugetlb.c (ffffffff812d0d33)
Location: mm/hugetlb.c:1175
Inline: True
Inline callers:
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
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
In mm/hugetlb.c (ffffffff812d7c91)
Location: mm/hugetlb.c:1185
Inline: True
Inline callers:
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:remove_pool_huge_page
  - mm/hugetlb.c:remove_pool_huge_page
  - mm/hugetlb.c:hstate_next_node_to_alloc
  - mm/hugetlb.c:hstate_next_node_to_alloc
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
In mm/hugetlb.c (ffffffff8131e5a8)
Location: mm/hugetlb.c:1199
Inline: True
Inline callers:
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:remove_pool_huge_page
  - mm/hugetlb.c:remove_pool_huge_page
  - mm/hugetlb.c:hstate_next_node_to_alloc
  - mm/hugetlb.c:hstate_next_node_to_alloc
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
In mm/hugetlb.c (ffffffff81389ef8)
Location: mm/hugetlb.c:1247
Inline: True
Inline callers:
  - mm/hugetlb.c:demote_store
  - mm/hugetlb.c:demote_store
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:remove_pool_huge_page
  - mm/hugetlb.c:remove_pool_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
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
In mm/hugetlb.c (ffffffff8140ab8e)
Location: mm/hugetlb.c:1411
Inline: True
Inline callers:
  - mm/hugetlb.c:demote_store
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:remove_pool_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:get_valid_node_allowed
  - mm/hugetlb.c:__alloc_bootmem_huge_page
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
In mm/hugetlb.c (ffffffff8143e23e)
Location: mm/hugetlb.c:1408
Inline: True
Inline callers:
  - mm/hugetlb.c:demote_store
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:remove_pool_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:get_valid_node_allowed
  - mm/hugetlb.c:__alloc_bootmem_huge_page
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
In mm/hugetlb.c (ffffffff81477ece)
Location: mm/hugetlb.c:1446
Inline: True
Inline callers:
  - mm/hugetlb.c:demote_store
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:remove_pool_hugetlb_folio
  - mm/hugetlb.c:alloc_pool_huge_folio
  - mm/hugetlb.c:get_valid_node_allowed
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffff80001032e12c)
Location: mm/hugetlb.c:985
Inline: True
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
In mm/hugetlb.c (c00000000040867c)
Location: mm/hugetlb.c:985
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:get_valid_node_allowed
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffe00022c014)
Location: mm/hugetlb.c:985
Inline: True
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
In mm/hugetlb.c (ffffffff8128a466)
Location: mm/hugetlb.c:985
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:get_valid_node_allowed
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
In mm/hugetlb.c (ffffffff8127c296)
Location: mm/hugetlb.c:985
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:get_valid_node_allowed
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
In mm/hugetlb.c (ffffffff81288276)
Location: mm/hugetlb.c:985
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:get_valid_node_allowed
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
In mm/hugetlb.c (ffffffff812986a4)
Location: mm/hugetlb.c:985
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:get_valid_node_allowed
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
