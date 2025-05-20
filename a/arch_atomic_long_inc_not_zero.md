# Function: <code>arch_atomic_long_inc_not_zero</code>

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
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/acct.c (ffffffff8118c5b9)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff8119cbc8)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811a070e)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff811a16ee)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/cpuset.c (ffffffff811a8168)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/events/core.c (ffffffff81289dc3)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/swapfile.c (ffffffff813137df)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_device
```
```
In mm/memcontrol.c (ffffffff8135b69b)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapin_charge_page
```
```
In mm/memremap.c (ffffffff8136924d)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/aio.c (ffffffff813d719e)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In block/blk-core.c (ffffffff815cc634)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - block/blk-core.c:blk_try_enter_queue
```
```
In block/blk-cgroup.c (ffffffff815f22b3)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
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
In kernel/fork.c (ffffffff810c943e)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/acct.c (ffffffff811bba3f)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff811ccec6)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811d0e4c)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff811d2045)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/cpuset.c (ffffffff811d9298)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/bpf/task_iter.c (ffffffff8129ae6e)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_file_seq_get_next
```
```
In kernel/events/core.c (ffffffff812de742)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_get_aux_event
```
```
In mm/swapfile.c (ffffffff8137ee28)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_device
```
```
In mm/memcontrol.c (ffffffff813d4ea0)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapin_charge_page
```
```
In mm/memremap.c (ffffffff813e70a8)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/file.c (ffffffff8141af54)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - fs/file.c:__fget_light
  - fs/file.c:fget_task
  - fs/file.c:fget_raw
  - fs/file.c:fget
```
```
In fs/aio.c (ffffffff81460d36)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In block/blk-core.c (ffffffff8167a003)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - block/blk-core.c:bio_poll
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff81684277)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_new_requests
```
```
In block/blk-cgroup.c (ffffffff816a3aba)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
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
In kernel/fork.c (ffffffff810e695e)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/acct.c (ffffffff811fd8cf)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff81210475)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff812149ac)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81215d75)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/cpuset.c (ffffffff8121e4f7)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/bpf/task_iter.c (ffffffff812f7726)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_file_seq_get_next
```
```
In kernel/events/core.c (ffffffff813468fc)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:event_sched_out
  - kernel/events/core.c:perf_get_aux_event
```
```
In mm/swapfile.c (ffffffff813fd92e)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_device
```
```
In mm/memcontrol.c (ffffffff8145a8d4)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapin_charge_folio
```
```
In mm/memremap.c (ffffffff8146f8c5)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - mm/memremap.c:zone_device_page_init
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/file.c (ffffffff814a6eda)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - fs/file.c:__fget_light
  - fs/file.c:fget_task
  - fs/file.c:fget_raw
  - fs/file.c:fget
```
```
In fs/aio.c (ffffffff814f0ce6)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In block/blk-core.c (ffffffff817364a8)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - block/blk-core.c:bio_poll
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff81741a57)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_new_requests
```
```
In block/blk-cgroup.c (ffffffff817627d8)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/pci/p2pdma.c (ffffffff8191c6f8)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_alloc_p2pmem
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
</details>
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
