# Function: <code>trace_print_flags_seq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
const char *trace_print_flags_seq(struct trace_seq *p, const char *delim, long unsigned int flags, const struct trace_print_flags *flag_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff81153890)
Location: kernel/trace/trace_output.c:63
Inline: False
Direct callers:
  - kernel/sched/core.c:trace_raw_output_sched_switch
  - kernel/module.c:trace_raw_output_module_load
  - mm/vmscan.c:trace_raw_output_mm_vmscan_direct_reclaim_begin_template
  - mm/vmscan.c:trace_raw_output_mm_shrink_slab_start
  - mm/vmscan.c:trace_raw_output_mm_vmscan_writepage
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_inactive
  - mm/slab_common.c:trace_raw_output_kmem_alloc
  - mm/slab_common.c:trace_raw_output_kmem_alloc_node
  - mm/slab_common.c:trace_raw_output_mm_page_alloc
  - fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_raw_output_writeback_single_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_lazytime_template
  - fs/locks.c:trace_raw_output_filelock_lease
  - fs/locks.c:trace_raw_output_generic_add_lease
  - fs/ext4/super.c:trace_raw_output_ext4_da_write_pages_extent
  - fs/ext4/super.c:trace_raw_output_ext4_request_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_allocate_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_free_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_mballoc_alloc
  - fs/ext4/super.c:trace_raw_output_ext4__fallocate_mode
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_enter
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit
  - fs/ext4/super.c:trace_raw_output_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:trace_raw_output_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:trace_raw_output_ext4__es_extent
  - fs/ext4/super.c:trace_raw_output_ext4_es_find_delayed_extent_range_exit
  - fs/ext4/super.c:trace_raw_output_ext4_es_lookup_extent_exit
  - drivers/ras/ras.c:trace_raw_output_aer_event
  - drivers/ras/ras.c:trace_raw_output_aer_event
```
**Symbols:**

```
ffffffff81153890-ffffffff811539c6: trace_print_flags_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
const char *trace_print_flags_seq(struct trace_seq *p, const char *delim, long unsigned int flags, const struct trace_print_flags *flag_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff8115c9f0)
Location: kernel/trace/trace_output.c:63
Inline: False
Direct callers:
  - kernel/sched/core.c:trace_raw_output_sched_switch
  - kernel/module.c:trace_raw_output_module_load
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:trace_raw_output_mm_vmscan_writepage
  - mm/vmscan.c:trace_raw_output_mm_shrink_slab_start
  - mm/vmscan.c:trace_raw_output_mm_vmscan_direct_reclaim_begin_template
  - mm/slab_common.c:trace_raw_output_mm_page_alloc
  - mm/slab_common.c:trace_raw_output_kmem_alloc_node
  - mm/slab_common.c:trace_raw_output_kmem_alloc
  - fs/fs-writeback.c:trace_raw_output_writeback_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_single_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template
  - fs/locks.c:trace_raw_output_generic_add_lease
  - fs/locks.c:trace_raw_output_filelock_lease
  - fs/locks.c:trace_raw_output_filelock_lock
  - fs/ext4/super.c:trace_raw_output_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_raw_output_ext4_es_find_delayed_extent_range_exit
  - fs/ext4/super.c:trace_raw_output_ext4__es_extent
  - fs/ext4/super.c:trace_raw_output_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:trace_raw_output_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_enter
  - fs/ext4/super.c:trace_raw_output_ext4__fallocate_mode
  - fs/ext4/super.c:trace_raw_output_ext4_mballoc_alloc
  - fs/ext4/super.c:trace_raw_output_ext4_free_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_allocate_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_request_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_da_write_pages_extent
  - drivers/ras/ras.c:trace_raw_output_aer_event
  - drivers/ras/ras.c:trace_raw_output_aer_event
```
**Symbols:**

```
ffffffff8115c9f0-ffffffff8115cb28: trace_print_flags_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
const char *trace_print_flags_seq(struct trace_seq *p, const char *delim, long unsigned int flags, const struct trace_print_flags *flag_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff811672c0)
Location: kernel/trace/trace_output.c:63
Inline: False
Direct callers:
  - kernel/sched/core.c:trace_raw_output_sched_switch
  - kernel/time/alarmtimer.c:trace_raw_output_alarm_class
  - kernel/time/alarmtimer.c:trace_raw_output_alarmtimer_suspend
  - kernel/module.c:trace_raw_output_module_load
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:trace_raw_output_mm_vmscan_writepage
  - mm/vmscan.c:trace_raw_output_mm_shrink_slab_start
  - mm/vmscan.c:trace_raw_output_mm_vmscan_direct_reclaim_begin_template
  - mm/slab_common.c:trace_raw_output_mm_page_alloc
  - mm/slab_common.c:trace_raw_output_kmem_alloc_node
  - mm/slab_common.c:trace_raw_output_kmem_alloc
  - fs/fs-writeback.c:trace_raw_output_writeback_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_single_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template
  - fs/locks.c:trace_raw_output_generic_add_lease
  - fs/locks.c:trace_raw_output_filelock_lease
  - fs/locks.c:trace_raw_output_filelock_lock
  - fs/ext4/super.c:trace_raw_output_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_raw_output_ext4_es_find_delayed_extent_range_exit
  - fs/ext4/super.c:trace_raw_output_ext4__es_extent
  - fs/ext4/super.c:trace_raw_output_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:trace_raw_output_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_enter
  - fs/ext4/super.c:trace_raw_output_ext4__fallocate_mode
  - fs/ext4/super.c:trace_raw_output_ext4_mballoc_alloc
  - fs/ext4/super.c:trace_raw_output_ext4_free_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_allocate_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_request_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_da_write_pages_extent
  - drivers/ras/ras.c:trace_raw_output_aer_event
  - drivers/ras/ras.c:trace_raw_output_aer_event
```
**Symbols:**

```
ffffffff811672c0-ffffffff811673f8: trace_print_flags_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
const char *trace_print_flags_seq(struct trace_seq *p, const char *delim, long unsigned int flags, const struct trace_print_flags *flag_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff8116a610)
Location: kernel/trace/trace_output.c:64
Inline: False
Direct callers:
  - kernel/sched/core.c:trace_raw_output_sched_switch
  - kernel/time/timer.c:trace_raw_output_timer_start
  - kernel/time/alarmtimer.c:trace_raw_output_alarm_class
  - kernel/time/alarmtimer.c:trace_raw_output_alarmtimer_suspend
  - kernel/module.c:trace_raw_output_module_load
  - mm/vmscan.c:trace_raw_output_mm_vmscan_inactive_list_is_low
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:trace_raw_output_mm_vmscan_writepage
  - mm/vmscan.c:trace_raw_output_mm_shrink_slab_start
  - mm/vmscan.c:trace_raw_output_mm_vmscan_direct_reclaim_begin_template
  - mm/slab_common.c:trace_raw_output_mm_page_alloc
  - mm/slab_common.c:trace_raw_output_kmem_alloc_node
  - mm/slab_common.c:trace_raw_output_kmem_alloc
  - fs/fs-writeback.c:trace_raw_output_writeback_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_single_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template
  - fs/dax.c:trace_raw_output_dax_pte_fault_class
  - fs/dax.c:trace_raw_output_dax_pte_fault_class
  - fs/dax.c:trace_raw_output_dax_pmd_insert_mapping_class
  - fs/dax.c:trace_raw_output_dax_pmd_fault_class
  - fs/dax.c:trace_raw_output_dax_pmd_fault_class
  - fs/locks.c:trace_raw_output_generic_add_lease
  - fs/locks.c:trace_raw_output_filelock_lease
  - fs/locks.c:trace_raw_output_filelock_lock
  - fs/ext4/super.c:trace_raw_output_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_raw_output_ext4_es_find_delayed_extent_range_exit
  - fs/ext4/super.c:trace_raw_output_ext4__es_extent
  - fs/ext4/super.c:trace_raw_output_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:trace_raw_output_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_enter
  - fs/ext4/super.c:trace_raw_output_ext4__fallocate_mode
  - fs/ext4/super.c:trace_raw_output_ext4_mballoc_alloc
  - fs/ext4/super.c:trace_raw_output_ext4_free_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_allocate_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_request_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_da_write_pages_extent
  - drivers/ras/ras.c:trace_raw_output_aer_event
  - drivers/ras/ras.c:trace_raw_output_aer_event
