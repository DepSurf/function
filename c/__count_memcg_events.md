# Function: <code>__count_memcg_events</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811efc31)
Location: include/linux/memcontrol.h:679
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/swap.c (ffffffff81200e17)
Location: include/linux/memcontrol.h:679
Inline: True
```
```
In mm/vmscan.c (ffffffff8120a786)
Location: include/linux/memcontrol.h:679
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff81211283)
Location: include/linux/memcontrol.h:679
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/memory.c (ffffffff812302cf)
Location: include/linux/memcontrol.h:679
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In mm/memcontrol.c (ffffffff81283639)
Location: include/linux/memcontrol.h:679
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_charge_statistics
  - mm/memcontrol.c:mem_cgroup_charge_statistics
```
```
In fs/dax.c (ffffffff812f9ae8)
Location: include/linux/memcontrol.h:679
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
In mm/filemap.c (ffffffff81201e8c)
Location: include/linux/memcontrol.h:719
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/swap.c (ffffffff8121378c)
Location: include/linux/memcontrol.h:719
Inline: True
```
```
In mm/vmscan.c (ffffffff8121d476)
Location: include/linux/memcontrol.h:719
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff812231cc)
Location: include/linux/memcontrol.h:719
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/memory.c (ffffffff81242c7f)
Location: include/linux/memcontrol.h:719
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In mm/memcontrol.c (ffffffff812971a9)
Location: include/linux/memcontrol.h:719
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_charge_statistics
  - mm/memcontrol.c:mem_cgroup_charge_statistics
  - mm/memcontrol.c:mem_cgroup_charge_statistics
  - mm/memcontrol.c:mem_cgroup_charge_statistics
```
```
In fs/dax.c (ffffffff8130da9d)
Location: include/linux/memcontrol.h:719
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __count_memcg_events(struct mem_cgroup *memcg, enum vm_event_item idx, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b2880)
Location: mm/memcontrol.c:795
Inline: False
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_charge_statistics
  - mm/memcontrol.c:mem_cgroup_charge_statistics
```
**Symbols:**

```
ffffffff812b2880-ffffffff812b2904: __count_memcg_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __count_memcg_events(struct mem_cgroup *memcg, enum vm_event_item idx, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c42c0)
Location: mm/memcontrol.c:806
Inline: False
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_charge_statistics
  - mm/memcontrol.c:mem_cgroup_charge_statistics
```
**Symbols:**

```
ffffffff812c42c0-ffffffff812c4344: __count_memcg_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __count_memcg_events(struct mem_cgroup *memcg, enum vm_event_item idx, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff812f983f)
Location: mm/memcontrol.c:796
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_batch
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/swap.c:lru_deactivate_file_fn
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/memcontrol.c:uncharge_batch
  - fs/dax.c:dax_iomap_pte_fault
```
**Symbols:**

```
ffffffff812f5c80-ffffffff812f5d01: __count_memcg_events.part.0 (STB_LOCAL)
ffffffff812fa6d0-ffffffff812fa6e6: __count_memcg_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __count_memcg_events(struct mem_cgroup *memcg, enum vm_event_item idx, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff813055cf)
Location: mm/memcontrol.c:899
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_batch
Direct callers:
  - mm/swap.c:lru_deactivate_file_fn
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/memcontrol.c:uncharge_batch
```
**Symbols:**

```
ffffffff813011c0-ffffffff81301245: __count_memcg_events.part.0 (STB_LOCAL)
ffffffff81306670-ffffffff81306686: __count_memcg_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __count_memcg_events(struct mem_cgroup *memcg, enum vm_event_item idx, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813095f5)
Location: mm/memcontrol.c:791
Inline: True
Direct callers:
  - mm/swap.c:lru_deactivate_file_fn
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/memcontrol.c:uncharge_batch
```
**Symbols:**

```
ffffffff8130cb60-ffffffff8130cb92: __count_memcg_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __count_memcg_events(struct mem_cgroup *memcg, enum vm_event_item idx, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81357490)
Location: mm/memcontrol.c:831
Inline: True
Direct callers:
  - mm/swap.c:lru_deactivate_file_fn
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/memcontrol.c:uncharge_batch
```
**Symbols:**

```
ffffffff81357490-ffffffff81357518: __count_memcg_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __count_memcg_events(struct mem_cgroup *memcg, enum vm_event_item idx, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813d05a5)
Location: mm/memcontrol.c:809
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_charge_statistics
  - mm/memcontrol.c:mem_cgroup_charge_statistics
