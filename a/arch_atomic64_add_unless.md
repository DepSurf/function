# Function: <code>arch_atomic64_add_unless</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8108b823)
Location: arch/x86/include/asm/atomic64_64.h:200
Inline: True
Inline callers:
  - kernel/fork.c:copy_mm
  - kernel/fork.c:get_task_exe_file
```
```
In kernel/acct.c (ffffffff81136502)
Location: arch/x86/include/asm/atomic64_64.h:200
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff81143875)
Location: arch/x86/include/asm/atomic64_64.h:200
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811462a5)
Location: arch/x86/include/asm/atomic64_64.h:200
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
```
In kernel/cgroup/freezer.c (ffffffff8114698b)
Location: arch/x86/include/asm/atomic64_64.h:200
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_write
  - kernel/cgroup/freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff81147a11)
Location: arch/x86/include/asm/atomic64_64.h:200
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff8114c183)
Location: arch/x86/include/asm/atomic64_64.h:200
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/events/core.c (ffffffff811df6f2)
Location: arch/x86/include/asm/atomic64_64.h:200
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
```
```
In kernel/memremap.c (ffffffff811e96e9)
Location: arch/x86/include/asm/atomic64_64.h:200
Inline: True
Inline callers:
  - kernel/memremap.c:get_dev_pagemap
  - kernel/memremap.c:devm_memremap_pages_release
```
```
In mm/page-writeback.c (ffffffff811fdbf1)
Location: arch/x86/include/asm/atomic64_64.h:200
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff8121907a)
Location: arch/x86/include/asm/atomic64_64.h:200
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/memcontrol.c (ffffffff8128608d)
Location: arch/x86/include/asm/atomic64_64.h:200
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_mm
```
```
In mm/hugetlb_cgroup.c (ffffffff81287f03)
Location: arch/x86/include/asm/atomic64_64.h:200
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/hmm.c (ffffffff812928a9)
Location: arch/x86/include/asm/atomic64_64.h:200
Inline: True
Inline callers:
  - mm/hmm.c:hmm_devmem_release
```
```
In fs/file.c (ffffffff812bb874)
Location: arch/x86/include/asm/atomic64_64.h:200
Inline: True
Inline callers:
  - fs/file.c:__fget
```
```
In fs/fs-writeback.c (ffffffff812ccad8)
Location: arch/x86/include/asm/atomic64_64.h:200
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/aio.c (ffffffff812f290b)
Location: arch/x86/include/asm/atomic64_64.h:200
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In block/blk-core.c (ffffffff8148472d)
Location: arch/x86/include/asm/atomic64_64.h:200
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff8148f22f)
Location: arch/x86/include/asm/atomic64_64.h:200
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-cgroup.c (ffffffff814a7da9)
Location: arch/x86/include/asm/atomic64_64.h:200
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
</details>
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
In kernel/fork.c (ffffffff810a3855)
Location: include/linux/atomic-arch-fallback.h:2218
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/acct.c (ffffffff8116911c)
Location: include/linux/atomic-arch-fallback.h:2218
Inline: True
Inline callers:
  - kernel/acct.c:acct_get
```
```
In kernel/cgroup/cgroup.c (ffffffff81178557)
Location: include/linux/atomic-arch-fallback.h:2218
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8117b38d)
Location: include/linux/atomic-arch-fallback.h:2218
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8117c3de)
Location: include/linux/atomic-arch-fallback.h:2218
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8117d453)
Location: include/linux/atomic-arch-fallback.h:2218
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff811830cb)
Location: include/linux/atomic-arch-fallback.h:2218
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/bpf/task_iter.c (ffffffff812166ed)
Location: include/linux/atomic-arch-fallback.h:2218
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_file_seq_get_next
```
```
In kernel/events/core.c (ffffffff81240744)
Location: include/linux/atomic-arch-fallback.h:2218
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/page-writeback.c (ffffffff8125b39c)
Location: include/linux/atomic-arch-fallback.h:2218
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff81276e82)
Location: include/linux/atomic-arch-fallback.h:2218
Inline: True
```
```
In mm/slub.c (ffffffff812d98eb)
Location: include/linux/atomic-arch-fallback.h:2218
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812fd9ed)
Location: include/linux/atomic-arch-fallback.h:2218
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_charge
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff812ff99c)
Location: include/linux/atomic-arch-fallback.h:2218
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memremap.c (ffffffff8130a0b2)
Location: include/linux/atomic-arch-fallback.h:2218
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/file.c (ffffffff8133882d)
Location: include/linux/atomic-arch-fallback.h:2218
Inline: True
Inline callers:
  - fs/file.c:__fget_files
```
```
In fs/fs-writeback.c (ffffffff8134e598)
Location: include/linux/atomic-arch-fallback.h:2218
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/eventpoll.c (ffffffff8136cf16)
Location: include/linux/atomic-arch-fallback.h:2218
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_loop_check_proc
```
```
In fs/aio.c (ffffffff81374ead)
Location: include/linux/atomic-arch-fallback.h:2218
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffffffff8137fc3d)
Location: include/linux/atomic-arch-fallback.h:2218
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_show_fdinfo
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_submit_sqes
```
```
In block/bio.c (ffffffff8153d9c2)
Location: include/linux/atomic-arch-fallback.h:2218
Inline: True
Inline callers:
  - block/bio.c:__bio_associate_blkg
```
```
In block/blk-core.c (ffffffff81544e81)
Location: include/linux/atomic-arch-fallback.h:2218
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff8154f964)
Location: include/linux/atomic-arch-fallback.h:2218
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff81555541)
Location: include/linux/atomic-arch-fallback.h:2218
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/genhd.c (ffffffff8155a71a)
Location: include/linux/atomic-arch-fallback.h:2218
Inline: True
Inline callers:
  - block/genhd.c:disk_map_sector_rcu
  - block/genhd.c:disk_map_sector_rcu
```
```
In block/blk-cgroup.c (ffffffff8156c004)
Location: include/linux/atomic-arch-fallback.h:2218
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
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
In kernel/fork.c (ffffffff8109f207)
Location: include/linux/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/acct.c (ffffffff811657ac)
Location: include/linux/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - kernel/acct.c:acct_get
```
```
In kernel/cgroup/cgroup.c (ffffffff811752bf)
Location: include/linux/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8117826b)
Location: include/linux/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8117925e)
Location: include/linux/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8117a2bc)
Location: include/linux/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff8118005c)
Location: include/linux/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/bpf/task_iter.c (ffffffff81218626)
Location: include/linux/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_file_seq_get_next
```
```
In kernel/events/core.c (ffffffff8124acb3)
Location: include/linux/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/page-writeback.c (ffffffff81265509)
Location: include/linux/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff8128175f)
Location: include/linux/atomic-arch-fallback.h:2288
Inline: True
```
```
In mm/memcontrol.c (ffffffff81309e35)
Location: include/linux/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_charge
  - mm/memcontrol.c:obj_cgroup_charge
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:get_obj_cgroup_from_current
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff8130bce9)
Location: include/linux/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memremap.c (ffffffff81315d7a)
Location: include/linux/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/file.c (ffffffff813441c0)
Location: include/linux/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - fs/file.c:__fget_files
```
```
In fs/fs-writeback.c (ffffffff8135b3bd)
Location: include/linux/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/aio.c (ffffffff81382e4b)
Location: include/linux/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffffffff81396dd8)
Location: include/linux/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_show_fdinfo
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_grab_identity
```
```
In block/blk-core.c (ffffffff81561440)
Location: include/linux/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff8156bd4c)
Location: include/linux/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff81571c0b)
Location: include/linux/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff81586d2c)
Location: include/linux/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
```
```
In net/mptcp/subflow.c (ffffffff81bc37c9)
Location: include/linux/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
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
In kernel/fork.c (ffffffff810a00d7)
Location: include/linux/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/acct.c (ffffffff81166df9)
Location: include/linux/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff81175e25)
Location: include/linux/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81178dde)
Location: include/linux/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81179dce)
Location: include/linux/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8117ae3c)
Location: include/linux/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff81180b2c)
Location: include/linux/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/bpf/task_iter.c (ffffffff8121bdd9)
Location: include/linux/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_file_seq_get_next
```
```
In kernel/events/core.c (ffffffff8124f093)
Location: include/linux/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/page-writeback.c (ffffffff81269718)
Location: include/linux/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff8128660f)
Location: include/linux/atomic-arch-fallback.h:2288
Inline: True
```
```
In mm/memcontrol.c (ffffffff813106a5)
Location: include/linux/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:mem_cgroup_swapin_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:obj_cgroup_charge_pages
  - mm/memcontrol.c:obj_cgroup_uncharge_pages
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff813122e9)
Location: include/linux/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memremap.c (ffffffff8131bf6d)
Location: include/linux/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/file.c (ffffffff8134a560)
Location: include/linux/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - fs/file.c:__fget_files
```
```
In fs/fs-writeback.c (ffffffff81361fbd)
Location: include/linux/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/aio.c (ffffffff81389ebe)
Location: include/linux/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffffffff8139ecc5)
Location: include/linux/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_uring_show_fdinfo
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_req_complete_post
```
```
In block/blk-core.c (ffffffff81569b90)
Location: include/linux/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff81573842)
Location: include/linux/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff81579c11)
Location: include/linux/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff8158db7c)
Location: include/linux/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
```
```
In net/mptcp/subflow.c (ffffffff81bb3e66)
Location: include/linux/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
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
In kernel/fork.c (ffffffff810b3237)
Location: include/linux/atomic/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/acct.c (ffffffff8118c5b9)
Location: include/linux/atomic/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff8119d412)
Location: include/linux/atomic/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811a070e)
Location: include/linux/atomic/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff811a16ee)
Location: include/linux/atomic/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff811a2921)
Location: include/linux/atomic/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff811a891c)
Location: include/linux/atomic/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/bpf/task_iter.c (ffffffff81252cd9)
Location: include/linux/atomic/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_file_seq_get_next
```
```
In kernel/events/core.c (ffffffff81289dc3)
Location: include/linux/atomic/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/page-writeback.c (ffffffff812a61a0)
Location: include/linux/atomic/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff812c6159)
Location: include/linux/atomic/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In mm/swapfile.c (ffffffff813137df)
Location: include/linux/atomic/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_device
```
```
In mm/memcontrol.c (ffffffff8135b9bb)
Location: include/linux/atomic/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:mem_cgroup_swapin_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:obj_cgroup_charge_pages
  - mm/memcontrol.c:obj_cgroup_uncharge_pages
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_mm
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff8135dc2b)
Location: include/linux/atomic/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memremap.c (ffffffff8136924d)
Location: include/linux/atomic/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/file.c (ffffffff813982e3)
Location: include/linux/atomic/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - fs/file.c:__fget_files
```
```
In fs/fs-writeback.c (ffffffff813b081d)
Location: include/linux/atomic/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/aio.c (ffffffff813d719e)
Location: include/linux/atomic/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffffffff813eef69)
Location: include/linux/atomic/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_uring_show_fdinfo
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_req_complete_post
```
```
In block/blk-core.c (ffffffff815cc634)
Location: include/linux/atomic/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - block/blk-core.c:blk_try_enter_queue
```
```
In block/blk-mq.c (ffffffff815d7e45)
Location: include/linux/atomic/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff815def59)
Location: include/linux/atomic/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff815f35eb)
Location: include/linux/atomic/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
```
```
In net/mptcp/subflow.c (ffffffff81c825a8)
Location: include/linux/atomic/atomic-arch-fallback.h:2288
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
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
Location: include/linux/atomic/atomic-arch-fallback.h:2386
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/acct.c (ffffffff811bba3f)
Location: include/linux/atomic/atomic-arch-fallback.h:2386
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff811cd797)
Location: include/linux/atomic/atomic-arch-fallback.h:2386
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811d0e4c)
Location: include/linux/atomic/atomic-arch-fallback.h:2386
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff811d2045)
Location: include/linux/atomic/atomic-arch-fallback.h:2386
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff811d3400)
Location: include/linux/atomic/atomic-arch-fallback.h:2386
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff811d9b49)
Location: include/linux/atomic/atomic-arch-fallback.h:2386
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/bpf/task_iter.c (ffffffff8129ae6e)
Location: include/linux/atomic/atomic-arch-fallback.h:2386
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_file_seq_get_next
```
```
In kernel/events/core.c (ffffffff812de742)
Location: include/linux/atomic/atomic-arch-fallback.h:2386
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_get_aux_event
```
```
In mm/page-writeback.c (ffffffff812fee33)
Location: include/linux/atomic/atomic-arch-fallback.h:2386
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff813235d6)
Location: include/linux/atomic/atomic-arch-fallback.h:2386
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In mm/swapfile.c (ffffffff8137ee28)
Location: include/linux/atomic/atomic-arch-fallback.h:2386
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_device
```
```
In mm/slub.c (ffffffff813a698b)
Location: include/linux/atomic/atomic-arch-fallback.h:2386
Inline: True
```
```
In mm/memcontrol.c (ffffffff813d5ccc)
Location: include/linux/atomic/atomic-arch-fallback.h:2386
Inline: True
Inline callers:
  - mm/memcontrol.c:obj_cgroup_may_zswap
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:mem_cgroup_swapin_charge_page
  - mm/memcontrol.c:obj_cgroup_charge
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:obj_cgroup_uncharge_pages
  - mm/memcontrol.c:__get_obj_cgroup_from_memcg
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_mm
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff813d7d2e)
Location: include/linux/atomic/atomic-arch-fallback.h:2386
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memremap.c (ffffffff813e70a8)
Location: include/linux/atomic/atomic-arch-fallback.h:2386
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/file.c (ffffffff8141af54)
Location: include/linux/atomic/atomic-arch-fallback.h:2386
Inline: True
Inline callers:
  - fs/file.c:__fget_light
  - fs/file.c:fget_task
  - fs/file.c:fget_raw
  - fs/file.c:fget
```
```
In fs/fs-writeback.c (ffffffff814356ae)
Location: include/linux/atomic/atomic-arch-fallback.h:2386
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/aio.c (ffffffff81460d36)
Location: include/linux/atomic/atomic-arch-fallback.h:2386
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In block/blk-core.c (ffffffff8167a003)
Location: include/linux/atomic/atomic-arch-fallback.h:2386
Inline: True
Inline callers:
  - block/blk-core.c:bio_poll
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff81684584)
Location: include/linux/atomic/atomic-arch-fallback.h:2386
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_get_new_requests
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff8168d6c9)
Location: include/linux/atomic/atomic-arch-fallback.h:2386
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff816a4bd5)
Location: include/linux/atomic/atomic-arch-fallback.h:2386
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
```
```
In io_uring/io_uring.c (ffffffff816d6d66)
Location: include/linux/atomic/atomic-arch-fallback.h:2386
Inline: True
Inline callers:
  - io_uring/io_uring.c:__do_sys_io_uring_enter
```
```
In net/mptcp/subflow.c (ffffffff81e282d7)
Location: include/linux/atomic/atomic-arch-fallback.h:2386
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
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
Location: include/linux/atomic/atomic-arch-fallback.h:2386
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/acct.c (ffffffff811fd8cf)
Location: include/linux/atomic/atomic-arch-fallback.h:2386
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff81210e27)
Location: include/linux/atomic/atomic-arch-fallback.h:2386
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff812149ac)
Location: include/linux/atomic/atomic-arch-fallback.h:2386
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81215d75)
Location: include/linux/atomic/atomic-arch-fallback.h:2386
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff81217380)
Location: include/linux/atomic/atomic-arch-fallback.h:2386
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff8121f019)
Location: include/linux/atomic/atomic-arch-fallback.h:2386
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/bpf/syscall.c (ffffffff812c5ec3)
Location: include/linux/atomic/atomic-arch-fallback.h:2386
Inline: True
```
```
In kernel/bpf/helpers.c (ffffffff812f43b9)
Location: include/linux/atomic/atomic-arch-fallback.h:2386
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_cgroup_kptr_get
```
```
In kernel/bpf/task_iter.c (ffffffff812f7726)
Location: include/linux/atomic/atomic-arch-fallback.h:2386
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_file_seq_get_next
```
```
In kernel/bpf/memalloc.c (ffffffff8131bee4)
Location: include/linux/atomic/atomic-arch-fallback.h:2386
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:alloc_bulk
```
```
In kernel/events/core.c (ffffffff813468fc)
Location: include/linux/atomic/atomic-arch-fallback.h:2386
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:event_sched_out
  - kernel/events/core.c:perf_get_aux_event
```
```
In mm/page-writeback.c (ffffffff813695b7)
Location: include/linux/atomic/atomic-arch-fallback.h:2386
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
```
```
In mm/vmscan.c (ffffffff81382654)
Location: include/linux/atomic/atomic-arch-fallback.h:2386
Inline: True
Inline callers:
  - mm/vmscan.c:run_cmd
```
```
In mm/backing-dev.c (ffffffff81397e26)
Location: include/linux/atomic/atomic-arch-fallback.h:2386
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In mm/swapfile.c (ffffffff813fd92e)
Location: include/linux/atomic/atomic-arch-fallback.h:2386
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_device
```
```
In mm/slub.c (ffffffff81427f6b)
Location: include/linux/atomic/atomic-arch-fallback.h:2386
Inline: True
```
```
In mm/memcontrol.c (ffffffff8145b6b3)
Location: include/linux/atomic/atomic-arch-fallback.h:2386
Inline: True
Inline callers:
  - mm/memcontrol.c:obj_cgroup_may_zswap
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:mem_cgroup_swapin_charge_folio
  - mm/memcontrol.c:obj_cgroup_charge
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:obj_cgroup_uncharge_pages
  - mm/memcontrol.c:__get_obj_cgroup_from_memcg
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_mm
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff8145db9c)
Location: include/linux/atomic/atomic-arch-fallback.h:2386
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memremap.c (ffffffff8146f8c5)
Location: include/linux/atomic/atomic-arch-fallback.h:2386
Inline: True
Inline callers:
  - mm/memremap.c:zone_device_page_init
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/file.c (ffffffff814a6eda)
Location: include/linux/atomic/atomic-arch-fallback.h:2386
Inline: True
Inline callers:
  - fs/file.c:__fget_light
  - fs/file.c:fget_task
  - fs/file.c:fget_raw
  - fs/file.c:fget
```
```
In fs/fs-writeback.c (ffffffff814c371b)
Location: include/linux/atomic/atomic-arch-fallback.h:2386
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/aio.c (ffffffff814f0ce6)
Location: include/linux/atomic/atomic-arch-fallback.h:2386
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In block/blk-core.c (ffffffff817364a8)
Location: include/linux/atomic/atomic-arch-fallback.h:2386
Inline: True
Inline callers:
  - block/blk-core.c:bio_poll
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff817423af)
Location: include/linux/atomic/atomic-arch-fallback.h:2386
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_get_new_requests
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff8174bec2)
Location: include/linux/atomic/atomic-arch-fallback.h:2386
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff81763964)
Location: include/linux/atomic/atomic-arch-fallback.h:2386
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
```
```
In io_uring/fdinfo.c (ffffffff8179b972)
Location: include/linux/atomic/atomic-arch-fallback.h:2386
Inline: True
Inline callers:
  - io_uring/fdinfo.c:io_uring_show_fdinfo
```
```
In drivers/pci/p2pdma.c (ffffffff8191c6f8)
Location: include/linux/atomic/atomic-arch-fallback.h:2386
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_alloc_p2pmem
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In net/mptcp/subflow.c (ffffffff82000239)
Location: include/linux/atomic/atomic-arch-fallback.h:2386
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
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