```
**Symbols:**

```
ffffffff8116a610-ffffffff8116a73c: trace_print_flags_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
const char *trace_print_flags_seq(struct trace_seq *p, const char *delim, long unsigned int flags, const struct trace_print_flags *flag_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff81177740)
Location: kernel/trace/trace_output.c:64
Inline: False
Direct callers:
  - kernel/sched/core.c:trace_raw_output_sched_switch
  - kernel/time/timer.c:trace_raw_output_timer_start
  - kernel/time/alarmtimer.c:trace_raw_output_alarm_class
  - kernel/time/alarmtimer.c:trace_raw_output_alarmtimer_suspend
  - kernel/module.c:trace_raw_output_module_load
  - mm/vmscan.c:trace_raw_output_mm_vmscan_inactive_list_is_low
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:trace_raw_output_mm_vmscan_writepage
  - mm/vmscan.c:trace_raw_output_mm_shrink_slab_start
  - mm/vmscan.c:trace_raw_output_mm_vmscan_direct_reclaim_begin_template
  - mm/slab_common.c:trace_raw_output_mm_page_alloc
  - mm/slab_common.c:trace_raw_output_kmem_alloc_node
  - mm/slab_common.c:trace_raw_output_kmem_alloc
  - fs/fs-writeback.c:trace_raw_output_writeback_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_single_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template
  - fs/dax.c:trace_raw_output_dax_pte_fault_class
  - fs/dax.c:trace_raw_output_dax_pte_fault_class
  - fs/dax.c:trace_raw_output_dax_pmd_insert_mapping_class
  - fs/dax.c:trace_raw_output_dax_pmd_fault_class
  - fs/dax.c:trace_raw_output_dax_pmd_fault_class
  - fs/locks.c:trace_raw_output_generic_add_lease
  - fs/locks.c:trace_raw_output_filelock_lease
  - fs/locks.c:trace_raw_output_filelock_lock
  - fs/ext4/super.c:trace_raw_output_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_raw_output_ext4_es_find_delayed_extent_range_exit
  - fs/ext4/super.c:trace_raw_output_ext4__es_extent
  - fs/ext4/super.c:trace_raw_output_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:trace_raw_output_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_enter
  - fs/ext4/super.c:trace_raw_output_ext4__fallocate_mode
  - fs/ext4/super.c:trace_raw_output_ext4_mballoc_alloc
  - fs/ext4/super.c:trace_raw_output_ext4_free_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_allocate_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_request_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_da_write_pages_extent
  - drivers/ras/ras.c:trace_raw_output_aer_event
  - drivers/ras/ras.c:trace_raw_output_aer_event
```
**Symbols:**

```
ffffffff81177740-ffffffff8117786c: trace_print_flags_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
const char *trace_print_flags_seq(struct trace_seq *p, const char *delim, long unsigned int flags, const struct trace_print_flags *flag_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff81186960)
Location: kernel/trace/trace_output.c:64
Inline: False
Direct callers:
  - kernel/sched/core.c:trace_raw_output_sched_switch
  - kernel/time/timer.c:trace_raw_output_timer_start
  - kernel/time/alarmtimer.c:trace_raw_output_alarm_class
  - kernel/time/alarmtimer.c:trace_raw_output_alarmtimer_suspend
  - kernel/module.c:trace_raw_output_module_load
  - mm/vmscan.c:trace_raw_output_mm_vmscan_inactive_list_is_low
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:trace_raw_output_mm_vmscan_writepage
  - mm/vmscan.c:trace_raw_output_mm_shrink_slab_start
  - mm/vmscan.c:trace_raw_output_mm_vmscan_direct_reclaim_begin_template
  - mm/vmscan.c:trace_raw_output_mm_vmscan_wakeup_kswapd
  - mm/slab_common.c:trace_raw_output_mm_page_alloc
  - mm/slab_common.c:trace_raw_output_kmem_alloc_node
  - mm/slab_common.c:trace_raw_output_kmem_alloc
  - fs/fs-writeback.c:trace_raw_output_writeback_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_single_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template
  - fs/dax.c:trace_raw_output_dax_pte_fault_class
  - fs/dax.c:trace_raw_output_dax_pte_fault_class
  - fs/dax.c:trace_raw_output_dax_pmd_insert_mapping_class
  - fs/dax.c:trace_raw_output_dax_pmd_fault_class
  - fs/dax.c:trace_raw_output_dax_pmd_fault_class
  - fs/locks.c:trace_raw_output_generic_add_lease
  - fs/locks.c:trace_raw_output_filelock_lease
  - fs/locks.c:trace_raw_output_filelock_lock
  - fs/ext4/super.c:trace_raw_output_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_raw_output_ext4_es_find_delayed_extent_range_exit
  - fs/ext4/super.c:trace_raw_output_ext4__es_extent
  - fs/ext4/super.c:trace_raw_output_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:trace_raw_output_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_enter
  - fs/ext4/super.c:trace_raw_output_ext4__fallocate_mode
  - fs/ext4/super.c:trace_raw_output_ext4_mballoc_alloc
  - fs/ext4/super.c:trace_raw_output_ext4_free_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_allocate_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_request_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_da_write_pages_extent
  - drivers/ras/ras.c:trace_raw_output_aer_event
  - drivers/ras/ras.c:trace_raw_output_aer_event
```
**Symbols:**

```
ffffffff81186960-ffffffff81186a90: trace_print_flags_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
const char *trace_print_flags_seq(struct trace_seq *p, const char *delim, long unsigned int flags, const struct trace_print_flags *flag_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff811942d0)
Location: kernel/trace/trace_output.c:65
Inline: False
Direct callers:
  - kernel/sched/core.c:trace_raw_output_sched_switch
  - kernel/time/timer.c:trace_raw_output_timer_start
  - kernel/time/alarmtimer.c:trace_raw_output_alarm_class
  - kernel/time/alarmtimer.c:trace_raw_output_alarmtimer_suspend
  - kernel/module.c:trace_raw_output_module_load
  - mm/vmscan.c:trace_raw_output_mm_vmscan_inactive_list_is_low
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:trace_raw_output_mm_vmscan_writepage
  - mm/vmscan.c:trace_raw_output_mm_shrink_slab_start
  - mm/vmscan.c:trace_raw_output_mm_vmscan_direct_reclaim_begin_template
  - mm/vmscan.c:trace_raw_output_mm_vmscan_wakeup_kswapd
  - mm/slab_common.c:trace_raw_output_mm_page_alloc
  - mm/slab_common.c:trace_raw_output_kmem_alloc_node
  - mm/slab_common.c:trace_raw_output_kmem_alloc
  - fs/fs-writeback.c:trace_raw_output_writeback_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_single_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template
  - fs/dax.c:trace_raw_output_dax_pte_fault_class
  - fs/dax.c:trace_raw_output_dax_pte_fault_class
  - fs/dax.c:trace_raw_output_dax_pmd_insert_mapping_class
  - fs/dax.c:trace_raw_output_dax_pmd_fault_class
  - fs/dax.c:trace_raw_output_dax_pmd_fault_class
  - fs/locks.c:trace_raw_output_generic_add_lease
  - fs/locks.c:trace_raw_output_filelock_lease
  - fs/locks.c:trace_raw_output_filelock_lock
  - fs/ext4/super.c:trace_raw_output_ext4_es_insert_delayed_block
  - fs/ext4/super.c:trace_raw_output_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_raw_output_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:trace_raw_output_ext4__es_extent
  - fs/ext4/super.c:trace_raw_output_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:trace_raw_output_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_enter
  - fs/ext4/super.c:trace_raw_output_ext4__fallocate_mode
  - fs/ext4/super.c:trace_raw_output_ext4_mballoc_alloc
  - fs/ext4/super.c:trace_raw_output_ext4_free_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_allocate_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_request_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_da_write_pages_extent
  - drivers/ras/ras.c:trace_raw_output_aer_event
  - drivers/ras/ras.c:trace_raw_output_aer_event
