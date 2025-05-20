# Function: <code>arch_atomic64_try_cmpxchg</code>

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
In kernel/fork.c (ffffffff8108b830)
Location: arch/x86/include/asm/atomic64_64.h:181
Inline: True
Inline callers:
  - kernel/fork.c:copy_mm
  - kernel/fork.c:get_task_exe_file
```
```
In kernel/locking/mutex.c (ffffffff819ef00d)
Location: arch/x86/include/asm/atomic64_64.h:181
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_lock_killable
  - kernel/locking/mutex.c:mutex_lock_interruptible
  - kernel/locking/mutex.c:mutex_lock
```
```
In kernel/acct.c (ffffffff8113650f)
Location: arch/x86/include/asm/atomic64_64.h:181
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff81143882)
Location: arch/x86/include/asm/atomic64_64.h:181
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811462b2)
Location: arch/x86/include/asm/atomic64_64.h:181
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
```
In kernel/cgroup/freezer.c (ffffffff81146998)
Location: arch/x86/include/asm/atomic64_64.h:181
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_write
  - kernel/cgroup/freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff81147a1e)
Location: arch/x86/include/asm/atomic64_64.h:181
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff8114c190)
Location: arch/x86/include/asm/atomic64_64.h:181
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/events/core.c (ffffffff811df702)
Location: arch/x86/include/asm/atomic64_64.h:181
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
```
```
In kernel/memremap.c (ffffffff811e96f5)
Location: arch/x86/include/asm/atomic64_64.h:181
Inline: True
Inline callers:
  - kernel/memremap.c:get_dev_pagemap
  - kernel/memremap.c:devm_memremap_pages_release
```
```
In mm/page-writeback.c (ffffffff811fdc01)
Location: arch/x86/include/asm/atomic64_64.h:181
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff8121908b)
Location: arch/x86/include/asm/atomic64_64.h:181
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/memcontrol.c (ffffffff8128609a)
Location: arch/x86/include/asm/atomic64_64.h:181
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_mm
```
```
In mm/hugetlb_cgroup.c (ffffffff81287f10)
Location: arch/x86/include/asm/atomic64_64.h:181
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/hmm.c (ffffffff812928bd)
Location: arch/x86/include/asm/atomic64_64.h:181
Inline: True
Inline callers:
  - mm/hmm.c:hmm_devmem_release
```
```
In fs/file.c (ffffffff812bb881)
Location: arch/x86/include/asm/atomic64_64.h:181
Inline: True
Inline callers:
  - fs/file.c:__fget
```
```
In fs/fs-writeback.c (ffffffff812ccae5)
Location: arch/x86/include/asm/atomic64_64.h:181
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/aio.c (ffffffff812f2917)
Location: arch/x86/include/asm/atomic64_64.h:181
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In block/blk-core.c (ffffffff8148473d)
Location: arch/x86/include/asm/atomic64_64.h:181
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff8148f23f)
Location: arch/x86/include/asm/atomic64_64.h:181
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-cgroup.c (ffffffff814a7db6)
Location: arch/x86/include/asm/atomic64_64.h:181
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
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
In kernel/fork.c (ffffffff8109230f)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/locking/mutex.c (ffffffff81a2a34d)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_lock_killable
  - kernel/locking/mutex.c:mutex_lock_interruptible
  - kernel/locking/mutex.c:mutex_lock
```
```
In kernel/acct.c (ffffffff81141c9f)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff8114f3a2)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81151e49)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
```
In kernel/cgroup/freezer.c (ffffffff81152667)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_write
  - kernel/cgroup/freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff811532de)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff81158dd8)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/events/core.c (ffffffff811efb42)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
```
```
In kernel/memremap.c (ffffffff811fa08f)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/memremap.c:get_dev_pagemap
```
```
In mm/page-writeback.c (ffffffff81210730)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff8122be4e)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/memcontrol.c (ffffffff8129affb)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_page
```
```
In mm/hugetlb_cgroup.c (ffffffff8129ce57)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/file.c (ffffffff812d0a71)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - fs/file.c:__fget
```
```
In fs/fs-writeback.c (ffffffff812e1e21)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/aio.c (ffffffff81306a21)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In block/bio.c (ffffffff81498155)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
```
```
In block/blk-core.c (ffffffff8149f703)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff814a7b4f)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff814ad4bc)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff814c33b9)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/tty/tty_ldsem.c (ffffffff816379be)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_read
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
In kernel/fork.c (ffffffff81096665)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/locking/mutex.c (ffffffff81a9a455)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
  - kernel/locking/mutex.c:mutex_lock_killable
  - kernel/locking/mutex.c:mutex_lock_interruptible
  - kernel/locking/mutex.c:mutex_lock