Direct callers:
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:__folio_activate
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:count_memcg_events
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_charge_statistics
```
**Symbols:**

```
ffffffff813d04f0-ffffffff813d0590: __count_memcg_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __count_memcg_events(struct mem_cgroup *memcg, enum vm_event_item idx, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81455890)
Location: mm/memcontrol.c:879
Inline: False
Direct callers:
  - mm/swap.c:lru_deactivate_file_fn
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:scan_folios
  - mm/vmscan.c:scan_folios
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:count_memcg_events
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:charge_memcg
  - mm/memcontrol.c:charge_memcg
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
```
**Symbols:**

```
ffffffff81455890-ffffffff81455976: __count_memcg_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __count_memcg_events(struct mem_cgroup *memcg, enum vm_event_item idx, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8148b6b0)
Location: mm/memcontrol.c:904
Inline: False
Direct callers:
  - mm/swap.c:lru_deactivate_file_fn
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:scan_folios
  - mm/vmscan.c:scan_folios
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:count_memcg_events
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:charge_memcg
  - mm/memcontrol.c:charge_memcg
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
```
**Symbols:**

```
ffffffff8148b6b0-ffffffff8148b79a: __count_memcg_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __count_memcg_events(struct mem_cgroup *memcg, enum vm_event_item idx, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814baf10)
Location: mm/memcontrol.c:951
Inline: False
Direct callers:
  - mm/swap.c:lru_deactivate_file_fn
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:scan_folios
  - mm/vmscan.c:scan_folios
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:count_memcg_events
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_replace_folio
  - mm/memcontrol.c:mem_cgroup_replace_folio
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
**Symbols:**

```
ffffffff814baf10-ffffffff814bb022: __count_memcg_events (STB_GLOBAL)
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
void __count_memcg_events(struct mem_cgroup *memcg, enum vm_event_item idx, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff800010366e38)
Location: mm/memcontrol.c:806
Inline: False
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_charge_statistics
  - mm/memcontrol.c:mem_cgroup_charge_statistics
```
**Symbols:**

```
ffff800010366e38-ffff800010366f08: __count_memcg_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __count_memcg_events(struct mem_cgroup *memcg, enum vm_event_item idx, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c0558600)
Location: mm/memcontrol.c:806
Inline: False
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_charge_statistics
  - mm/memcontrol.c:mem_cgroup_charge_statistics
```
**Symbols:**

```
c0558600-c05586d8: __count_memcg_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __count_memcg_events(struct mem_cgroup *memcg, enum vm_event_item idx, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c000000000454220)
Location: mm/memcontrol.c:806
Inline: False
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_charge_statistics
  - mm/memcontrol.c:mem_cgroup_charge_statistics
```
**Symbols:**

```
c000000000454220-c0000000004542d4: __count_memcg_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __count_memcg_events(struct mem_cgroup *memcg, enum vm_event_item idx, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe00024510c)
Location: mm/memcontrol.c:806
Inline: False
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_charge_statistics
  - mm/memcontrol.c:mem_cgroup_charge_statistics
```
**Symbols:**

```
ffffffe00024510c-ffffffe0002451cc: __count_memcg_events (STB_GLOBAL)
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
void __count_memcg_events(struct mem_cgroup *memcg, enum vm_event_item idx, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bc8a0)
Location: mm/memcontrol.c:806
Inline: False
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_charge_statistics
  - mm/memcontrol.c:mem_cgroup_charge_statistics
```
**Symbols:**

```
ffffffff812bc8a0-ffffffff812bc924: __count_memcg_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __count_memcg_events(struct mem_cgroup *memcg, enum vm_event_item idx, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812ada00)
Location: mm/memcontrol.c:806
Inline: False
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_charge_statistics
  - mm/memcontrol.c:mem_cgroup_charge_statistics
```
**Symbols:**

```
ffffffff812ada00-ffffffff812ada84: __count_memcg_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __count_memcg_events(struct mem_cgroup *memcg, enum vm_event_item idx, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812ba6b0)
Location: mm/memcontrol.c:806
Inline: False
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_charge_statistics
  - mm/memcontrol.c:mem_cgroup_charge_statistics
```
**Symbols:**

```
ffffffff812ba6b0-ffffffff812ba734: __count_memcg_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __count_memcg_events(struct mem_cgroup *memcg, enum vm_event_item idx, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812cadf0)
Location: mm/memcontrol.c:806
Inline: False
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_charge_statistics
  - mm/memcontrol.c:mem_cgroup_charge_statistics
```
**Symbols:**

```
ffffffff812cadf0-ffffffff812cae74: __count_memcg_events (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
