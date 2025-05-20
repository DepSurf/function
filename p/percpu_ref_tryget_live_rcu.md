# Function: <code>percpu_ref_tryget_live_rcu</code>

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
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811ccea9)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811d0de7)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff811d1fc5)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/cpuset.c (ffffffff811d8eca)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In mm/swapfile.c (ffffffff8137eddc)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_device
```
```
In mm/memcontrol.c (ffffffff813d4e54)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapin_charge_page
```
```
In mm/memremap.c (ffffffff813e7049)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/aio.c (ffffffff81460cee)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In block/blk-core.c (ffffffff81679f24)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - block/blk-core.c:bio_poll
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff8168416e)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_new_requests
```
```
In block/blk-cgroup.c (ffffffff816a3a15)
Location: include/linux/percpu-refcount.h:275
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
In kernel/cgroup/cgroup.c (ffffffff81210458)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81214947)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81215cf5)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/cpuset.c (ffffffff8121e0a3)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In mm/swapfile.c (ffffffff813fd8c4)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_device
```
```
In mm/memcontrol.c (ffffffff8145a893)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapin_charge_folio
```
```
In mm/memremap.c (ffffffff8146f838)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - mm/memremap.c:zone_device_page_init
  - mm/memremap.c:zone_device_page_init
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/aio.c (ffffffff814f0c9e)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In block/blk-core.c (ffffffff817363c9)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - block/blk-core.c:bio_poll
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff8174194e)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_new_requests
```
```
In block/blk-cgroup.c (ffffffff817626fe)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/pci/p2pdma.c (ffffffff8191c6a1)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_alloc_p2pmem
  - drivers/pci/p2pdma.c:pci_alloc_p2pmem
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
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
In kernel/cgroup/cgroup.c (ffffffff81225e68)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8122a267)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8122b629)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/cpuset.c (ffffffff812341a3)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In mm/swapfile.c (ffffffff81430b84)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_device
```
```
In mm/memcontrol.c (ffffffff814904f3)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapin_charge_folio
```
```
In mm/memremap.c (ffffffff814a4018)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - mm/memremap.c:zone_device_page_init
  - mm/memremap.c:zone_device_page_init
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/aio.c (ffffffff81527a3e)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In block/blk-core.c (ffffffff81771538)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff81781e6b)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_new_requests
```
```
In block/blk-cgroup.c (ffffffff817a13aa)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/pci/p2pdma.c (ffffffff8195fc61)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_alloc_p2pmem
  - drivers/pci/p2pdma.c:pci_alloc_p2pmem
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/md/md.c (ffffffff81d5fcb4)
Location: include/linux/percpu-refcount.h:275
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
In kernel/cgroup/cgroup.c (ffffffff8123daf8)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cgroup_tryget_css
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81242107)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81243619)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/cpuset.c (ffffffff8124dd3d)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In mm/swapfile.c (ffffffff81469fa4)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_device
```
```
In mm/zswap.c (ffffffff8146f7ef)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - mm/zswap.c:shrink_worker
```
```
In mm/memcontrol.c (ffffffff814bfddb)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapin_charge_folio
```
```
In mm/memremap.c (ffffffff814d4ec8)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - mm/memremap.c:zone_device_page_init
  - mm/memremap.c:zone_device_page_init
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/aio.c (ffffffff8155c7ce)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In block/blk-core.c (ffffffff817b3878)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff817c660b)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
```
```
In block/blk-cgroup.c (ffffffff817e4ef7)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/pci/p2pdma.c (ffffffff819a9321)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_alloc_p2pmem
  - drivers/pci/p2pdma.c:pci_alloc_p2pmem
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/md/md.c (ffffffff81e17290)
Location: include/linux/percpu-refcount.h:275
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