```
```
In kernel/locking/rwsem.c (ffffffff810f7b25)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_write_trylock
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read_trylock
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
```
In kernel/acct.c (ffffffff8114d06d)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff8115b233)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115db7f)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8115ecce)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8115fbd0)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff811654d8)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/events/core.c (ffffffff81207346)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/page-writeback.c (ffffffff8121fddf)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff8123b813)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slub.c (ffffffff812940c5)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812b62cd)
Location: arch/x86/include/asm/atomic64_64.h:184
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
In mm/hugetlb_cgroup.c (ffffffff812b8017)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memremap.c (ffffffff812c24db)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/file.c (ffffffff812edaa3)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - fs/file.c:__fget
```
```
In fs/fs-writeback.c (ffffffff813002e3)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/aio.c (ffffffff8132801a)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffffffff813305fb)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
  - fs/io_uring.c:io_submit_sqe
```
```
In block/bio.c (ffffffff814c5ff5)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
```
```
In block/blk-core.c (ffffffff814cd82b)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff814d5bb9)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff814db752)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff814f1ac3)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/tty/tty_ldsem.c (ffffffff8166bc8e)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_read
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
In kernel/fork.c (ffffffff8109cc25)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/locking/mutex.c (ffffffff81ad1da5)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
  - kernel/locking/mutex.c:mutex_lock_killable
  - kernel/locking/mutex.c:mutex_lock_interruptible
  - kernel/locking/mutex.c:mutex_lock
```
```
In kernel/locking/rwsem.c (ffffffff81103955)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_write_trylock
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read_trylock
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
```
In kernel/acct.c (ffffffff81158d3d)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff81166ef1)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8116978f)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8116a92e)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8116b830)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff811713c8)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/events/core.c (ffffffff812146b6)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/page-writeback.c (ffffffff8122d88f)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff81248c93)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
```
```
In mm/slub.c (ffffffff812a3e35)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812c81a2)
Location: arch/x86/include/asm/atomic64_64.h:184
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
In mm/hugetlb_cgroup.c (ffffffff812c9ec4)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memremap.c (ffffffff812d440b)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/file.c (ffffffff812ff563)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - fs/file.c:__fget
```
```
In fs/fs-writeback.c (ffffffff81314bc8)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/aio.c (ffffffff8133adba)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffffffff81343e77)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (ffffffff814de3f5)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
```
```
In block/blk-core.c (ffffffff814e6b1b)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff814eeee9)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff814f4b82)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff8150b090)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/tty/tty_ldsem.c (ffffffff8168e2fe)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_read
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
In kernel/fork.c (ffffffff810a3862)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/locking/mutex.c (ffffffff8110e1ab)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
  - kernel/locking/mutex.c:mutex_lock_io
  - kernel/locking/mutex.c:mutex_lock_killable
  - kernel/locking/mutex.c:mutex_lock_interruptible