```
**Symbols:**

```
ffffffff811942d0-ffffffff81194400: trace_print_flags_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
const char *trace_print_flags_seq(struct trace_seq *p, const char *delim, long unsigned int flags, const struct trace_print_flags *flag_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff811a1ff0)
Location: kernel/trace/trace_output.c:65
Inline: False
Direct callers:
  - kernel/sched/core.c:trace_raw_output_sched_switch
  - kernel/time/timer.c:trace_raw_output_timer_start
  - kernel/time/alarmtimer.c:trace_raw_output_alarm_class
  - kernel/time/alarmtimer.c:trace_raw_output_alarmtimer_suspend
  - kernel/module.c:trace_raw_output_module_load
  - mm/vmscan.c:trace_raw_output_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:trace_raw_output_mm_vmscan_inactive_list_is_low
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:trace_raw_output_mm_vmscan_writepage
  - mm/vmscan.c:trace_raw_output_mm_shrink_slab_start
  - mm/vmscan.c:trace_raw_output_mm_vmscan_direct_reclaim_begin_template
  - mm/vmscan.c:trace_raw_output_mm_vmscan_wakeup_kswapd
  - mm/slab_common.c:trace_raw_output_mm_page_alloc
  - mm/slab_common.c:trace_raw_output_kmem_alloc_node
  - mm/slab_common.c:trace_raw_output_kmem_alloc
  - mm/compaction.c:trace_raw_output_mm_compaction_try_to_compact_pages
  - fs/fs-writeback.c:trace_raw_output_writeback_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_single_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template
  - fs/dax.c:trace_raw_output_dax_pte_fault_class
  - fs/dax.c:trace_raw_output_dax_pte_fault_class
  - fs/dax.c:trace_raw_output_dax_pmd_insert_mapping_class
  - fs/dax.c:trace_raw_output_dax_pmd_fault_class
  - fs/dax.c:trace_raw_output_dax_pmd_fault_class
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_generic_add_lease
  - fs/locks.c:trace_raw_output_filelock_lease
  - fs/locks.c:trace_raw_output_filelock_lock
  - fs/ext4/super.c:trace_raw_output_ext4_es_insert_delayed_block
  - fs/ext4/super.c:trace_raw_output_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_raw_output_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:trace_raw_output_ext4__es_extent
  - fs/ext4/super.c:trace_raw_output_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:trace_raw_output_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_enter
  - fs/ext4/super.c:trace_raw_output_ext4__fallocate_mode
  - fs/ext4/super.c:trace_raw_output_ext4_mballoc_alloc
  - fs/ext4/super.c:trace_raw_output_ext4_free_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_allocate_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_request_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_da_write_pages_extent
  - drivers/ras/ras.c:trace_raw_output_aer_event
  - drivers/ras/ras.c:trace_raw_output_aer_event
```
**Symbols:**

```
ffffffff811a1ff0-ffffffff811a2120: trace_print_flags_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
const char *trace_print_flags_seq(struct trace_seq *p, const char *delim, long unsigned int flags, const struct trace_print_flags *flag_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff811ad9d0)
Location: kernel/trace/trace_output.c:65
Inline: False
Direct callers:
  - kernel/sched/core.c:trace_raw_output_sched_switch
  - kernel/time/timer.c:trace_raw_output_timer_start
  - kernel/time/alarmtimer.c:trace_raw_output_alarm_class
  - kernel/time/alarmtimer.c:trace_raw_output_alarmtimer_suspend
  - kernel/module.c:trace_raw_output_module_load
  - kernel/trace/trace_events_hist.c:print_synth_event
  - mm/vmscan.c:trace_raw_output_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:trace_raw_output_mm_vmscan_inactive_list_is_low
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:trace_raw_output_mm_vmscan_writepage
  - mm/vmscan.c:trace_raw_output_mm_shrink_slab_start
  - mm/vmscan.c:trace_raw_output_mm_vmscan_direct_reclaim_begin_template
  - mm/vmscan.c:trace_raw_output_mm_vmscan_wakeup_kswapd
  - mm/slab_common.c:trace_raw_output_mm_page_alloc
  - mm/slab_common.c:trace_raw_output_kmem_alloc_node
  - mm/slab_common.c:trace_raw_output_kmem_alloc
  - mm/compaction.c:trace_raw_output_mm_compaction_try_to_compact_pages
  - fs/fs-writeback.c:trace_raw_output_writeback_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_single_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template
  - fs/dax.c:trace_raw_output_dax_pte_fault_class
  - fs/dax.c:trace_raw_output_dax_pte_fault_class
  - fs/dax.c:trace_raw_output_dax_pmd_insert_mapping_class
  - fs/dax.c:trace_raw_output_dax_pmd_fault_class
  - fs/dax.c:trace_raw_output_dax_pmd_fault_class
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_generic_add_lease
  - fs/locks.c:trace_raw_output_filelock_lease
  - fs/locks.c:trace_raw_output_filelock_lock
  - fs/ext4/super.c:trace_raw_output_ext4_es_insert_delayed_block
  - fs/ext4/super.c:trace_raw_output_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_raw_output_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:trace_raw_output_ext4__es_extent
  - fs/ext4/super.c:trace_raw_output_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:trace_raw_output_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_enter
  - fs/ext4/super.c:trace_raw_output_ext4__fallocate_mode
  - fs/ext4/super.c:trace_raw_output_ext4_mballoc_alloc
  - fs/ext4/super.c:trace_raw_output_ext4_free_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_allocate_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_request_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_da_write_pages_extent
  - drivers/ras/ras.c:trace_raw_output_aer_event
  - drivers/ras/ras.c:trace_raw_output_aer_event
```
**Symbols:**

```
ffffffff811ad9d0-ffffffff811adb00: trace_print_flags_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const char *trace_print_flags_seq(struct trace_seq *p, const char *delim, long unsigned int flags, const struct trace_print_flags *flag_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff811c5a90)
Location: kernel/trace/trace_output.c:65
Inline: False
Direct callers:
  - kernel/sched/core.c:trace_raw_output_sched_switch
  - kernel/time/timer.c:trace_raw_output_timer_start
  - kernel/time/alarmtimer.c:trace_raw_output_alarm_class
  - kernel/time/alarmtimer.c:trace_raw_output_alarmtimer_suspend
  - kernel/module.c:trace_raw_output_module_load
  - kernel/trace/trace_events_synth.c:print_synth_event
  - mm/vmscan.c:trace_raw_output_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:trace_raw_output_mm_vmscan_inactive_list_is_low
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:trace_raw_output_mm_vmscan_writepage
  - mm/vmscan.c:trace_raw_output_mm_shrink_slab_start
  - mm/vmscan.c:trace_raw_output_mm_vmscan_direct_reclaim_begin_template
  - mm/vmscan.c:trace_raw_output_mm_vmscan_wakeup_kswapd
  - mm/slab_common.c:trace_raw_output_mm_page_alloc
  - mm/slab_common.c:trace_raw_output_kmem_alloc_node
  - mm/slab_common.c:trace_raw_output_kmem_alloc
  - mm/compaction.c:trace_raw_output_mm_compaction_try_to_compact_pages
  - fs/fs-writeback.c:trace_raw_output_writeback_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_single_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template
  - fs/dax.c:trace_raw_output_dax_pte_fault_class
  - fs/dax.c:trace_raw_output_dax_pte_fault_class
  - fs/dax.c:trace_raw_output_dax_pmd_insert_mapping_class
  - fs/dax.c:trace_raw_output_dax_pmd_fault_class
  - fs/dax.c:trace_raw_output_dax_pmd_fault_class
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_generic_add_lease
  - fs/locks.c:trace_raw_output_filelock_lease
  - fs/locks.c:trace_raw_output_filelock_lock
  - fs/iomap/trace.c:trace_raw_output_iomap_apply
  - fs/iomap/trace.c:trace_raw_output_iomap_class
  - fs/ext4/super.c:trace_raw_output_ext4_es_insert_delayed_block
  - fs/ext4/super.c:trace_raw_output_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_raw_output_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:trace_raw_output_ext4__es_extent
  - fs/ext4/super.c:trace_raw_output_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:trace_raw_output_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_enter
  - fs/ext4/super.c:trace_raw_output_ext4__fallocate_mode
  - fs/ext4/super.c:trace_raw_output_ext4_mballoc_alloc
  - fs/ext4/super.c:trace_raw_output_ext4_free_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_allocate_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_request_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_da_write_pages_extent
  - drivers/ras/ras.c:trace_raw_output_aer_event
  - drivers/ras/ras.c:trace_raw_output_aer_event
