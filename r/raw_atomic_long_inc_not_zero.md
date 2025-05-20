# Function: <code>raw_atomic_long_inc_not_zero</code>

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
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810f22fe)
Location: include/linux/atomic/atomic-long.h:1728
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/acct.c (ffffffff81212a4f)
Location: include/linux/atomic/atomic-long.h:1728
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff81225e85)
Location: include/linux/atomic/atomic-long.h:1728
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8122a2cc)
Location: include/linux/atomic/atomic-long.h:1728
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8122b6ae)
Location: include/linux/atomic/atomic-long.h:1728
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/cpuset.c (ffffffff812345f7)
Location: include/linux/atomic/atomic-long.h:1728
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/bpf/task_iter.c (ffffffff81325606)
Location: include/linux/atomic/atomic-long.h:1728
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_file_seq_get_next
```
```
In kernel/events/core.c (ffffffff81377a02)
Location: include/linux/atomic/atomic-long.h:1728
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:event_sched_out
  - kernel/events/core.c:perf_get_aux_event
```
```
In mm/swapfile.c (ffffffff81430bee)
Location: include/linux/atomic/atomic-long.h:1728
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_device
```
```
In mm/memcontrol.c (ffffffff81490534)
Location: include/linux/atomic/atomic-long.h:1728
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapin_charge_folio
```
```
In mm/memremap.c (ffffffff814a40a5)
Location: include/linux/atomic/atomic-long.h:1728
Inline: True
Inline callers:
  - mm/memremap.c:zone_device_page_init
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/file.c (ffffffff814dbeba)
Location: include/linux/atomic/atomic-long.h:1728
Inline: True
Inline callers:
  - fs/file.c:__fget_light
  - fs/file.c:fget_task
  - fs/file.c:fget_raw
  - fs/file.c:fget
```
```
In fs/aio.c (ffffffff81527a86)
Location: include/linux/atomic/atomic-long.h:1728
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In block/blk-core.c (ffffffff81771645)
Location: include/linux/atomic/atomic-long.h:1728
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff81781f77)
Location: include/linux/atomic/atomic-long.h:1728
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_new_requests
```
```
In block/blk-cgroup.c (ffffffff817a1484)
Location: include/linux/atomic/atomic-long.h:1728
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/pci/p2pdma.c (ffffffff8195fcb8)
Location: include/linux/atomic/atomic-long.h:1728
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_alloc_p2pmem
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/md/md.c (ffffffff81d5fd05)
Location: include/linux/atomic/atomic-long.h:1728
Inline: True
Inline callers:
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
In kernel/cred.c (ffffffff8113e6c1)
Location: include/linux/atomic/atomic-long.h:1728
Inline: True
Inline callers:
  - kernel/cred.c:get_task_cred
```
```
In kernel/acct.c (ffffffff8122a0ef)
Location: include/linux/atomic/atomic-long.h:1728
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff8123db15)
Location: include/linux/atomic/atomic-long.h:1728
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cgroup_tryget_css
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8124216c)
Location: include/linux/atomic/atomic-long.h:1728
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8124369e)
Location: include/linux/atomic/atomic-long.h:1728
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/cpuset.c (ffffffff8124e216)
Location: include/linux/atomic/atomic-long.h:1728
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/events/core.c (ffffffff813a0ce2)
Location: include/linux/atomic/atomic-long.h:1728
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:event_sched_out
  - kernel/events/core.c:perf_get_aux_event
```
```
In mm/swapfile.c (ffffffff8146a00e)
Location: include/linux/atomic/atomic-long.h:1728
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_device
```
```
In mm/zswap.c (ffffffff8146f84c)
Location: include/linux/atomic/atomic-long.h:1728
Inline: True
Inline callers:
  - mm/zswap.c:shrink_worker
```
```
In mm/memcontrol.c (ffffffff814bfe1c)
Location: include/linux/atomic/atomic-long.h:1728
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapin_charge_folio
```
```
In mm/memremap.c (ffffffff814d4f52)
Location: include/linux/atomic/atomic-long.h:1728
Inline: True
Inline callers:
  - mm/memremap.c:zone_device_page_init
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/file.c (ffffffff8150ede0)
Location: include/linux/atomic/atomic-long.h:1728
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
  - fs/file.c:__ia32_sys_dup2
  - fs/file.c:__x64_sys_dup2
  - fs/file.c:__fdget_pos
  - fs/file.c:__fdget_raw
  - fs/file.c:task_lookup_next_fdget_rcu
  - fs/file.c:task_lookup_fdget_rcu
  - fs/file.c:lookup_fdget_rcu
  - fs/file.c:fget_task
  - fs/file.c:fget
  - fs/file.c:__get_file_rcu
```
```
In fs/aio.c (ffffffff8155c816)
Location: include/linux/atomic/atomic-long.h:1728
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In block/blk-core.c (ffffffff817b3985)
Location: include/linux/atomic/atomic-long.h:1728
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff817c6c3a)
Location: include/linux/atomic/atomic-long.h:1728
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
```
```
In block/blk-cgroup.c (ffffffff817e4fd1)
Location: include/linux/atomic/atomic-long.h:1728
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/pci/p2pdma.c (ffffffff819a9378)
Location: include/linux/atomic/atomic-long.h:1728
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_alloc_p2pmem
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/md/md.c (ffffffff81e172e1)
Location: include/linux/atomic/atomic-long.h:1728
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
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
