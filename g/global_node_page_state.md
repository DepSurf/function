# Function: <code>global_node_page_state</code>

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
In kernel/power/snapshot.c (ffffffff810d65a6)
Location: include/linux/vmstat.h:137
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
```
```
In mm/page_alloc.c (ffffffff811ab668)
Location: include/linux/vmstat.h:137
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
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_mem_available
```
```
In mm/page-writeback.c (ffffffff811b062b)
Location: include/linux/vmstat.h:137
Inline: True
Inline callers:
  - mm/page-writeback.c:laptop_mode_timer_fn
  - mm/page-writeback.c:laptop_mode_timer_fn
  - mm/page-writeback.c:throttle_vm_writeout
  - mm/page-writeback.c:throttle_vm_writeout
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:global_dirty_limits
  - mm/page-writeback.c:global_dirty_limits
```
```
In mm/util.c (ffffffff811c4e63)
Location: include/linux/vmstat.h:137
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
```
```
In mm/vmstat.c (ffffffff811c6184)
Location: include/linux/vmstat.h:137
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
```
```
In fs/fs-writeback.c (ffffffff8125f936)
Location: include/linux/vmstat.h:137
Inline: True
Inline callers:
  - fs/fs-writeback.c:get_nr_dirty_pages
  - fs/fs-writeback.c:get_nr_dirty_pages
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
```
```
In fs/proc/meminfo.c (ffffffff812af70e)
Location: include/linux/vmstat.h:137
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
In kernel/power/snapshot.c (ffffffff810dd116)
Location: include/linux/vmstat.h:137
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
```
```
In mm/page_alloc.c (ffffffff811bbc4d)
Location: include/linux/vmstat.h:137
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
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_mem_available
```
```
In mm/page-writeback.c (ffffffff811c0c1b)
Location: include/linux/vmstat.h:137
Inline: True
Inline callers:
  - mm/page-writeback.c:laptop_mode_timer_fn
  - mm/page-writeback.c:laptop_mode_timer_fn
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:global_dirty_limits
  - mm/page-writeback.c:global_dirty_limits
```
```
In mm/util.c (ffffffff811d4f73)
Location: include/linux/vmstat.h:137
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
```
```
In mm/vmstat.c (ffffffff811d62d1)
Location: include/linux/vmstat.h:137
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
```
```
In fs/fs-writeback.c (ffffffff81272e56)
Location: include/linux/vmstat.h:137
Inline: True
Inline callers:
  - fs/fs-writeback.c:get_nr_dirty_pages
  - fs/fs-writeback.c:get_nr_dirty_pages
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
```
```
In fs/proc/meminfo.c (ffffffff812c519a)
Location: include/linux/vmstat.h:137
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
In kernel/power/snapshot.c (ffffffff810dc22e)
Location: include/linux/vmstat.h:136
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
```
```
In mm/page_alloc.c (ffffffff811c3ed6)
Location: include/linux/vmstat.h:136
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
In mm/page-writeback.c (ffffffff811c8d79)
Location: include/linux/vmstat.h:136
Inline: True
Inline callers:
  - mm/page-writeback.c:laptop_mode_timer_fn
  - mm/page-writeback.c:laptop_mode_timer_fn
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:global_dirty_limits
  - mm/page-writeback.c:global_dirty_limits
