# Function: <code>__SetPageLocked</code>

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
In mm/filemap.c (ffffffff811a0fdf)
Location: include/linux/page-flags.h:255
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/shmem.c (ffffffff811bf3cc)
Location: include/linux/page-flags.h:255
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/swap_state.c (ffffffff811f08d4)
Location: include/linux/page-flags.h:255
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff811fb3c6)
Location: include/linux/page-flags.h:255
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
```
```
In mm/ksm.c (ffffffff81205e44)
Location: include/linux/page-flags.h:255
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff81213080)
Location: include/linux/page-flags.h:255
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/khugepaged.c (ffffffff8121ac02)
Location: include/linux/page-flags.h:255
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/pipe.c (ffffffff8123ba11)
Location: include/linux/page-flags.h:255
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
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
In mm/filemap.c (ffffffff811b0bdf)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/shmem.c (ffffffff811d093e)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/swap_state.c (ffffffff812012d6)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff8120bec6)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
```
```
In mm/ksm.c (ffffffff81217e56)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff812253f0)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/khugepaged.c (ffffffff8122c3f8)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/pipe.c (ffffffff8124e7b1)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
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
In mm/filemap.c (ffffffff811b810f)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/shmem.c (ffffffff811dcc0b)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mcopy_atomic_pte
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/swap_state.c (ffffffff8120c181)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff81217576)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
```
```
In mm/ksm.c (ffffffff81223a35)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff81230ab5)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/khugepaged.c (ffffffff81238c97)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/pipe.c (ffffffff8125a711)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
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
In mm/filemap.c (ffffffff811cc7ff)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/shmem.c (ffffffff811eeafd)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/memory.c (ffffffff8120ca4b)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/swap_state.c (ffffffff81225845)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff81232226)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
```
```
In mm/ksm.c (ffffffff8123f075)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff8124e831)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/khugepaged.c (ffffffff81257397)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/pipe.c (ffffffff8127ca71)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
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
In mm/filemap.c (ffffffff811ed5df)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/shmem.c (ffffffff8120f625)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/memory.c (ffffffff8122d9a2)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/swap_state.c (ffffffff81247de5)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff8125528a)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
```
```
In mm/ksm.c (ffffffff81262822)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff8127263a)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/khugepaged.c (ffffffff8127b2cc)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/pipe.c (ffffffff812a39c1)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
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
In mm/filemap.c (ffffffff811febaf)
Location: include/linux/page-flags.h:281
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/shmem.c (ffffffff81222550)
Location: include/linux/page-flags.h:281
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/memory.c (ffffffff81240f8e)
Location: include/linux/page-flags.h:281
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/swap_state.c (ffffffff8125c3a6)
Location: include/linux/page-flags.h:281
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff8126966a)
Location: include/linux/page-flags.h:281
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
```
```
In mm/ksm.c (ffffffff812770a2)
Location: include/linux/page-flags.h:281
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff81286c33)
Location: include/linux/page-flags.h:281
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/khugepaged.c (ffffffff8128f926)
Location: include/linux/page-flags.h:281
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/pipe.c (ffffffff812b8a31)
Location: include/linux/page-flags.h:281
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
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
In mm/filemap.c (ffffffff81215eae)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/shmem.c (ffffffff81231b51)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/memory.c (ffffffff81253313)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/swap_state.c (ffffffff8127758e)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff812847e9)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
```
```
In mm/ksm.c (ffffffff81292900)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff812a11d3)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/khugepaged.c (ffffffff812aa9cd)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/pipe.c (ffffffff812d5771)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
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
In mm/filemap.c (ffffffff812237ae)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/shmem.c (ffffffff8123fc11)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/memory.c (ffffffff81261876)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/swap_state.c (ffffffff8128706e)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff81294389)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
```
```
In mm/ksm.c (ffffffff812a2683)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff812b25e3)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/khugepaged.c (ffffffff812bbf6e)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/pipe.c (ffffffff812e72e1)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
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
In mm/filemap.c (ffffffff81250e7e)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/shmem.c (ffffffff8126e47d)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/memory.c (ffffffff81291ab5)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/swap_state.c (ffffffff812b9681)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff812c7779)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
```
```
In mm/ksm.c (ffffffff812d6da0)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff812e7b83)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/khugepaged.c (ffffffff812f1494)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/pipe.c (ffffffff8131ec51)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_try_steal
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
In mm/filemap.c (ffffffff8125b1be)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/shmem.c (ffffffff81278e7f)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/memory.c (ffffffff8129c3b6)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/swap_state.c (ffffffff812c5115)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff812d32e9)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
```
```
In mm/ksm.c (ffffffff812e2930)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff812f2f73)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/khugepaged.c (ffffffff812fd9e9)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/pipe.c (ffffffff8132a17b)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_try_steal
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
In mm/filemap.c (ffffffff8125ee4e)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/shmem.c (ffffffff8127de2f)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/memory.c (ffffffff812a1687)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/swap_state.c (ffffffff812cbdca)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff812da029)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
```
```
In mm/ksm.c (ffffffff812ea0c0)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff812f92f3)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/khugepaged.c (ffffffff8130476b)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/pipe.c (ffffffff8133012b)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_try_steal
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
In mm/filemap.c (ffffffff8129c25e)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/shmem.c (ffffffff812bfea9)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/memory.c (ffffffff812e25a9)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/swap_state.c (ffffffff81310f80)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff81320ddd)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
```
```
In mm/ksm.c (ffffffff81331fe2)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/khugepaged.c (ffffffff8134e4a0)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/pipe.c (ffffffff8137d8e8)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_try_steal
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
In mm/shmem.c (ffffffff8131c783)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_replace_page
```
```
In mm/memory.c (ffffffff81344281)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/swap_state.c (ffffffff8137bde2)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff8138daf9)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
```
```
In mm/ksm.c (ffffffff813a3344)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/khugepaged.c (ffffffff813c4bb0)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/pipe.c (ffffffff813fe60b)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_try_steal
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
In mm/ksm.c (ffffffff81422fe1)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/khugepaged.c (ffffffff8144940a)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/pipe.c (ffffffff814882ab)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_try_steal
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81458037)
Location: include/linux/page-flags.h:465
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/khugepaged.c (ffffffff8147f5ed)
Location: include/linux/page-flags.h:465
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/pipe.c (ffffffff814bd1b3)
Location: include/linux/page-flags.h:465
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_try_steal
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff814ad619)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/pipe.c (ffffffff814ef650)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_try_steal
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
In mm/filemap.c (ffff8000102b1180)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/shmem.c (ffff8000102d2f54)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/memory.c (ffff8000102f8ad8)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/swap_state.c (ffff800010321b50)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffff800010332bf8)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
```
```
In mm/ksm.c (ffff800010342088)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffff800010352e30)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/khugepaged.c (ffff80001035d278)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/pipe.c (ffff80001038fb94)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
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
In mm/filemap.c (c04dda70)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/shmem.c (c04fae90)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/memory.c (c051af08)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/swap_state.c (c053a288)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/ksm.c (c0547df0)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In fs/pipe.c (c05767fc)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
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
In mm/filemap.c (c000000000366770)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/shmem.c (c000000000391918)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/memory.c (c0000000003c2138)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/swap_state.c (c0000000003f7330)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (c00000000040d72c)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
```
```
In mm/ksm.c (c00000000041f8ec)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (c0000000004399b8)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/khugepaged.c (c0000000004485f0)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/pipe.c (c000000000487874)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
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
In mm/filemap.c (ffffffe0001d69ba)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/shmem.c (ffffffe0001ee1c4)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/memory.c (ffffffe000208bac)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/swap_state.c (ffffffe000222cac)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffe00022f2c8)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
```
```
In mm/ksm.c (ffffffe000236330)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In fs/pipe.c (ffffffe00025f7be)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
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
In mm/filemap.c (ffffffff8121bdfe)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/shmem.c (ffffffff81238261)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/memory.c (ffffffff81259ec6)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/swap_state.c (ffffffff8127f6be)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff8128c969)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
```
```
In mm/ksm.c (ffffffff8129ac63)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff812aabc3)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/khugepaged.c (ffffffff812b454e)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/pipe.c (ffffffff812df8c1)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
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
In mm/filemap.c (ffffffff8120efee)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/shmem.c (ffffffff8122b29e)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/memory.c (ffffffff8124c2c2)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/swap_state.c (ffffffff812714de)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff8127e789)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
```
```
In mm/ksm.c (ffffffff8128c823)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff8129c520)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/khugepaged.c (ffffffff812a55ce)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/pipe.c (ffffffff812d0501)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
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
In mm/filemap.c (ffffffff81219b9e)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/shmem.c (ffffffff81236001)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/memory.c (ffffffff81257c66)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/swap_state.c (ffffffff8127d45e)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff8128a779)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
```
```
In mm/ksm.c (ffffffff81298a73)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff812a89d3)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/khugepaged.c (ffffffff812b235e)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/pipe.c (ffffffff812dd6d1)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
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
In mm/filemap.c (ffffffff81228c9e)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/shmem.c (ffffffff812462e1)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/memory.c (ffffffff8126764f)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/swap_state.c (ffffffff8128d033)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff8129a569)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
```
```
In mm/ksm.c (ffffffff812a8852)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff812b8cf3)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/khugepaged.c (ffffffff812c2765)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/pipe.c (ffffffff812ee651)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
```
</details>
</li>
</ul>

## Differences
