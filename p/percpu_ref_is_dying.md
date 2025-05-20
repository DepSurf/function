# Function: <code>percpu_ref_is_dying</code>

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
In fs/fs-writeback.c (0)
Location: include/linux/percpu-refcount.h:306
Inline: True
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
In kernel/cgroup.c (0)
Location: include/linux/percpu-refcount.h:304
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812632ca)
Location: include/linux/percpu-refcount.h:304
Inline: True
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
In kernel/cgroup.c (0)
Location: include/linux/percpu-refcount.h:304
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8127671a)
Location: include/linux/percpu-refcount.h:304
Inline: True
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
In kernel/cgroup/cgroup.c (0)
Location: include/linux/percpu-refcount.h:305
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/percpu-refcount.h:305
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81283ba1)
Location: include/linux/percpu-refcount.h:305
Inline: True
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
In kernel/cgroup/cgroup.c (0)
Location: include/linux/percpu-refcount.h:306
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/percpu-refcount.h:306
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/percpu-refcount.h:306
Inline: True
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
In kernel/cgroup/cgroup.c (ffffffff81140ef5)
Location: include/linux/percpu-refcount.h:312
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
```
```
In kernel/cgroup/cpuset.c (ffffffff8114b265)
Location: include/linux/percpu-refcount.h:312
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
```
```
In fs/fs-writeback.c (ffffffff812cd314)
Location: include/linux/percpu-refcount.h:312
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
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
In kernel/cgroup/cgroup.c (ffffffff8114c935)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
```
```
In kernel/cgroup/cpuset.c (ffffffff81157ba3)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
```
```
In fs/fs-writeback.c (ffffffff812e2634)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
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
In kernel/cgroup/cgroup.c (ffffffff81158537)
Location: include/linux/percpu-refcount.h:321
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115da08)
Location: include/linux/percpu-refcount.h:321
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/cpuset.c (ffffffff81164b20)
Location: include/linux/percpu-refcount.h:321
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In fs/fs-writeback.c (ffffffff81300681)
Location: include/linux/percpu-refcount.h:321
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
```
```
In fs/io_uring.c (ffffffff81331cd9)
Location: include/linux/percpu-refcount.h:321
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
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
In kernel/cgroup/cgroup.c (ffffffff81164190)
Location: include/linux/percpu-refcount.h:321
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81169618)
Location: include/linux/percpu-refcount.h:321
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/cpuset.c (ffffffff81170a00)
Location: include/linux/percpu-refcount.h:321
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In fs/fs-writeback.c (ffffffff81312cc5)
Location: include/linux/percpu-refcount.h:321
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
```
```
In fs/io_uring.c (ffffffff81345899)
Location: include/linux/percpu-refcount.h:321
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
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
In kernel/cgroup/cgroup.c (ffffffff8117503a)
Location: include/linux/percpu-refcount.h:337
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8117b330)
Location: include/linux/percpu-refcount.h:337
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/cpuset.c (ffffffff81182780)
Location: include/linux/percpu-refcount.h:337
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_root_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In fs/fs-writeback.c (ffffffff8134c5c1)
Location: include/linux/percpu-refcount.h:337
Inline: True
```
```
In fs/io_uring.c (ffffffff813812c5)
Location: include/linux/percpu-refcount.h:337
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_file_data_ref_zero
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
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
In kernel/cgroup/cgroup.c (ffffffff81171ceb)
Location: include/linux/percpu-refcount.h:350
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81178205)
Location: include/linux/percpu-refcount.h:350
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/cpuset.c (ffffffff8117f69e)
Location: include/linux/percpu-refcount.h:350
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_root_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In fs/fs-writeback.c (ffffffff813595ca)
Location: include/linux/percpu-refcount.h:350
Inline: True
```
```
In fs/io_uring.c (ffffffff8138f199)
Location: include/linux/percpu-refcount.h:350
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_file_data_ref_zero
  - fs/io_uring.c:__io_sq_thread
  - fs/io_uring.c:io_iopoll_queue
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
In kernel/cgroup/cgroup.c (ffffffff8117290b)
Location: include/linux/percpu-refcount.h:350
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81178d85)
Location: include/linux/percpu-refcount.h:350
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/cpuset.c (ffffffff8117fcde)
Location: include/linux/percpu-refcount.h:350
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In fs/fs-writeback.c (ffffffff81360241)
Location: include/linux/percpu-refcount.h:350
Inline: True
```
```
In fs/io_uring.c (ffffffff8139e299)
Location: include/linux/percpu-refcount.h:350
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_rw_should_reissue
```
```
In lib/percpu-refcount.c (ffffffff815b52ae)
Location: include/linux/percpu-refcount.h:350
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
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
In kernel/cgroup/cgroup.c (ffffffff81199499)
Location: include/linux/percpu-refcount.h:350
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811a06b5)
Location: include/linux/percpu-refcount.h:350
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/cpuset.c (ffffffff811a7d9f)
Location: include/linux/percpu-refcount.h:350
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In fs/fs-writeback.c (ffffffff813ae8c5)
Location: include/linux/percpu-refcount.h:350
Inline: True
```
```
In fs/io_uring.c (ffffffff813ee379)
Location: include/linux/percpu-refcount.h:350
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_rw_should_reissue
```
```
In lib/percpu-refcount.c (ffffffff8161b64e)
Location: include/linux/percpu-refcount.h:350
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
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
In kernel/cgroup/cgroup.c (ffffffff811c970a)
Location: include/linux/percpu-refcount.h:363
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811d0e12)
Location: include/linux/percpu-refcount.h:363
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/cpuset.c (ffffffff811d8eb5)
Location: include/linux/percpu-refcount.h:363
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In fs/fs-writeback.c (ffffffff814330cd)
Location: include/linux/percpu-refcount.h:363
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
```
```
In io_uring/io_uring.c (ffffffff816d8418)
Location: include/linux/percpu-refcount.h:363
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:io_sq_thread
  - io_uring/io_uring.c:io_rw_should_reissue
