# Function: <code>global_zone_page_state</code>

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
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810e61d3)
Location: include/linux/vmstat.h:166
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:save_image_lzo
```
```
In mm/page_alloc.c (ffffffff826d7f9d)
Location: include/linux/vmstat.h:166
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
In mm/page-writeback.c (ffffffff811dd9e0)
Location: include/linux/vmstat.h:166
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:global_dirty_limits
```
```
In mm/util.c (ffffffff811f383c)
Location: include/linux/vmstat.h:166
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
```
```
In mm/vmstat.c (ffffffff811f4c19)
Location: include/linux/vmstat.h:166
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
```
```
In mm/mmap.c (ffffffff81213155)
Location: include/linux/vmstat.h:166
Inline: True
```
```
In fs/file_table.c (ffffffff826e0d68)
Location: include/linux/vmstat.h:166
Inline: True
Inline callers:
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/proc/meminfo.c (ffffffff812f6d98)
Location: include/linux/vmstat.h:166
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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810ee5eb)
Location: include/linux/vmstat.h:177
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:save_image_lzo
```
```
In mm/page_alloc.c (ffffffff82702446)
Location: include/linux/vmstat.h:177
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
In mm/page-writeback.c (ffffffff811fef71)
Location: include/linux/vmstat.h:177
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:global_dirty_limits
```
```
In mm/util.c (ffffffff81214b50)
Location: include/linux/vmstat.h:177
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
```
```
In mm/vmstat.c (ffffffff81215e91)
Location: include/linux/vmstat.h:177
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
```
```
In mm/mmap.c (ffffffff812341d5)
Location: include/linux/vmstat.h:177
Inline: True
```
```
In fs/file_table.c (ffffffff8270b294)
Location: include/linux/vmstat.h:177
Inline: True
Inline callers:
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/proc/meminfo.c (ffffffff81324133)
Location: include/linux/vmstat.h:177
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
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810f9c5b)
Location: include/linux/vmstat.h:177
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:save_image_lzo
```
```
In mm/page_alloc.c (ffffffff828b9b74)
Location: include/linux/vmstat.h:177
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
In mm/page-writeback.c (ffffffff8121182c)
Location: include/linux/vmstat.h:177
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:global_dirty_limits
```
```
In mm/util.c (ffffffff81227a30)
Location: include/linux/vmstat.h:177
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
```
```
In mm/vmstat.c (ffffffff81228d91)
Location: include/linux/vmstat.h:177
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
```
```
In mm/mmap.c (ffffffff81247985)
Location: include/linux/vmstat.h:177
Inline: True
```
```
In fs/file_table.c (ffffffff828c24b3)
Location: include/linux/vmstat.h:177
Inline: True
Inline callers:
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/proc/meminfo.c (ffffffff8133b2be)
Location: include/linux/vmstat.h:177
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
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff8110233f)
Location: include/linux/vmstat.h:177
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:save_image_lzo
```
```
In mm/page-writeback.c (ffffffff81220e4f)
Location: include/linux/vmstat.h:177
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:global_dirty_limits
```
```
In mm/vmstat.c (ffffffff81238a76)
Location: include/linux/vmstat.h:177
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
```
```
In mm/mmap.c (ffffffff81259ab5)
Location: include/linux/vmstat.h:177
Inline: True
```
```
In mm/page_alloc.c (ffffffff828d6c8d)
Location: include/linux/vmstat.h:177
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
In fs/file_table.c (ffffffff828db881)
Location: include/linux/vmstat.h:177
Inline: True
Inline callers:
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/proc/meminfo.c (ffffffff8136347d)
Location: include/linux/vmstat.h:177
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
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff8110e750)
Location: include/linux/vmstat.h:177
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:save_image_lzo
```
```
In mm/page-writeback.c (ffffffff8122e8ff)
Location: include/linux/vmstat.h:177
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:global_dirty_limits
```
```
In mm/vmstat.c (ffffffff81246d66)
Location: include/linux/vmstat.h:177
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
```
```
In mm/mmap.c (ffffffff81267f65)
Location: include/linux/vmstat.h:177
Inline: True
```
```
In mm/page_alloc.c (ffffffff828df11e)
Location: include/linux/vmstat.h:177
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
In fs/file_table.c (ffffffff828e3cb7)
Location: include/linux/vmstat.h:177
Inline: True
Inline callers:
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/proc/meminfo.c (ffffffff8137b6dd)
Location: include/linux/vmstat.h:177
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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff811197db)
Location: include/linux/vmstat.h:185
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:swap_write_page
  - kernel/power/swap.c:swap_write_page
  - kernel/power/swap.c:get_swap_writer