```
```
In mm/util.c (ffffffff811dddc3)
Location: include/linux/vmstat.h:136
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
```
```
In mm/vmstat.c (ffffffff811deffb)
Location: include/linux/vmstat.h:136
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
```
```
In fs/fs-writeback.c (ffffffff81280236)
Location: include/linux/vmstat.h:136
Inline: True
Inline callers:
  - fs/fs-writeback.c:get_nr_dirty_pages
  - fs/fs-writeback.c:get_nr_dirty_pages
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
```
```
In fs/proc/meminfo.c (ffffffff812d23da)
Location: include/linux/vmstat.h:136
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
In kernel/power/snapshot.c (ffffffff810e444e)
Location: include/linux/vmstat.h:176
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
```
```
In mm/oom_kill.c (ffffffff811d2a95)
Location: include/linux/vmstat.h:176
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
In mm/page_alloc.c (ffffffff811d8ce9)
Location: include/linux/vmstat.h:176
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
In mm/page-writeback.c (ffffffff811dd9f6)
Location: include/linux/vmstat.h:176
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
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
In mm/util.c (ffffffff811f3843)
Location: include/linux/vmstat.h:176
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
```
```
In mm/vmstat.c (ffffffff811f4c60)
Location: include/linux/vmstat.h:176
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
```
```
In fs/fs-writeback.c (ffffffff812a2d66)
Location: include/linux/vmstat.h:176
Inline: True
Inline callers:
  - fs/fs-writeback.c:get_nr_dirty_pages
  - fs/fs-writeback.c:get_nr_dirty_pages
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
```
```
In fs/proc/meminfo.c (ffffffff812f6c1a)
Location: include/linux/vmstat.h:176
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
In kernel/power/snapshot.c (ffffffff810ed486)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
```
```
In mm/oom_kill.c (ffffffff811f3995)
Location: include/linux/vmstat.h:187
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
In mm/page_alloc.c (ffffffff811fae64)
Location: include/linux/vmstat.h:187
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
  - mm/page_alloc.c:si_mem_available
```
```
In mm/page-writeback.c (ffffffff811fef83)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
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
In mm/util.c (ffffffff81214b57)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
```
```
In mm/vmstat.c (ffffffff81215f0e)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
```
```
In fs/fs-writeback.c (ffffffff812c97e5)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - fs/fs-writeback.c:get_nr_dirty_pages
  - fs/fs-writeback.c:get_nr_dirty_pages
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
```
```
In fs/proc/meminfo.c (ffffffff81323f91)
Location: include/linux/vmstat.h:187
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
```
```
In drivers/virtio/virtio_balloon.c (ffffffff815f02f0)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
In kernel/power/snapshot.c (ffffffff810f8aeb)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
```
```
In mm/oom_kill.c (ffffffff81205943)
Location: include/linux/vmstat.h:187
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
In mm/page_alloc.c (ffffffff8120d70d)
Location: include/linux/vmstat.h:187
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
In mm/page-writeback.c (ffffffff8121183e)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
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
In mm/util.c (ffffffff81227a37)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
```
```
In mm/vmstat.c (ffffffff81228e0e)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
```
```
In fs/fs-writeback.c (ffffffff812dea15)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - fs/fs-writeback.c:get_nr_dirty_pages
  - fs/fs-writeback.c:get_nr_dirty_pages
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
```
```
In fs/proc/meminfo.c (ffffffff8133b0e1)
Location: include/linux/vmstat.h:187
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
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8160a8d0)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
In kernel/power/snapshot.c (ffffffff81101162)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
```
```
In mm/oom_kill.c (ffffffff8121d075)
Location: include/linux/vmstat.h:187
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
In mm/page-writeback.c (ffffffff81220e61)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
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
In mm/vmstat.c (ffffffff81238af0)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
```
```
In mm/page_alloc.c (ffffffff81273bc4)
Location: include/linux/vmstat.h:187
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
In fs/fs-writeback.c (ffffffff812ff7d6)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
```
```
In fs/proc/meminfo.c (ffffffff813632a1)
Location: include/linux/vmstat.h:187
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
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8163e6d0)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
In kernel/power/snapshot.c (ffffffff8110d59f)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
```
```
In mm/oom_kill.c (ffffffff8122aa52)
Location: include/linux/vmstat.h:187
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
In mm/page-writeback.c (ffffffff8122e911)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
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
In mm/vmstat.c (ffffffff81246de0)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
```
```
In mm/page_alloc.c (ffffffff812829df)
Location: include/linux/vmstat.h:187
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
In fs/fs-writeback.c (ffffffff813146e6)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
```
```
In fs/proc/meminfo.c (ffffffff8137b501)
Location: include/linux/vmstat.h:187
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
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81660c40)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
In kernel/power/snapshot.c (ffffffff8111887d)
Location: include/linux/vmstat.h:195
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
```
```
In mm/oom_kill.c (ffffffff81257810)
Location: include/linux/vmstat.h:195
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
In mm/page-writeback.c (ffffffff8125bb01)
Location: include/linux/vmstat.h:195
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
In mm/vmstat.c (ffffffff812749c4)
Location: include/linux/vmstat.h:195
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
```
```
In mm/page_alloc.c (ffffffff812b4a81)
Location: include/linux/vmstat.h:195
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
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
```
```
In fs/fs-writeback.c (ffffffff8134e1c6)
Location: include/linux/vmstat.h:195
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
In fs/proc/meminfo.c (ffffffff813c4852)
Location: include/linux/vmstat.h:195
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
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8170ffd0)
Location: include/linux/vmstat.h:195
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
In kernel/power/snapshot.c (ffffffff81bdfd1b)
Location: include/linux/vmstat.h:207
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
```
```
In mm/oom_kill.c (ffffffff81be6b15)
Location: include/linux/vmstat.h:207
Inline: True
Inline callers:
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
Location: include/linux/vmstat.h:207
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
In mm/page_alloc.c (ffffffff81be7d9a)
Location: include/linux/vmstat.h:207
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
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
```
```
In fs/fs-writeback.c (ffffffff8135b076)
Location: include/linux/vmstat.h:207
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
Location: include/linux/vmstat.h:207
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
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8172ccd1)
Location: include/linux/vmstat.h:207
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
In kernel/power/snapshot.c (ffffffff81bd1c22)
Location: include/linux/vmstat.h:207
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
```
```
In mm/oom_kill.c (ffffffff81bd88a8)
Location: include/linux/vmstat.h:207
Inline: True
Inline callers:
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
Location: include/linux/vmstat.h:207
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
In mm/page_alloc.c (ffffffff81bd9b91)
Location: include/linux/vmstat.h:207
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
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
```
```
In mm/swap_state.c (ffffffff81bda63f)
Location: include/linux/vmstat.h:207
Inline: True
Inline callers:
  - mm/swap_state.c:show_swap_cache_info
