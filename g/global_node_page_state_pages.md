# Function: <code>global_node_page_state_pages</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81bdfd14)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
```
```
In mm/oom_kill.c (ffffffff81be6b15)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
```
```
In mm/page-writeback.c (ffffffff81265f21)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:global_dirty_limits
  - mm/page-writeback.c:global_dirty_limits
```
```
In mm/vmstat.c (ffffffff8127f214)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
```
```
In mm/page_alloc.c (ffffffff81be7d9a)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
```
```
In fs/fs-writeback.c (ffffffff8135b076)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:wb_check_start_all
  - fs/fs-writeback.c:wb_check_old_data_flush
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
```
```
In fs/proc/meminfo.c (ffffffff813d67a6)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8172ccd1)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
In kernel/power/snapshot.c (ffffffff81bd1c1b)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
```
```
In mm/oom_kill.c (ffffffff81bd88a8)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
```
```
In mm/page-writeback.c (ffffffff8126aa05)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:global_dirty_limits
  - mm/page-writeback.c:global_dirty_limits
```
```
In mm/vmstat.c (ffffffff81284363)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
```
```
In mm/page_alloc.c (ffffffff81bd9b91)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
```
```
In mm/swap_state.c (ffffffff81bda63f)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/swap_state.c:show_swap_cache_info
```
```
In fs/fs-writeback.c (ffffffff81361c76)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
```
```
In fs/proc/meminfo.c (ffffffff813dd6a8)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81710870)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
In kernel/power/snapshot.c (ffffffff81caa8d5)
Location: include/linux/vmstat.h:190
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
```
```
In mm/oom_kill.c (ffffffff81cba160)
Location: include/linux/vmstat.h:190
Inline: True
Inline callers:
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
```
```
In mm/page-writeback.c (ffffffff812a76b5)
Location: include/linux/vmstat.h:190
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:global_dirty_limits
  - mm/page-writeback.c:global_dirty_limits
```
```
In mm/vmstat.c (ffffffff812c46f8)
Location: include/linux/vmstat.h:190
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
```
```
In mm/page_alloc.c (ffffffff81cbda43)
Location: include/linux/vmstat.h:190
Inline: True
Inline callers:
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
```
```
In mm/swap_state.c (ffffffff81cbe979)
Location: include/linux/vmstat.h:190
Inline: True
Inline callers:
  - mm/swap_state.c:show_swap_cache_info
```
```
In fs/fs-writeback.c (ffffffff813b02d6)
Location: include/linux/vmstat.h:190
Inline: True
Inline callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
```
```
In fs/proc/meminfo.c (ffffffff8142ee3f)
Location: include/linux/vmstat.h:190
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8178d260)
Location: include/linux/vmstat.h:190
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
In kernel/power/snapshot.c (ffffffff81e5acfb)
Location: include/linux/vmstat.h:190
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
```
```
In mm/oom_kill.c (ffffffff81e6b8a9)
Location: include/linux/vmstat.h:190
Inline: True
Inline callers:
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
```
```
In mm/page-writeback.c (ffffffff812ffcd5)
Location: include/linux/vmstat.h:190
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:global_dirty_limits
  - mm/page-writeback.c:global_dirty_limits
```
```
In mm/vmstat.c (ffffffff813212f3)
Location: include/linux/vmstat.h:190
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
```
```
In mm/page_alloc.c (ffffffff81e6f8fe)
Location: include/linux/vmstat.h:190
Inline: True
Inline callers:
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
```
```
In mm/swap_state.c (ffffffff81e70ad4)
Location: include/linux/vmstat.h:190
Inline: True
Inline callers:
  - mm/swap_state.c:show_swap_cache_info
```
```
In fs/fs-writeback.c (ffffffff81434f06)
Location: include/linux/vmstat.h:190
Inline: True
Inline callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
```
```
In fs/proc/meminfo.c (ffffffff814a8a50)
Location: include/linux/vmstat.h:190
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
```
```
In drivers/virtio/virtio_balloon.c (ffffffff818c5374)
Location: include/linux/vmstat.h:190
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
In kernel/power/snapshot.c (ffffffff81187193)
Location: include/linux/vmstat.h:184
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
```
```
In mm/oom_kill.c (ffffffff8136423a)
Location: include/linux/vmstat.h:184
Inline: True
Inline callers:
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
```
```
In mm/page-writeback.c (ffffffff8136a5d5)
Location: include/linux/vmstat.h:184
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:bdi_set_max_bytes
  - mm/page-writeback.c:bdi_set_max_bytes
  - mm/page-writeback.c:bdi_set_min_bytes
  - mm/page-writeback.c:bdi_set_min_bytes
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:global_dirty_limits
  - mm/page-writeback.c:global_dirty_limits
