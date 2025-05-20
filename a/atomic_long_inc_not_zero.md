# Function: <code>atomic_long_inc_not_zero</code>

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
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/acct.c (ffffffff8114d05f)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff8115b226)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115db72)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8115ecc0)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8115fbc3)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff811654cb)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/events/core.c (ffffffff81207389)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/page-writeback.c (ffffffff8121fdcf)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff8123b803)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slub.c (ffffffff812940b8)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812b62c0)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff812b800a)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memremap.c (ffffffff812c24cf)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/fs-writeback.c (ffffffff813002d6)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/aio.c (ffffffff8132800e)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffffffff813305ef)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
  - fs/io_uring.c:io_submit_sqe
```
```
In block/bio.c (ffffffff814c5fe8)
Location: include/asm-generic/atomic-long.h:494
Inline: True
```
```
In block/blk-core.c (ffffffff814cd81a)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff814d5ba9)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff814db73e)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff814f1ab6)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
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
In kernel/acct.c (ffffffff81158d2f)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff81166ee4)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81169782)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8116a920)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8116b823)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff811713bb)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/events/core.c (ffffffff812146f9)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/page-writeback.c (ffffffff8122d87f)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff81248c82)
Location: include/asm-generic/atomic-long.h:494
Inline: True
```
```
In mm/slub.c (ffffffff812a3e28)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812c8195)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff812c9eb7)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memremap.c (ffffffff812d43ff)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/fs-writeback.c (ffffffff81314bbb)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/aio.c (ffffffff8133adae)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffffffff81343e6b)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (ffffffff814de3e8)
Location: include/asm-generic/atomic-long.h:494
Inline: True
```
```
In block/blk-core.c (ffffffff814e6b0a)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff814eeed9)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff814f4b6e)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff8150b083)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
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
In kernel/acct.c (ffffffff8116911c)
Location: include/asm-generic/atomic-long.h:495
Inline: True
Inline callers:
  - kernel/acct.c:acct_get
```
```
In kernel/cgroup/cgroup.c (ffffffff81177d6f)
Location: include/asm-generic/atomic-long.h:495
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8117b38d)
Location: include/asm-generic/atomic-long.h:495
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8117c3de)
Location: include/asm-generic/atomic-long.h:495
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/cpuset.c (ffffffff811829a7)
Location: include/asm-generic/atomic-long.h:495
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/events/core.c (ffffffff81240744)
Location: include/asm-generic/atomic-long.h:495
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/slub.c (ffffffff812d98eb)
Location: include/asm-generic/atomic-long.h:495
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812fe22b)
Location: include/asm-generic/atomic-long.h:495
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_charge
  - mm/memcontrol.c:memcg_kmem_get_cache
```
```
In mm/memremap.c (ffffffff8130a0b2)
Location: include/asm-generic/atomic-long.h:495
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/aio.c (ffffffff81374ead)
Location: include/asm-generic/atomic-long.h:495
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In block/blk-core.c (ffffffff81544e81)
Location: include/asm-generic/atomic-long.h:495
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_enter
```
```
In block/genhd.c (ffffffff8155a71a)
Location: include/asm-generic/atomic-long.h:495
Inline: True
Inline callers:
  - block/genhd.c:disk_map_sector_rcu
  - block/genhd.c:disk_map_sector_rcu
```
```
In block/blk-cgroup.c (ffffffff8156b629)
Location: include/asm-generic/atomic-long.h:495
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
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
In kernel/acct.c (ffffffff811657ac)
Location: include/asm-generic/atomic-long.h:495
Inline: True
Inline callers:
  - kernel/acct.c:acct_get