```
```
In mm/page-writeback.c (ffffffff8125baef)
Location: include/linux/vmstat.h:185
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:global_dirty_limits
```
```
In mm/vmstat.c (ffffffff8127496c)
Location: include/linux/vmstat.h:185
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
```
```
In mm/mmap.c (ffffffff81298a05)
Location: include/linux/vmstat.h:185
Inline: True
Inline callers:
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
```
```
In mm/page_alloc.c (ffffffff82cfc507)
Location: include/linux/vmstat.h:185
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
In fs/file_table.c (ffffffff82d007f8)
Location: include/linux/vmstat.h:185
Inline: True
Inline callers:
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/proc/meminfo.c (ffffffff813c4b89)
Location: include/linux/vmstat.h:185
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
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
In kernel/power/swap.c (ffffffff81115024)
Location: include/linux/vmstat.h:186
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:swap_write_page
  - kernel/power/swap.c:swap_write_page
```
```
In mm/page-writeback.c (ffffffff81265f0f)
Location: include/linux/vmstat.h:186
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:global_dirty_limits
```
```
In mm/vmstat.c (ffffffff8127f1bc)
Location: include/linux/vmstat.h:186
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
```
```
In mm/mmap.c (ffffffff812a3b85)
Location: include/linux/vmstat.h:186
Inline: True
Inline callers:
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
```
```
In mm/page_alloc.c (ffffffff82fe8f22)
Location: include/linux/vmstat.h:186
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_mem_available
```
```
In fs/file_table.c (ffffffff82fed1bd)
Location: include/linux/vmstat.h:186
Inline: True
Inline callers:
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/proc/meminfo.c (ffffffff813d6adf)
Location: include/linux/vmstat.h:186
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
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
In kernel/power/swap.c (ffffffff81115997)
Location: include/linux/vmstat.h:186
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:swap_write_page
  - kernel/power/swap.c:swap_write_page
```
```
In mm/page-writeback.c (ffffffff8126a9f8)
Location: include/linux/vmstat.h:186
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:global_dirty_limits
```
```
In mm/vmstat.c (ffffffff81284303)
Location: include/linux/vmstat.h:186
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
```
```
In mm/mmap.c (ffffffff812a9395)
Location: include/linux/vmstat.h:186
Inline: True
Inline callers:
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
```
```
In mm/page_alloc.c (ffffffff831f3766)
Location: include/linux/vmstat.h:186
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_mem_available
```
```
In fs/file_table.c (ffffffff831f79ee)
Location: include/linux/vmstat.h:186
Inline: True
Inline callers:
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/proc/meminfo.c (ffffffff813dd9df)
Location: include/linux/vmstat.h:186
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
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
In kernel/power/swap.c (ffffffff81135bc8)
Location: include/linux/vmstat.h:179
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:swap_write_page
  - kernel/power/swap.c:swap_write_page
```
```
In mm/page-writeback.c (ffffffff812a76a8)
Location: include/linux/vmstat.h:179
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:global_dirty_limits
```
```
In mm/vmstat.c (ffffffff812c4683)
Location: include/linux/vmstat.h:179
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
```
```
In mm/mmap.c (ffffffff812eaa05)
Location: include/linux/vmstat.h:179
Inline: True
Inline callers:
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
```
```
In mm/page_alloc.c (ffffffff832d99a2)
Location: include/linux/vmstat.h:179
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_mem_available
```
```
In fs/file_table.c (ffffffff832de930)
Location: include/linux/vmstat.h:179
Inline: True
Inline callers:
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/proc/meminfo.c (ffffffff8142f195)
Location: include/linux/vmstat.h:179
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
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
In kernel/power/swap.c (ffffffff81157fbd)
Location: include/linux/vmstat.h:179
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:swap_write_page
  - kernel/power/swap.c:swap_write_page