```
```
In kernel/locking/rwsem.c (ffffffff8110e4a5)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_write_trylock
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read_trylock
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
```
In kernel/acct.c (ffffffff8116912a)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/acct.c:acct_get
```
```
In kernel/cgroup/cgroup.c (ffffffff81178564)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8117b39a)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8117c3ec)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8117d460)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff811830d8)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/bpf/syscall.c (ffffffff81200dcc)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_get_fd_by_id
  - kernel/bpf/syscall.c:bpf_prog_inc_not_zero
  - kernel/bpf/syscall.c:__bpf_map_inc_not_zero
```
```
In kernel/bpf/task_iter.c (ffffffff812166fe)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_file_seq_get_next
```
```
In kernel/events/core.c (ffffffff8124075b)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/page-writeback.c (ffffffff8125b3ac)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff81276e93)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
```
```
In mm/slub.c (ffffffff812d98f8)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812fd9fa)
Location: arch/x86/include/asm/atomic64_64.h:188
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
In mm/hugetlb_cgroup.c (ffffffff812ff9a9)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memremap.c (ffffffff8130a0be)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/file.c (ffffffff8133883e)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - fs/file.c:__fget_files
```
```
In fs/fs-writeback.c (ffffffff8134e5a5)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/eventpoll.c (ffffffff8136cf23)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_loop_check_proc
```
```
In fs/aio.c (ffffffff81374eb9)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffffffff8137fc4a)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_show_fdinfo
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_submit_sqes
```
```
In block/bio.c (ffffffff8153d9cf)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - block/bio.c:__bio_associate_blkg
```
```
In block/blk-core.c (ffffffff81544e91)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff8154f974)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff81555555)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/genhd.c (ffffffff8155a727)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - block/genhd.c:disk_map_sector_rcu
  - block/genhd.c:disk_map_sector_rcu
```
```
In block/blk-cgroup.c (ffffffff8156c011)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/tty/tty_ldsem.c (ffffffff817405be)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_read_trylock
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:__ldsem_wake_readers
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
In kernel/fork.c (ffffffff8109f215)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/locking/mutex.c (ffffffff8110b46b)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
  - kernel/locking/mutex.c:mutex_lock_io
  - kernel/locking/mutex.c:mutex_lock_killable
  - kernel/locking/mutex.c:mutex_lock_interruptible
```
```
In kernel/locking/rwsem.c (ffffffff8110bd85)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_write_trylock
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read_trylock
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_interruptible
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff8111c4cf)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:_prb_commit
  - kernel/printk/printk_ringbuffer.c:prb_reserve_in_last
  - kernel/printk/printk_ringbuffer.c:data_realloc
  - kernel/printk/printk_ringbuffer.c:data_alloc
  - kernel/printk/printk_ringbuffer.c:desc_reserve
  - kernel/printk/printk_ringbuffer.c:desc_reserve
```
```
In kernel/acct.c (ffffffff811657ba)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/acct.c:acct_get
```
```
In kernel/cgroup/cgroup.c (ffffffff811752cb)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81178278)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8117926a)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8117a2c8)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff81180068)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/bpf/syscall.c (ffffffff811fa63c)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_inc_not_zero
  - kernel/bpf/syscall.c:__bpf_map_inc_not_zero
```
```
In kernel/bpf/task_iter.c (ffffffff81218638)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_file_seq_get_next
```
```
In kernel/events/core.c (ffffffff8124acca)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/page-writeback.c (ffffffff81265515)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff8128176b)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
```
```
In mm/memcontrol.c (ffffffff81309e42)
Location: arch/x86/include/asm/atomic64_64.h:188
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
In mm/hugetlb_cgroup.c (ffffffff8130bcf5)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memremap.c (ffffffff81315d86)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/file.c (ffffffff813441d3)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - fs/file.c:__fget_files
```
```
In fs/fs-writeback.c (ffffffff8135b3c9)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/aio.c (ffffffff81382e57)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffffffff81396de5)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_show_fdinfo
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_grab_identity
```
```
In block/blk-core.c (ffffffff8156144c)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff8156bd59)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff81571c17)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff81586d38)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/tty/tty_ldsem.c (ffffffff8175c4ee)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_read_trylock
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:__ldsem_wake_readers
```
```
In net/mptcp/subflow.c (ffffffff81bc37d5)
Location: arch/x86/include/asm/atomic64_64.h:188
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
In kernel/fork.c (ffffffff810a00e5)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/locking/mutex.c (ffffffff8110d28b)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
  - kernel/locking/mutex.c:mutex_lock_io
  - kernel/locking/mutex.c:mutex_lock_killable
  - kernel/locking/mutex.c:mutex_lock_interruptible
```
```
In kernel/locking/rwsem.c (ffffffff8110dba5)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_write_trylock
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read_trylock
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_interruptible
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff8111d47c)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_final_commit
  - kernel/printk/printk_ringbuffer.c:prb_commit
  - kernel/printk/printk_ringbuffer.c:prb_reserve
  - kernel/printk/printk_ringbuffer.c:prb_reserve
  - kernel/printk/printk_ringbuffer.c:prb_reserve_in_last
  - kernel/printk/printk_ringbuffer.c:data_realloc
  - kernel/printk/printk_ringbuffer.c:data_alloc
```
```
In kernel/acct.c (ffffffff81166e07)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff81175e31)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81178deb)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81179dda)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8117ae48)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff81180b38)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/bpf/syscall.c (ffffffff811fb59c)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_inc_not_zero
  - kernel/bpf/syscall.c:__bpf_map_inc_not_zero
```
```
In kernel/bpf/task_iter.c (ffffffff8121bdeb)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_file_seq_get_next
```
```
In kernel/events/core.c (ffffffff8124f0aa)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/page-writeback.c (ffffffff81269724)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff8128661b)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
```
```
In mm/memcontrol.c (ffffffff813106b2)
Location: arch/x86/include/asm/atomic64_64.h:188
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
In mm/hugetlb_cgroup.c (ffffffff813122f5)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memremap.c (ffffffff8131bf79)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/file.c (ffffffff8134a573)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - fs/file.c:__fget_files
```
```
In fs/fs-writeback.c (ffffffff81361fc9)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/aio.c (ffffffff81389eca)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffffffff8139ecd1)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_uring_show_fdinfo
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_req_complete_post
```
```
In block/blk-core.c (ffffffff81569b9c)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff8157384f)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff81579c1d)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff8158db88)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/tty/tty_ldsem.c (ffffffff8174038e)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_read_trylock
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:__ldsem_wake_readers
```
```
In net/mptcp/subflow.c (ffffffff81bb3e72)
Location: arch/x86/include/asm/atomic64_64.h:188
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
In kernel/fork.c (ffffffff810b3245)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/ucount.c (ffffffff810ea2bb)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/ucount.c:dec_ucount
```
```
In kernel/locking/mutex.c (ffffffff8112cacb)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
  - kernel/locking/mutex.c:mutex_trylock
  - kernel/locking/mutex.c:mutex_lock_io
  - kernel/locking/mutex.c:mutex_lock_killable
  - kernel/locking/mutex.c:mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_unlock
```
```
In kernel/locking/rwsem.c (ffffffff8112d455)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_write_trylock
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read_trylock
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_interruptible
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff8113d7cb)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_final_commit
  - kernel/printk/printk_ringbuffer.c:prb_commit
  - kernel/printk/printk_ringbuffer.c:prb_reserve
  - kernel/printk/printk_ringbuffer.c:prb_reserve
  - kernel/printk/printk_ringbuffer.c:prb_reserve_in_last
  - kernel/printk/printk_ringbuffer.c:data_realloc
  - kernel/printk/printk_ringbuffer.c:data_alloc
```
```
In kernel/acct.c (ffffffff8118c5c7)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff8119d41e)
Location: arch/x86/include/asm/atomic64_64.h:188
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
In kernel/cgroup/cgroup-v1.c (ffffffff811a071b)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff811a16fa)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff811a292d)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff811a8928)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/bpf/syscall.c (ffffffff8122cd0c)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_inc_not_zero
  - kernel/bpf/syscall.c:__bpf_map_inc_not_zero
```
```
In kernel/bpf/task_iter.c (ffffffff81252ceb)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_file_seq_get_next
```
```
In kernel/events/core.c (ffffffff81289dda)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/page-writeback.c (ffffffff812a61ac)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff812c6165)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In mm/swapfile.c (ffffffff813137eb)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_device
```
```
In mm/memcontrol.c (ffffffff8135b9c7)
Location: arch/x86/include/asm/atomic64_64.h:188
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
In mm/hugetlb_cgroup.c (ffffffff8135dc37)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memremap.c (ffffffff81369259)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/file.c (ffffffff813982f4)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - fs/file.c:__fget_files
```
```
In fs/fs-writeback.c (ffffffff813b0829)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/aio.c (ffffffff813d71aa)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffffffff813eef75)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_uring_show_fdinfo
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_req_complete_post
```
```
In block/blk-core.c (ffffffff815cc640)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - block/blk-core.c:blk_try_enter_queue
```
```
In block/blk-mq.c (ffffffff815d7e52)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff815def65)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff815f35f7)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/tty/tty_ldsem.c (ffffffff817c0b6e)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_read_trylock
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:__ldsem_wake_readers
```
```
In net/mptcp/subflow.c (ffffffff81c825b4)
Location: arch/x86/include/asm/atomic64_64.h:188
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
In kernel/fork.c (ffffffff810c944b)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/ucount.c (ffffffff81104f3b)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/ucount.c:dec_ucount
```
```
In kernel/locking/mutex.c (ffffffff8114dd0e)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
  - kernel/locking/mutex.c:mutex_lock_io
  - kernel/locking/mutex.c:mutex_lock_killable
  - kernel/locking/mutex.c:mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_trylock
  - kernel/locking/mutex.c:ww_mutex_trylock
  - kernel/locking/mutex.c:ww_mutex_unlock
```
```
In kernel/locking/rwsem.c (ffffffff8114e825)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_write_trylock
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read_trylock
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_interruptible
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff8115f795)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:_prb_commit
  - kernel/printk/printk_ringbuffer.c:prb_reserve_in_last
  - kernel/printk/printk_ringbuffer.c:data_realloc
  - kernel/printk/printk_ringbuffer.c:data_alloc
  - kernel/printk/printk_ringbuffer.c:desc_reserve
  - kernel/printk/printk_ringbuffer.c:desc_reserve
  - kernel/printk/printk_ringbuffer.c:data_push_tail
```
```
In kernel/acct.c (ffffffff811bba4c)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff811cd7a3)
Location: arch/x86/include/asm/atomic64_64.h:188
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
In kernel/cgroup/cgroup-v1.c (ffffffff811d0e58)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff811d2051)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff811d340c)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff811d9b59)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/bpf/syscall.c (ffffffff8126f0c5)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_inc_not_zero
  - kernel/bpf/syscall.c:bpf_prog_inc_not_zero
  - kernel/bpf/syscall.c:__bpf_map_inc_not_zero
```
```
In kernel/bpf/task_iter.c (ffffffff8129ae7b)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_file_seq_get_next
```
```
In kernel/events/core.c (ffffffff812de752)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:perf_get_aux_event
```
```
In mm/page-writeback.c (ffffffff812fee3f)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff813235e6)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In mm/swapfile.c (ffffffff8137ee34)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_device
```
```
In mm/slub.c (ffffffff813a6997)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
```
```
In mm/memcontrol.c (ffffffff813d5cd8)
Location: arch/x86/include/asm/atomic64_64.h:188
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
In mm/hugetlb_cgroup.c (ffffffff813d7d3a)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memremap.c (ffffffff813e70b4)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/file.c (ffffffff8141af61)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - fs/file.c:__fget_light
  - fs/file.c:fget_task
  - fs/file.c:fget_raw
  - fs/file.c:fget
```
```
In fs/fs-writeback.c (ffffffff814356be)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/aio.c (ffffffff81460d42)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In block/blk-core.c (ffffffff8167a013)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - block/blk-core.c:bio_poll
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff81684590)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_get_new_requests
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff8168d6d5)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff816a4be1)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
```
```
In io_uring/io_uring.c (ffffffff816d6d76)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - io_uring/io_uring.c:__do_sys_io_uring_enter
```
```
In drivers/tty/tty_ldsem.c (ffffffff818fd42e)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_read_trylock
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:__ldsem_wake_readers
```
```
In net/mptcp/subflow.c (ffffffff81e282e3)
Location: arch/x86/include/asm/atomic64_64.h:188
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
In kernel/fork.c (ffffffff810e696b)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/ucount.c (ffffffff8112a92d)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/ucount.c:dec_ucount
```
```
In kernel/locking/mutex.c (ffffffff8117cece)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
  - kernel/locking/mutex.c:mutex_lock_io
  - kernel/locking/mutex.c:mutex_lock_killable
  - kernel/locking/mutex.c:mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_trylock
  - kernel/locking/mutex.c:ww_mutex_trylock
  - kernel/locking/mutex.c:ww_mutex_unlock
```
```
In kernel/locking/rwsem.c (ffffffff8117d89c)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_write_trylock
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read_trylock
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_interruptible
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff81192af5)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:_prb_commit
  - kernel/printk/printk_ringbuffer.c:prb_reserve_in_last
  - kernel/printk/printk_ringbuffer.c:data_realloc
  - kernel/printk/printk_ringbuffer.c:data_alloc
  - kernel/printk/printk_ringbuffer.c:desc_reserve
  - kernel/printk/printk_ringbuffer.c:desc_reserve
  - kernel/printk/printk_ringbuffer.c:data_push_tail
```
```
In kernel/acct.c (ffffffff811fd8dc)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff81210e33)
Location: arch/x86/include/asm/atomic64_64.h:188
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
In kernel/cgroup/cgroup-v1.c (ffffffff812149b8)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81215d81)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8121738c)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff8121f029)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/bpf/syscall.c (ffffffff812c4935)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_inc_not_zero
  - kernel/bpf/syscall.c:bpf_prog_inc_not_zero
  - kernel/bpf/syscall.c:__bpf_map_inc_not_zero
```
```
In kernel/bpf/helpers.c (ffffffff812f43c5)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_cgroup_kptr_get
```
```
In kernel/bpf/task_iter.c (ffffffff812f7733)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_file_seq_get_next
```
```
In kernel/bpf/memalloc.c (ffffffff8131bef0)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:alloc_bulk
```
```
In kernel/events/core.c (ffffffff8134690c)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:event_sched_out
  - kernel/events/core.c:perf_get_aux_event
```
```
In mm/page-writeback.c (ffffffff813695c3)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
```
```
In mm/vmscan.c (ffffffff81382660)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - mm/vmscan.c:run_cmd
```
```
In mm/backing-dev.c (ffffffff81397e36)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In mm/swapfile.c (ffffffff813fd93a)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_device
```
```
In mm/slub.c (ffffffff81427f77)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
```
```
In mm/memcontrol.c (ffffffff8145b6bf)
Location: arch/x86/include/asm/atomic64_64.h:188
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
In mm/hugetlb_cgroup.c (ffffffff8145dba8)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memremap.c (ffffffff8146f8d1)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - mm/memremap.c:zone_device_page_init
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/file.c (ffffffff814a6ee7)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - fs/file.c:__fget_light
  - fs/file.c:fget_task
  - fs/file.c:fget_raw
  - fs/file.c:fget
```
```
In fs/libfs.c (ffffffff814b7b8a)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - fs/libfs.c:inode_maybe_inc_iversion
```
```
In fs/fs-writeback.c (ffffffff814c372b)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/aio.c (ffffffff814f0cf2)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/ext4/dir.c (ffffffff81559754)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff8157758c)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/fat/namei_vfat.c (ffffffff81606381)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_lookup
```
```
In fs/fuse/readdir.c (ffffffff8162f93a)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
```
```
In security/integrity/ima/ima_api.c (ffffffff816f9837)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
```
In block/blk-core.c (ffffffff817364b8)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - block/blk-core.c:bio_poll
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff817423bb)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_get_new_requests
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff8174bece)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff81763970)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_scale_delay
  - block/blk-cgroup.c:blkg_create