```
```
In lib/percpu-refcount.c (ffffffff816e8e59)
Location: include/linux/percpu-refcount.h:363
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
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
In kernel/cgroup/cgroup.c (ffffffff8120c83a)
Location: include/linux/percpu-refcount.h:363
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81214972)
Location: include/linux/percpu-refcount.h:363
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/cpuset.c (ffffffff8121e08e)
Location: include/linux/percpu-refcount.h:363
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In kernel/bpf/bpf_cgrp_storage.c (ffffffff8132581a)
Location: include/linux/percpu-refcount.h:363
Inline: True
Inline callers:
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_get
```
```
In fs/fs-writeback.c (ffffffff814c10bd)
Location: include/linux/percpu-refcount.h:363
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
```
```
In io_uring/io_uring.c (ffffffff8178c1b4)
Location: include/linux/percpu-refcount.h:363
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_uring_register
```
```
In io_uring/sqpoll.c (ffffffff8179a5aa)
Location: include/linux/percpu-refcount.h:363
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread
```
```
In io_uring/rw.c (ffffffff817a308b)
Location: include/linux/percpu-refcount.h:363
Inline: True
Inline callers:
  - io_uring/rw.c:io_rw_should_reissue
```
```
In lib/percpu-refcount.c (ffffffff817d8f19)
Location: include/linux/percpu-refcount.h:363
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
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
In kernel/cgroup/cgroup.c (ffffffff81221e4a)
Location: include/linux/percpu-refcount.h:363
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8122a292)
Location: include/linux/percpu-refcount.h:363
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/cpuset.c (ffffffff8123418e)
Location: include/linux/percpu-refcount.h:363
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In kernel/bpf/bpf_cgrp_storage.c (ffffffff81355a6a)
Location: include/linux/percpu-refcount.h:363
Inline: True
Inline callers:
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_get
```
```
In fs/fs-writeback.c (ffffffff814f636d)
Location: include/linux/percpu-refcount.h:363
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
```
```
In io_uring/io_uring.c (ffffffff817cd2f4)
Location: include/linux/percpu-refcount.h:363
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_uring_register
```
```
In io_uring/sqpoll.c (ffffffff817db600)
Location: include/linux/percpu-refcount.h:363
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread
```
```
In io_uring/rw.c (ffffffff817e403d)
Location: include/linux/percpu-refcount.h:363
Inline: True
Inline callers:
  - io_uring/rw.c:io_rw_should_reissue