```
```
In mm/page-writeback.c (ffffffff812ffcc8)
Location: include/linux/vmstat.h:179
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:global_dirty_limits
```
```
In mm/vmstat.c (ffffffff81321293)
Location: include/linux/vmstat.h:179
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
```
```
In mm/mmap.c (ffffffff8134d805)
Location: include/linux/vmstat.h:179
Inline: True
Inline callers:
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
```
```
In mm/page_alloc.c (ffffffff8348e949)
Location: include/linux/vmstat.h:179
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_mem_available
```
```
In fs/file_table.c (ffffffff8349426b)
Location: include/linux/vmstat.h:179
Inline: True
Inline callers:
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/proc/meminfo.c (ffffffff814a8da7)
Location: include/linux/vmstat.h:179
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
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
In kernel/power/swap.c (ffffffff8118905d)
Location: include/linux/vmstat.h:173
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:swap_write_page
  - kernel/power/swap.c:swap_write_page
```
```
In mm/page-writeback.c (ffffffff8136a5c8)
Location: include/linux/vmstat.h:173
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:bdi_set_max_bytes
  - mm/page-writeback.c:bdi_set_min_bytes
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:global_dirty_limits
```
```
In mm/vmstat.c (ffffffff81395253)
Location: include/linux/vmstat.h:173
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
```
```
In mm/mmap.c (ffffffff813c69f5)
Location: include/linux/vmstat.h:173
Inline: True
Inline callers:
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
```
```
In mm/page_alloc.c (ffffffff83ec0ba4)
Location: include/linux/vmstat.h:173
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:si_meminfo
  - mm/page_alloc.c:si_mem_available
```
```
In fs/file_table.c (ffffffff83ec887c)
Location: include/linux/vmstat.h:173
Inline: True
Inline callers:
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/proc/meminfo.c (ffffffff8153e817)
Location: include/linux/vmstat.h:173
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
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
In kernel/power/swap.c (ffffffff8119a222)
Location: include/linux/vmstat.h:179
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:swap_write_page
  - kernel/power/swap.c:swap_write_page
```
```
In mm/page-writeback.c (ffffffff8139c758)
Location: include/linux/vmstat.h:179
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:bdi_set_max_bytes
  - mm/page-writeback.c:bdi_set_min_bytes
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:global_dirty_limits
```
```
In mm/vmstat.c (ffffffff813c7e73)
Location: include/linux/vmstat.h:179
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
```
```
In mm/mm_init.c (ffffffff836e317e)
Location: include/linux/vmstat.h:179
Inline: True
Inline callers:
  - mm/mm_init.c:mm_core_init
```
```
In mm/show_mem.c (ffffffff813ddd30)
Location: include/linux/vmstat.h:179
Inline: True
Inline callers:
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:si_meminfo
  - mm/show_mem.c:si_mem_available
```
```
In mm/mmap.c (ffffffff813fae95)
Location: include/linux/vmstat.h:179
Inline: True
Inline callers:
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
```
```
In fs/file_table.c (ffffffff836ed8ec)
Location: include/linux/vmstat.h:179
Inline: True
Inline callers:
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/proc/meminfo.c (ffffffff81576ae7)
Location: include/linux/vmstat.h:179
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
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
In kernel/power/swap.c (ffffffff811a929d)
Location: include/linux/vmstat.h:179
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:swap_write_page
  - kernel/power/swap.c:swap_write_page