```
```
In kernel/cgroup/cgroup.c (ffffffff81174a8e)
Location: include/asm-generic/atomic-long.h:495
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8117826b)
Location: include/asm-generic/atomic-long.h:495
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8117925e)
Location: include/asm-generic/atomic-long.h:495
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/cpuset.c (ffffffff8117f8d7)
Location: include/asm-generic/atomic-long.h:495
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/events/core.c (ffffffff8124acb3)
Location: include/asm-generic/atomic-long.h:495
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/memcontrol.c (ffffffff8130a74e)
Location: include/asm-generic/atomic-long.h:495
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_charge
```
```
In mm/memremap.c (ffffffff81315d7a)
Location: include/asm-generic/atomic-long.h:495
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/aio.c (ffffffff81382e4b)
Location: include/asm-generic/atomic-long.h:495
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffffffff81396dd8)
Location: include/asm-generic/atomic-long.h:495
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_grab_identity
```
```
In block/blk-core.c (ffffffff81561440)
Location: include/asm-generic/atomic-long.h:495
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-cgroup.c (ffffffff81586138)
Location: include/asm-generic/atomic-long.h:495
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
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
In kernel/acct.c (ffffffff81166df9)
Location: include/asm-generic/atomic-long.h:495
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff8117564e)
Location: include/asm-generic/atomic-long.h:495
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81178dde)
Location: include/asm-generic/atomic-long.h:495
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81179dce)
Location: include/asm-generic/atomic-long.h:495
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/cpuset.c (ffffffff8117ff17)
Location: include/asm-generic/atomic-long.h:495
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/events/core.c (ffffffff8124f093)
Location: include/asm-generic/atomic-long.h:495
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/memcontrol.c (ffffffff8131036e)
Location: include/asm-generic/atomic-long.h:495
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapin_charge_page
```
```
In mm/memremap.c (ffffffff8131bf6d)
Location: include/asm-generic/atomic-long.h:495
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/aio.c (ffffffff81389ebe)
Location: include/asm-generic/atomic-long.h:495
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In block/blk-core.c (ffffffff81569b90)
Location: include/asm-generic/atomic-long.h:495
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-cgroup.c (ffffffff8158cb28)
Location: include/asm-generic/atomic-long.h:495
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
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
In kernel/acct.c (ffffffff8118c5b9)
Location: include/linux/atomic/atomic-instrumented.h:1731
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff8119cbc8)
Location: include/linux/atomic/atomic-instrumented.h:1731
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811a070e)
Location: include/linux/atomic/atomic-instrumented.h:1731
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff811a16ee)
Location: include/linux/atomic/atomic-instrumented.h:1731
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/cpuset.c (ffffffff811a8168)
Location: include/linux/atomic/atomic-instrumented.h:1731
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/events/core.c (ffffffff81289dc3)
Location: include/linux/atomic/atomic-instrumented.h:1731
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/swapfile.c (ffffffff813137df)
Location: include/linux/atomic/atomic-instrumented.h:1731
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_device
```
```
In mm/memcontrol.c (ffffffff8135b69b)
Location: include/linux/atomic/atomic-instrumented.h:1731
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapin_charge_page
```
```
In mm/memremap.c (ffffffff8136924d)
Location: include/linux/atomic/atomic-instrumented.h:1731
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/aio.c (ffffffff813d719e)
Location: include/linux/atomic/atomic-instrumented.h:1731
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In block/blk-core.c (ffffffff815cc634)
Location: include/linux/atomic/atomic-instrumented.h:1731
Inline: True
Inline callers:
  - block/blk-core.c:blk_try_enter_queue
```
```
In block/blk-cgroup.c (ffffffff815f22b3)
Location: include/linux/atomic/atomic-instrumented.h:1731
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
Location: include/linux/atomic/atomic-instrumented.h:1850
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/acct.c (ffffffff811bba3f)
Location: include/linux/atomic/atomic-instrumented.h:1850
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff811ccec6)
Location: include/linux/atomic/atomic-instrumented.h:1850
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811d0e4c)
Location: include/linux/atomic/atomic-instrumented.h:1850
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff811d2045)
Location: include/linux/atomic/atomic-instrumented.h:1850
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/cpuset.c (ffffffff811d9298)
Location: include/linux/atomic/atomic-instrumented.h:1850
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/bpf/task_iter.c (ffffffff8129ae6e)
Location: include/linux/atomic/atomic-instrumented.h:1850
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_file_seq_get_next
```
```
In kernel/events/core.c (ffffffff812de742)
Location: include/linux/atomic/atomic-instrumented.h:1850
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_get_aux_event
```
```
In mm/swapfile.c (ffffffff8137ee28)
Location: include/linux/atomic/atomic-instrumented.h:1850
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_device
```
```
In mm/memcontrol.c (ffffffff813d4ea0)
Location: include/linux/atomic/atomic-instrumented.h:1850
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapin_charge_page
```
```
In mm/memremap.c (ffffffff813e70a8)
Location: include/linux/atomic/atomic-instrumented.h:1850
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/file.c (ffffffff8141af54)
Location: include/linux/atomic/atomic-instrumented.h:1850
Inline: True
Inline callers:
  - fs/file.c:__fget_light
  - fs/file.c:fget_task
  - fs/file.c:fget_raw
  - fs/file.c:fget
