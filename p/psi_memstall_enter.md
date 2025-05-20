# Function: <code>psi_memstall_enter</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void psi_memstall_enter(long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810ef790)
Location: kernel/sched/psi.c:572
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/compaction.c:kcompactd
```
**Symbols:**

```
ffffffff810ef790-ffffffff810ef80e: psi_memstall_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void psi_memstall_enter(long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810f6c20)
Location: kernel/sched/psi.c:812
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/compaction.c:kcompactd
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffffffff810f6c20-ffffffff810f6ca4: psi_memstall_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void psi_memstall_enter(long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff811029b0)
Location: kernel/sched/psi.c:813
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/compaction.c:kcompactd
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - block/blk-core.c:submit_bio
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffffffff811029b0-ffffffff81102a34: psi_memstall_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void psi_memstall_enter(long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff8110d9d0)
Location: kernel/sched/psi.c:860
Inline: False
Direct callers:
  - mm/filemap.c:wait_on_page_bit_common
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/compaction.c:kcompactd
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_io.c:swap_readpage
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - block/blk-core.c:submit_bio
  - block/blk-cgroup.c:blkcg_maybe_throttle_blkg
```
**Symbols:**

```
ffffffff8110d9d0-ffffffff8110da58: psi_memstall_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void psi_memstall_enter(long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff8110acc0)
Location: kernel/sched/psi.c:876
Inline: False
Direct callers:
  - mm/filemap.c:wait_on_page_bit_common
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_io.c:swap_readpage
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - block/blk-core.c:submit_bio
  - block/blk-cgroup.c:blkcg_maybe_throttle_blkg
```
**Symbols:**

```
ffffffff8110acc0-ffffffff8110ad79: psi_memstall_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void psi_memstall_enter(long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff8110c8f0)
Location: kernel/sched/psi.c:888
Inline: False
Direct callers:
  - mm/filemap.c:wait_on_page_bit_common
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_io.c:swap_readpage
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - block/blk-core.c:submit_bio
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffffffff8110c8f0-ffffffff8110c9a9: psi_memstall_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void psi_memstall_enter(long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/psi.c (0)
Location: kernel/sched/psi.c:903
Inline: False
Direct callers:
  - mm/filemap.c:wait_on_page_bit_common
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_io.c:swap_readpage
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - block/blk-core.c:submit_bio
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffffffff81ca9557-ffffffff81ca956b: psi_memstall_enter.cold (STB_LOCAL)
ffffffff8112b920-ffffffff8112b9e7: psi_memstall_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void psi_memstall_enter(long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/psi.c:901
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:__folio_lock_or_retry
  - mm/filemap.c:__folio_lock_or_retry
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_io.c:swap_readpage
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffffffff81e59561-ffffffff81e59576: psi_memstall_enter.cold (STB_LOCAL)
ffffffff8114c080-ffffffff8114c162: psi_memstall_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void psi_memstall_enter(long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/psi.c:1021
Inline: False
Direct callers:
  - mm/filemap.c:filemap_read_folio
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:folio_wait_bit_common
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:read_pages
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_io.c:swap_readpage
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffffffff820581dc-ffffffff820581f1: psi_memstall_enter.cold (STB_LOCAL)
ffffffff8117a8c0-ffffffff8117a9aa: psi_memstall_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void psi_memstall_enter(long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/psi.c:1044
Inline: False
Direct callers:
  - mm/filemap.c:filemap_read_folio
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:folio_wait_bit_common
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:read_pages
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_io.c:swap_readpage
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffffffff820d6ad4-ffffffff820d6ae9: psi_memstall_enter.cold (STB_LOCAL)
ffffffff8118b420-ffffffff8118b50c: psi_memstall_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void psi_memstall_enter(long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/psi.c:1036
Inline: False
Direct callers:
  - mm/filemap.c:filemap_read_folio
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:folio_wait_bit_common
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:read_pages
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_io.c:swap_read_folio
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:reclaim_high
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffffffff821b1d6a-ffffffff821b1d7f: psi_memstall_enter.cold (STB_LOCAL)
ffffffff81199d50-ffffffff81199e3d: psi_memstall_enter (STB_GLOBAL)
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
void psi_memstall_enter(long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffff800010167748)
Location: kernel/sched/psi.c:813
Inline: False
Direct callers:
  - mm/filemap.c:wait_on_page_bit_common
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/compaction.c:kcompactd
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - block/blk-core.c:submit_bio
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffff800010167748-ffff800010167820: psi_memstall_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void psi_memstall_enter(long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (c03b4584)
Location: kernel/sched/psi.c:813
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/compaction.c:kcompactd
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - block/blk-core.c:submit_bio
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
c03b4584-c03b4644: psi_memstall_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void psi_memstall_enter(long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (c0000000001bf490)
Location: kernel/sched/psi.c:813
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/compaction.c:kcompactd
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - block/blk-core.c:submit_bio
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
c0000000001bf490-c0000000001bf5ac: psi_memstall_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void psi_memstall_enter(long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffe000109caa)
Location: kernel/sched/psi.c:813
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/compaction.c:kcompactd
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - block/blk-core.c:submit_bio
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffffffe000109caa-ffffffe000109d80: psi_memstall_enter (STB_GLOBAL)
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
void psi_memstall_enter(long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810fbcc0)
Location: kernel/sched/psi.c:813
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/compaction.c:kcompactd
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - block/blk-core.c:submit_bio
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffffffff810fbcc0-ffffffff810fbd44: psi_memstall_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void psi_memstall_enter(long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810ebee0)
Location: kernel/sched/psi.c:813
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/compaction.c:kcompactd
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - block/blk-core.c:submit_bio
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffffffff810ebee0-ffffffff810ebf58: psi_memstall_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void psi_memstall_enter(long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810f8e80)
Location: kernel/sched/psi.c:813
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/compaction.c:kcompactd
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - block/blk-core.c:submit_bio
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffffffff810f8e80-ffffffff810f8f04: psi_memstall_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void psi_memstall_enter(long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff81103fd0)
Location: kernel/sched/psi.c:813
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/compaction.c:kcompactd
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - block/blk-core.c:submit_bio
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffffffff81103fd0-ffffffff8110404b: psi_memstall_enter (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