```
```
In fs/fs-writeback.c (ffffffff81361c76)
Location: include/linux/vmstat.h:207
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
Location: include/linux/vmstat.h:207
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
In drivers/virtio/virtio_balloon.c (ffffffff81710870)
Location: include/linux/vmstat.h:207
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
In kernel/power/snapshot.c (ffffffff81caa8dc)
Location: include/linux/vmstat.h:200
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
```
```
In mm/oom_kill.c (ffffffff81cba160)
Location: include/linux/vmstat.h:200
Inline: True
Inline callers:
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
Location: include/linux/vmstat.h:200
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
In mm/page_alloc.c (ffffffff81cbda43)
Location: include/linux/vmstat.h:200
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
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
```
```
In mm/swap_state.c (ffffffff81cbe979)
Location: include/linux/vmstat.h:200
Inline: True
Inline callers:
  - mm/swap_state.c:show_swap_cache_info
```
```
In fs/fs-writeback.c (ffffffff813b02d6)
Location: include/linux/vmstat.h:200
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
Location: include/linux/vmstat.h:200
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
In drivers/virtio/virtio_balloon.c (ffffffff8178d260)
Location: include/linux/vmstat.h:200
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
In kernel/power/snapshot.c (ffffffff81e5ad02)
Location: include/linux/vmstat.h:200
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
```
```
In mm/oom_kill.c (ffffffff81e6b8a9)
Location: include/linux/vmstat.h:200
Inline: True
Inline callers:
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
Location: include/linux/vmstat.h:200
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
In mm/page_alloc.c (ffffffff81e6f8fe)
Location: include/linux/vmstat.h:200
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
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
```
```
In mm/swap_state.c (ffffffff81e70ad4)
Location: include/linux/vmstat.h:200
Inline: True
Inline callers:
  - mm/swap_state.c:show_swap_cache_info
```
```
In fs/fs-writeback.c (ffffffff81434f06)
Location: include/linux/vmstat.h:200
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
Location: include/linux/vmstat.h:200
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
In drivers/virtio/virtio_balloon.c (ffffffff818c5374)
Location: include/linux/vmstat.h:200
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
In kernel/power/snapshot.c (ffffffff8118719a)
Location: include/linux/vmstat.h:194
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
```
```
In mm/oom_kill.c (ffffffff8136423a)
Location: include/linux/vmstat.h:194
Inline: True
Inline callers:
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
Location: include/linux/vmstat.h:194
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
In mm/page_alloc.c (ffffffff813ed9ce)
Location: include/linux/vmstat.h:194
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
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:si_mem_available
```
```
In mm/swap_state.c (ffffffff813f8545)
Location: include/linux/vmstat.h:194
Inline: True
Inline callers:
  - mm/swap_state.c:show_swap_cache_info