```
**Symbols:**

```
ffffffff811c5a90-ffffffff811c5bc0: trace_print_flags_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const char *trace_print_flags_seq(struct trace_seq *p, const char *delim, long unsigned int flags, const struct trace_print_flags *flag_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff811c30c0)
Location: kernel/trace/trace_output.c:65
Inline: False
Direct callers:
  - kernel/sched/core.c:trace_raw_output_sched_switch
  - kernel/time/timer.c:trace_raw_output_timer_start
  - kernel/time/alarmtimer.c:trace_raw_output_alarm_class
  - kernel/time/alarmtimer.c:trace_raw_output_alarmtimer_suspend
  - kernel/module.c:trace_raw_output_module_load
  - kernel/trace/trace_events_synth.c:print_synth_event
  - mm/vmscan.c:trace_raw_output_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:trace_raw_output_mm_vmscan_inactive_list_is_low
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:trace_raw_output_mm_vmscan_writepage
  - mm/vmscan.c:trace_raw_output_mm_shrink_slab_start
  - mm/vmscan.c:trace_raw_output_mm_vmscan_direct_reclaim_begin_template
  - mm/vmscan.c:trace_raw_output_mm_vmscan_wakeup_kswapd
  - mm/slab_common.c:trace_raw_output_mm_page_alloc
  - mm/slab_common.c:trace_raw_output_kmem_alloc_node
  - mm/slab_common.c:trace_raw_output_kmem_alloc
  - mm/compaction.c:trace_raw_output_mm_compaction_try_to_compact_pages
  - fs/fs-writeback.c:trace_raw_output_writeback_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_single_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template
  - fs/dax.c:trace_raw_output_dax_pte_fault_class
  - fs/dax.c:trace_raw_output_dax_pte_fault_class
  - fs/dax.c:trace_raw_output_dax_pmd_insert_mapping_class
  - fs/dax.c:trace_raw_output_dax_pmd_fault_class
  - fs/dax.c:trace_raw_output_dax_pmd_fault_class
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_generic_add_lease
  - fs/locks.c:trace_raw_output_filelock_lease
  - fs/locks.c:trace_raw_output_filelock_lock
  - fs/iomap/trace.c:trace_raw_output_iomap_apply
  - fs/iomap/trace.c:trace_raw_output_iomap_class
  - fs/ext4/super.c:trace_raw_output_ext4_es_insert_delayed_block
  - fs/ext4/super.c:trace_raw_output_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_raw_output_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:trace_raw_output_ext4__es_extent
  - fs/ext4/super.c:trace_raw_output_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:trace_raw_output_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_enter
  - fs/ext4/super.c:trace_raw_output_ext4__fallocate_mode
  - fs/ext4/super.c:trace_raw_output_ext4_mballoc_alloc
  - fs/ext4/super.c:trace_raw_output_ext4_free_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_allocate_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_request_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_da_write_pages_extent
  - drivers/ras/ras.c:trace_raw_output_aer_event
  - drivers/ras/ras.c:trace_raw_output_aer_event
```
**Symbols:**

```
ffffffff811c30c0-ffffffff811c31f0: trace_print_flags_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const char *trace_print_flags_seq(struct trace_seq *p, const char *delim, long unsigned int flags, const struct trace_print_flags *flag_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff811c4120)
Location: kernel/trace/trace_output.c:65
Inline: False
Direct callers:
  - kernel/sched/core.c:trace_raw_output_sched_switch
  - kernel/time/timer.c:trace_raw_output_timer_start
  - kernel/time/alarmtimer.c:trace_raw_output_alarm_class
  - kernel/time/alarmtimer.c:trace_raw_output_alarmtimer_suspend
  - kernel/module.c:trace_raw_output_module_load
  - kernel/trace/trace_events_synth.c:print_synth_event
  - mm/vmscan.c:trace_raw_output_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:trace_raw_output_mm_vmscan_inactive_list_is_low
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:trace_raw_output_mm_vmscan_writepage
  - mm/vmscan.c:trace_raw_output_mm_shrink_slab_start
  - mm/vmscan.c:trace_raw_output_mm_vmscan_direct_reclaim_begin_template
  - mm/vmscan.c:trace_raw_output_mm_vmscan_wakeup_kswapd
  - mm/slab_common.c:trace_raw_output_mm_page_alloc
  - mm/slab_common.c:trace_raw_output_kmem_alloc_node
  - mm/slab_common.c:trace_raw_output_kmem_alloc
  - mm/compaction.c:trace_raw_output_mm_compaction_try_to_compact_pages
  - fs/fs-writeback.c:trace_raw_output_writeback_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_single_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template
  - fs/dax.c:trace_raw_output_dax_pte_fault_class
  - fs/dax.c:trace_raw_output_dax_pte_fault_class
  - fs/dax.c:trace_raw_output_dax_pmd_insert_mapping_class
  - fs/dax.c:trace_raw_output_dax_pmd_fault_class
  - fs/dax.c:trace_raw_output_dax_pmd_fault_class
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_generic_add_lease
  - fs/locks.c:trace_raw_output_filelock_lease
  - fs/locks.c:trace_raw_output_filelock_lock
  - fs/iomap/trace.c:trace_raw_output_iomap_apply
  - fs/iomap/trace.c:trace_raw_output_iomap_class
  - fs/ext4/super.c:trace_raw_output_ext4_es_insert_delayed_block
  - fs/ext4/super.c:trace_raw_output_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_raw_output_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:trace_raw_output_ext4__es_extent
  - fs/ext4/super.c:trace_raw_output_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:trace_raw_output_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_enter
  - fs/ext4/super.c:trace_raw_output_ext4__fallocate_mode
  - fs/ext4/super.c:trace_raw_output_ext4_mballoc_alloc
  - fs/ext4/super.c:trace_raw_output_ext4_free_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_allocate_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_request_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_da_write_pages_extent
  - drivers/ras/ras.c:trace_raw_output_aer_event
  - drivers/ras/ras.c:trace_raw_output_aer_event
```
**Symbols:**

```
ffffffff811c4120-ffffffff811c424f: trace_print_flags_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const char *trace_print_flags_seq(struct trace_seq *p, const char *delim, long unsigned int flags, const struct trace_print_flags *flag_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff811ef4e0)
Location: kernel/trace/trace_output.c:65
Inline: False
Direct callers:
  - kernel/sched/core.c:trace_raw_output_sched_switch
  - kernel/time/timer.c:trace_raw_output_timer_start
  - kernel/time/alarmtimer.c:trace_raw_output_alarm_class
  - kernel/time/alarmtimer.c:trace_raw_output_alarmtimer_suspend
  - kernel/module.c:trace_raw_output_module_load
  - kernel/trace/trace_events_synth.c:print_synth_event
  - mm/vmscan.c:trace_raw_output_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:trace_raw_output_mm_vmscan_writepage
  - mm/vmscan.c:trace_raw_output_mm_shrink_slab_start
  - mm/vmscan.c:trace_raw_output_mm_vmscan_direct_reclaim_begin_template
  - mm/vmscan.c:trace_raw_output_mm_vmscan_wakeup_kswapd
  - mm/slab_common.c:trace_raw_output_mm_page_alloc
  - mm/slab_common.c:trace_raw_output_kmem_alloc_node
  - mm/slab_common.c:trace_raw_output_kmem_alloc
  - mm/compaction.c:trace_raw_output_mm_compaction_try_to_compact_pages
  - fs/fs-writeback.c:trace_raw_output_writeback_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_single_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template
  - fs/dax.c:trace_raw_output_dax_pte_fault_class
  - fs/dax.c:trace_raw_output_dax_pte_fault_class
  - fs/dax.c:trace_raw_output_dax_pmd_insert_mapping_class
  - fs/dax.c:trace_raw_output_dax_pmd_fault_class
  - fs/dax.c:trace_raw_output_dax_pmd_fault_class
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_generic_add_lease
  - fs/locks.c:trace_raw_output_filelock_lease
  - fs/locks.c:trace_raw_output_filelock_lock
  - fs/iomap/trace.c:trace_raw_output_iomap_iter
  - fs/iomap/trace.c:trace_raw_output_iomap_class
  - fs/ext4/super.c:trace_raw_output_ext4_es_insert_delayed_block
  - fs/ext4/super.c:trace_raw_output_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_raw_output_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:trace_raw_output_ext4__es_extent
  - fs/ext4/super.c:trace_raw_output_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:trace_raw_output_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_enter
  - fs/ext4/super.c:trace_raw_output_ext4__fallocate_mode
  - fs/ext4/super.c:trace_raw_output_ext4_mballoc_alloc
  - fs/ext4/super.c:trace_raw_output_ext4_free_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_allocate_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_request_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_da_write_pages_extent
  - drivers/ras/ras.c:trace_raw_output_aer_event
  - drivers/ras/ras.c:trace_raw_output_aer_event