```
```
In mm/page-writeback.c (ffffffff813c6438)
Location: include/linux/vmstat.h:179
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:bdi_set_max_bytes
  - mm/page-writeback.c:bdi_set_min_bytes
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:global_dirty_limits
```
```
In mm/vmstat.c (ffffffff813f2882)
Location: include/linux/vmstat.h:179
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
```
```
In mm/mm_init.c (ffffffff83915a0e)
Location: include/linux/vmstat.h:179
Inline: True
Inline callers:
  - mm/mm_init.c:mm_core_init
```
```
In mm/show_mem.c (ffffffff81407b20)
Location: include/linux/vmstat.h:179
Inline: True
Inline callers:
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:si_meminfo
  - mm/show_mem.c:si_mem_available
```
```
In mm/mmap.c (ffffffff81426ae5)
Location: include/linux/vmstat.h:179
Inline: True
Inline callers:
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
  - mm/mmap.c:reserve_mem_notifier
```
```
In fs/file_table.c (ffffffff8392094c)
Location: include/linux/vmstat.h:179
Inline: True
Inline callers:
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/proc/meminfo.c (ffffffff815af437)
Location: include/linux/vmstat.h:179
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
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
In mm/page-writeback.c (ffff8000102bda1c)
Location: include/linux/vmstat.h:177
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:global_dirty_limits
```
```
In mm/vmstat.c (ffff8000102da108)
Location: include/linux/vmstat.h:177
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
```
```
In mm/mmap.c (ffff8000102ff230)
Location: include/linux/vmstat.h:177
Inline: True
```
```
In mm/page_alloc.c (ffff800011457e94)
Location: include/linux/vmstat.h:177
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
In fs/file_table.c (ffff80001145d2c4)
Location: include/linux/vmstat.h:177
Inline: True
Inline callers:
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/proc/meminfo.c (ffff800010447e38)
Location: include/linux/vmstat.h:177
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
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (c03c1658)
Location: include/linux/vmstat.h:177
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:save_image_lzo
```
```
In mm/page-writeback.c (c04e6124)
Location: include/linux/vmstat.h:177
Inline: True
Inline callers:
  - mm/page-writeback.c:global_dirtyable_memory
```
```
In mm/vmscan.c (c04f3538)
Location: include/linux/vmstat.h:177
Inline: True
Inline callers:
  - mm/vmscan.c:get_scan_count
```
```
In mm/vmstat.c (c0500e68)
Location: include/linux/vmstat.h:177
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
```
```
In mm/mmap.c (c051dfb8)
Location: include/linux/vmstat.h:177
Inline: True
Inline callers:
  - mm/mmap.c:init_admin_reserve
  - mm/mmap.c:init_user_reserve
```
```
In mm/page_alloc.c (c1531e40)
Location: include/linux/vmstat.h:177
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
In fs/file_table.c (c15357b0)
Location: include/linux/vmstat.h:177
Inline: True
Inline callers:
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/proc/meminfo.c (c060cd18)
Location: include/linux/vmstat.h:177
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
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (c000000000376684)
Location: include/linux/vmstat.h:177
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:global_dirty_limits
```
```
In mm/vmstat.c (c00000000039a8f0)
Location: include/linux/vmstat.h:177
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
```
```
In mm/mmap.c (c0000000003cada0)
Location: include/linux/vmstat.h:177
Inline: True
```
```
In mm/page_alloc.c (c000000001381638)
Location: include/linux/vmstat.h:177
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
In fs/file_table.c (c000000001387ac4)
Location: include/linux/vmstat.h:177
Inline: True
Inline callers:
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/proc/meminfo.c (c00000000055e228)
Location: include/linux/vmstat.h:177
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
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffe0001e05c8)
Location: include/linux/vmstat.h:177
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:global_dirty_limits
```
```
In mm/vmscan.c (ffffffe0001e89a2)
Location: include/linux/vmstat.h:177
Inline: True
Inline callers:
  - mm/vmscan.c:get_scan_count