```
```
In lib/percpu-refcount.c (ffffffff81818129)
Location: include/linux/percpu-refcount.h:363
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
```
```
In drivers/md/md.c (ffffffff81d6a247)
Location: include/linux/percpu-refcount.h:363
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_write_start
  - drivers/md/md.c:md_write_start
  - drivers/md/md.c:mddev_detach
  - drivers/md/md.c:md_handle_request
  - drivers/md/md.c:md_handle_request
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
In kernel/cgroup/cgroup.c (ffffffff81239b3a)
Location: include/linux/percpu-refcount.h:363
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81242132)
Location: include/linux/percpu-refcount.h:363
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/cpuset.c (ffffffff8124dd28)
Location: include/linux/percpu-refcount.h:363
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:compute_partition_effective_cpumask
  - kernel/cgroup/cpuset.c:compute_partition_effective_cpumask
  - kernel/cgroup/cpuset.c:update_parent_effective_cpumask
  - kernel/cgroup/cpuset.c:tasks_nocpu_error
  - kernel/cgroup/cpuset.c:tasks_nocpu_error
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In kernel/bpf/bpf_cgrp_storage.c (ffffffff8137e59a)
Location: include/linux/percpu-refcount.h:363
Inline: True
Inline callers:
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_get
```
```
In fs/fs-writeback.c (ffffffff8152aaad)
Location: include/linux/percpu-refcount.h:363
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
```
```
In io_uring/sqpoll.c (ffffffff8181f94b)
Location: include/linux/percpu-refcount.h:363
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread
```
```
In io_uring/rw.c (ffffffff818280ed)
Location: include/linux/percpu-refcount.h:363
Inline: True
Inline callers:
  - io_uring/rw.c:io_rw_should_reissue
```
```
In io_uring/register.c (ffffffff8182b834)
Location: include/linux/percpu-refcount.h:363
Inline: True
Inline callers:
  - io_uring/register.c:__io_uring_register
