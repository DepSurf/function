# Function: <code>bdi_dev_name</code>

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
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81314f26)
Location: include/linux/backing-dev.h:510
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_bdi_register
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages
  - fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit
  - fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io
  - fs/fs-writeback.c:trace_event_raw_event_wbc_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register
  - fs/fs-writeback.c:trace_event_raw_event_writeback_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_work_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_flush_foreign
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const char *bdi_dev_name(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81276510)
Location: mm/backing-dev.c:1036
Inline: False
Direct callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_bdi_register
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages
  - fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit
  - fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io
  - fs/fs-writeback.c:trace_event_raw_event_wbc_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register
  - fs/fs-writeback.c:trace_event_raw_event_writeback_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_work_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_flush_foreign
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:__blkg_prfill_u64
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
  - block/blk-wbt.c:trace_event_raw_event_wbt_timer
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_stat
```
**Symbols:**

```
ffffffff81276510-ffffffff8127653a: bdi_dev_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const char *bdi_dev_name(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81280e20)
Location: mm/backing-dev.c:905
Inline: False
Direct callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_bdi_register
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages
  - fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit
  - fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io
  - fs/fs-writeback.c:trace_event_raw_event_wbc_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register
  - fs/fs-writeback.c:trace_event_raw_event_writeback_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_work_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_flush_foreign
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:__blkg_prfill_u64
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
  - block/blk-wbt.c:trace_event_raw_event_wbt_timer
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_stat
```
**Symbols:**

```
ffffffff81280e20-ffffffff81280e4a: bdi_dev_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const char *bdi_dev_name(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81285f50)
Location: mm/backing-dev.c:904
Inline: False
Direct callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_bdi_register
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages
  - fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit
  - fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io
  - fs/fs-writeback.c:trace_event_raw_event_wbc_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register
  - fs/fs-writeback.c:trace_event_raw_event_writeback_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_work_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_flush_foreign
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:__blkg_prfill_u64
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
  - block/blk-wbt.c:trace_event_raw_event_wbt_timer
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_stat
```
**Symbols:**

```
ffffffff81285f50-ffffffff81285f7a: bdi_dev_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const char *bdi_dev_name(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff812c51a0)
Location: mm/backing-dev.c:987
Inline: False
Direct callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_bdi_register
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages
  - fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit
  - fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io
  - fs/fs-writeback.c:trace_event_raw_event_wbc_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register
  - fs/fs-writeback.c:trace_event_raw_event_writeback_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_work_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_flush_foreign
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
  - block/blk-cgroup.c:blkcg_print_one_stat
  - block/blk-cgroup.c:__blkg_prfill_u64
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
  - block/blk-wbt.c:trace_event_raw_event_wbt_timer
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_stat
```
**Symbols:**

```
ffffffff812c51a0-ffffffff812c51ca: bdi_dev_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const char *bdi_dev_name(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81322740)
Location: mm/backing-dev.c:993
Inline: False
Direct callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_bdi_register
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_folio_template
  - fs/fs-writeback.c:perf_trace_writeback_folio_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages
  - fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit
  - fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io
  - fs/fs-writeback.c:trace_event_raw_event_wbc_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register
  - fs/fs-writeback.c:trace_event_raw_event_writeback_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_work_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_flush_foreign
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_folio_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_folio_template
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:__blkg_prfill_u64
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
  - block/blk-wbt.c:trace_event_raw_event_wbt_timer
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_stat
```
**Symbols:**

```
ffffffff81322740-ffffffff81322776: bdi_dev_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const char *bdi_dev_name(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff813969c0)
Location: mm/backing-dev.c:1116
Inline: False
Direct callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_bdi_register
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_folio_template
  - fs/fs-writeback.c:perf_trace_writeback_folio_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages
  - fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit
  - fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io
  - fs/fs-writeback.c:trace_event_raw_event_wbc_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register
  - fs/fs-writeback.c:trace_event_raw_event_writeback_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_work_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_flush_foreign
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_folio_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_folio_template
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:__blkg_prfill_u64
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
  - block/blk-wbt.c:trace_event_raw_event_wbt_timer
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_stat
```
**Symbols:**

```
ffffffff813969c0-ffffffff813969f6: bdi_dev_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const char *bdi_dev_name(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff813c9900)
Location: mm/backing-dev.c:1129
Inline: False
Direct callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_bdi_register
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_folio_template
  - fs/fs-writeback.c:perf_trace_writeback_folio_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages
  - fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit
  - fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io
  - fs/fs-writeback.c:trace_event_raw_event_wbc_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register
  - fs/fs-writeback.c:trace_event_raw_event_writeback_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_work_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_flush_foreign
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_folio_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_folio_template
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:__blkg_prfill_u64
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
  - block/blk-wbt.c:trace_event_raw_event_wbt_timer
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_stat
```
**Symbols:**

```
ffffffff813c9900-ffffffff813c9936: bdi_dev_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const char *bdi_dev_name(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff813f4290)
Location: mm/backing-dev.c:1125
Inline: False
Direct callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_bdi_register
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_folio_template
  - fs/fs-writeback.c:perf_trace_writeback_folio_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages
  - fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit
  - fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io
  - fs/fs-writeback.c:trace_event_raw_event_wbc_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register
  - fs/fs-writeback.c:trace_event_raw_event_writeback_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_work_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_flush_foreign
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_folio_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_folio_template
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:__blkg_prfill_u64
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
  - block/blk-wbt.c:trace_event_raw_event_wbt_timer
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_stat
```
**Symbols:**

```
ffffffff813f4290-ffffffff813f42c6: bdi_dev_name (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffff8000103cb0ac)
Location: include/linux/backing-dev.h:510
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_bdi_register
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages
  - fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit
  - fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io
  - fs/fs-writeback.c:trace_event_raw_event_wbc_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register
  - fs/fs-writeback.c:trace_event_raw_event_writeback_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_work_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_flush_foreign
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (c05a74ac)
Location: include/linux/backing-dev.h:510
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_bdi_register
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages
  - fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit
  - fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io
  - fs/fs-writeback.c:trace_event_raw_event_wbc_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register
  - fs/fs-writeback.c:trace_event_raw_event_writeback_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_work_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_flush_foreign
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (c0000000004ccc34)
Location: include/linux/backing-dev.h:510
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_bdi_register
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages
  - fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit
  - fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io
  - fs/fs-writeback.c:trace_event_raw_event_wbc_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register
  - fs/fs-writeback.c:trace_event_raw_event_writeback_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_work_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_flush_foreign
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffe000289042)
Location: include/linux/backing-dev.h:510
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_bdi_register
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages
  - fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit
  - fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io
  - fs/fs-writeback.c:trace_event_raw_event_wbc_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register
  - fs/fs-writeback.c:trace_event_raw_event_writeback_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_work_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_flush_foreign
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8130d506)
Location: include/linux/backing-dev.h:510
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_bdi_register
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages
  - fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit
  - fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io
  - fs/fs-writeback.c:trace_event_raw_event_wbc_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register
  - fs/fs-writeback.c:trace_event_raw_event_writeback_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_work_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_flush_foreign
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812fe116)
Location: include/linux/backing-dev.h:510
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_bdi_register
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages
  - fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit
  - fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io
  - fs/fs-writeback.c:trace_event_raw_event_wbc_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register
  - fs/fs-writeback.c:trace_event_raw_event_writeback_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_work_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_flush_foreign
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8130b2f6)
Location: include/linux/backing-dev.h:510
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_bdi_register
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages
  - fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit
  - fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io
  - fs/fs-writeback.c:trace_event_raw_event_wbc_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register
  - fs/fs-writeback.c:trace_event_raw_event_writeback_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_work_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_flush_foreign
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8131cab6)
Location: include/linux/backing-dev.h:510
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_bdi_register
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_page_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages
  - fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit
  - fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io
  - fs/fs-writeback.c:trace_event_raw_event_wbc_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register
  - fs/fs-writeback.c:trace_event_raw_event_writeback_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_work_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_flush_foreign
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_page_template
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