```
```
In fs/fs-writeback.c (ffffffff814c2f36)
Location: include/linux/vmstat.h:194
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
Location: include/linux/vmstat.h:194
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
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a15c64)
Location: include/linux/vmstat.h:194
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
In kernel/power/snapshot.c (ffffffff8119830a)
Location: include/linux/vmstat.h:200
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
```
```
In mm/oom_kill.c (ffffffff8139670a)
Location: include/linux/vmstat.h:200
Inline: True
Inline callers:
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
Location: include/linux/vmstat.h:200
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
In mm/show_mem.c (ffffffff813ddd3e)
Location: include/linux/vmstat.h:200
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
  - mm/show_mem.c:si_meminfo
  - mm/show_mem.c:si_mem_available
  - mm/show_mem.c:si_mem_available
```
```
In mm/swap_state.c (ffffffff8142b305)
Location: include/linux/vmstat.h:200
Inline: True
Inline callers:
  - mm/swap_state.c:show_swap_cache_info
```
```
In mm/memcontrol.c (ffffffff81486c7c)
Location: include/linux/vmstat.h:200
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
Location: include/linux/vmstat.h:200
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
Location: include/linux/vmstat.h:200
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
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a5ed14)
Location: include/linux/vmstat.h:200
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
In kernel/power/snapshot.c (ffffffff811a716f)
Location: include/linux/vmstat.h:200
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
```
```
In mm/oom_kill.c (ffffffff813c0765)
Location: include/linux/vmstat.h:200
Inline: True
Inline callers:
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
Location: include/linux/vmstat.h:200
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
In mm/show_mem.c (ffffffff81407b2e)
Location: include/linux/vmstat.h:200
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
  - mm/show_mem.c:si_meminfo
  - mm/show_mem.c:si_mem_available
  - mm/show_mem.c:si_mem_available
  - mm/show_mem.c:si_mem_available
```
```
In mm/swap_state.c (ffffffff81464af5)
Location: include/linux/vmstat.h:200
Inline: True
Inline callers:
  - mm/swap_state.c:show_swap_cache_info
```
```
In mm/memcontrol.c (ffffffff814b53fc)
Location: include/linux/vmstat.h:200
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
Location: include/linux/vmstat.h:200
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
Location: include/linux/vmstat.h:200
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
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81ab1474)
Location: include/linux/vmstat.h:200
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffff8000102b8ddc)
Location: include/linux/vmstat.h:187
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
In mm/page-writeback.c (ffff8000102bda1c)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
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
In mm/vmstat.c (ffff8000102da158)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
```
```
In mm/page_alloc.c (ffff800010319300)
Location: include/linux/vmstat.h:187
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
In fs/fs-writeback.c (ffff8000103ca578)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
```
```
In fs/proc/meminfo.c (ffff800010447c98)
Location: include/linux/vmstat.h:187
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
```
```
In drivers/virtio/virtio_balloon.c (ffff800010829920)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
In kernel/power/snapshot.c (c03c01cc)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
```
```
In mm/oom_kill.c (c04e55d8)
Location: include/linux/vmstat.h:187
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
In mm/page-writeback.c (c04e9d44)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:global_dirtyable_memory
  - mm/page-writeback.c:global_dirtyable_memory
```
```
In mm/vmscan.c (c04f1e2c)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/vmstat.c (c0500e88)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
  - mm/vmstat.c:zoneinfo_show_print