```
**Symbols:**

```
ffffffff811ef4e0-ffffffff811ef60f: trace_print_flags_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const char *trace_print_flags_seq(struct trace_seq *p, const char *delim, long unsigned int flags, const struct trace_print_flags *flag_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff812279d0)
Location: kernel/trace/trace_output.c:66
Inline: False
Direct callers:
  - kernel/sched/core.c:trace_raw_output_sched_switch
  - kernel/locking/mutex.c:trace_raw_output_contention_begin
  - kernel/module/main.c:trace_raw_output_module_load
  - kernel/time/timer.c:trace_raw_output_timer_start
  - kernel/time/alarmtimer.c:trace_raw_output_alarm_class
  - kernel/time/alarmtimer.c:trace_raw_output_alarmtimer_suspend
  - kernel/trace/trace_events_synth.c:print_synth_event
  - mm/vmscan.c:trace_raw_output_mm_vmscan_throttled
  - mm/vmscan.c:trace_raw_output_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:trace_raw_output_mm_vmscan_write_folio
  - mm/vmscan.c:trace_raw_output_mm_shrink_slab_start
  - mm/vmscan.c:trace_raw_output_mm_vmscan_direct_reclaim_begin_template
  - mm/vmscan.c:trace_raw_output_mm_vmscan_wakeup_kswapd
  - mm/percpu.c:trace_raw_output_percpu_alloc_percpu
  - mm/slab_common.c:trace_raw_output_mm_page_alloc
  - mm/slab_common.c:trace_raw_output_kmem_alloc_node
  - mm/slab_common.c:trace_raw_output_kmem_alloc
  - mm/compaction.c:trace_raw_output_mm_compaction_try_to_compact_pages
  - fs/fs-writeback.c:trace_raw_output_writeback_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_single_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template
  - fs/dax.c:trace_raw_output_dax_pte_fault_class
  - fs/dax.c:trace_raw_output_dax_pte_fault_class
  - fs/dax.c:trace_raw_output_dax_pmd_insert_mapping_class
  - fs/dax.c:trace_raw_output_dax_pmd_fault_class
  - fs/dax.c:trace_raw_output_dax_pmd_fault_class
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_generic_add_lease
  - fs/locks.c:trace_raw_output_filelock_lease
  - fs/locks.c:trace_raw_output_filelock_lock
  - fs/iomap/trace.c:trace_raw_output_iomap_iter
  - fs/iomap/trace.c:trace_raw_output_iomap_class
  - fs/ext4/super.c:trace_raw_output_ext4_es_insert_delayed_block
  - fs/ext4/super.c:trace_raw_output_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_raw_output_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:trace_raw_output_ext4__es_extent
  - fs/ext4/super.c:trace_raw_output_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:trace_raw_output_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_enter
  - fs/ext4/super.c:trace_raw_output_ext4__fallocate_mode
  - fs/ext4/super.c:trace_raw_output_ext4_mballoc_alloc
  - fs/ext4/super.c:trace_raw_output_ext4_free_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_allocate_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_request_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_da_write_pages_extent
  - drivers/ras/ras.c:trace_raw_output_aer_event
  - drivers/ras/ras.c:trace_raw_output_aer_event
```
**Symbols:**

```
ffffffff812279d0-ffffffff81227b0b: trace_print_flags_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const char *trace_print_flags_seq(struct trace_seq *p, const char *delim, long unsigned int flags, const struct trace_print_flags *flag_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff81272f40)
Location: kernel/trace/trace_output.c:65
Inline: False
Direct callers:
  - kernel/sched/core.c:trace_raw_output_sched_switch
  - kernel/locking/mutex.c:trace_raw_output_contention_begin
  - kernel/module/main.c:trace_raw_output_module_load
  - kernel/time/timer.c:trace_raw_output_timer_start
  - kernel/time/alarmtimer.c:trace_raw_output_alarm_class
  - kernel/time/alarmtimer.c:trace_raw_output_alarmtimer_suspend
  - kernel/trace/trace_events_synth.c:print_synth_event
  - mm/vmscan.c:trace_raw_output_mm_vmscan_throttled
  - mm/vmscan.c:trace_raw_output_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:trace_raw_output_mm_vmscan_write_folio
  - mm/vmscan.c:trace_raw_output_mm_shrink_slab_start
  - mm/vmscan.c:trace_raw_output_mm_vmscan_direct_reclaim_begin_template
  - mm/vmscan.c:trace_raw_output_mm_vmscan_wakeup_kswapd
  - mm/percpu.c:trace_raw_output_percpu_alloc_percpu
  - mm/slab_common.c:trace_raw_output_mm_page_alloc
  - mm/slab_common.c:trace_raw_output_kmalloc
  - mm/slab_common.c:trace_raw_output_kmem_cache_alloc
  - mm/compaction.c:trace_raw_output_mm_compaction_try_to_compact_pages
  - fs/fs-writeback.c:trace_raw_output_writeback_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_single_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template
  - fs/dax.c:trace_raw_output_dax_pte_fault_class
  - fs/dax.c:trace_raw_output_dax_pte_fault_class
  - fs/dax.c:trace_raw_output_dax_pmd_insert_mapping_class
  - fs/dax.c:trace_raw_output_dax_pmd_fault_class
  - fs/dax.c:trace_raw_output_dax_pmd_fault_class
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_generic_add_lease
  - fs/locks.c:trace_raw_output_filelock_lease
  - fs/locks.c:trace_raw_output_filelock_lock
  - fs/iomap/trace.c:trace_raw_output_iomap_iter
  - fs/iomap/trace.c:trace_raw_output_iomap_class
  - fs/ext4/super.c:trace_raw_output_ext4_es_insert_delayed_block
  - fs/ext4/super.c:trace_raw_output_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_raw_output_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:trace_raw_output_ext4__es_extent
  - fs/ext4/super.c:trace_raw_output_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:trace_raw_output_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_enter
  - fs/ext4/super.c:trace_raw_output_ext4__fallocate_mode
  - fs/ext4/super.c:trace_raw_output_ext4_mballoc_alloc
  - fs/ext4/super.c:trace_raw_output_ext4_free_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_allocate_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_request_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_da_write_pages_extent
  - drivers/ras/ras.c:trace_raw_output_aer_event
  - drivers/ras/ras.c:trace_raw_output_aer_event
```
**Symbols:**

```
ffffffff81272f40-ffffffff8127307b: trace_print_flags_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const char *trace_print_flags_seq(struct trace_seq *p, const char *delim, long unsigned int flags, const struct trace_print_flags *flag_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff8128a2d0)
Location: kernel/trace/trace_output.c:65
Inline: False
Direct callers:
  - kernel/sched/core.c:trace_raw_output_sched_switch
  - kernel/locking/mutex.c:trace_raw_output_contention_begin
  - kernel/module/main.c:trace_raw_output_module_load
  - kernel/time/timer.c:trace_raw_output_timer_start
  - kernel/time/alarmtimer.c:trace_raw_output_alarm_class
  - kernel/time/alarmtimer.c:trace_raw_output_alarmtimer_suspend
  - kernel/trace/trace_events_synth.c:print_synth_event
  - mm/vmscan.c:trace_raw_output_mm_vmscan_throttled
  - mm/vmscan.c:trace_raw_output_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:trace_raw_output_mm_vmscan_write_folio
  - mm/vmscan.c:trace_raw_output_mm_shrink_slab_start
  - mm/vmscan.c:trace_raw_output_mm_vmscan_direct_reclaim_begin_template
  - mm/vmscan.c:trace_raw_output_mm_vmscan_wakeup_kswapd
  - mm/percpu.c:trace_raw_output_percpu_alloc_percpu
  - mm/slab_common.c:trace_raw_output_mm_page_alloc
  - mm/slab_common.c:trace_raw_output_kmalloc
  - mm/slab_common.c:trace_raw_output_kmem_cache_alloc
  - mm/compaction.c:trace_raw_output_mm_compaction_try_to_compact_pages
  - fs/fs-writeback.c:trace_raw_output_writeback_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_single_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template
  - fs/dax.c:trace_raw_output_dax_pte_fault_class
  - fs/dax.c:trace_raw_output_dax_pte_fault_class
  - fs/dax.c:trace_raw_output_dax_pmd_insert_mapping_class
  - fs/dax.c:trace_raw_output_dax_pmd_fault_class
  - fs/dax.c:trace_raw_output_dax_pmd_fault_class
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_generic_add_lease
  - fs/locks.c:trace_raw_output_filelock_lease
  - fs/locks.c:trace_raw_output_filelock_lock
  - fs/iomap/trace.c:trace_raw_output_iomap_dio_complete
  - fs/iomap/trace.c:trace_raw_output_iomap_dio_rw_begin
  - fs/iomap/trace.c:trace_raw_output_iomap_dio_rw_begin
  - fs/iomap/trace.c:trace_raw_output_iomap_iter
  - fs/iomap/trace.c:trace_raw_output_iomap_class
  - fs/ext4/super.c:trace_raw_output_ext4_es_insert_delayed_block
  - fs/ext4/super.c:trace_raw_output_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_raw_output_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:trace_raw_output_ext4__es_extent
  - fs/ext4/super.c:trace_raw_output_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:trace_raw_output_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_enter
  - fs/ext4/super.c:trace_raw_output_ext4__fallocate_mode
  - fs/ext4/super.c:trace_raw_output_ext4_mballoc_alloc
  - fs/ext4/super.c:trace_raw_output_ext4_free_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_allocate_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_request_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_da_write_pages_extent
  - drivers/ras/ras.c:trace_raw_output_aer_event
  - drivers/ras/ras.c:trace_raw_output_aer_event
