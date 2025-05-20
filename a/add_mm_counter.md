# Function: <code>add_mm_counter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811bbc46)
Location: include/linux/mm.h:1370
Inline: True
Inline callers:
  - mm/memory.c:sync_mm_rss
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/huge_memory.c (ffffffff811f565e)
Location: include/linux/mm.h:1370
Inline: True
Inline callers:
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In fs/exec.c (ffffffff81212fd8)
Location: include/linux/mm.h:1370
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811da32e)
Location: include/linux/mm.h:1464
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:sync_mm_rss
```
```
In mm/madvise.c (ffffffff811eedad)
Location: include/linux/mm.h:1464
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/huge_memory.c (ffffffff8121601b)
Location: include/linux/mm.h:1464
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8121a5d0)
Location: include/linux/mm.h:1464
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/exec.c (ffffffff8123a240)
Location: include/linux/mm.h:1464
Inline: True
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
In mm/memory.c (ffffffff811e9e56)
Location: include/linux/mm.h:1438
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:sync_mm_rss
```
```
In mm/madvise.c (ffffffff811ff6dc)
Location: include/linux/mm.h:1438
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/huge_memory.c (ffffffff812285e3)
Location: include/linux/mm.h:1438
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8122e9d7)
Location: include/linux/mm.h:1438
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/exec.c (ffffffff8124cf97)
Location: include/linux/mm.h:1438
Inline: True
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
In mm/memory.c (ffffffff811f4f4f)
Location: include/linux/mm.h:1470
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:sync_mm_rss
```
```
In mm/madvise.c (ffffffff8120a4d1)
Location: include/linux/mm.h:1470
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/huge_memory.c (ffffffff81231d1e)
Location: include/linux/mm.h:1470
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8123866c)
Location: include/linux/mm.h:1470
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/exec.c (ffffffff81258f39)
Location: include/linux/mm.h:1470
Inline: True
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
In mm/memory.c (ffffffff8120d03a)
Location: include/linux/mm.h:1544
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:copy_pte_range
  - mm/memory.c:sync_mm_rss
```
```
In mm/madvise.c (ffffffff81223751)
Location: include/linux/mm.h:1544
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/huge_memory.c (ffffffff8125298e)
Location: include/linux/mm.h:1544
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81259b3d)
Location: include/linux/mm.h:1544
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/exec.c (ffffffff8127b0cd)
Location: include/linux/mm.h:1544
Inline: True
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
In mm/memory.c (ffffffff8122dc03)
Location: include/linux/mm.h:1631
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:sync_mm_rss
```
```
In mm/madvise.c (ffffffff81246558)
Location: include/linux/mm.h:1631
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/huge_memory.c (ffffffff81276dd3)
Location: include/linux/mm.h:1631
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8127c4b2)
Location: include/linux/mm.h:1631
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/exec.c (ffffffff812a1eb4)
Location: include/linux/mm.h:1631
Inline: True
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
In mm/memory.c (ffffffff81241399)
Location: include/linux/mm.h:1701
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:sync_mm_rss
```
```
In mm/madvise.c (ffffffff8125a97b)
Location: include/linux/mm.h:1701
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/huge_memory.c (ffffffff81288686)
Location: include/linux/mm.h:1701
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81290b54)
Location: include/linux/mm.h:1701
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/exec.c (ffffffff812b6c63)
Location: include/linux/mm.h:1701
Inline: True
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
In mm/memory.c (ffffffff81253860)
Location: include/linux/mm.h:1696
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:sync_mm_rss
```
```
In mm/madvise.c (ffffffff81275956)
Location: include/linux/mm.h:1696
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/huge_memory.c (ffffffff812a32c4)
Location: include/linux/mm.h:1696
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812a9e88)
Location: include/linux/mm.h:1696
Inline: True
```
```
In fs/exec.c (ffffffff812d3936)
Location: include/linux/mm.h:1696
Inline: True
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
In mm/memory.c (ffffffff81261dc0)
Location: include/linux/mm.h:1668
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:sync_mm_rss
```
```
In mm/madvise.c (ffffffff81284926)
Location: include/linux/mm.h:1668
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/huge_memory.c (ffffffff812b47c4)
Location: include/linux/mm.h:1668
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812bdfe6)
Location: include/linux/mm.h:1668
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/exec.c (ffffffff812e54c6)
Location: include/linux/mm.h:1668
Inline: True
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
In mm/memory.c (ffffffff8128c85a)
Location: include/linux/mm.h:1882
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:add_mm_counter_fast
  - mm/memory.c:sync_mm_rss