```
```
In mm/compaction.c (c050e504)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (c0513864)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
```
```
In mm/page_alloc.c (c0533d6c)
Location: include/linux/vmstat.h:187
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
In fs/fs-writeback.c (c05a6b84)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
```
```
In fs/proc/meminfo.c (c060cb80)
Location: include/linux/vmstat.h:187
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
```
```
In drivers/virtio/virtio_balloon.c (c0947b68)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
In mm/oom_kill.c (c000000000370f44)
Location: include/linux/vmstat.h:187
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
In mm/page-writeback.c (c0000000003766a4)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
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
In mm/vmstat.c (c00000000039a970)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
```
```
In mm/page_alloc.c (c0000000003ebdcc)
Location: include/linux/vmstat.h:187
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
In fs/fs-writeback.c (c0000000004cbed8)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
```
```
In fs/proc/meminfo.c (c00000000055e070)
Location: include/linux/vmstat.h:187
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
```
```
In drivers/virtio/virtio_balloon.c (c0000000008d7a4c)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
In mm/oom_kill.c (ffffffe0001dca14)
Location: include/linux/vmstat.h:187
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
In mm/page-writeback.c (ffffffe0001e05c8)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:global_dirty_limits
  - mm/page-writeback.c:global_dirty_limits
```
```
In mm/vmscan.c (ffffffe0001e7476)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/vmstat.c (ffffffe0001f4330)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
  - mm/vmstat.c:zoneinfo_show_print
```
```
In mm/compaction.c (ffffffe0001ff3ce)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffe0002039a2)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
```
```
In mm/page_alloc.c (ffffffe00021f01a)
Location: include/linux/vmstat.h:187
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
In fs/fs-writeback.c (ffffffe00028878a)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
```
```
In fs/proc/meminfo.c (ffffffe0002dd8b4)
Location: include/linux/vmstat.h:187
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
```
```
In drivers/virtio/virtio_balloon.c (ffffffe00052058e)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
In kernel/power/snapshot.c (ffffffff811057bf)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
```
```
In mm/oom_kill.c (ffffffff812230a2)
Location: include/linux/vmstat.h:187
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
In mm/page-writeback.c (ffffffff81226f61)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
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
In mm/vmstat.c (ffffffff8123f430)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
```
```
In mm/page_alloc.c (ffffffff8127b02f)
Location: include/linux/vmstat.h:187
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
In fs/fs-writeback.c (ffffffff8130ccc6)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
```
```
In fs/proc/meminfo.c (ffffffff81373ae1)
Location: include/linux/vmstat.h:187
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
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81626ab0)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
In kernel/power/snapshot.c (ffffffff810f6a5f)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
```
```
In mm/oom_kill.c (ffffffff81216252)
Location: include/linux/vmstat.h:187
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
In mm/page-writeback.c (ffffffff8121a0d1)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
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
In mm/vmstat.c (ffffffff81232430)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
```
```
In mm/page_alloc.c (ffffffff8126cf0f)
Location: include/linux/vmstat.h:187
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
In fs/fs-writeback.c (ffffffff812fd8e6)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
```
```
In fs/proc/meminfo.c (ffffffff813645b1)
Location: include/linux/vmstat.h:187
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
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8161b130)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
In kernel/power/snapshot.c (ffffffff81103a6f)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
```
```
In mm/oom_kill.c (ffffffff81220e42)
Location: include/linux/vmstat.h:187
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
In mm/page-writeback.c (ffffffff81224d01)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
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
In mm/vmstat.c (ffffffff8123d1d0)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
```
```
In mm/page_alloc.c (ffffffff81278dcf)
Location: include/linux/vmstat.h:187
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
In fs/fs-writeback.c (ffffffff8130aab6)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
```
```
In fs/proc/meminfo.c (ffffffff813715b1)
Location: include/linux/vmstat.h:187
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
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81654a80)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
In kernel/power/snapshot.c (ffffffff8110ee5f)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
```
```
In mm/oom_kill.c (ffffffff8122ffe0)
Location: include/linux/vmstat.h:187
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
In mm/page-writeback.c (ffffffff81233fd1)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
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
In mm/vmstat.c (ffffffff8124c900)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
```
```
In mm/page_alloc.c (ffffffff812889bf)
Location: include/linux/vmstat.h:187
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
In fs/fs-writeback.c (ffffffff8131c1e6)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:perf_trace_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
  - fs/fs-writeback.c:trace_event_raw_event_global_dirty_state
```
```
In fs/proc/meminfo.c (ffffffff81384f91)
Location: include/linux/vmstat.h:187
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
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8166f450)
Location: include/linux/vmstat.h:187
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
</details>
</li>
</ul>

## Differences
