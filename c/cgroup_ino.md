# Function: <code>cgroup_ino</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff811fc7e2)
Location: include/linux/cgroup.h:486
Inline: True
Inline callers:
  - mm/memcontrol.c:page_cgroup_ino
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812203f6)
Location: include/linux/cgroup.h:507
Inline: True
Inline callers:
  - mm/memcontrol.c:page_cgroup_ino
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81232a86)
Location: include/linux/cgroup.h:524
Inline: True
Inline callers:
  - mm/memcontrol.c:page_cgroup_ino
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8123e298)
Location: include/linux/cgroup.h:544
Inline: True
Inline callers:
  - mm/memcontrol.c:page_cgroup_ino
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8125de38)
Location: include/linux/cgroup.h:581
Inline: True
Inline callers:
  - mm/memcontrol.c:page_cgroup_ino
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812820c6)
Location: include/linux/cgroup.h:581
Inline: True
Inline callers:
  - mm/memcontrol.c:page_cgroup_ino
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812962a6)
Location: include/linux/cgroup.h:604
Inline: True
Inline callers:
  - mm/memcontrol.c:page_cgroup_ino
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b25f3)
Location: include/linux/cgroup.h:617
Inline: True
Inline callers:
  - mm/memcontrol.c:page_cgroup_ino
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c4031)
Location: include/linux/cgroup.h:619
Inline: True
Inline callers:
  - mm/memcontrol.c:page_cgroup_ino
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
In kernel/cgroup/cgroup.c (ffffffff81170ac7)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_setup_root
```
```
In mm/memcontrol.c (ffffffff812fa1c1)
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - mm/memcontrol.c:page_cgroup_ino
```
```
In fs/fs-writeback.c (ffffffff81349ca8)
Location: include/linux/cgroup.h:625
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
Location: include/linux/cgroup.h:625
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
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - mm/memcontrol.c:page_cgroup_ino
```
```
In fs/fs-writeback.c (ffffffff81356ba8)
Location: include/linux/cgroup.h:625
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
Location: include/linux/cgroup.h:625
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
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - mm/memcontrol.c:page_cgroup_ino
```
```
In fs/fs-writeback.c (ffffffff8135d5d8)
Location: include/linux/cgroup.h:625
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
Location: include/linux/cgroup.h:625
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
Location: include/linux/cgroup.h:625
Inline: True
Inline callers:
  - mm/memcontrol.c:page_cgroup_ino
```
```
In fs/fs-writeback.c (ffffffff813ab9bb)
Location: include/linux/cgroup.h:625
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
Location: include/linux/cgroup.h:626
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
Location: include/linux/cgroup.h:626
Inline: True
Inline callers:
  - mm/memcontrol.c:page_cgroup_ino
```
```
In fs/fs-writeback.c (ffffffff8142f121)
Location: include/linux/cgroup.h:626
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
Location: include/linux/cgroup.h:566
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_cgroup_alloc
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_change
```
```
In kernel/cgroup/cgroup.c (ffffffff8120d732)
Location: include/linux/cgroup.h:566
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
Location: include/linux/cgroup.h:566
Inline: True
Inline callers:
  - mm/memcontrol.c:page_cgroup_ino
```
```
In fs/fs-writeback.c (ffffffff814bcb5e)
Location: include/linux/cgroup.h:566
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
Location: include/linux/cgroup.h:565
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_cgroup_alloc
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_change
```
```
In kernel/cgroup/cgroup.c (ffffffff81223122)
Location: include/linux/cgroup.h:565
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
Location: include/linux/cgroup.h:565
Inline: True
Inline callers:
  - mm/memcontrol.c:page_cgroup_ino
```
```
In fs/fs-writeback.c (ffffffff814f1c7b)
Location: include/linux/cgroup.h:565
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
Location: include/linux/cgroup.h:563
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_cgroup_alloc
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_change
```
```
In kernel/cgroup/cgroup.c (ffffffff8123ae12)
Location: include/linux/cgroup.h:563
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
Location: include/linux/cgroup.h:563
Inline: True
Inline callers:
  - mm/memcontrol.c:page_cgroup_ino
```
```
In fs/fs-writeback.c (ffffffff8152638b)
Location: include/linux/cgroup.h:563
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
In mm/memcontrol.c (ffff800010366b38)
Location: include/linux/cgroup.h:619
Inline: True
Inline callers:
  - mm/memcontrol.c:page_cgroup_ino
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
In mm/memcontrol.c (c0558308)
Location: include/linux/cgroup.h:619
Inline: True
Inline callers:
  - mm/memcontrol.c:page_cgroup_ino
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
In mm/memcontrol.c (c000000000453e90)
Location: include/linux/cgroup.h:619
Inline: True
Inline callers:
  - mm/memcontrol.c:page_cgroup_ino
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
In mm/memcontrol.c (ffffffe000244e5e)
Location: include/linux/cgroup.h:619
Inline: True
Inline callers:
  - mm/memcontrol.c:page_cgroup_ino
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
In mm/memcontrol.c (ffffffff812bc611)
Location: include/linux/cgroup.h:619
Inline: True
Inline callers:
  - mm/memcontrol.c:page_cgroup_ino
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
In mm/memcontrol.c (ffffffff812ad771)
Location: include/linux/cgroup.h:619
Inline: True
Inline callers:
  - mm/memcontrol.c:page_cgroup_ino
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
In mm/memcontrol.c (ffffffff812ba421)
Location: include/linux/cgroup.h:619
Inline: True
Inline callers:
  - mm/memcontrol.c:page_cgroup_ino
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
In mm/memcontrol.c (ffffffff812cab18)
Location: include/linux/cgroup.h:619
Inline: True
Inline callers:
  - mm/memcontrol.c:page_cgroup_ino
```
</details>
</li>
</ul>

## Differences