```
```
In fs/aio.c (ffffffff81460d36)
Location: include/linux/atomic/atomic-instrumented.h:1850
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In block/blk-core.c (ffffffff8167a003)
Location: include/linux/atomic/atomic-instrumented.h:1850
Inline: True
Inline callers:
  - block/blk-core.c:bio_poll
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff81684277)
Location: include/linux/atomic/atomic-instrumented.h:1850
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_new_requests
```
```
In block/blk-cgroup.c (ffffffff816a3aba)
Location: include/linux/atomic/atomic-instrumented.h:1850
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
Location: include/linux/atomic/atomic-instrumented.h:1850
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/acct.c (ffffffff811fd8cf)
Location: include/linux/atomic/atomic-instrumented.h:1850
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff81210475)
Location: include/linux/atomic/atomic-instrumented.h:1850
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff812149ac)
Location: include/linux/atomic/atomic-instrumented.h:1850
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81215d75)
Location: include/linux/atomic/atomic-instrumented.h:1850
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/cpuset.c (ffffffff8121e4f7)
Location: include/linux/atomic/atomic-instrumented.h:1850
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/bpf/task_iter.c (ffffffff812f7726)
Location: include/linux/atomic/atomic-instrumented.h:1850
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_file_seq_get_next
```
```
In kernel/events/core.c (ffffffff813468fc)
Location: include/linux/atomic/atomic-instrumented.h:1850
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:event_sched_out
  - kernel/events/core.c:perf_get_aux_event
```
```
In mm/swapfile.c (ffffffff813fd92e)
Location: include/linux/atomic/atomic-instrumented.h:1850
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_device
```
```
In mm/memcontrol.c (ffffffff8145a8d4)
Location: include/linux/atomic/atomic-instrumented.h:1850
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapin_charge_folio
```
```
In mm/memremap.c (ffffffff8146f8c5)
Location: include/linux/atomic/atomic-instrumented.h:1850
Inline: True
Inline callers:
  - mm/memremap.c:zone_device_page_init
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/file.c (ffffffff814a6eda)
Location: include/linux/atomic/atomic-instrumented.h:1850
Inline: True
Inline callers:
  - fs/file.c:__fget_light
  - fs/file.c:fget_task
  - fs/file.c:fget_raw
  - fs/file.c:fget
```
```
In fs/aio.c (ffffffff814f0ce6)
Location: include/linux/atomic/atomic-instrumented.h:1850
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In block/blk-core.c (ffffffff817364a8)
Location: include/linux/atomic/atomic-instrumented.h:1850
Inline: True
Inline callers:
  - block/blk-core.c:bio_poll
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff81741a57)
Location: include/linux/atomic/atomic-instrumented.h:1850
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_new_requests
```
```
In block/blk-cgroup.c (ffffffff817627d8)
Location: include/linux/atomic/atomic-instrumented.h:1850
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/pci/p2pdma.c (ffffffff8191c6f8)
Location: include/linux/atomic/atomic-instrumented.h:1850
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_alloc_p2pmem
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
In kernel/fork.c (ffffffff810f22fe)
Location: include/linux/atomic/atomic-instrumented.h:4650
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/acct.c (ffffffff81212a4f)
Location: include/linux/atomic/atomic-instrumented.h:4650
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff81225e85)
Location: include/linux/atomic/atomic-instrumented.h:4650
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8122a2cc)
Location: include/linux/atomic/atomic-instrumented.h:4650
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8122b6ae)
Location: include/linux/atomic/atomic-instrumented.h:4650
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/cpuset.c (ffffffff812345f7)
Location: include/linux/atomic/atomic-instrumented.h:4650
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/bpf/task_iter.c (ffffffff81325606)
Location: include/linux/atomic/atomic-instrumented.h:4650
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_file_seq_get_next
```
```
In kernel/events/core.c (ffffffff81377a02)
Location: include/linux/atomic/atomic-instrumented.h:4650
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:event_sched_out
  - kernel/events/core.c:perf_get_aux_event
