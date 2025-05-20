# Function: <code>lru_add_drain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void lru_add_drain();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8119e129)
Location: mm/swap.c:857
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_per_cpu
  - mm/swap.c:__pagevec_release
Direct callers:
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_active_list
  - mm/shmem.c:shmem_add_seals
  - mm/gup.c:follow_page_pte
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/mmap.c:unmap_region
  - mm/mmap.c:exit_mmap
  - mm/madvise.c:force_swapin_readahead
  - mm/madvise.c:SyS_madvise
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:swapin_readahead
  - mm/migrate.c:migrate_prep_local
  - mm/huge_memory.c:follow_trans_huge_pmd
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff8119e200-ffffffff8119e217: lru_add_drain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void lru_add_drain();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811b3a0d)
Location: mm/swap.c:658
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_release
  - mm/swap.c:lru_add_drain_per_cpu
Direct callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/shmem.c:shmem_add_seals
  - mm/gup.c:follow_page_pte
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
  - mm/madvise.c:SyS_madvise
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:force_swapin_readahead
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/migrate.c:migrate_prep_local
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:follow_trans_huge_pmd
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff811b3bb0-ffffffff811b3bc7: lru_add_drain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void lru_add_drain();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811c409d)
Location: mm/swap.c:659
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_release
  - mm/swap.c:lru_add_drain_per_cpu
Direct callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/shmem.c:shmem_add_seals
  - mm/gup.c:follow_page_pte
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
  - mm/fadvise.c:SyS_fadvise64
  - mm/madvise.c:SyS_madvise
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:force_swapin_readahead
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/migrate.c:migrate_prep_local
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:follow_trans_huge_pmd
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff811c4240-ffffffff811c4257: lru_add_drain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void lru_add_drain();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811cc48d)
Location: mm/swap.c:678
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_release
  - mm/swap.c:lru_add_drain_per_cpu
Direct callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/shmem.c:shmem_add_seals
  - mm/gup.c:follow_page_pte
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
  - mm/fadvise.c:SyS_fadvise64
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_willneed
  - mm/madvise.c:madvise_willneed
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/migrate.c:migrate_prep_local
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:follow_trans_huge_pmd
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff811cc630-ffffffff811cc647: lru_add_drain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void lru_add_drain();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811e1483)
Location: mm/swap.c:678
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_release
  - mm/swap.c:lru_add_drain_per_cpu
Direct callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/shmem.c:shmem_add_seals
  - mm/gup.c:follow_page_pte
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
  - mm/fadvise.c:SyS_fadvise64
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_willneed
  - mm/madvise.c:madvise_willneed
  - mm/swap_state.c:do_swap_page_readahead
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_prep_local
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:follow_trans_huge_pmd
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff811e1660-ffffffff811e1677: lru_add_drain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void lru_add_drain();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81202bf5)
Location: mm/swap.c:651
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_release
  - mm/swap.c:lru_add_drain_per_cpu
Direct callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/gup.c:follow_page_pte
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
  - mm/fadvise.c:ksys_fadvise64_64
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_willneed
  - mm/madvise.c:madvise_willneed
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_prep_local
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/memfd.c:memfd_fcntl
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff81202d90-ffffffff81202da7: lru_add_drain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void lru_add_drain();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81215575)
Location: mm/swap.c:645
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_release
  - mm/swap.c:lru_add_drain_per_cpu
Direct callers:
  - mm/fadvise.c:vfs_fadvise
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/gup.c:follow_page_pte
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_willneed
  - mm/madvise.c:madvise_willneed
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_prep_local
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/memfd.c:memfd_fcntl
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff81215730-ffffffff81215747: lru_add_drain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void lru_add_drain();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81224f95)
Location: mm/swap.c:646
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_release
  - mm/swap.c:lru_add_drain_per_cpu