```
```
In mm/vmstat.c (ffffffe0001f4306)
Location: include/linux/vmstat.h:177
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
```
```
In mm/mmap.c (ffffffe00020d22a)
Location: include/linux/vmstat.h:177
Inline: True
Inline callers:
  - mm/mmap.c:init_admin_reserve
  - mm/mmap.c:init_user_reserve
```
```
In mm/page_alloc.c (ffffffe0000167c6)
Location: include/linux/vmstat.h:177
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
In fs/file_table.c (ffffffe00001a264)
Location: include/linux/vmstat.h:177
Inline: True
Inline callers:
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/proc/meminfo.c (ffffffe0002dda6c)
Location: include/linux/vmstat.h:177
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
In kernel/power/swap.c (ffffffff81106d28)
Location: include/linux/vmstat.h:177
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
```
```
In mm/page-writeback.c (ffffffff81226f4f)
Location: include/linux/vmstat.h:177
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:global_dirty_limits
```
```
In mm/vmstat.c (ffffffff8123f3b6)
Location: include/linux/vmstat.h:177
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
```
```
In mm/mmap.c (ffffffff812605b5)
Location: include/linux/vmstat.h:177
Inline: True
```
```
In mm/page_alloc.c (ffffffff828c7fd2)
Location: include/linux/vmstat.h:177
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
In fs/file_table.c (ffffffff828ccb6b)
Location: include/linux/vmstat.h:177
Inline: True
Inline callers:
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/proc/meminfo.c (ffffffff81373cbd)
Location: include/linux/vmstat.h:177
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
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810f7c10)
Location: include/linux/vmstat.h:177
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:save_image_lzo
```
```
In mm/page-writeback.c (ffffffff8121a0bf)
Location: include/linux/vmstat.h:177
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:global_dirty_limits
```
```
In mm/vmstat.c (ffffffff812323b6)
Location: include/linux/vmstat.h:177
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
```
```
In mm/mmap.c (ffffffff812529d5)
Location: include/linux/vmstat.h:177
Inline: True
```
```
In mm/page_alloc.c (ffffffff828c06f7)
Location: include/linux/vmstat.h:177
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
In fs/file_table.c (ffffffff828c5287)
Location: include/linux/vmstat.h:177
Inline: True
Inline callers:
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/proc/meminfo.c (ffffffff8136478d)
Location: include/linux/vmstat.h:177
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
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff81104c20)
Location: include/linux/vmstat.h:177
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:save_image_lzo
```
```
In mm/page-writeback.c (ffffffff81224cef)
Location: include/linux/vmstat.h:177
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:global_dirty_limits
```
```
In mm/vmstat.c (ffffffff8123d156)
Location: include/linux/vmstat.h:177
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
```
```
In mm/mmap.c (ffffffff8125e355)
Location: include/linux/vmstat.h:177
Inline: True
```
```
In mm/page_alloc.c (ffffffff828dad52)
Location: include/linux/vmstat.h:177
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
In fs/file_table.c (ffffffff828df8eb)
Location: include/linux/vmstat.h:177
Inline: True
Inline callers:
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/proc/meminfo.c (ffffffff8137178d)
Location: include/linux/vmstat.h:177
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
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff81110000)
Location: include/linux/vmstat.h:177
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:save_image_lzo
```
```
In mm/page-writeback.c (ffffffff81233fbf)
Location: include/linux/vmstat.h:177
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_over_bg_thresh
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:global_dirty_limits
```
```
In mm/vmstat.c (ffffffff8124c886)
Location: include/linux/vmstat.h:177
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
```
```
In mm/mmap.c (ffffffff8126dd35)
Location: include/linux/vmstat.h:177
Inline: True
```
```
In mm/page_alloc.c (ffffffff828e0173)
Location: include/linux/vmstat.h:177
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
In fs/file_table.c (ffffffff828e4d02)
Location: include/linux/vmstat.h:177
Inline: True
Inline callers:
  - fs/file_table.c:files_maxfiles_init
```
```
In fs/proc/meminfo.c (ffffffff8138516d)
Location: include/linux/vmstat.h:177
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
</ul>

## Differences