```
```
In io_uring/fdinfo.c (ffffffff8179b97e)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - io_uring/fdinfo.c:io_uring_show_fdinfo
```
```
In io_uring/rsrc.c (ffffffff817a0876)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - io_uring/rsrc.c:__io_account_mem
```
```
In lib/sbitmap.c (ffffffff818a4294)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_queue_get_batch
```
```
In drivers/pci/p2pdma.c (ffffffff8191c704)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_alloc_p2pmem
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/tty/tty_ldsem.c (ffffffff81a56b0e)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_read_trylock
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:__ldsem_wake_readers
```
```
In net/core/skbuff.c (ffffffff81da6640)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_account_pinned_pages
```
```
In net/mptcp/subflow.c (ffffffff82000245)
Location: arch/x86/include/asm/atomic64_64.h:188
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
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
In arch/x86/kernel/pvclock.c (ffffffff821410cc)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read_nowd
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In kernel/fork.c (ffffffff810f230b)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/ucount.c (ffffffff811379ad)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - kernel/ucount.c:dec_ucount
```
```
In kernel/locking/mutex.c (ffffffff8118db7e)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
  - kernel/locking/mutex.c:mutex_lock_io
  - kernel/locking/mutex.c:mutex_lock_killable
  - kernel/locking/mutex.c:mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_trylock
  - kernel/locking/mutex.c:ww_mutex_trylock
  - kernel/locking/mutex.c:ww_mutex_unlock
