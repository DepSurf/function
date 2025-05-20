# Function: <code>kernfs_ino</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81170ac7)
Location: include/linux/kernfs.h:310
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_setup_root
```
```
In mm/memcontrol.c (ffffffff812fa1c1)
Location: include/linux/kernfs.h:310
Inline: True
Inline callers:
  - mm/memcontrol.c:page_cgroup_ino
```
```
In fs/fs-writeback.c (ffffffff81349ca8)
Location: include/linux/kernfs.h:310
Inline: True
Inline callers:
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages
  - fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit
  - fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io
  - fs/fs-writeback.c:trace_event_raw_event_wbc_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_work_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_flush_foreign
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs
  - fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
```
```
In fs/kernfs/inode.c (ffffffff813cd7d5)
Location: include/linux/kernfs.h:310
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_get_inode
```
```
In fs/kernfs/dir.c (ffffffff813ceb8c)
Location: include/linux/kernfs.h:310
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_id
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/kernfs/file.c (ffffffff813d0c0a)
Location: include/linux/kernfs.h:310
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
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
In kernel/cgroup/cgroup.c (ffffffff811728a7)
Location: include/linux/kernfs.h:310
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_setup_root
```
```
In mm/memcontrol.c (ffffffff81305fe8)
Location: include/linux/kernfs.h:310
Inline: True
Inline callers:
  - mm/memcontrol.c:page_cgroup_ino
```
```
In fs/fs-writeback.c (ffffffff81356ba8)
Location: include/linux/kernfs.h:310
Inline: True
Inline callers:
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages
  - fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit
  - fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io
  - fs/fs-writeback.c:trace_event_raw_event_wbc_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_work_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_flush_foreign
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs
  - fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
```
```
In fs/kernfs/inode.c (ffffffff813df405)
Location: include/linux/kernfs.h:310
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_get_inode
```
```
In fs/kernfs/dir.c (ffffffff813e07bc)
Location: include/linux/kernfs.h:310
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_id
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/kernfs/file.c (ffffffff813e28a4)
Location: include/linux/kernfs.h:310
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
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
In kernel/cgroup/cgroup.c (ffffffff81173497)
Location: include/linux/kernfs.h:310
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_setup_root
```
```
In mm/memcontrol.c (ffffffff8130c497)
Location: include/linux/kernfs.h:310
Inline: True
Inline callers:
  - mm/memcontrol.c:page_cgroup_ino
```
```
In fs/fs-writeback.c (ffffffff8135d5d8)
Location: include/linux/kernfs.h:310
Inline: True
Inline callers:
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages
  - fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit
  - fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io
  - fs/fs-writeback.c:trace_event_raw_event_wbc_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_work_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_flush_foreign
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs
  - fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
```
```
In fs/kernfs/inode.c (ffffffff813e5fd5)
Location: include/linux/kernfs.h:310
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_get_inode
```
```
In fs/kernfs/dir.c (ffffffff813e72e1)
Location: include/linux/kernfs.h:310
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_id
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/kernfs/file.c (ffffffff813e94b4)
Location: include/linux/kernfs.h:310
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
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
In kernel/cgroup/cgroup.c (ffffffff8119a447)
Location: include/linux/kernfs.h:315
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_setup_root
```
```
In mm/memcontrol.c (ffffffff81356367)
Location: include/linux/kernfs.h:315
Inline: True
Inline callers:
  - mm/memcontrol.c:page_cgroup_ino
```
```
In fs/fs-writeback.c (ffffffff813ab9bb)
Location: include/linux/kernfs.h:315
Inline: True
Inline callers:
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages
  - fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit
  - fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io
  - fs/fs-writeback.c:trace_event_raw_event_wbc_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_work_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_flush_foreign
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs
  - fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
```
```
In fs/kernfs/inode.c (ffffffff81437bd5)
Location: include/linux/kernfs.h:315
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_get_inode
```
```
In fs/kernfs/dir.c (ffffffff81438e97)
Location: include/linux/kernfs.h:315
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_id
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/kernfs/file.c (ffffffff8143b214)
Location: include/linux/kernfs.h:315
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
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
In kernel/cgroup/cgroup.c (ffffffff811ca557)
Location: include/linux/kernfs.h:299
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_setup_root
```
```
In mm/memcontrol.c (ffffffff813cef32)
Location: include/linux/kernfs.h:299
Inline: True
Inline callers:
  - mm/memcontrol.c:page_cgroup_ino