```
```
In mm/swapfile.c (ffffffff81430bee)
Location: include/linux/atomic/atomic-instrumented.h:4650
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_device
```
```
In mm/memcontrol.c (ffffffff81490534)
Location: include/linux/atomic/atomic-instrumented.h:4650
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapin_charge_folio
```
```
In mm/memremap.c (ffffffff814a40a5)
Location: include/linux/atomic/atomic-instrumented.h:4650
Inline: True
Inline callers:
  - mm/memremap.c:zone_device_page_init
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/file.c (ffffffff814dbeba)
Location: include/linux/atomic/atomic-instrumented.h:4650
Inline: True
Inline callers:
  - fs/file.c:__fget_light
  - fs/file.c:fget_task
  - fs/file.c:fget_raw
  - fs/file.c:fget
```
```
In fs/aio.c (ffffffff81527a86)
Location: include/linux/atomic/atomic-instrumented.h:4650
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In block/blk-core.c (ffffffff81771645)
Location: include/linux/atomic/atomic-instrumented.h:4650
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff81781f77)
Location: include/linux/atomic/atomic-instrumented.h:4650
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_new_requests
```
```
In block/blk-cgroup.c (ffffffff817a1484)
Location: include/linux/atomic/atomic-instrumented.h:4650
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/pci/p2pdma.c (ffffffff8195fcb8)
Location: include/linux/atomic/atomic-instrumented.h:4650
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_alloc_p2pmem
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/md/md.c (ffffffff81d5fd05)
Location: include/linux/atomic/atomic-instrumented.h:4650
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
Location: include/linux/atomic/atomic-instrumented.h:4650
Inline: True
Inline callers:
  - kernel/cred.c:get_task_cred
```
```
In kernel/acct.c (ffffffff8122a0ef)
Location: include/linux/atomic/atomic-instrumented.h:4650
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff8123db15)
Location: include/linux/atomic/atomic-instrumented.h:4650
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cgroup_tryget_css
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8124216c)
Location: include/linux/atomic/atomic-instrumented.h:4650
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8124369e)
Location: include/linux/atomic/atomic-instrumented.h:4650
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/cpuset.c (ffffffff8124e216)
Location: include/linux/atomic/atomic-instrumented.h:4650
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/events/core.c (ffffffff813a0ce2)
Location: include/linux/atomic/atomic-instrumented.h:4650
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:event_sched_out
  - kernel/events/core.c:perf_get_aux_event
```
```
In mm/swapfile.c (ffffffff8146a00e)
Location: include/linux/atomic/atomic-instrumented.h:4650
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_device
```
```
In mm/zswap.c (ffffffff8146f84c)
Location: include/linux/atomic/atomic-instrumented.h:4650
Inline: True
Inline callers:
  - mm/zswap.c:shrink_worker