```
```
In kernel/locking/rwsem.c (ffffffff8118e53c)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_write_trylock
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read_trylock
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_interruptible
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff811a4355)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:_prb_commit
  - kernel/printk/printk_ringbuffer.c:prb_reserve_in_last
  - kernel/printk/printk_ringbuffer.c:data_realloc
  - kernel/printk/printk_ringbuffer.c:data_alloc
  - kernel/printk/printk_ringbuffer.c:desc_reserve
  - kernel/printk/printk_ringbuffer.c:desc_reserve
  - kernel/printk/printk_ringbuffer.c:data_push_tail
```
```
In kernel/dma/swiotlb.c (ffffffff811d72ff)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_do_find_slots
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811fd9f9)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
```
```
In kernel/acct.c (ffffffff81212a5c)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff81226823)
Location: arch/x86/include/asm/atomic64_64.h:107
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
In kernel/cgroup/cgroup-v1.c (ffffffff8122a2d8)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8122b6ba)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8122ccac)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff81235159)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/bpf/syscall.c (ffffffff812eba15)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_inc_not_zero
  - kernel/bpf/syscall.c:bpf_prog_inc_not_zero
  - kernel/bpf/syscall.c:__bpf_map_inc_not_zero
```
```
In kernel/bpf/helpers.c (ffffffff81321563)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_cgroup_ancestor
  - kernel/bpf/helpers.c:bpf_cgroup_acquire