```
**Symbols:**

```
ffffffff8128a2d0-ffffffff8128a416: trace_print_flags_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const char *trace_print_flags_seq(struct trace_seq *p, const char *delim, long unsigned int flags, const struct trace_print_flags *flag_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff812a5680)
Location: kernel/trace/trace_output.c:65
Inline: False
Direct callers:
  - kernel/sched/core.c:trace_raw_output_sched_switch
  - kernel/locking/mutex.c:trace_raw_output_contention_begin
  - kernel/module/main.c:trace_raw_output_module_load
  - kernel/time/timer.c:trace_raw_output_timer_start
  - kernel/time/alarmtimer.c:trace_raw_output_alarm_class
  - kernel/time/alarmtimer.c:trace_raw_output_alarmtimer_suspend
  - kernel/trace/trace_events_synth.c:print_synth_event
  - mm/vmscan.c:trace_raw_output_mm_vmscan_throttled
  - mm/vmscan.c:trace_raw_output_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:trace_raw_output_mm_vmscan_write_folio
  - mm/vmscan.c:trace_raw_output_mm_shrink_slab_start
  - mm/vmscan.c:trace_raw_output_mm_vmscan_direct_reclaim_begin_template
  - mm/vmscan.c:trace_raw_output_mm_vmscan_wakeup_kswapd
  - mm/percpu.c:trace_raw_output_percpu_alloc_percpu
  - mm/slab_common.c:trace_raw_output_mm_page_alloc
  - mm/slab_common.c:trace_raw_output_kmalloc
  - mm/slab_common.c:trace_raw_output_kmem_cache_alloc
  - mm/compaction.c:trace_raw_output_mm_compaction_try_to_compact_pages
  - fs/fs-writeback.c:trace_raw_output_writeback_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_single_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template
  - fs/dax.c:trace_raw_output_dax_pte_fault_class
  - fs/dax.c:trace_raw_output_dax_pte_fault_class
  - fs/dax.c:trace_raw_output_dax_pmd_insert_mapping_class
  - fs/dax.c:trace_raw_output_dax_pmd_fault_class
  - fs/dax.c:trace_raw_output_dax_pmd_fault_class
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_generic_add_lease
  - fs/locks.c:trace_raw_output_filelock_lease
  - fs/locks.c:trace_raw_output_filelock_lock
  - fs/iomap/trace.c:trace_raw_output_iomap_dio_complete
  - fs/iomap/trace.c:trace_raw_output_iomap_dio_rw_begin
  - fs/iomap/trace.c:trace_raw_output_iomap_dio_rw_begin
  - fs/iomap/trace.c:trace_raw_output_iomap_iter
  - fs/iomap/trace.c:trace_raw_output_iomap_class
  - fs/ext4/super.c:trace_raw_output_ext4_es_insert_delayed_block
  - fs/ext4/super.c:trace_raw_output_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_raw_output_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:trace_raw_output_ext4__es_extent
  - fs/ext4/super.c:trace_raw_output_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:trace_raw_output_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_enter
  - fs/ext4/super.c:trace_raw_output_ext4__fallocate_mode
  - fs/ext4/super.c:trace_raw_output_ext4_mballoc_alloc
  - fs/ext4/super.c:trace_raw_output_ext4_free_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_allocate_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_request_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_da_write_pages_extent
  - drivers/ras/ras.c:trace_raw_output_aer_event
  - drivers/ras/ras.c:trace_raw_output_aer_event
```
**Symbols:**

```
ffffffff812a5680-ffffffff812a57c6: trace_print_flags_seq (STB_GLOBAL)
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
const char *trace_print_flags_seq(struct trace_seq *p, const char *delim, long unsigned int flags, const struct trace_print_flags *flag_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffff80001022acd8)
Location: kernel/trace/trace_output.c:65
Inline: False
Direct callers:
  - kernel/sched/core.c:trace_raw_output_sched_switch
  - kernel/time/timer.c:trace_raw_output_timer_start
  - kernel/time/alarmtimer.c:trace_raw_output_alarm_class
  - kernel/time/alarmtimer.c:trace_raw_output_alarmtimer_suspend
  - kernel/module.c:trace_raw_output_module_load
  - kernel/trace/trace_events_hist.c:print_synth_event
  - mm/vmscan.c:trace_raw_output_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:trace_raw_output_mm_vmscan_inactive_list_is_low
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:trace_raw_output_mm_vmscan_writepage
  - mm/vmscan.c:trace_raw_output_mm_shrink_slab_start
  - mm/vmscan.c:trace_raw_output_mm_vmscan_direct_reclaim_begin_template
  - mm/vmscan.c:trace_raw_output_mm_vmscan_wakeup_kswapd
  - mm/slab_common.c:trace_raw_output_mm_page_alloc
  - mm/slab_common.c:trace_raw_output_kmem_alloc_node
  - mm/slab_common.c:trace_raw_output_kmem_alloc
  - mm/compaction.c:trace_raw_output_mm_compaction_try_to_compact_pages
  - fs/fs-writeback.c:trace_raw_output_writeback_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_single_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template
  - fs/dax.c:trace_raw_output_dax_pte_fault_class
  - fs/dax.c:trace_raw_output_dax_pte_fault_class
  - fs/dax.c:trace_raw_output_dax_pmd_insert_mapping_class
  - fs/dax.c:trace_raw_output_dax_pmd_fault_class
  - fs/dax.c:trace_raw_output_dax_pmd_fault_class
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_generic_add_lease
  - fs/locks.c:trace_raw_output_filelock_lease
  - fs/locks.c:trace_raw_output_filelock_lock
  - fs/ext4/super.c:trace_raw_output_ext4_es_insert_delayed_block
  - fs/ext4/super.c:trace_raw_output_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_raw_output_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:trace_raw_output_ext4__es_extent
  - fs/ext4/super.c:trace_raw_output_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:trace_raw_output_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_enter
  - fs/ext4/super.c:trace_raw_output_ext4__fallocate_mode
  - fs/ext4/super.c:trace_raw_output_ext4_mballoc_alloc
  - fs/ext4/super.c:trace_raw_output_ext4_free_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_allocate_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_request_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_da_write_pages_extent
  - drivers/ras/ras.c:trace_raw_output_aer_event
  - drivers/ras/ras.c:trace_raw_output_aer_event