```
```
In mm/madvise.c (ffffffff812b6ad5)
Location: include/linux/mm.h:1882
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/huge_memory.c (ffffffff812e9d97)
Location: include/linux/mm.h:1882
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812f3945)
Location: include/linux/mm.h:1882
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:__collapse_huge_page_copy
```
```
In fs/exec.c (ffffffff8131bbde)
Location: include/linux/mm.h:1882
Inline: True
Inline callers:
  - fs/exec.c:acct_arg_size
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
In mm/memory.c (ffffffff81297b07)
Location: include/linux/mm.h:1927
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:add_mm_counter_fast
  - mm/memory.c:sync_mm_rss
```
```
In mm/madvise.c (ffffffff812c2d25)
Location: include/linux/mm.h:1927
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/huge_memory.c (ffffffff812f4f77)
Location: include/linux/mm.h:1927
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812ff160)
Location: include/linux/mm.h:1927
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/exec.c (ffffffff81326d1e)
Location: include/linux/mm.h:1927
Inline: True
Inline callers:
  - fs/exec.c:acct_arg_size
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
In mm/memory.c (ffffffff812a18ba)
Location: include/linux/mm.h:1935
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:add_mm_counter_fast
  - mm/memory.c:sync_mm_rss
```
```
In mm/madvise.c (ffffffff812c9b9e)
Location: include/linux/mm.h:1935
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/huge_memory.c (ffffffff812fb4dd)
Location: include/linux/mm.h:1935
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81305dd5)
Location: include/linux/mm.h:1935
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/exec.c (ffffffff8132cdbe)
Location: include/linux/mm.h:1935
Inline: True
Inline callers:
  - fs/exec.c:acct_arg_size
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
In mm/memory.c (ffffffff812e28a4)
Location: include/linux/mm.h:1964
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:add_mm_counter_fast
  - mm/memory.c:sync_mm_rss
```
```
In mm/madvise.c (ffffffff8130ebbe)
Location: include/linux/mm.h:1964
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/huge_memory.c (ffffffff81345316)
Location: include/linux/mm.h:1964
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8134fc43)
Location: include/linux/mm.h:1964
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/exec.c (ffffffff8137a55e)
Location: include/linux/mm.h:1964
Inline: True
Inline callers:
  - fs/exec.c:acct_arg_size
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void add_mm_counter(struct mm_struct *mm, int member, long int value);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81343088)
Location: include/linux/mm.h:2042
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:add_mm_counter_fast
  - mm/memory.c:sync_mm_rss
```
```
In mm/madvise.c (ffffffff81376a46)
Location: include/linux/mm.h:2042
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/huge_memory.c (ffffffff813bb1b5)
Location: include/linux/mm.h:2042
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff813c32f0)
Location: include/linux/mm.h:2042
Inline: True
Direct callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/exec.c (ffffffff813fa2ae)
Location: include/linux/mm.h:2042
Inline: True
Inline callers:
  - fs/exec.c:acct_arg_size
```
**Symbols:**

```
ffffffff813c32f0-ffffffff813c3357: add_mm_counter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void add_mm_counter(struct mm_struct *mm, int member, long int value);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813bb033)
Location: include/linux/mm.h:2208
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/madvise.c (ffffffff813f431c)
Location: include/linux/mm.h:2208
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/huge_memory.c (ffffffff8143d787)
Location: include/linux/mm.h:2208
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81445a20)
Location: include/linux/mm.h:2208
Inline: True
Direct callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/exec.c (ffffffff81484711)
Location: include/linux/mm.h:2208
Inline: True
Inline callers:
  - fs/exec.c:free_bprm
  - fs/exec.c:begin_new_exec
  - fs/exec.c:get_arg_page
```
**Symbols:**

```
ffffffff81445a20-ffffffff81445a89: add_mm_counter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void add_mm_counter(struct mm_struct *mm, int member, long int value);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813efb39)
Location: include/linux/mm.h:2528
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/madvise.c (ffffffff81427bb8)
Location: include/linux/mm.h:2528
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/huge_memory.c (ffffffff81472e2d)
Location: include/linux/mm.h:2528
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8147b080)
Location: include/linux/mm.h:2528
Inline: True
Direct callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/exec.c (ffffffff814b92f1)
Location: include/linux/mm.h:2528
Inline: True
Inline callers:
  - fs/exec.c:free_bprm
  - fs/exec.c:begin_new_exec
  - fs/exec.c:get_arg_page