```
```
In kernel/bpf/task_iter.c (ffffffff81325613)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_file_seq_get_next
```
```
In kernel/bpf/memalloc.c (ffffffff8134c573)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:bpf_mem_cache_alloc_flags
  - kernel/bpf/memalloc.c:alloc_bulk
```
```
In kernel/events/core.c (ffffffff81377a12)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:event_sched_out
  - kernel/events/core.c:perf_get_aux_event
```
```
In mm/page-writeback.c (ffffffff8139b763)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
```
```
In mm/vmscan.c (ffffffff813b41cd)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - mm/vmscan.c:run_cmd
  - mm/vmscan.c:shrink_many
```
```
In mm/backing-dev.c (ffffffff813cadb6)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In mm/swapfile.c (ffffffff81430bfa)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_device
```
```
In mm/slub.c (ffffffff8145c9b7)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
```
```
In mm/memcontrol.c (ffffffff8149132f)
Location: arch/x86/include/asm/atomic64_64.h:107
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
In mm/hugetlb_cgroup.c (ffffffff81493898)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memremap.c (ffffffff814a40b1)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - mm/memremap.c:zone_device_page_init
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/file.c (ffffffff814dbec7)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - fs/file.c:__fget_light
  - fs/file.c:fget_task
  - fs/file.c:fget_raw
  - fs/file.c:fget
```
```
In fs/libfs.c (ffffffff814eca36)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - fs/libfs.c:inode_query_iversion
  - fs/libfs.c:inode_maybe_inc_iversion
```
```
In fs/fs-writeback.c (ffffffff814f8b0e)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/aio.c (ffffffff81527a92)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In block/blk-core.c (ffffffff81772ae5)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - block/blk-core.c:bio_poll
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff8177f9e4)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - block/blk-mq.c:blk_rq_poll
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_get_new_requests
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff817885ee)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff817a2a00)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_scale_delay
  - block/blk-cgroup.c:blkg_create
```
```
In io_uring/fdinfo.c (ffffffff817dcab0)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - io_uring/fdinfo.c:io_uring_show_fdinfo
```
```
In io_uring/rsrc.c (ffffffff817e1aca)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - io_uring/rsrc.c:__io_account_mem
```
```
In lib/sbitmap.c (ffffffff818e6724)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_queue_get_batch
```
```
In drivers/pci/p2pdma.c (ffffffff8195fcc4)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_alloc_p2pmem
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/tty/tty_ldsem.c (ffffffff81aa10ee)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_read_trylock
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:__ldsem_wake_readers
```
```
In drivers/md/md.c (ffffffff81d5fd11)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
```
```
In net/core/skbuff.c (ffffffff81e1574d)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_account_pinned_pages
```
```
In net/mptcp/subflow.c (ffffffff8207c417)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
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
In arch/x86/kernel/pvclock.c (ffffffff82222fdc)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read_nowd
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In kernel/cred.c (ffffffff8113e6cd)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - kernel/cred.c:get_task_cred
```
```
In kernel/ucount.c (ffffffff81142bbd)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - kernel/ucount.c:dec_ucount
```
```
In kernel/locking/mutex.c (ffffffff8119c52e)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
  - kernel/locking/mutex.c:mutex_lock_io
  - kernel/locking/mutex.c:mutex_lock_killable
  - kernel/locking/mutex.c:mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_trylock
  - kernel/locking/mutex.c:ww_mutex_trylock
  - kernel/locking/mutex.c:ww_mutex_unlock
