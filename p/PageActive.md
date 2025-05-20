# Function: <code>PageActive</code>

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
In mm/swap.c (ffffffff8119c9a6)
Location: include/linux/page-flags.h:215
Inline: True
Inline callers:
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_file
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:lru_add_page_tail
```
```
In mm/vmscan.c (ffffffff811a292a)
Location: include/linux/page-flags.h:215
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:putback_inactive_pages
```
```
In mm/compaction.c (ffffffff811b61c4)
Location: include/linux/page-flags.h:215
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff811c2cfe)
Location: include/linux/page-flags.h:215
Inline: True
```
```
In mm/slub.c (ffffffff811ea6d1)
Location: include/linux/page-flags.h:215
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
```
In mm/memcontrol.c (ffffffff811fed02)
Location: include/linux/page-flags.h:215
Inline: True
Inline callers:
  - mm/memcontrol.c:lock_page_lru
  - mm/memcontrol.c:unlock_page_lru
```
```
In fs/proc/task_mmu.c (ffffffff81276a2a)
Location: include/linux/page-flags.h:215
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
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
In mm/swap.c (ffffffff811b1f3e)
Location: include/linux/page-flags.h:263
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:deactivate_page
  - mm/swap.c:lru_cache_add_file
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff811ba38b)
Location: include/linux/page-flags.h:263
Inline: True
Inline callers:
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffffffff811d0274)
Location: include/linux/page-flags.h:263
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff811de9a5)
Location: include/linux/page-flags.h:263
Inline: True
```
```
In mm/madvise.c (ffffffff811eee5c)
Location: include/linux/page-flags.h:263
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/slub.c (ffffffff81209e74)
Location: include/linux/page-flags.h:263
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
```
In mm/huge_memory.c (ffffffff81218398)
Location: include/linux/page-flags.h:263
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memcontrol.c (ffffffff81224b3a)
Location: include/linux/page-flags.h:263
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In fs/proc/task_mmu.c (ffffffff812a471f)
Location: include/linux/page-flags.h:263
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
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
In mm/swap.c (ffffffff811c259e)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:deactivate_page
  - mm/swap.c:lru_cache_add_file
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff811caa3b)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffffffff811e02ea)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff811ee7c7)
Location: include/linux/page-flags.h:273
Inline: True
```
```
In mm/madvise.c (ffffffff811ff806)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/slub.c (ffffffff8121bee4)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
```
In mm/huge_memory.c (ffffffff8122a93c)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memcontrol.c (ffffffff81237128)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In fs/proc/task_mmu.c (ffffffff812ba098)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
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
In mm/swap.c (ffffffff811caa1e)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_anon
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff811d3551)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffffffff811e9f71)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff811f974d)
Location: include/linux/page-flags.h:273
Inline: True
```
```
In mm/slub.c (ffffffff812278fc)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
```
In mm/memcontrol.c (ffffffff81242be9)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In fs/proc/task_mmu.c (ffffffff812c77e7)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
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
In mm/swap.c (ffffffff811df78e)
Location: include/linux/page-flags.h:274
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_anon
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff811e8aa7)
Location: include/linux/page-flags.h:274
Inline: True
Inline callers:
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffffffff812002cc)
Location: include/linux/page-flags.h:274
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff81211b7d)
Location: include/linux/page-flags.h:274
Inline: True
```
```
In mm/slub.c (ffffffff81243a49)
Location: include/linux/page-flags.h:274
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
```
In mm/memcontrol.c (ffffffff81262a29)
Location: include/linux/page-flags.h:274
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In fs/proc/task_mmu.c (ffffffff812eb3e7)
Location: include/linux/page-flags.h:274
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
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
In mm/swap.c (ffffffff81201fb7)
Location: include/linux/page-flags.h:281
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_anon
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff81209d0b)
Location: include/linux/page-flags.h:281
Inline: True
Inline callers:
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffffffff81221721)
Location: include/linux/page-flags.h:281
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff812328ef)
Location: include/linux/page-flags.h:281
Inline: True
```
```
In mm/slub.c (ffffffff8126610e)
Location: include/linux/page-flags.h:281
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
```
In mm/memcontrol.c (ffffffff81286924)
Location: include/linux/page-flags.h:281
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In fs/proc/task_mmu.c (ffffffff81318717)
Location: include/linux/page-flags.h:281
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
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
In mm/filemap.c (ffffffff811febde)
Location: include/linux/page-flags.h:290
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap.c (ffffffff81214937)
Location: include/linux/page-flags.h:290
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_anon
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8121c9eb)
Location: include/linux/page-flags.h:290
Inline: True
Inline callers:
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffffffff8123477e)
Location: include/linux/page-flags.h:290
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff81246132)
Location: include/linux/page-flags.h:290
Inline: True
```
```
In mm/slub.c (ffffffff8127ae4e)
Location: include/linux/page-flags.h:290
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
```
In mm/memcontrol.c (ffffffff8129b8b0)
Location: include/linux/page-flags.h:290
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In fs/proc/task_mmu.c (ffffffff8132f629)
Location: include/linux/page-flags.h:290
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
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
In mm/filemap.c (ffffffff81215ed4)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap.c (ffffffff812245fa)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_file
  - mm/swap.c:lru_cache_add_anon
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8122c5ea)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffffffff81244598)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff81258349)
Location: include/linux/page-flags.h:321
Inline: True
```
```
In mm/slub.c (ffffffff8129678a)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
```
In mm/memcontrol.c (ffffffff812b6cc0)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In fs/proc/task_mmu.c (ffffffff8135706c)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
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
In mm/filemap.c (ffffffff812237d4)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap.c (ffffffff8123238a)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:deactivate_page
  - mm/swap.c:lru_cache_add_file
  - mm/swap.c:lru_cache_add_anon
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8123a80a)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffffffff81252a58)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff81266819)
Location: include/linux/page-flags.h:321
Inline: True
```
```
In mm/slub.c (ffffffff812a655b)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
```
In mm/memcontrol.c (ffffffff812c8b90)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In fs/proc/task_mmu.c (ffffffff8136f63c)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
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
In mm/filemap.c (ffffffff81250ea4)
Location: include/linux/page-flags.h:329
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap.c (ffffffff8125f680)
Location: include/linux/page-flags.h:329
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:deactivate_page
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff81269f50)
Location: include/linux/page-flags.h:329
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffffffff81282b45)
Location: include/linux/page-flags.h:329
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff812968e4)
Location: include/linux/page-flags.h:329
Inline: True
```
```
In mm/slub.c (ffffffff812db4f8)
Location: include/linux/page-flags.h:329
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
```
In fs/proc/task_mmu.c (ffffffff813b6e8d)
Location: include/linux/page-flags.h:329
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
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
In mm/filemap.c (ffffffff8125b1e4)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap.c (ffffffff81269bff)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:release_pages
  - mm/swap.c:deactivate_page
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8126fefb)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffffffff8128d107)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff812a1c9f)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/slub.c (ffffffff812e7a3a)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
```
In fs/proc/task_mmu.c (ffffffff813c852d)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
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
In mm/filemap.c (ffffffff8125ee74)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap.c (ffffffff8126d916)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:deactivate_page
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff81276162)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffffffff81291bca)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff812a756f)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/slub.c (ffffffff812ef1be)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
```
In fs/proc/task_mmu.c (ffffffff813cf56c)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
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
In mm/filemap.c (ffffffff8129c284)
Location: include/linux/page-flags.h:352
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap.c (ffffffff812a9f83)
Location: include/linux/page-flags.h:352
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:deactivate_page
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff812b27bb)
Location: include/linux/page-flags.h:352
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffffffff812d1924)
Location: include/linux/page-flags.h:352
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff812e8851)
Location: include/linux/page-flags.h:352
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/slub.c (ffffffff813374dd)
Location: include/linux/page-flags.h:352
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
```
In fs/proc/task_mmu.c (ffffffff8142094c)
Location: include/linux/page-flags.h:352
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
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
In mm/swap.c (ffffffff81306958)
Location: include/linux/page-flags.h:502
Inline: True
Inline callers:
  - mm/swap.c:deactivate_page
  - mm/swap.c:lru_deactivate_file_fn
```
```
In mm/vmscan.c (ffffffff8130d15c)
Location: include/linux/page-flags.h:502
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
```
```
In fs/proc/task_mmu.c (ffffffff8149969b)
Location: include/linux/page-flags.h:502
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
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
In fs/proc/task_mmu.c (ffffffff8152d855)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
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
In fs/proc/task_mmu.c (ffffffff81565c85)
Location: include/linux/page-flags.h:475
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
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
In fs/proc/task_mmu.c (ffffffff8159dc62)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
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
In mm/filemap.c (ffff8000102b11bc)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap.c (ffff8000102c1214)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:deactivate_page
  - mm/swap.c:lru_cache_add_anon
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffff8000102cb790)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffff8000102eb2e4)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffff8000102fd7dc)
Location: include/linux/page-flags.h:321
Inline: True
```
```
In mm/slub.c (ffff8000103477e0)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
```
In mm/memcontrol.c (ffff80001036b81c)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In fs/proc/task_mmu.c (ffff800010438d28)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
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
In mm/filemap.c (c04ddaa4)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap.c (c04ed4a8)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:release_pages
  - mm/swap.c:deactivate_page
  - mm/swap.c:lru_cache_add_anon
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (c04f5628)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (c050eba8)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (c051cbd8)
Location: include/linux/page-flags.h:321
Inline: True
```
```
In mm/slub.c (c054bfa8)
Location: include/linux/page-flags.h:321
Inline: True
```
```
In mm/memcontrol.c (c055d110)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
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
In mm/filemap.c (c0000000003667a8)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap.c (c00000000037c288)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:deactivate_page
  - mm/swap.c:lru_cache_add_file
  - mm/swap.c:lru_cache_add_anon
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (c0000000003888ec)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (c0000000003acb14)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (c0000000003c8b74)
Location: include/linux/page-flags.h:321
Inline: True
```
```
In mm/slub.c (c000000000425a40)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
```
In mm/memcontrol.c (c00000000045b654)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In fs/proc/task_mmu.c (c00000000054c618)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
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
In mm/filemap.c (ffffffe0001d69e8)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap.c (ffffffe0001e358c)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:release_pages
  - mm/swap.c:deactivate_page
  - mm/swap.c:lru_cache_add_anon
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffe0001ea420)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffffffe0001ff92e)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffe00020c072)
Location: include/linux/page-flags.h:321
Inline: True
```
```
In mm/slub.c (ffffffe000239fec)
Location: include/linux/page-flags.h:321
Inline: True
```
```
In mm/memcontrol.c (ffffffe000249040)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
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
In mm/filemap.c (ffffffff8121be24)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap.c (ffffffff8122a9da)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:deactivate_page
  - mm/swap.c:lru_cache_add_file
  - mm/swap.c:lru_cache_add_anon
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff81232e5a)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffffffff8124b0a8)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff8125ee69)
Location: include/linux/page-flags.h:321
Inline: True
```
```
In mm/slub.c (ffffffff8129eb3b)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
```
In mm/memcontrol.c (ffffffff812c1170)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In fs/proc/task_mmu.c (ffffffff81367c1c)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
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
In mm/filemap.c (ffffffff8120f014)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap.c (ffffffff8121dafa)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:deactivate_page
  - mm/swap.c:lru_cache_add_file
  - mm/swap.c:lru_cache_add_anon
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff81225efa)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffffffff8123e048)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff81251299)
Location: include/linux/page-flags.h:321
Inline: True
```
```
In mm/slub.c (ffffffff8129067b)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
```
In mm/memcontrol.c (ffffffff812b21be)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In fs/proc/task_mmu.c (ffffffff813588bc)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
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
In mm/filemap.c (ffffffff81219bc4)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap.c (ffffffff8122877a)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:deactivate_page
  - mm/swap.c:lru_cache_add_file
  - mm/swap.c:lru_cache_add_anon
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff81230bfa)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffffffff81248e48)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff8125cc09)
Location: include/linux/page-flags.h:321
Inline: True
```
```
In mm/slub.c (ffffffff8129c94b)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
```
In mm/memcontrol.c (ffffffff812bef80)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In fs/proc/task_mmu.c (ffffffff813656ec)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
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
In mm/filemap.c (ffffffff81228cc4)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap.c (ffffffff81237aea)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:deactivate_page
  - mm/swap.c:lru_cache_add_file
  - mm/swap.c:lru_cache_add_anon
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8124004a)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/compaction.c (ffffffff81258691)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff8126c5e9)
Location: include/linux/page-flags.h:321
Inline: True
```
```
In mm/slub.c (ffffffff812ac97b)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
```
In mm/memcontrol.c (ffffffff812cf9f7)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In fs/proc/task_mmu.c (ffffffff81378dcc)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
```
</details>
</li>
</ul>

## Differences
