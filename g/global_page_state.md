# Function: <code>global_page_state</code>

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
In kernel/power/snapshot.c (ffffffff810d1822)
Location: include/linux/vmstat.h:120
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
In kernel/power/swap.c (ffffffff810d3610)
Location: include/linux/vmstat.h:120
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:swsusp_write
```
```
In mm/page_alloc.c (ffffffff81191bea)
Location: include/linux/vmstat.h:120
Inline: True
Inline callers:
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_meminfo
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
  - mm/page_alloc.c:mem_init_print_info
```
```
In mm/page-writeback.c (ffffffff81199869)
Location: include/linux/vmstat.h:120
Inline: True
Inline callers:
  - mm/page-writeback.c:global_dirty_limits
  - mm/page-writeback.c:global_dirty_limits
  - mm/page-writeback.c:global_dirty_limits
  - mm/page-writeback.c:zone_dirty_ok
  - mm/page-writeback.c:zone_dirty_ok
  - mm/page-writeback.c:zone_dirty_ok
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:throttle_vm_writeout
  - mm/page-writeback.c:throttle_vm_writeout
  - mm/page-writeback.c:laptop_mode_timer_fn
  - mm/page-writeback.c:laptop_mode_timer_fn
```
```
In mm/vmstat.c (ffffffff811acef9)
Location: include/linux/vmstat.h:120
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
```
```
In mm/mmap.c (ffffffff811c3f55)
Location: include/linux/vmstat.h:120
Inline: True
Inline callers:
  - mm/mmap.c:__vm_enough_memory
  - mm/mmap.c:__vm_enough_memory
  - mm/mmap.c:__vm_enough_memory
  - mm/mmap.c:__vm_enough_memory
```
```
In fs/file_table.c (ffffffff81f8e921)
Location: include/linux/vmstat.h:120
Inline: True
Inline callers:
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/fs-writeback.c (ffffffff81235fc5)
Location: include/linux/vmstat.h:120
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
In fs/proc/meminfo.c (ffffffff8128265e)
Location: include/linux/vmstat.h:120
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
In kernel/power/snapshot.c (ffffffff810d659f)
Location: include/linux/vmstat.h:127
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
```
```
In kernel/power/swap.c (ffffffff810d83b9)
Location: include/linux/vmstat.h:127
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:save_image_lzo
```
```
In mm/page_alloc.c (ffffffff81fb109c)
Location: include/linux/vmstat.h:127
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
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
In mm/page-writeback.c (ffffffff811b0370)
Location: include/linux/vmstat.h:127
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:global_dirty_limits
```
```
In mm/util.c (ffffffff811c4e5c)
Location: include/linux/vmstat.h:127
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
```
```
In mm/vmstat.c (ffffffff811c6152)
Location: include/linux/vmstat.h:127
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
```
```
In mm/mmap.c (ffffffff811dfe15)
Location: include/linux/vmstat.h:127
Inline: True
```
```
In fs/file_table.c (ffffffff81fb8f18)
Location: include/linux/vmstat.h:127
Inline: True
Inline callers:
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/proc/meminfo.c (ffffffff812af76d)
Location: include/linux/vmstat.h:127
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
In kernel/power/snapshot.c (ffffffff810dd10f)
Location: include/linux/vmstat.h:127
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
```
```
In kernel/power/swap.c (ffffffff810dee97)
Location: include/linux/vmstat.h:127
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:save_image_lzo
```
```
In mm/page_alloc.c (ffffffff81fed942)
Location: include/linux/vmstat.h:127
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
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
In mm/page-writeback.c (ffffffff811c0a30)
Location: include/linux/vmstat.h:127
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:global_dirty_limits
```
```
In mm/util.c (ffffffff811d4f6c)
Location: include/linux/vmstat.h:127
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
  - mm/util.c:__vm_enough_memory
```
```
In mm/vmstat.c (ffffffff811d629f)
Location: include/linux/vmstat.h:127
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
```
```
In mm/mmap.c (ffffffff811efd65)
Location: include/linux/vmstat.h:127
Inline: True
```
```
In fs/file_table.c (ffffffff81ff5889)
Location: include/linux/vmstat.h:127
Inline: True
Inline callers:
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/proc/meminfo.c (ffffffff812c5318)
Location: include/linux/vmstat.h:127
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
In kernel/power/swap.c (ffffffff810ddf63)
Location: include/linux/vmstat.h:126
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:save_image_lzo
```
```
In mm/page_alloc.c (ffffffff820cf57d)
Location: include/linux/vmstat.h:126
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_mem_available
```
```
In mm/page-writeback.c (ffffffff811c8b80)
Location: include/linux/vmstat.h:126
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:global_dirty_limits
```
```
In mm/util.c (ffffffff811dddbc)
Location: include/linux/vmstat.h:126
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
```
```
In mm/vmstat.c (ffffffff811defc9)
Location: include/linux/vmstat.h:126
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
```
```
In mm/mmap.c (ffffffff811fac45)
Location: include/linux/vmstat.h:126
Inline: True
```
```
In fs/file_table.c (ffffffff820d806b)
Location: include/linux/vmstat.h:126
Inline: True
Inline callers:
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/proc/meminfo.c (ffffffff812d2558)
Location: include/linux/vmstat.h:126
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
```
</details>
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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