```
```
In kernel/locking/rwsem.c (ffffffff8119ceec)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_write_trylock
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read_trylock
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_interruptible
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff811b3e45)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:_prb_commit
  - kernel/printk/printk_ringbuffer.c:prb_reserve_in_last
  - kernel/printk/printk_ringbuffer.c:data_realloc
  - kernel/printk/printk_ringbuffer.c:data_alloc
  - kernel/printk/printk_ringbuffer.c:desc_reserve
  - kernel/printk/printk_ringbuffer.c:desc_reserve
  - kernel/printk/printk_ringbuffer.c:data_push_tail
```
```
In kernel/dma/swiotlb.c (ffffffff811ec2c0)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_search_pool_area
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81213d19)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
```
```
In kernel/acct.c (ffffffff8122a0fc)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff8123e4b3)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:cgroup_tryget_css
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff812422b5)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:task_get_cgroup1
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff812436aa)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff81244d6c)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff8124eda8)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/bpf/syscall.c (ffffffff81309f65)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_inc_not_zero
  - kernel/bpf/syscall.c:bpf_prog_inc_not_zero
  - kernel/bpf/syscall.c:__bpf_map_inc_not_zero
```
```
In kernel/bpf/helpers.c (ffffffff81343c93)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_cgroup_ancestor
  - kernel/bpf/helpers.c:bpf_cgroup_acquire
```
```
In kernel/bpf/memalloc.c (ffffffff81371ecf)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
```
```
In kernel/events/core.c (ffffffff813a0cf2)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:event_sched_out
  - kernel/events/core.c:perf_get_aux_event
```
```
In mm/page-writeback.c (ffffffff813c56d3)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
```
```
In mm/vmscan.c (ffffffff813dd84d)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - mm/vmscan.c:run_cmd
  - mm/vmscan.c:shrink_many
```
```
In mm/backing-dev.c (ffffffff813f5d96)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In mm/workingset.c (ffffffff8140c45c)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - mm/workingset.c:workingset_test_recent
```
```
In mm/slub.c (ffffffff81454e91)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
```
```
In mm/swapfile.c (ffffffff8146a01a)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_device
```
```
In mm/zswap.c (ffffffff8147121c)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - mm/zswap.c:zswap_store
  - mm/zswap.c:zswap_store
  - mm/zswap.c:shrink_worker
  - mm/zswap.c:zswap_lru_add
```
```
In mm/memcontrol.c (ffffffff814c0c9f)
Location: arch/x86/include/asm/atomic64_64.h:107
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
  - mm/memcontrol.c:get_obj_cgroup_from_folio
  - mm/memcontrol.c:current_objcg_update
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_current
  - mm/memcontrol.c:get_mem_cgroup_from_mm
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff814c320a)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memremap.c (ffffffff814d4f5e)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - mm/memremap.c:zone_device_page_init
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/file.c (ffffffff8150eded)
Location: arch/x86/include/asm/atomic64_64.h:107
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
In fs/libfs.c (ffffffff81520986)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - fs/libfs.c:inode_query_iversion
  - fs/libfs.c:inode_maybe_inc_iversion
```
```
In fs/fs-writeback.c (ffffffff8152d36d)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/aio.c (ffffffff8155c822)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In block/blk-core.c (ffffffff817b4e7f)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - block/blk-core.c:bio_poll
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff817c24c4)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - block/blk-mq.c:blk_rq_poll
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff817cacbe)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff817e6543)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_scale_delay
  - block/blk-cgroup.c:blkg_create
```
```
In io_uring/rsrc.c (ffffffff81825e8a)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - io_uring/rsrc.c:__io_account_mem
```
```
In lib/sbitmap.c (ffffffff8192d744)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_queue_get_batch
```
```
In drivers/pci/p2pdma.c (ffffffff819a9384)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_alloc_p2pmem
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/tty/tty_ldsem.c (ffffffff81af3b4e)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_read_trylock
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:__ldsem_wake_readers
```
```
In drivers/md/md.c (ffffffff81e172ed)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
```
```
In net/core/skbuff.c (ffffffff81ed2aed)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - net/core/skbuff.c:mm_account_pinned_pages
```
```
In net/mptcp/subflow.c (ffffffff821518fe)
Location: arch/x86/include/asm/atomic64_64.h:107
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81096545)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/locking/mutex.c (ffffffff81a70c15)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
  - kernel/locking/mutex.c:mutex_lock_killable
  - kernel/locking/mutex.c:mutex_lock_interruptible
  - kernel/locking/mutex.c:mutex_lock