```
```
In mm/memcontrol.c (ffffffff814bfe1c)
Location: include/linux/atomic/atomic-instrumented.h:4650
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapin_charge_folio
```
```
In mm/memremap.c (ffffffff814d4f52)
Location: include/linux/atomic/atomic-instrumented.h:4650
Inline: True
Inline callers:
  - mm/memremap.c:zone_device_page_init
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/file.c (ffffffff8150ede0)
Location: include/linux/atomic/atomic-instrumented.h:4650
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
Location: include/linux/atomic/atomic-instrumented.h:4650
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In block/blk-core.c (ffffffff817b3985)
Location: include/linux/atomic/atomic-instrumented.h:4650
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff817c6c3a)
Location: include/linux/atomic/atomic-instrumented.h:4650
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
```
```
In block/blk-cgroup.c (ffffffff817e4fd1)
Location: include/linux/atomic/atomic-instrumented.h:4650
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/pci/p2pdma.c (ffffffff819a9378)
Location: include/linux/atomic/atomic-instrumented.h:4650
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_alloc_p2pmem
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/md/md.c (ffffffff81e172e1)
Location: include/linux/atomic/atomic-instrumented.h:4650
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/acct.c (ffff8000101c826c)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffff8000101d8da0)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffff8000101dca34)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffff8000101de85c)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffff8000101dfc00)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffff8000101e4af8)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/events/core.c (ffff80001029e718)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/page-writeback.c (ffff8000102bc77c)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffff8000102de4c4)
Location: include/asm-generic/atomic-long.h:494
Inline: True
```
```
In mm/slub.c (ffff800010345b6c)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffff800010369eb0)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:percpu_ref_tryget_live
```
```
In mm/hugetlb_cgroup.c (ffff80001036d74c)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffff8000103cab14)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/aio.c (ffff8000103fbfe0)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffff800010405d6c)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - fs/io_uring.c:__arm64_sys_io_uring_enter
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (ffff8000105db7b8)
Location: include/asm-generic/atomic-long.h:494
Inline: True
```
```
In block/blk-core.c (ffff8000105e4398)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffff8000105ef73c)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffff8000105f4994)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffff80001060e9e4)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
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
In kernel/acct.c (c040f29c)
Location: include/asm-generic/atomic-long.h:988
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (c041bbd4)
Location: include/asm-generic/atomic-long.h:988
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (c041ece8)
Location: include/asm-generic/atomic-long.h:988
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (c04202f4)
Location: include/asm-generic/atomic-long.h:988
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (c0421528)
Location: include/asm-generic/atomic-long.h:988
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (c04258f8)
Location: include/asm-generic/atomic-long.h:988
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/events/core.c (c04cdf0c)
Location: include/asm-generic/atomic-long.h:988
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/page-writeback.c (c04e8ddc)
Location: include/asm-generic/atomic-long.h:988
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (c05036ac)
Location: include/asm-generic/atomic-long.h:988
Inline: True
```
```
In mm/slub.c (c0549938)
Location: include/asm-generic/atomic-long.h:988
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (c055c764)
Location: include/asm-generic/atomic-long.h:988
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In fs/fs-writeback.c (c05a70d8)
Location: include/asm-generic/atomic-long.h:988
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/aio.c (c05cedb0)
Location: include/asm-generic/atomic-long.h:988
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (c05d7568)
Location: include/asm-generic/atomic-long.h:988
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_enter
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (c0788394)
Location: include/asm-generic/atomic-long.h:988
Inline: True
Inline callers:
  - block/bio.c:__bio_associate_blkg