```
**Symbols:**

```
ffff80001022acd8-ffff80001022adf8: trace_print_flags_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const char *trace_print_flags_seq(struct trace_seq *p, const char *delim, long unsigned int flags, const struct trace_print_flags *flag_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (c0468154)
Location: kernel/trace/trace_output.c:65
Inline: False
Direct callers:
  - kernel/sched/core.c:trace_raw_output_sched_switch
  - kernel/time/timer.c:trace_raw_output_timer_start
  - kernel/time/alarmtimer.c:trace_raw_output_alarm_class
  - kernel/time/alarmtimer.c:trace_raw_output_alarmtimer_suspend
  - kernel/module.c:trace_raw_output_module_load
  - mm/vmscan.c:trace_raw_output_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:trace_raw_output_mm_vmscan_inactive_list_is_low
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:trace_raw_output_mm_vmscan_writepage
  - mm/vmscan.c:trace_raw_output_mm_shrink_slab_start
  - mm/vmscan.c:trace_raw_output_mm_vmscan_direct_reclaim_begin_template
  - mm/vmscan.c:trace_raw_output_mm_vmscan_wakeup_kswapd
  - mm/slab_common.c:trace_raw_output_mm_page_alloc
  - mm/slab_common.c:trace_raw_output_kmem_alloc_node
  - mm/slab_common.c:trace_raw_output_kmem_alloc
  - mm/compaction.c:trace_raw_output_mm_compaction_try_to_compact_pages
  - fs/fs-writeback.c:trace_raw_output_writeback_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_single_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_generic_add_lease
  - fs/locks.c:trace_raw_output_filelock_lease
  - fs/locks.c:trace_raw_output_filelock_lock
  - fs/ext4/super.c:trace_raw_output_ext4_es_insert_delayed_block
  - fs/ext4/super.c:trace_raw_output_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_raw_output_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:trace_raw_output_ext4__es_extent
  - fs/ext4/super.c:trace_raw_output_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:trace_raw_output_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_enter
  - fs/ext4/super.c:trace_raw_output_ext4__fallocate_mode
  - fs/ext4/super.c:trace_raw_output_ext4_mballoc_alloc
  - fs/ext4/super.c:trace_raw_output_ext4_free_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_allocate_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_request_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_da_write_pages_extent
  - drivers/ras/ras.c:trace_raw_output_aer_event
  - drivers/ras/ras.c:trace_raw_output_aer_event
```
**Symbols:**

```
c0468154-c0468274: trace_print_flags_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const char *trace_print_flags_seq(struct trace_seq *p, const char *delim, long unsigned int flags, const struct trace_print_flags *flag_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (c0000000002b28b0)
Location: kernel/trace/trace_output.c:65
Inline: False
Direct callers:
  - kernel/sched/core.c:trace_raw_output_sched_switch
  - kernel/time/timer.c:trace_raw_output_timer_start
  - kernel/time/alarmtimer.c:trace_raw_output_alarm_class
  - kernel/time/alarmtimer.c:trace_raw_output_alarmtimer_suspend
  - kernel/module.c:trace_raw_output_module_load
  - kernel/trace/trace_events_hist.c:print_synth_event
  - mm/vmscan.c:trace_raw_output_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:trace_raw_output_mm_vmscan_inactive_list_is_low
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:trace_raw_output_mm_vmscan_writepage
  - mm/vmscan.c:trace_raw_output_mm_shrink_slab_start
  - mm/vmscan.c:trace_raw_output_mm_vmscan_direct_reclaim_begin_template
  - mm/vmscan.c:trace_raw_output_mm_vmscan_wakeup_kswapd
  - mm/slab_common.c:trace_raw_output_mm_page_alloc
  - mm/slab_common.c:trace_raw_output_kmem_alloc_node
  - mm/slab_common.c:trace_raw_output_kmem_alloc
  - mm/compaction.c:trace_raw_output_mm_compaction_try_to_compact_pages
  - fs/fs-writeback.c:trace_raw_output_writeback_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_single_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template
  - fs/dax.c:trace_raw_output_dax_pte_fault_class
  - fs/dax.c:trace_raw_output_dax_pte_fault_class
  - fs/dax.c:trace_raw_output_dax_pmd_insert_mapping_class
  - fs/dax.c:trace_raw_output_dax_pmd_fault_class
  - fs/dax.c:trace_raw_output_dax_pmd_fault_class
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_generic_add_lease
  - fs/locks.c:trace_raw_output_filelock_lease
  - fs/locks.c:trace_raw_output_filelock_lock
  - fs/ext4/super.c:trace_raw_output_ext4_es_insert_delayed_block
  - fs/ext4/super.c:trace_raw_output_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_raw_output_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:trace_raw_output_ext4__es_extent
  - fs/ext4/super.c:trace_raw_output_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:trace_raw_output_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_enter
  - fs/ext4/super.c:trace_raw_output_ext4__fallocate_mode
  - fs/ext4/super.c:trace_raw_output_ext4_mballoc_alloc
  - fs/ext4/super.c:trace_raw_output_ext4_free_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_allocate_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_request_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_da_write_pages_extent
  - drivers/ras/ras.c:trace_raw_output_aer_event
  - drivers/ras/ras.c:trace_raw_output_aer_event
```
**Symbols:**

```
c0000000002b28b0-c0000000002b2a74: trace_print_flags_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const char *trace_print_flags_seq(struct trace_seq *p, const char *delim, long unsigned int flags, const struct trace_print_flags *flag_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffe000184f28)
Location: kernel/trace/trace_output.c:65
Inline: False
Direct callers:
  - kernel/sched/core.c:trace_raw_output_sched_switch
  - kernel/time/timer.c:trace_raw_output_timer_start
  - kernel/time/alarmtimer.c:trace_raw_output_alarm_class
  - kernel/time/alarmtimer.c:trace_raw_output_alarmtimer_suspend
  - kernel/module.c:trace_raw_output_module_load
  - mm/vmscan.c:trace_raw_output_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:trace_raw_output_mm_vmscan_inactive_list_is_low
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:trace_raw_output_mm_vmscan_writepage
  - mm/vmscan.c:trace_raw_output_mm_shrink_slab_start
  - mm/vmscan.c:trace_raw_output_mm_vmscan_direct_reclaim_begin_template
  - mm/vmscan.c:trace_raw_output_mm_vmscan_wakeup_kswapd
  - mm/slab_common.c:trace_raw_output_mm_page_alloc
  - mm/slab_common.c:trace_raw_output_kmem_alloc_node
  - mm/slab_common.c:trace_raw_output_kmem_alloc
  - mm/compaction.c:trace_raw_output_mm_compaction_try_to_compact_pages
  - fs/fs-writeback.c:trace_raw_output_writeback_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_single_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template
  - fs/dax.c:trace_raw_output_dax_pte_fault_class
  - fs/dax.c:trace_raw_output_dax_pte_fault_class
  - fs/dax.c:trace_raw_output_dax_pmd_insert_mapping_class
  - fs/dax.c:trace_raw_output_dax_pmd_fault_class
  - fs/dax.c:trace_raw_output_dax_pmd_fault_class
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_generic_add_lease
  - fs/locks.c:trace_raw_output_filelock_lease
  - fs/locks.c:trace_raw_output_filelock_lock
  - fs/ext4/super.c:trace_raw_output_ext4_es_insert_delayed_block
  - fs/ext4/super.c:trace_raw_output_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_raw_output_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:trace_raw_output_ext4__es_extent
  - fs/ext4/super.c:trace_raw_output_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:trace_raw_output_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_enter
  - fs/ext4/super.c:trace_raw_output_ext4__fallocate_mode
  - fs/ext4/super.c:trace_raw_output_ext4_mballoc_alloc
  - fs/ext4/super.c:trace_raw_output_ext4_free_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_allocate_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_request_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_da_write_pages_extent
  - drivers/ras/ras.c:trace_raw_output_aer_event
  - drivers/ras/ras.c:trace_raw_output_aer_event
```
**Symbols:**

```
ffffffe000184f28-ffffffe000185018: trace_print_flags_seq (STB_GLOBAL)
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
const char *trace_print_flags_seq(struct trace_seq *p, const char *delim, long unsigned int flags, const struct trace_print_flags *flag_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff811a5ff0)
Location: kernel/trace/trace_output.c:65
Inline: False
Direct callers:
  - kernel/sched/core.c:trace_raw_output_sched_switch
  - kernel/time/timer.c:trace_raw_output_timer_start
  - kernel/time/alarmtimer.c:trace_raw_output_alarm_class
  - kernel/time/alarmtimer.c:trace_raw_output_alarmtimer_suspend
  - kernel/module.c:trace_raw_output_module_load
  - kernel/trace/trace_events_hist.c:print_synth_event
  - mm/vmscan.c:trace_raw_output_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:trace_raw_output_mm_vmscan_inactive_list_is_low
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:trace_raw_output_mm_vmscan_writepage
  - mm/vmscan.c:trace_raw_output_mm_shrink_slab_start
  - mm/vmscan.c:trace_raw_output_mm_vmscan_direct_reclaim_begin_template
  - mm/vmscan.c:trace_raw_output_mm_vmscan_wakeup_kswapd
  - mm/slab_common.c:trace_raw_output_mm_page_alloc
  - mm/slab_common.c:trace_raw_output_kmem_alloc_node
  - mm/slab_common.c:trace_raw_output_kmem_alloc
  - mm/compaction.c:trace_raw_output_mm_compaction_try_to_compact_pages
  - fs/fs-writeback.c:trace_raw_output_writeback_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_single_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template
  - fs/dax.c:trace_raw_output_dax_pte_fault_class
  - fs/dax.c:trace_raw_output_dax_pte_fault_class
  - fs/dax.c:trace_raw_output_dax_pmd_insert_mapping_class
  - fs/dax.c:trace_raw_output_dax_pmd_fault_class
  - fs/dax.c:trace_raw_output_dax_pmd_fault_class
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_generic_add_lease
  - fs/locks.c:trace_raw_output_filelock_lease
  - fs/locks.c:trace_raw_output_filelock_lock
  - fs/ext4/super.c:trace_raw_output_ext4_es_insert_delayed_block
  - fs/ext4/super.c:trace_raw_output_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_raw_output_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:trace_raw_output_ext4__es_extent
  - fs/ext4/super.c:trace_raw_output_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:trace_raw_output_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_enter
  - fs/ext4/super.c:trace_raw_output_ext4__fallocate_mode
  - fs/ext4/super.c:trace_raw_output_ext4_mballoc_alloc
  - fs/ext4/super.c:trace_raw_output_ext4_free_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_allocate_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_request_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_da_write_pages_extent
  - drivers/ras/ras.c:trace_raw_output_aer_event
  - drivers/ras/ras.c:trace_raw_output_aer_event
```
**Symbols:**

```
ffffffff811a5ff0-ffffffff811a6120: trace_print_flags_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
const char *trace_print_flags_seq(struct trace_seq *p, const char *delim, long unsigned int flags, const struct trace_print_flags *flag_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff81198f70)
Location: kernel/trace/trace_output.c:65
Inline: False
Direct callers:
  - kernel/sched/core.c:trace_raw_output_sched_switch
  - kernel/time/timer.c:trace_raw_output_timer_start
  - kernel/time/alarmtimer.c:trace_raw_output_alarm_class
  - kernel/time/alarmtimer.c:trace_raw_output_alarmtimer_suspend
  - kernel/module.c:trace_raw_output_module_load
  - kernel/trace/trace_events_hist.c:print_synth_event
  - mm/vmscan.c:trace_raw_output_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:trace_raw_output_mm_vmscan_inactive_list_is_low
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:trace_raw_output_mm_vmscan_writepage
  - mm/vmscan.c:trace_raw_output_mm_shrink_slab_start
  - mm/vmscan.c:trace_raw_output_mm_vmscan_direct_reclaim_begin_template
  - mm/vmscan.c:trace_raw_output_mm_vmscan_wakeup_kswapd
  - mm/slab_common.c:trace_raw_output_mm_page_alloc
  - mm/slab_common.c:trace_raw_output_kmem_alloc_node
  - mm/slab_common.c:trace_raw_output_kmem_alloc
  - mm/compaction.c:trace_raw_output_mm_compaction_try_to_compact_pages
  - fs/fs-writeback.c:trace_raw_output_writeback_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_single_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template
  - fs/dax.c:trace_raw_output_dax_pte_fault_class
  - fs/dax.c:trace_raw_output_dax_pte_fault_class
  - fs/dax.c:trace_raw_output_dax_pmd_insert_mapping_class
  - fs/dax.c:trace_raw_output_dax_pmd_fault_class
  - fs/dax.c:trace_raw_output_dax_pmd_fault_class
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_generic_add_lease
  - fs/locks.c:trace_raw_output_filelock_lease
  - fs/locks.c:trace_raw_output_filelock_lock
  - fs/ext4/super.c:trace_raw_output_ext4_es_insert_delayed_block
  - fs/ext4/super.c:trace_raw_output_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_raw_output_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:trace_raw_output_ext4__es_extent
  - fs/ext4/super.c:trace_raw_output_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:trace_raw_output_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_enter
  - fs/ext4/super.c:trace_raw_output_ext4__fallocate_mode
  - fs/ext4/super.c:trace_raw_output_ext4_mballoc_alloc
  - fs/ext4/super.c:trace_raw_output_ext4_free_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_allocate_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_request_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_da_write_pages_extent
  - drivers/ras/ras.c:trace_raw_output_aer_event
  - drivers/ras/ras.c:trace_raw_output_aer_event
```
**Symbols:**

```
ffffffff81198f70-ffffffff811990a0: trace_print_flags_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
const char *trace_print_flags_seq(struct trace_seq *p, const char *delim, long unsigned int flags, const struct trace_print_flags *flag_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff811a3dc0)
Location: kernel/trace/trace_output.c:65
Inline: False
Direct callers:
  - kernel/sched/core.c:trace_raw_output_sched_switch
  - kernel/time/timer.c:trace_raw_output_timer_start
  - kernel/time/alarmtimer.c:trace_raw_output_alarm_class
  - kernel/time/alarmtimer.c:trace_raw_output_alarmtimer_suspend
  - kernel/module.c:trace_raw_output_module_load
  - kernel/trace/trace_events_hist.c:print_synth_event
  - mm/vmscan.c:trace_raw_output_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:trace_raw_output_mm_vmscan_inactive_list_is_low
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:trace_raw_output_mm_vmscan_writepage
  - mm/vmscan.c:trace_raw_output_mm_shrink_slab_start
  - mm/vmscan.c:trace_raw_output_mm_vmscan_direct_reclaim_begin_template
  - mm/vmscan.c:trace_raw_output_mm_vmscan_wakeup_kswapd
  - mm/slab_common.c:trace_raw_output_mm_page_alloc
  - mm/slab_common.c:trace_raw_output_kmem_alloc_node
  - mm/slab_common.c:trace_raw_output_kmem_alloc
  - mm/compaction.c:trace_raw_output_mm_compaction_try_to_compact_pages
  - fs/fs-writeback.c:trace_raw_output_writeback_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_single_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template
  - fs/dax.c:trace_raw_output_dax_pte_fault_class
  - fs/dax.c:trace_raw_output_dax_pte_fault_class
  - fs/dax.c:trace_raw_output_dax_pmd_insert_mapping_class
  - fs/dax.c:trace_raw_output_dax_pmd_fault_class
  - fs/dax.c:trace_raw_output_dax_pmd_fault_class
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_generic_add_lease
  - fs/locks.c:trace_raw_output_filelock_lease
  - fs/locks.c:trace_raw_output_filelock_lock
  - fs/ext4/super.c:trace_raw_output_ext4_es_insert_delayed_block
  - fs/ext4/super.c:trace_raw_output_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_raw_output_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:trace_raw_output_ext4__es_extent
  - fs/ext4/super.c:trace_raw_output_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:trace_raw_output_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_enter
  - fs/ext4/super.c:trace_raw_output_ext4__fallocate_mode
  - fs/ext4/super.c:trace_raw_output_ext4_mballoc_alloc
  - fs/ext4/super.c:trace_raw_output_ext4_free_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_allocate_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_request_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_da_write_pages_extent
  - drivers/ras/ras.c:trace_raw_output_aer_event
  - drivers/ras/ras.c:trace_raw_output_aer_event
```
**Symbols:**

```
ffffffff811a3dc0-ffffffff811a3ef0: trace_print_flags_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
const char *trace_print_flags_seq(struct trace_seq *p, const char *delim, long unsigned int flags, const struct trace_print_flags *flag_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_output.c (ffffffff811b1b50)
Location: kernel/trace/trace_output.c:65
Inline: False
Direct callers:
  - kernel/sched/core.c:trace_raw_output_sched_switch
  - kernel/time/timer.c:trace_raw_output_timer_start
  - kernel/time/alarmtimer.c:trace_raw_output_alarm_class
  - kernel/time/alarmtimer.c:trace_raw_output_alarmtimer_suspend
  - kernel/module.c:trace_raw_output_module_load
  - kernel/trace/trace_events_hist.c:print_synth_event
  - mm/vmscan.c:trace_raw_output_mm_vmscan_node_reclaim_begin
  - mm/vmscan.c:trace_raw_output_mm_vmscan_inactive_list_is_low
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_active
  - mm/vmscan.c:trace_raw_output_mm_vmscan_lru_shrink_inactive
  - mm/vmscan.c:trace_raw_output_mm_vmscan_writepage
  - mm/vmscan.c:trace_raw_output_mm_shrink_slab_start
  - mm/vmscan.c:trace_raw_output_mm_vmscan_direct_reclaim_begin_template
  - mm/vmscan.c:trace_raw_output_mm_vmscan_wakeup_kswapd
  - mm/slab_common.c:trace_raw_output_mm_page_alloc
  - mm/slab_common.c:trace_raw_output_kmem_alloc_node
  - mm/slab_common.c:trace_raw_output_kmem_alloc
  - mm/compaction.c:trace_raw_output_mm_compaction_try_to_compact_pages
  - fs/fs-writeback.c:trace_raw_output_writeback_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_single_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_raw_output_writeback_dirty_inode_template
  - fs/dax.c:trace_raw_output_dax_pte_fault_class
  - fs/dax.c:trace_raw_output_dax_pte_fault_class
  - fs/dax.c:trace_raw_output_dax_pmd_insert_mapping_class
  - fs/dax.c:trace_raw_output_dax_pmd_fault_class
  - fs/dax.c:trace_raw_output_dax_pmd_fault_class
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_leases_conflict
  - fs/locks.c:trace_raw_output_generic_add_lease
  - fs/locks.c:trace_raw_output_filelock_lease
  - fs/locks.c:trace_raw_output_filelock_lock
  - fs/ext4/super.c:trace_raw_output_ext4_es_insert_delayed_block
  - fs/ext4/super.c:trace_raw_output_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_raw_output_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:trace_raw_output_ext4__es_extent
  - fs/ext4/super.c:trace_raw_output_ext4_get_implied_cluster_alloc_exit
  - fs/ext4/super.c:trace_raw_output_ext4_ext_handle_unwritten_extents
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_exit
  - fs/ext4/super.c:trace_raw_output_ext4__map_blocks_enter
  - fs/ext4/super.c:trace_raw_output_ext4__fallocate_mode
  - fs/ext4/super.c:trace_raw_output_ext4_mballoc_alloc
  - fs/ext4/super.c:trace_raw_output_ext4_free_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_allocate_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_request_blocks
  - fs/ext4/super.c:trace_raw_output_ext4_da_write_pages_extent
  - drivers/ras/ras.c:trace_raw_output_aer_event
  - drivers/ras/ras.c:trace_raw_output_aer_event
```
**Symbols:**

```
ffffffff811b1b50-ffffffff811b1c80: trace_print_flags_seq (STB_GLOBAL)
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