```
**Symbols:**

```
ffffffff8147b080-ffffffff8147b0e9: add_mm_counter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void add_mm_counter(struct mm_struct *mm, int member, long int value);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8141b355)
Location: include/linux/mm.h:2577
Inline: True
Inline callers:
  - mm/memory.c:set_pte_range
  - mm/memory.c:set_pte_range
  - mm/memory.c:do_set_pmd
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/madvise.c (ffffffff814613cd)
Location: include/linux/mm.h:2577
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/huge_memory.c (ffffffff814a1590)
Location: include/linux/mm.h:2577
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff814b08d4)
Location: include/linux/mm.h:2577
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
Direct callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/exec.c (ffffffff814ebae1)
Location: include/linux/mm.h:2577
Inline: True
Inline callers:
  - fs/exec.c:free_bprm
  - fs/exec.c:begin_new_exec
  - fs/exec.c:get_arg_page
```
**Symbols:**

```
ffffffff814aa500-ffffffff814aa569: add_mm_counter (STB_LOCAL)
```
</details>
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
In mm/memory.c (ffff8000102f8d40)
Location: include/linux/mm.h:1668
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:vm_insert_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:sync_mm_rss
```
```
In mm/madvise.c (ffff80001031ed80)
Location: include/linux/mm.h:1668
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/huge_memory.c (ffff800010355da8)
Location: include/linux/mm.h:1668
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffff80001035f5b4)
Location: include/linux/mm.h:1668
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/exec.c (ffff80001038c64c)
Location: include/linux/mm.h:1668
Inline: True
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
In mm/memory.c (c0519030)
Location: include/linux/mm.h:1668
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:sync_mm_rss
```
```
In mm/madvise.c (c05378ec)
Location: include/linux/mm.h:1668
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In fs/exec.c (c0573620)
Location: include/linux/mm.h:1668
Inline: True
Inline callers:
  - fs/exec.c:acct_arg_size
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
In mm/memory.c (c0000000003c2b80)
Location: include/linux/mm.h:1668
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:vm_insert_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:sync_mm_rss
```
```
In mm/madvise.c (c0000000003f315c)
Location: include/linux/mm.h:1668
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/huge_memory.c (c00000000043c0b8)
Location: include/linux/mm.h:1668
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (c00000000044a4bc)
Location: include/linux/mm.h:1668
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/exec.c (c000000000484fcc)
Location: include/linux/mm.h:1668
Inline: True
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
In mm/memory.c (ffffffe000209bfa)
Location: include/linux/mm.h:1668
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:vm_insert_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/madvise.c (ffffffe0002206aa)
Location: include/linux/mm.h:1668
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In fs/exec.c (ffffffe00025ecea)
Location: include/linux/mm.h:1668
Inline: True
Inline callers:
  - fs/exec.c:__do_execve_file
  - fs/exec.c:copy_strings
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
In mm/memory.c (ffffffff8125a410)
Location: include/linux/mm.h:1668
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:sync_mm_rss
```
```
In mm/madvise.c (ffffffff8127cf76)
Location: include/linux/mm.h:1668
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/huge_memory.c (ffffffff812acda4)
Location: include/linux/mm.h:1668
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812b65c6)
Location: include/linux/mm.h:1668
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/exec.c (ffffffff812ddaa6)
Location: include/linux/mm.h:1668
Inline: True
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
In mm/memory.c (ffffffff8124c835)
Location: include/linux/mm.h:1668
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:sync_mm_rss
```
```
In mm/madvise.c (ffffffff8126eca0)
Location: include/linux/mm.h:1668
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/huge_memory.c (ffffffff8129de6d)
Location: include/linux/mm.h:1668
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812a779c)
Location: include/linux/mm.h:1668
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/exec.c (ffffffff812ce726)
Location: include/linux/mm.h:1668
Inline: True
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
In mm/memory.c (ffffffff812581b0)
Location: include/linux/mm.h:1668
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:sync_mm_rss
```
```
In mm/madvise.c (ffffffff8127ad16)
Location: include/linux/mm.h:1668
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/huge_memory.c (ffffffff812aabb4)
Location: include/linux/mm.h:1668
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812b43d6)
Location: include/linux/mm.h:1668
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/exec.c (ffffffff812db8b6)
Location: include/linux/mm.h:1668
Inline: True
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
In mm/memory.c (ffffffff81267b9a)
Location: include/linux/mm.h:1668
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:sync_mm_rss
```
```
In mm/madvise.c (ffffffff8128a8f5)
Location: include/linux/mm.h:1668
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/huge_memory.c (ffffffff812baf04)
Location: include/linux/mm.h:1668
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812c48a2)
Location: include/linux/mm.h:1668
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/exec.c (ffffffff812ec869)
Location: include/linux/mm.h:1668
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