```
```
In block/blk-core.c (c0791654)
Location: include/asm-generic/atomic-long.h:988
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (c079af88)
Location: include/asm-generic/atomic-long.h:988
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (c07a060c)
Location: include/asm-generic/atomic-long.h:988
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (c07b9254)
Location: include/asm-generic/atomic-long.h:988
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
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
In kernel/acct.c (c000000000230930)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (c000000000246278)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (c00000000024a960)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (c00000000024c91c)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (c00000000024e368)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (c000000000255370)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/events/core.c (c00000000034f7e0)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/page-writeback.c (c000000000374c50)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (c00000000039d7e0)
Location: include/asm-generic/atomic-long.h:494
Inline: True
```
```
In mm/slub.c (c0000000004221e0)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (c00000000045a85c)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (c00000000045d8e0)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memremap.c (c00000000046db10)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/fs-writeback.c (c0000000004cc660)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/aio.c (c000000000504058)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (c00000000050eb10)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_enter
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (c00000000076b6e0)
Location: include/asm-generic/atomic-long.h:494
Inline: True
```
```
In block/blk-core.c (c000000000778120)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (c000000000783e80)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (c00000000078c340)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (c0000000007abfc0)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
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
In kernel/acct.c (ffffffe0001481d0)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffe000151d1a)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffe000154944)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffe000155c64)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffe000156b8a)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffe00015ac6e)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/events/core.c (ffffffe0001c9bae)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/page-writeback.c (ffffffe0001df3b6)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffe0001f61ae)
Location: include/asm-generic/atomic-long.h:494
Inline: True
```
```
In mm/slub.c (ffffffe000238082)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffe000248804)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffe00024a412)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/fs-writeback.c (ffffffe000288c80)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/aio.c (ffffffe0002a9308)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffffffe0002b101e)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_enter
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (ffffffe00041e422)
Location: include/asm-generic/atomic-long.h:494
Inline: True
```
```
In block/blk-core.c (ffffffe000425bda)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffe00042d4ec)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffe0004328d6)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffe000446e42)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
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
In kernel/acct.c (ffffffff8115134f)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff8115f504)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81161da2)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81162f40)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff81163e43)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff811699db)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/events/core.c (ffffffff8120cd49)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/page-writeback.c (ffffffff81225ecf)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff812412d2)
Location: include/asm-generic/atomic-long.h:494
Inline: True
```
```
In mm/slub.c (ffffffff8129c408)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812c0775)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff812c2497)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memremap.c (ffffffff812cc9df)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/fs-writeback.c (ffffffff8130d19b)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/aio.c (ffffffff8133338e)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffffffff8133c44b)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (ffffffff814d69c8)
Location: include/asm-generic/atomic-long.h:494
Inline: True
```
```
In block/blk-core.c (ffffffff814df0ea)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff814e74b9)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff814ed14e)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff81503663)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
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
In kernel/acct.c (ffffffff8114462f)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff81152794)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81155002)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81156190)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff81157093)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff8115cbdb)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/events/core.c (ffffffff811ffb19)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/page-writeback.c (ffffffff8121906f)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff812342d2)
Location: include/asm-generic/atomic-long.h:494
Inline: True
```
```
In mm/slub.c (ffffffff8128dfb9)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812b1835)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff812b34e7)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memremap.c (ffffffff812bd84f)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/fs-writeback.c (ffffffff812fddab)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/aio.c (ffffffff81323ffe)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffffffff8132d11b)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (ffffffff814c7388)
Location: include/asm-generic/atomic-long.h:494
Inline: True
```
```
In block/blk-core.c (ffffffff814cfa8a)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff814d7a29)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff814dd69e)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff814f3b23)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
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
In kernel/acct.c (ffffffff8114f1ff)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff8115d2d4)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115fb72)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81160d10)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff81161c13)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff811677ab)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/events/core.c (ffffffff8120aae9)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/page-writeback.c (ffffffff81223c6f)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff8123f072)
Location: include/asm-generic/atomic-long.h:494
Inline: True
```
```
In mm/slub.c (ffffffff8129a218)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812be585)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff812c02a7)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memremap.c (ffffffff812ca7ef)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/fs-writeback.c (ffffffff8130af8b)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/aio.c (ffffffff81330e5e)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffffffff81339f1b)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (ffffffff814d2a58)
Location: include/asm-generic/atomic-long.h:494
Inline: True
```
```
In block/blk-core.c (ffffffff814db17a)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff814e3549)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff814e91de)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff814ff6f3)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
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
In kernel/acct.c (ffffffff8115c008)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff8116a4eb)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8116ce72)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8116e149)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8116f0bd)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff81174ed5)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/events/core.c (ffffffff812198cd)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/page-writeback.c (ffffffff81232ef9)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff8124ebb4)
Location: include/asm-generic/atomic-long.h:494
Inline: True
```
```
In mm/slub.c (ffffffff812aa0c2)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812cefcd)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff812d0d6e)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memremap.c (ffffffff812db54f)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/fs-writeback.c (ffffffff8131c71a)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/aio.c (ffffffff81343a59)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffffffff8134d913)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (ffffffff814eb5c5)
Location: include/asm-generic/atomic-long.h:494
Inline: True
```
```
In block/blk-core.c (ffffffff814f3fb9)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff814fc46a)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff81502196)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff815188d1)
Location: include/asm-generic/atomic-long.h:494
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
```
</details>
</li>
</ul>

## Differences