```
```
In lib/percpu-refcount.c (ffffffff8185d429)
Location: include/linux/percpu-refcount.h:363
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
```
```
In drivers/md/md.c (ffffffff81e15e2d)
Location: include/linux/percpu-refcount.h:363
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_start
  - drivers/md/md.c:md_write_start
  - drivers/md/md.c:mddev_detach
  - drivers/md/md.c:md_handle_request
  - drivers/md/md.c:md_handle_request
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
In kernel/cgroup/cgroup.c (ffff8000101d5a3c)
Location: include/linux/percpu-refcount.h:321
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
```
```
In kernel/cgroup/cgroup-v1.c (ffff8000101dc874)
Location: include/linux/percpu-refcount.h:321
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/cpuset.c (ffff8000101e4134)
Location: include/linux/percpu-refcount.h:321
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In fs/fs-writeback.c (ffff8000103c81e8)
Location: include/linux/percpu-refcount.h:321
Inline: True
```
```
In fs/io_uring.c (ffff800010403a74)
Location: include/linux/percpu-refcount.h:321
Inline: True
Inline callers:
  - fs/io_uring.c:__arm64_sys_io_uring_register
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
In kernel/cgroup/cgroup.c (c0418548)
Location: include/linux/percpu-refcount.h:321
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
```
```
In kernel/cgroup/cgroup-v1.c (c041eb60)
Location: include/linux/percpu-refcount.h:321
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/cpuset.c (c0425090)
Location: include/linux/percpu-refcount.h:321
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In fs/fs-writeback.c (c05a2938)
Location: include/linux/percpu-refcount.h:321
Inline: True
```
```
In fs/io_uring.c (c05d7700)
Location: include/linux/percpu-refcount.h:321
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_register
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
In kernel/cgroup/cgroup.c (c000000000241334)
Location: include/linux/percpu-refcount.h:321
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
```
```
In kernel/cgroup/cgroup-v1.c (c00000000024a6bc)
Location: include/linux/percpu-refcount.h:321
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/cpuset.c (c0000000002546f0)
Location: include/linux/percpu-refcount.h:321
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In fs/fs-writeback.c (c0000000004c67d4)
Location: include/linux/percpu-refcount.h:321
Inline: True
```
```
In fs/io_uring.c (c00000000051080c)
Location: include/linux/percpu-refcount.h:321
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_register
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
In kernel/cgroup/cgroup.c (ffffffe00014ecec)
Location: include/linux/percpu-refcount.h:321
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
```
```
In kernel/cgroup/cgroup-v1.c (ffffffe0001547f4)
Location: include/linux/percpu-refcount.h:321
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/cpuset.c (ffffffe00015a4f2)
Location: include/linux/percpu-refcount.h:321
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In fs/fs-writeback.c (ffffffe000286c48)
Location: include/linux/percpu-refcount.h:321
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
```
```
In fs/io_uring.c (ffffffe0002b1138)
Location: include/linux/percpu-refcount.h:321
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_register
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
In kernel/cgroup/cgroup.c (ffffffff8115c7b0)
Location: include/linux/percpu-refcount.h:321
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81161c38)
Location: include/linux/percpu-refcount.h:321
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/cpuset.c (ffffffff81169020)
Location: include/linux/percpu-refcount.h:321
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In fs/fs-writeback.c (ffffffff8130b2a5)
Location: include/linux/percpu-refcount.h:321
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
```
```
In fs/io_uring.c (ffffffff8133de79)
Location: include/linux/percpu-refcount.h:321
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
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
In kernel/cgroup/cgroup.c (ffffffff8114faa0)
Location: include/linux/percpu-refcount.h:321
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81154e98)
Location: include/linux/percpu-refcount.h:321
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/cpuset.c (ffffffff8115c22a)
Location: include/linux/percpu-refcount.h:321
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In fs/fs-writeback.c (ffffffff812fbec5)
Location: include/linux/percpu-refcount.h:321
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
```
```
In fs/io_uring.c (ffffffff8132eb39)
Location: include/linux/percpu-refcount.h:321
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
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
In kernel/cgroup/cgroup.c (ffffffff8115a580)
Location: include/linux/percpu-refcount.h:321
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115fa08)
Location: include/linux/percpu-refcount.h:321
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/cpuset.c (ffffffff81166df0)
Location: include/linux/percpu-refcount.h:321
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In fs/fs-writeback.c (ffffffff81309095)
Location: include/linux/percpu-refcount.h:321
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
```
```
In fs/io_uring.c (ffffffff8133b949)
Location: include/linux/percpu-refcount.h:321
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
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
In kernel/cgroup/cgroup.c (ffffffff811675e0)
Location: include/linux/percpu-refcount.h:321
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8116cd03)
Location: include/linux/percpu-refcount.h:321
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/cpuset.c (ffffffff8117454b)
Location: include/linux/percpu-refcount.h:321
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_write_u64
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In fs/fs-writeback.c (ffffffff8131ada3)
Location: include/linux/percpu-refcount.h:321
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
```
```
In fs/io_uring.c (ffffffff8134eaf9)
Location: include/linux/percpu-refcount.h:321
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
```
</details>
</li>
</ul>

## Differences
