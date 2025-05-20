# Function: <code>psi_memstall_leave</code>

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
void psi_memstall_leave(long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810ef810)
Location: kernel/sched/psi.c:602
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
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
ffffffff810ef810-ffffffff810ef87c: psi_memstall_leave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void psi_memstall_leave(long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810f6cb0)
Location: kernel/sched/psi.c:842
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
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
ffffffff810f6cb0-ffffffff810f6d20: psi_memstall_leave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void psi_memstall_leave(long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff81102a40)
Location: kernel/sched/psi.c:843
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
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
ffffffff81102a40-ffffffff81102ab0: psi_memstall_leave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void psi_memstall_leave(long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff8110da60)
Location: kernel/sched/psi.c:890
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
ffffffff8110da60-ffffffff8110dad2: psi_memstall_leave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void psi_memstall_leave(long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff8110ad80)
Location: kernel/sched/psi.c:906
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
ffffffff8110ad80-ffffffff8110ae27: psi_memstall_leave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void psi_memstall_leave(long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff8110c9b0)
Location: kernel/sched/psi.c:918
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
ffffffff8110c9b0-ffffffff8110ca57: psi_memstall_leave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void psi_memstall_leave(long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/psi.c (0)
Location: kernel/sched/psi.c:933
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
ffffffff81ca956b-ffffffff81ca957f: psi_memstall_leave.cold (STB_LOCAL)
ffffffff8112b9f0-ffffffff8112baa5: psi_memstall_leave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void psi_memstall_leave(long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/psi.c:931
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_folio
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
ffffffff81e59576-ffffffff81e5958b: psi_memstall_leave.cold (STB_LOCAL)
ffffffff8114c170-ffffffff8114c240: psi_memstall_leave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void psi_memstall_leave(long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8117a9eb)
Location: kernel/sched/psi.c:1052
Inline: True
Direct callers:
  - mm/filemap.c:filemap_read_folio
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:folio_wait_bit_common
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
ffffffff820581f1-ffffffff82058206: psi_memstall_leave.cold (STB_LOCAL)
ffffffff8117a9c0-ffffffff8117aa96: psi_memstall_leave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void psi_memstall_leave(long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8118b54b)
Location: kernel/sched/psi.c:1075
Inline: True
Direct callers:
  - mm/filemap.c:filemap_read_folio
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:folio_wait_bit_common
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
ffffffff820d6ae9-ffffffff820d6afe: psi_memstall_leave.cold (STB_LOCAL)
ffffffff8118b520-ffffffff8118b5f8: psi_memstall_leave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void psi_memstall_leave(long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81199e7b)
Location: kernel/sched/psi.c:1067
Inline: True
Direct callers:
  - mm/filemap.c:filemap_read_folio
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:folio_wait_bit_common
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
ffffffff821b1d7f-ffffffff821b1d94: psi_memstall_leave.cold (STB_LOCAL)
ffffffff81199e50-ffffffff81199f28: psi_memstall_leave (STB_GLOBAL)
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
void psi_memstall_leave(long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffff800010167820)
Location: kernel/sched/psi.c:843
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
ffff800010167820-ffff8000101678ec: psi_memstall_leave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void psi_memstall_leave(long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (c03b4644)
Location: kernel/sched/psi.c:843
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
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
c03b4644-c03b46ec: psi_memstall_leave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void psi_memstall_leave(long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (c0000000001bf5b0)
Location: kernel/sched/psi.c:843
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
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
c0000000001bf5b0-c0000000001bf6ac: psi_memstall_leave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void psi_memstall_leave(long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffe000109d80)
Location: kernel/sched/psi.c:843
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
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
ffffffe000109d80-ffffffe000109e48: psi_memstall_leave (STB_GLOBAL)
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
void psi_memstall_leave(long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810fbd50)
Location: kernel/sched/psi.c:843
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
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
ffffffff810fbd50-ffffffff810fbdc0: psi_memstall_leave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void psi_memstall_leave(long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810ebf60)
Location: kernel/sched/psi.c:843
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
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
ffffffff810ebf60-ffffffff810ebfc4: psi_memstall_leave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void psi_memstall_leave(long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810f8f10)
Location: kernel/sched/psi.c:843
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
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
ffffffff810f8f10-ffffffff810f8f80: psi_memstall_leave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void psi_memstall_leave(long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff81104050)
Location: kernel/sched/psi.c:843
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
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
ffffffff81104050-ffffffff811040b7: psi_memstall_leave (STB_GLOBAL)
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