```
```
In kernel/locking/rwsem.c (ffffffff810fcc65)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_write_trylock
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read_trylock
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
```
In kernel/acct.c (ffffffff8115135d)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff8115f511)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81161daf)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81162f4e)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff81163e50)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff811699e8)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/events/core.c (ffffffff8120cd06)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/page-writeback.c (ffffffff81225edf)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff812412e3)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
```
```
In mm/slub.c (ffffffff8129c415)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812c0782)
Location: arch/x86/include/asm/atomic64_64.h:184
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
In mm/hugetlb_cgroup.c (ffffffff812c24a4)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memremap.c (ffffffff812cc9eb)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/file.c (ffffffff812f7b43)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - fs/file.c:__fget
```
```
In fs/fs-writeback.c (ffffffff8130d1a8)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/aio.c (ffffffff8133339a)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffffffff8133c457)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (ffffffff814d69d5)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
```
```
In block/blk-core.c (ffffffff814df0fb)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff814e74c9)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff814ed162)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff81503670)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/tty/tty_ldsem.c (ffffffff81653d7e)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_read
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
In kernel/fork.c (ffffffff81084fc5)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/locking/mutex.c (ffffffff81a2d005)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
  - kernel/locking/mutex.c:mutex_lock_killable
  - kernel/locking/mutex.c:mutex_lock_interruptible
  - kernel/locking/mutex.c:mutex_lock
```
```
In kernel/locking/rwsem.c (ffffffff810ece75)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_write_trylock
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read_trylock
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
```
In kernel/acct.c (ffffffff8114463d)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff811527a1)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115500f)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8115619e)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff811570a0)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff8115cbe8)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/events/core.c (ffffffff811ffad6)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/page-writeback.c (ffffffff8121907f)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff812342e3)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
```
```
In mm/slub.c (ffffffff8128dfc6)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812b1842)
Location: arch/x86/include/asm/atomic64_64.h:184
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
In mm/hugetlb_cgroup.c (ffffffff812b34f4)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memremap.c (ffffffff812bd85b)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/file.c (ffffffff812e8763)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - fs/file.c:__fget
```
```
In fs/fs-writeback.c (ffffffff812fddb8)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/aio.c (ffffffff8132400a)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffffffff8132d127)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (ffffffff814c7395)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
```
```
In block/blk-core.c (ffffffff814cfa9b)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff814d7a39)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff814dd6b2)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff814f3b30)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/tty/tty_ldsem.c (ffffffff8163415e)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_read
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
In kernel/fork.c (ffffffff810964f5)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/locking/mutex.c (ffffffff81add025)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
  - kernel/locking/mutex.c:mutex_lock_killable
  - kernel/locking/mutex.c:mutex_lock_interruptible
  - kernel/locking/mutex.c:mutex_lock
```
```
In kernel/locking/rwsem.c (ffffffff810f9e25)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_write_trylock
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read_trylock
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
```
In kernel/acct.c (ffffffff8114f20d)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff8115d2e1)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115fb7f)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81160d1e)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff81161c20)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff811677b8)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/events/core.c (ffffffff8120aaa6)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/page-writeback.c (ffffffff81223c7f)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff8123f083)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
```
```
In mm/slub.c (ffffffff8129a225)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812be592)
Location: arch/x86/include/asm/atomic64_64.h:184
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
In mm/hugetlb_cgroup.c (ffffffff812c02b4)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memremap.c (ffffffff812ca7fb)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/file.c (ffffffff812f5953)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - fs/file.c:__fget
```
```
In fs/fs-writeback.c (ffffffff8130af98)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/aio.c (ffffffff81330e6a)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffffffff81339f27)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (ffffffff814d2a65)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
```
```
In block/blk-core.c (ffffffff814db18b)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff814e3559)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff814e91f2)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff814ff700)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/tty/tty_ldsem.c (ffffffff8168213e)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_read
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
In kernel/fork.c (ffffffff8109e4c0)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/locking/mutex.c (ffffffff81ae9b41)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
  - kernel/locking/mutex.c:mutex_lock_killable
  - kernel/locking/mutex.c:mutex_lock_interruptible
  - kernel/locking/mutex.c:mutex_lock
```
```
In kernel/locking/rwsem.c (ffffffff81104f95)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_write_trylock
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read_trylock
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
```
In kernel/acct.c (ffffffff8115c016)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff8116a4f8)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8116ce83)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8116e157)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8116f0ca)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff81174ee2)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/events/core.c (ffffffff8121987b)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/page-writeback.c (ffffffff81232f09)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff8124ebc5)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
```
```
In mm/slub.c (ffffffff812aa0cf)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812cefda)
Location: arch/x86/include/asm/atomic64_64.h:184
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
In mm/hugetlb_cgroup.c (ffffffff812d0d7c)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memremap.c (ffffffff812db55b)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/file.c (ffffffff81307319)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - fs/file.c:__fget
```
```
In fs/fs-writeback.c (ffffffff8131c727)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/aio.c (ffffffff81343a65)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffffffff8134d923)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (ffffffff814eb5d2)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
```
```
In block/blk-core.c (ffffffff814f3fca)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff814fc47a)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff815021aa)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff815188de)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/tty/tty_ldsem.c (ffffffff8169c77e)
Location: arch/x86/include/asm/atomic64_64.h:184
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
</details>
</li>
</ul>

## Differences