Direct callers:
  - mm/fadvise.c:vfs_fadvise
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/gup.c:follow_page_pte
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_willneed
  - mm/madvise.c:madvise_willneed
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/migrate.c:migrate_prep_local
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/memfd.c:memfd_wait_for_pins
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff81225130-ffffffff81225147: lru_add_drain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void lru_add_drain();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81232d65)
Location: mm/swap.c:687
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_release
  - mm/swap.c:lru_add_drain_per_cpu
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/gup.c:follow_page_pte
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_prep_local
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/khugepaged.c:collapse_file
  - mm/memfd.c:memfd_wait_for_pins
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff81232fb0-ffffffff81232fc7: lru_add_drain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void lru_add_drain();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81260299)
Location: mm/swap.c:731
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_release
  - mm/swap.c:lru_add_drain_per_cpu
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/gup.c:follow_page_pte
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/madvise.c:madvise_willneed
  - mm/madvise.c:madvise_willneed
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_prep_local
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff81260560-ffffffff81260596: lru_add_drain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void lru_add_drain();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8126acd9)
Location: mm/swap.c:717
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_release
  - mm/swap.c:lru_add_drain_per_cpu
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/gup.c:follow_page_pte
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/madvise.c:force_shm_swapin_readahead
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_prep_local
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff8126abe0-ffffffff8126ac16: lru_add_drain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void lru_add_drain();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8126feb9)
Location: mm/swap.c:721
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_release
  - mm/swap.c:lru_add_drain_per_cpu
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/compaction.c:compact_zone
  - mm/gup.c:follow_page_pte
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/madvise.c:force_shm_swapin_readahead
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/migrate.c:migrate_vma_prepare
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff8126fdc0-ffffffff8126fdf6: lru_add_drain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void lru_add_drain();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff812ad2a8)
Location: mm/swap.c:698
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_release
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/compaction.c:compact_zone
  - mm/gup.c:follow_page_pte
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/madvise.c:force_shm_swapin_readahead
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/migrate.c:migrate_vma_prepare
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff812ad1a0-ffffffff812ad1d6: lru_add_drain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void lru_add_drain();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81307340)
Location: mm/swap.c:703
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_release
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/compaction.c:compact_zone
  - mm/gup.c:faultin_vma_page_range
  - mm/gup.c:populate_vma_page_range
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/mlock.c:mlock_fixup
  - mm/mlock.c:mlock_fixup
  - mm/mlock.c:mlock_fixup
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/madvise.c:force_shm_swapin_readahead
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/migrate_device.c:migrate_vma_unmap
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff81307200-ffffffff81307244: lru_add_drain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void lru_add_drain();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81370d60)
Location: mm/swap.c:783
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_release
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - mm/vmscan.c:lru_gen_shrink_lruvec
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/compaction.c:compact_zone
  - mm/gup.c:faultin_vma_page_range
  - mm/gup.c:populate_vma_page_range
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/mlock.c:mlock_fixup
  - mm/mlock.c:mlock_fixup
  - mm/mlock.c:mlock_fixup
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/madvise.c:force_shm_swapin_readahead
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/migrate_device.c:migrate_device_unmap
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff813710b0-ffffffff813710f4: lru_add_drain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void lru_add_drain();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff813a2f40)
Location: mm/swap.c:749
Inline: True
Inline callers:
  - mm/swap.c:__folio_batch_release
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_lruvec
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/compaction.c:compact_zone
  - mm/gup.c:faultin_vma_page_range
  - mm/gup.c:populate_vma_page_range
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:zap_page_range_single
  - mm/mlock.c:mlock_fixup
  - mm/mlock.c:mlock_fixup
  - mm/mlock.c:mlock_fixup
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate_device.c:migrate_device_unmap
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff813a3240-ffffffff813a3284: lru_add_drain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void lru_add_drain();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff813ccbc0)
Location: mm/swap.c:749
Inline: True
Inline callers:
  - mm/swap.c:__folio_batch_release
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - mm/vmscan.c:shrink_lruvec
  - mm/vmscan.c:lru_gen_shrink_node
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/compaction.c:compact_zone
  - mm/gup.c:faultin_vma_page_range
  - mm/gup.c:populate_vma_page_range
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:zap_page_range_single
  - mm/mlock.c:mlock_fixup
  - mm/mlock.c:mlock_fixup
  - mm/mlock.c:mlock_fixup
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate_device.c:migrate_device_unmap
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff813cceb0-ffffffff813ccef4: lru_add_drain (STB_GLOBAL)
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
void lru_add_drain();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffff8000102c3068)
Location: mm/swap.c:687
Inline: False
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - mm/swap.c:__pagevec_release
  - mm/swap.c:lru_add_drain_per_cpu
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/gup.c:follow_page_pte
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
  - mm/madvise.c:__arm64_sys_madvise
  - mm/madvise.c:__arm64_sys_madvise
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/migrate.c:migrate_prep_local
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/khugepaged.c:collapse_file
  - mm/memfd.c:memfd_wait_for_pins
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffff8000102c3068-ffff8000102c3094: lru_add_drain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void lru_add_drain();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (c04ede80)
Location: mm/swap.c:687
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_release
  - mm/swap.c:lru_add_drain_per_cpu
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:madvise_free_single_vma
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/migrate.c:migrate_prep_local
  - mm/memfd.c:memfd_wait_for_pins
  - fs/exec.c:setup_arg_pages
```
**Symbols:**

```
c04ee1a4-c04ee1d0: lru_add_drain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void lru_add_drain();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (c00000000037cfa0)
Location: mm/swap.c:687
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_release
  - mm/swap.c:lru_add_drain_per_cpu
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/gup.c:follow_page_pte
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_prep_local
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/khugepaged.c:collapse_file
  - mm/memfd.c:memfd_wait_for_pins
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
c00000000037d3c0-c00000000037d3f4: lru_add_drain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void lru_add_drain();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffe0001e406e)
Location: mm/swap.c:687
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_release
  - mm/swap.c:lru_add_drain_per_cpu
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/migrate.c:migrate_prep_local
  - mm/memfd.c:memfd_wait_for_pins
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffe0001e4338-ffffffe0001e435e: lru_add_drain (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void lru_add_drain();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8122b3b5)
Location: mm/swap.c:687
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_release
  - mm/swap.c:lru_add_drain_per_cpu
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/gup.c:follow_page_pte
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_prep_local
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/khugepaged.c:collapse_file
  - mm/memfd.c:memfd_wait_for_pins
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff8122b600-ffffffff8122b617: lru_add_drain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void lru_add_drain();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8121e4a5)
Location: mm/swap.c:687
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_release
  - mm/swap.c:lru_add_drain_per_cpu
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/gup.c:follow_page_pte
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_prep_local
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/khugepaged.c:collapse_file
  - mm/memfd.c:memfd_wait_for_pins
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff8121e6f0-ffffffff8121e707: lru_add_drain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void lru_add_drain();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81229155)
Location: mm/swap.c:687
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_release
  - mm/swap.c:lru_add_drain_per_cpu
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/gup.c:follow_page_pte
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_prep_local
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/khugepaged.c:collapse_file
  - mm/memfd.c:memfd_wait_for_pins
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff812293a0-ffffffff812293b7: lru_add_drain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void lru_add_drain();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81238760)
Location: mm/swap.c:687
Inline: False
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - mm/swap.c:__pagevec_release
  - mm/swap.c:lru_add_drain_per_cpu
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/gup.c:follow_page_pte
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:unmap_region
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_prep_local
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/khugepaged.c:collapse_file
  - mm/memfd.c:memfd_wait_for_pins
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff81238760-ffffffff8123878e: lru_add_drain (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