```
```
In mm/vmstat.c (ffffffff813952b3)
Location: include/linux/vmstat.h:184
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
```
```
In mm/page_alloc.c (ffffffff813ed9ce)
Location: include/linux/vmstat.h:184
Inline: True
Inline callers:
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
```
```
In mm/swap_state.c (ffffffff813f8545)
Location: include/linux/vmstat.h:184
Inline: True
Inline callers:
  - mm/swap_state.c:show_swap_cache_info
```
```
In fs/fs-writeback.c (ffffffff814c2f36)
Location: include/linux/vmstat.h:184
Inline: True
Inline callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
```
```
In fs/proc/meminfo.c (ffffffff8153e4c0)
Location: include/linux/vmstat.h:184
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a15c64)
Location: include/linux/vmstat.h:184
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
In kernel/power/snapshot.c (ffffffff81198303)
Location: include/linux/vmstat.h:190
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
```
```
In mm/oom_kill.c (ffffffff8139670a)
Location: include/linux/vmstat.h:190
Inline: True
Inline callers:
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
```
```
In mm/page-writeback.c (ffffffff8139c765)
Location: include/linux/vmstat.h:190
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:bdi_set_max_bytes
  - mm/page-writeback.c:bdi_set_max_bytes
  - mm/page-writeback.c:bdi_set_min_bytes
  - mm/page-writeback.c:bdi_set_min_bytes
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:global_dirty_limits
  - mm/page-writeback.c:global_dirty_limits
```
```
In mm/vmstat.c (ffffffff813c7ed3)
Location: include/linux/vmstat.h:190
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
```
```
In mm/show_mem.c (ffffffff813ddd3e)
Location: include/linux/vmstat.h:190
Inline: True
Inline callers:
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:si_meminfo
  - mm/show_mem.c:si_mem_available
  - mm/show_mem.c:si_mem_available
  - mm/show_mem.c:si_mem_available
```
```
In mm/swap_state.c (ffffffff8142b305)
Location: include/linux/vmstat.h:190
Inline: True
Inline callers:
  - mm/swap_state.c:show_swap_cache_info
```
```
In mm/memcontrol.c (ffffffff81486c7c)
Location: include/linux/vmstat.h:190
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
```
```
In fs/fs-writeback.c (ffffffff814f8316)
Location: include/linux/vmstat.h:190
Inline: True
Inline callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
```
```
In fs/proc/meminfo.c (ffffffff81576790)
Location: include/linux/vmstat.h:190
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a5ed14)
Location: include/linux/vmstat.h:190
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
In kernel/power/snapshot.c (ffffffff811a7168)
Location: include/linux/vmstat.h:190
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
```
```
In mm/oom_kill.c (ffffffff813c0765)
Location: include/linux/vmstat.h:190
Inline: True
Inline callers:
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
```
```
In mm/page-writeback.c (ffffffff813c6445)
Location: include/linux/vmstat.h:190
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:bdi_set_max_bytes
  - mm/page-writeback.c:bdi_set_max_bytes
  - mm/page-writeback.c:bdi_set_min_bytes
  - mm/page-writeback.c:bdi_set_min_bytes
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:global_dirty_limits
  - mm/page-writeback.c:global_dirty_limits
```
```
In mm/vmstat.c (ffffffff813f28e2)
Location: include/linux/vmstat.h:190
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
```
```
In mm/show_mem.c (ffffffff81407b2e)
Location: include/linux/vmstat.h:190
Inline: True
Inline callers:
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:si_meminfo
  - mm/show_mem.c:si_mem_available
  - mm/show_mem.c:si_mem_available
  - mm/show_mem.c:si_mem_available
  - mm/show_mem.c:si_mem_available
```
```
In mm/swap_state.c (ffffffff81464af5)
Location: include/linux/vmstat.h:190
Inline: True
Inline callers:
  - mm/swap_state.c:show_swap_cache_info
```
```
In mm/memcontrol.c (ffffffff814b53fc)
Location: include/linux/vmstat.h:190
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
```
```
In fs/fs-writeback.c (ffffffff8152ca96)
Location: include/linux/vmstat.h:190
Inline: True
Inline callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
```
```
In fs/proc/meminfo.c (ffffffff815af0e0)
Location: include/linux/vmstat.h:190
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81ab1474)
Location: include/linux/vmstat.h:190
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
