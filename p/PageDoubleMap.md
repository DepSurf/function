# Function: <code>PageDoubleMap</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811c4972)
Location: include/linux/page-flags.h:579
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
```
```
In mm/huge_memory.c (ffffffff81214f71)
Location: include/linux/page-flags.h:579
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811d4a82)
Location: include/linux/page-flags.h:595
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
```
```
In mm/huge_memory.c (ffffffff812275bd)
Location: include/linux/page-flags.h:595
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811dd8a2)
Location: include/linux/page-flags.h:598
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
```
```
In mm/huge_memory.c (ffffffff812337f4)
Location: include/linux/page-flags.h:598
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811f3322)
Location: include/linux/page-flags.h:599
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
```
```
In mm/swapfile.c (ffffffff81229dda)
Location: include/linux/page-flags.h:599
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/huge_memory.c (ffffffff81254665)
Location: include/linux/page-flags.h:599
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81214561)
Location: include/linux/page-flags.h:606
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
```
```
In mm/swapfile.c (ffffffff8124b09e)
Location: include/linux/page-flags.h:606
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/huge_memory.c (ffffffff812784b5)
Location: include/linux/page-flags.h:606
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81227431)
Location: include/linux/page-flags.h:623
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
```
```
In mm/swapfile.c (ffffffff8125f6f5)
Location: include/linux/page-flags.h:623
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/huge_memory.c (ffffffff8128e17f)
Location: include/linux/page-flags.h:623
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81237121)
Location: include/linux/page-flags.h:656
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
```
```
In mm/swapfile.c (ffffffff8127a357)
Location: include/linux/page-flags.h:656
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/huge_memory.c (ffffffff812a8af1)
Location: include/linux/page-flags.h:656
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81245391)
Location: include/linux/page-flags.h:672
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
```
```
In mm/swapfile.c (ffffffff81289e37)
Location: include/linux/page-flags.h:672
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/huge_memory.c (ffffffff812ba071)
Location: include/linux/page-flags.h:672
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81272ee1)
Location: include/linux/page-flags.h:688
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
```
```
In mm/swapfile.c (ffffffff812bc6b9)
Location: include/linux/page-flags.h:688
Inline: True
Inline callers:
  - mm/swapfile.c:page_trans_huge_map_swapcount
```
```
In mm/huge_memory.c (ffffffff812eec4f)
Location: include/linux/page-flags.h:688
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8127d5c7)
Location: include/linux/page-flags.h:692
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
```
```
In mm/swapfile.c (ffffffff812c81d9)
Location: include/linux/page-flags.h:692
Inline: True
Inline callers:
  - mm/swapfile.c:page_trans_huge_map_swapcount
```
```
In mm/huge_memory.c (ffffffff812fa2ab)
Location: include/linux/page-flags.h:692
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81282757)
Location: include/linux/page-flags.h:686
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
```
```
In mm/swapfile.c (ffffffff812cec53)
Location: include/linux/page-flags.h:686
Inline: True
Inline callers:
  - mm/swapfile.c:page_trans_huge_map_swapcount
```
```
In mm/huge_memory.c (ffffffff81301086)
Location: include/linux/page-flags.h:686
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff812c0877)
Location: include/linux/page-flags.h:669
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
```
```
In mm/rmap.c (ffffffff812f818d)
Location: include/linux/page-flags.h:669
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff813141e3)
Location: include/linux/page-flags.h:669
Inline: True
Inline callers:
  - mm/swapfile.c:page_trans_huge_map_swapcount
```
```
In mm/huge_memory.c (ffffffff8134acf6)
Location: include/linux/page-flags.h:669
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8131d805)
Location: include/linux/page-flags.h:892
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
```
```
In mm/rmap.c (ffffffff8135d3c0)
Location: include/linux/page-flags.h:892
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/util.c (ffff8000102d82d4)
Location: include/linux/page-flags.h:672
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
```
```
In mm/huge_memory.c (ffff800010359388)
Location: include/linux/page-flags.h:672
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/util.c (0)
Location: include/linux/page-flags.h:705
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/util.c (c000000000398018)
Location: include/linux/page-flags.h:672
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
```
```
In mm/huge_memory.c (c0000000004444a0)
Location: include/linux/page-flags.h:672
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
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
In mm/util.c (0)
Location: include/linux/page-flags.h:705
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8123d9e1)
Location: include/linux/page-flags.h:672
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
```
```
In mm/swapfile.c (ffffffff81282417)
Location: include/linux/page-flags.h:672
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/huge_memory.c (ffffffff812b2651)
Location: include/linux/page-flags.h:672
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff812309e1)
Location: include/linux/page-flags.h:672
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
```
```
In mm/swapfile.c (ffffffff81273f37)
Location: include/linux/page-flags.h:672
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/huge_memory.c (ffffffff812a39d8)
Location: include/linux/page-flags.h:672
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8123b781)
Location: include/linux/page-flags.h:672
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
```
```
In mm/swapfile.c (ffffffff81280227)
Location: include/linux/page-flags.h:672
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/huge_memory.c (ffffffff812b0461)
Location: include/linux/page-flags.h:672
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8124ae91)
Location: include/linux/page-flags.h:672
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
```
```
In mm/swapfile.c (ffffffff8128ff21)
Location: include/linux/page-flags.h:672
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/huge_memory.c (ffffffff812c07a1)
Location: include/linux/page-flags.h:672
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
</details>
</li>
</ul>

## Differences
