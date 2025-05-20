# Function: <code>compound_mapcount</code>

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
In mm/debug.c (ffffffff811d4525)
Location: include/linux/mm.h:507
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/huge_memory.c (ffffffff81216594)
Location: include/linux/mm.h:507
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
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
In mm/debug.c (ffffffff811e45b1)
Location: include/linux/mm.h:494
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/huge_memory.c (ffffffff81228b4e)
Location: include/linux/mm.h:494
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
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
In mm/vmscan.c (ffffffff811d2c98)
Location: include/linux/mm.h:550
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/debug.c (ffffffff811eea96)
Location: include/linux/mm.h:550
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/huge_memory.c (ffffffff812321b2)
Location: include/linux/mm.h:550
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/vmscan.c (ffffffff811e81dc)
Location: include/linux/mm.h:567
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/debug.c (ffffffff81204f06)
Location: include/linux/mm.h:567
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/swapfile.c (ffffffff81229df6)
Location: include/linux/mm.h:567
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/huge_memory.c (ffffffff8125466d)
Location: include/linux/mm.h:567
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:__split_huge_pmd
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
In mm/vmscan.c (ffffffff812095e9)
Location: include/linux/mm.h:609
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/debug.c (ffffffff81225d4a)
Location: include/linux/mm.h:609
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/swapfile.c (ffffffff8124b0b8)
Location: include/linux/mm.h:609
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/huge_memory.c (ffffffff812784c6)
Location: include/linux/mm.h:609
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:__split_huge_pmd
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
In mm/vmscan.c (ffffffff8121c2d0)
Location: include/linux/mm.h:637
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/debug.c (ffffffff81239410)
Location: include/linux/mm.h:637
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/swapfile.c (ffffffff8125f712)
Location: include/linux/mm.h:637
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/huge_memory.c (ffffffff8128cb1a)
Location: include/linux/mm.h:637
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/vmscan.c (ffffffff8122bc7f)
Location: include/linux/mm.h:703
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/debug.c (ffffffff8124a470)
Location: include/linux/mm.h:703
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/swapfile.c (ffffffff8127a374)
Location: include/linux/mm.h:703
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/huge_memory.c (ffffffff812a781a)
Location: include/linux/mm.h:703
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/vmscan.c (ffffffff81239b41)
Location: include/linux/mm.h:698
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/debug.c (ffffffff812587e6)
Location: include/linux/mm.h:698
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/swapfile.c (ffffffff81289e54)
Location: include/linux/mm.h:698
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/huge_memory.c (ffffffff812b8cba)
Location: include/linux/mm.h:698
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/vmscan.c (ffffffff81266590)
Location: include/linux/mm.h:787
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/debug.c (ffffffff812870e5)
Location: include/linux/mm.h:787
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/swapfile.c (ffffffff812bc6d8)
Location: include/linux/mm.h:787
Inline: True
Inline callers:
  - mm/swapfile.c:page_trans_huge_map_swapcount
```
```
In mm/huge_memory.c (ffffffff812ed86e)
Location: include/linux/mm.h:787
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/vmscan.c (ffffffff81271184)
Location: include/linux/mm.h:820
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/swapfile.c (ffffffff812c81ec)
Location: include/linux/mm.h:820
Inline: True
Inline callers:
  - mm/swapfile.c:page_trans_huge_map_swapcount
```
```
In mm/huge_memory.c (ffffffff812f8efb)
Location: include/linux/mm.h:820
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/vmscan.c (ffffffff81275ce1)
Location: include/linux/mm.h:843
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/swapfile.c (ffffffff812cec65)
Location: include/linux/mm.h:843
Inline: True
Inline callers:
  - mm/swapfile.c:page_trans_huge_map_swapcount
```
```
In mm/huge_memory.c (ffffffff812ff53e)
Location: include/linux/mm.h:843
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/vmscan.c (ffffffff812b39d8)
Location: include/linux/mm.h:846
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/swapfile.c (ffffffff813141f5)
Location: include/linux/mm.h:846
Inline: True
Inline callers:
  - mm/swapfile.c:page_trans_huge_map_swapcount
```
```
In mm/huge_memory.c (ffffffff8134914e)
Location: include/linux/mm.h:846
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:follow_trans_huge_pmd
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
In mm/huge_memory.c (ffffffff813bbab7)
Location: include/linux/mm.h:797
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/vmscan.c (ffff8000102caa18)
Location: include/linux/mm.h:698
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/debug.c (ffff8000102f07ec)
Location: include/linux/mm.h:698
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/huge_memory.c (ffff8000103593a0)
Location: include/linux/mm.h:698
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:follow_trans_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (0)
Location: include/linux/mm.h:698
Inline: True
```
```
In mm/debug.c (c0513d34)
Location: include/linux/mm.h:698
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
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
In mm/vmscan.c (c00000000038768c)
Location: include/linux/mm.h:698
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/debug.c (c0000000003b5170)
Location: include/linux/mm.h:698
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/huge_memory.c (c000000000442814)
Location: include/linux/mm.h:698
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:follow_trans_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (0)
Location: include/linux/mm.h:698
Inline: True
```
```
In mm/debug.c (ffffffe000203ff8)
Location: include/linux/mm.h:698
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
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
In mm/vmscan.c (ffffffff81232191)
Location: include/linux/mm.h:698
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/debug.c (ffffffff81250e36)
Location: include/linux/mm.h:698
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/swapfile.c (ffffffff81282434)
Location: include/linux/mm.h:698
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/huge_memory.c (ffffffff812b129a)
Location: include/linux/mm.h:698
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/vmscan.c (ffffffff81225251)
Location: include/linux/mm.h:698
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/debug.c (ffffffff81243d76)
Location: include/linux/mm.h:698
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/swapfile.c (ffffffff81273f54)
Location: include/linux/mm.h:698
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/huge_memory.c (ffffffff812a266a)
Location: include/linux/mm.h:698
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/vmscan.c (ffffffff8122ff31)
Location: include/linux/mm.h:698
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/debug.c (ffffffff8124ebd6)
Location: include/linux/mm.h:698
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/swapfile.c (ffffffff81280244)
Location: include/linux/mm.h:698
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/huge_memory.c (ffffffff812af0aa)
Location: include/linux/mm.h:698
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/vmscan.c (ffffffff8123f37a)
Location: include/linux/mm.h:698
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/debug.c (ffffffff8125e556)
Location: include/linux/mm.h:698
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/swapfile.c (ffffffff8128ff3f)
Location: include/linux/mm.h:698
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/huge_memory.c (ffffffff812bf3fa)
Location: include/linux/mm.h:698
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:follow_trans_huge_pmd
```
</details>
</li>
</ul>

## Differences
