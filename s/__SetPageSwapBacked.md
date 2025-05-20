# Function: <code>__SetPageSwapBacked</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811a9302)
Location: include/linux/page-flags.h:224
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
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
In mm/shmem.c (ffffffff811bf3df)
Location: include/linux/page-flags.h:279
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/rmap.c (ffffffff811e7da3)
Location: include/linux/page-flags.h:279
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/swap_state.c (ffffffff811f08e7)
Location: include/linux/page-flags.h:279
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/migrate.c (ffffffff81213094)
Location: include/linux/page-flags.h:279
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffffffff8121abe7)
Location: include/linux/page-flags.h:279
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
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
In mm/shmem.c (ffffffff811d0951)
Location: include/linux/page-flags.h:289
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/rmap.c (ffffffff811f9123)
Location: include/linux/page-flags.h:289
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/swap_state.c (ffffffff812012e9)
Location: include/linux/page-flags.h:289
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/migrate.c (ffffffff81225404)
Location: include/linux/page-flags.h:289
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffffffff8122c3dd)
Location: include/linux/page-flags.h:289
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
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
In mm/shmem.c (ffffffff811dcc1e)
Location: include/linux/page-flags.h:289
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mcopy_atomic_pte
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/rmap.c (ffffffff81203cd3)
Location: include/linux/page-flags.h:289
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/swap_state.c (ffffffff8120c194)
Location: include/linux/page-flags.h:289
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/migrate.c (ffffffff81230f51)
Location: include/linux/page-flags.h:289
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffffffff81238c75)
Location: include/linux/page-flags.h:289
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
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
In mm/shmem.c (ffffffff811eeb10)
Location: include/linux/page-flags.h:290
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/memory.c (ffffffff8120ca5e)
Location: include/linux/page-flags.h:290
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffff8121ca43)
Location: include/linux/page-flags.h:290
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/swap_state.c (ffffffff81225858)
Location: include/linux/page-flags.h:290
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/migrate.c (ffffffff8124ecf2)
Location: include/linux/page-flags.h:290
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffffffff81257375)
Location: include/linux/page-flags.h:290
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
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
In mm/shmem.c (ffffffff8120f639)
Location: include/linux/page-flags.h:297
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/memory.c (ffffffff8122d9b6)
Location: include/linux/page-flags.h:297
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffff8123e7d2)
Location: include/linux/page-flags.h:297
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/swap_state.c (ffffffff81247df9)
Location: include/linux/page-flags.h:297
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/migrate.c (ffffffff81272b5a)
Location: include/linux/page-flags.h:297
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffffffff8127b2bc)
Location: include/linux/page-flags.h:297
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
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
In mm/shmem.c (ffffffff81222564)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/memory.c (ffffffff81240fa2)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffff81252d62)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/swap_state.c (ffffffff8125c3ba)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/migrate.c (ffffffff81286c61)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffffffff8128f93b)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
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
In mm/shmem.c (ffffffff81231b66)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/memory.c (ffffffff81253327)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffff812650e4)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/swap_state.c (ffffffff812775a2)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/migrate.c (ffffffff812a143f)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffffffff812aa9e2)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
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
In mm/shmem.c (ffffffff8123fc26)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/memory.c (ffffffff8126188a)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffff81273974)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/swap_state.c (ffffffff81287082)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/migrate.c (ffffffff812b2611)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffffffff812bc182)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
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
In mm/shmem.c (ffffffff8126e492)
Location: include/linux/page-flags.h:350
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/memory.c (ffffffff81291ac9)
Location: include/linux/page-flags.h:350
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffff812a4c48)
Location: include/linux/page-flags.h:350
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/swap_state.c (ffffffff812b9691)
Location: include/linux/page-flags.h:350
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/migrate.c (ffffffff812e7bb1)
Location: include/linux/page-flags.h:350
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffffffff812f16ab)
Location: include/linux/page-flags.h:350
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
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
In mm/shmem.c (ffffffff81278e94)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/memory.c (ffffffff8129c3ca)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffff812b02f4)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/swap_state.c (ffffffff812c5125)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/migrate.c (ffffffff812f3345)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffffffff812fdc03)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
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
In mm/shmem.c (ffffffff8127de44)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/memory.c (ffffffff812a169b)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffff812b58f4)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/swap_state.c (ffffffff812cbdda)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/migrate.c (ffffffff812f9321)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffffffff81304ac3)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
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
In mm/shmem.c (ffffffff812bfebe)
Location: include/linux/page-flags.h:373
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/memory.c (ffffffff812e25bd)
Location: include/linux/page-flags.h:373
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffff812f7584)
Location: include/linux/page-flags.h:373
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/swap_state.c (ffffffff81310f90)
Location: include/linux/page-flags.h:373
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/migrate.c (ffffffff813404d3)
Location: include/linux/page-flags.h:373
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffffffff8134e836)
Location: include/linux/page-flags.h:373
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
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
In mm/shmem.c (ffffffff8131c79c)
Location: include/linux/page-flags.h:523
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_replace_page
```
```
In mm/memory.c (ffffffff8134428e)
Location: include/linux/page-flags.h:523
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffff8135d00c)
Location: include/linux/page-flags.h:523
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/swap_state.c (ffffffff8137bdf7)
Location: include/linux/page-flags.h:523
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/khugepaged.c (ffffffff813c4ff5)
Location: include/linux/page-flags.h:523
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff813d7b65)
Location: include/linux/page-flags.h:502
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/khugepaged.c (ffffffff81449d73)
Location: include/linux/page-flags.h:502
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
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
In mm/khugepaged.c (ffffffff8147ffc0)
Location: include/linux/page-flags.h:495
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
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
In mm/khugepaged.c (ffffffff814adf4e)
Location: include/linux/page-flags.h:497
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
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
In mm/shmem.c (ffff8000102d2f70)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/memory.c (ffff8000102f8b00)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffff800010309530)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/swap_state.c (ffff800010321b7c)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/migrate.c (ffff800010352e68)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffff80001035d2a4)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
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
In mm/shmem.c (c04faeac)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/memory.c (c051af30)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (c0526144)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/swap_state.c (c053a2ac)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/migrate.c (c0550f80)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
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
In mm/shmem.c (c000000000391938)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/memory.c (c0000000003c215c)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (c0000000003d8aec)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/swap_state.c (c0000000003f7350)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/migrate.c (c0000000004399f4)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (c000000000448940)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
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
In mm/shmem.c (ffffffe0001ee1d2)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/memory.c (ffffffe000208bba)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffe00021392c)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/swap_state.c (ffffffe000222cb8)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/migrate.c (ffffffe00023ea70)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
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
In mm/shmem.c (ffffffff81238276)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/memory.c (ffffffff81259eda)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffff8126bfc4)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/swap_state.c (ffffffff8127f6d2)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/migrate.c (ffffffff812aabf1)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffffffff812b4762)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
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
In mm/shmem.c (ffffffff8122b2b2)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/memory.c (ffffffff8124c2d6)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffff8125e034)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/swap_state.c (ffffffff812714f2)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/migrate.c (ffffffff8129c54d)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffffffff812a57d2)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
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
In mm/shmem.c (ffffffff81236016)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/memory.c (ffffffff81257c7a)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffff81269d64)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/swap_state.c (ffffffff8127d472)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/migrate.c (ffffffff812a8a01)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffffffff812b2572)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
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
In mm/shmem.c (ffffffff812462f6)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/memory.c (ffffffff81267663)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffff812796d4)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/swap_state.c (ffffffff8128d048)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/migrate.c (ffffffff812b8d21)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffffffff812c296a)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
</details>
</li>
</ul>

## Differences