```
```
In fs/fs-writeback.c (ffffffff8142f121)
Location: include/linux/kernfs.h:299
Inline: True
Inline callers:
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages
  - fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit
  - fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io
  - fs/fs-writeback.c:trace_event_raw_event_wbc_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_work_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_flush_foreign
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs
  - fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
```
```
In fs/kernfs/inode.c (ffffffff814b2935)
Location: include/linux/kernfs.h:299
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_get_inode
```
```
In fs/kernfs/dir.c (ffffffff814b3fae)
Location: include/linux/kernfs.h:299
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_id
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/kernfs/file.c (ffffffff814b5c42)
Location: include/linux/kernfs.h:299
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
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
In kernel/sched/build_utility.c (ffffffff8117ad8e)
Location: include/linux/kernfs.h:358
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_cgroup_alloc
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_change
```
```
In kernel/cgroup/cgroup.c (ffffffff8120d732)
Location: include/linux/kernfs.h:358
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_show
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_setup_root
```
```
In mm/memcontrol.c (ffffffff81454082)
Location: include/linux/kernfs.h:358
Inline: True
Inline callers:
  - mm/memcontrol.c:page_cgroup_ino
```
```
In fs/fs-writeback.c (ffffffff814bcb5e)
Location: include/linux/kernfs.h:358
Inline: True
Inline callers:
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages
  - fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit
  - fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io
  - fs/fs-writeback.c:trace_event_raw_event_wbc_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_work_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_flush_foreign
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs
  - fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
```
```
In fs/kernfs/inode.c (ffffffff81549515)
Location: include/linux/kernfs.h:358
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_get_inode
```
```
In fs/kernfs/dir.c (ffffffff8154ad9d)
Location: include/linux/kernfs.h:358
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_id
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/kernfs/file.c (ffffffff8154cdd2)
Location: include/linux/kernfs.h:358
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
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
In kernel/sched/build_utility.c (ffffffff8118b8fe)
Location: include/linux/kernfs.h:358
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_cgroup_alloc
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_change
```
```
In kernel/cgroup/cgroup.c (ffffffff81223122)
Location: include/linux/kernfs.h:358
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_show
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_setup_root
```
```
In mm/memcontrol.c (ffffffff81489df0)
Location: include/linux/kernfs.h:358
Inline: True
Inline callers:
  - mm/memcontrol.c:page_cgroup_ino
```
```
In fs/fs-writeback.c (ffffffff814f1c7b)
Location: include/linux/kernfs.h:358
Inline: True
Inline callers:
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages
  - fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit
  - fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io
  - fs/fs-writeback.c:trace_event_raw_event_wbc_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_work_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_flush_foreign
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs
  - fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
```
```
In fs/kernfs/inode.c (ffffffff815810f5)
Location: include/linux/kernfs.h:358
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_get_inode
```
```
In fs/kernfs/dir.c (ffffffff815829f0)
Location: include/linux/kernfs.h:358
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_id
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/kernfs/file.c (ffffffff81584aa5)
Location: include/linux/kernfs.h:358
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
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
In kernel/sched/build_utility.c (ffffffff8119a25d)
Location: include/linux/kernfs.h:359
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_cgroup_alloc
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_change
```
```
In kernel/cgroup/cgroup.c (ffffffff8123ae12)
Location: include/linux/kernfs.h:359
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_show
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_setup_root
```
```
In mm/memcontrol.c (ffffffff814b95d0)
Location: include/linux/kernfs.h:359
Inline: True
Inline callers:
  - mm/memcontrol.c:page_cgroup_ino
```
```
In fs/fs-writeback.c (ffffffff8152638b)
Location: include/linux/kernfs.h:359
Inline: True
Inline callers:
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_flush_foreign
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_switch_wbs
  - fs/fs-writeback.c:perf_trace_inode_foreign_history
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages
  - fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit
  - fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io
  - fs/fs-writeback.c:trace_event_raw_event_wbc_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_work_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_flush_foreign
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs
  - fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs
  - fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history
```
```
In fs/kernfs/inode.c (ffffffff815b9ba5)
Location: include/linux/kernfs.h:359
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_get_inode
```
```
In fs/kernfs/dir.c (ffffffff815bb620)
Location: include/linux/kernfs.h:359
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_id
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In fs/kernfs/file.c (ffffffff815bd4f5)
Location: include/linux/kernfs.h:359
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
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
