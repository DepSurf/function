# Function: <code>atomic64_try_cmpxchg</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81080b32)
Location: arch/x86/include/asm/atomic64_64.h:180
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/acct.c (ffffffff8111cef3)
Location: arch/x86/include/asm/atomic64_64.h:180
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff81128b0c)
Location: arch/x86/include/asm/atomic64_64.h:180
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8112ac48)
Location: arch/x86/include/asm/atomic64_64.h:180
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
```
In kernel/cgroup/freezer.c (ffffffff8112b39f)
Location: arch/x86/include/asm/atomic64_64.h:180
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_write
  - kernel/cgroup/freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8112bfc4)
Location: arch/x86/include/asm/atomic64_64.h:180
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff81130940)
Location: arch/x86/include/asm/atomic64_64.h:180
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/events/core.c (ffffffff811abad8)
Location: arch/x86/include/asm/atomic64_64.h:180
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
```
```
In kernel/memremap.c (ffffffff811b51a8)
Location: arch/x86/include/asm/atomic64_64.h:180
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages_release
```
```
In mm/page-writeback.c (ffffffff811c74f9)
Location: arch/x86/include/asm/atomic64_64.h:180
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff811e1ce0)
Location: arch/x86/include/asm/atomic64_64.h:180
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/gup.c (ffffffff811f0d1d)
Location: arch/x86/include/asm/atomic64_64.h:180
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:follow_page_pte
```
```
In mm/huge_memory.c (ffffffff8123339a)
Location: arch/x86/include/asm/atomic64_64.h:180
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff812422a4)
Location: arch/x86/include/asm/atomic64_64.h:180
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_mm
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff81243d74)
Location: arch/x86/include/asm/atomic64_64.h:180
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/file.c (ffffffff81272dc9)
Location: arch/x86/include/asm/atomic64_64.h:180
Inline: True
Inline callers:
  - fs/file.c:__fget
```
```
In fs/fs-writeback.c (ffffffff8128337a)
Location: arch/x86/include/asm/atomic64_64.h:180
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In block/bio.c (ffffffff8141bf94)
Location: arch/x86/include/asm/atomic64_64.h:180
Inline: True
Inline callers:
  - block/bio.c:bio_associate_current
```
```
In block/blk-core.c (ffffffff81426066)
Location: arch/x86/include/asm/atomic64_64.h:180
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff8142fda2)
Location: arch/x86/include/asm/atomic64_64.h:180
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-cgroup.c (ffffffff8144697a)
Location: arch/x86/include/asm/atomic64_64.h:180
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
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
In kernel/fork.c (ffffffff810873cf)
Location: arch/x86/include/asm/atomic64_64.h:181
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/acct.c (ffffffff811285fa)
Location: arch/x86/include/asm/atomic64_64.h:181
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff8113515b)
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
In kernel/cgroup/cgroup-v1.c (ffffffff811379de)
Location: arch/x86/include/asm/atomic64_64.h:181
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
```
In kernel/cgroup/freezer.c (ffffffff8113819f)
Location: arch/x86/include/asm/atomic64_64.h:181
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_write
  - kernel/cgroup/freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff81138dd4)
Location: arch/x86/include/asm/atomic64_64.h:181
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff8113d880)
Location: arch/x86/include/asm/atomic64_64.h:181
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/events/core.c (ffffffff811bf44b)
Location: arch/x86/include/asm/atomic64_64.h:181
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
```
```
In kernel/memremap.c (ffffffff811c94b0)
Location: arch/x86/include/asm/atomic64_64.h:181
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages_release
```
```
In mm/page-writeback.c (ffffffff811dc30f)
Location: arch/x86/include/asm/atomic64_64.h:181
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff811f7d41)
Location: arch/x86/include/asm/atomic64_64.h:181
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/gup.c (ffffffff81205877)
Location: arch/x86/include/asm/atomic64_64.h:181
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:follow_page_pte
```
```
In mm/huge_memory.c (ffffffff81250cec)
Location: arch/x86/include/asm/atomic64_64.h:181
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff8126209a)
Location: arch/x86/include/asm/atomic64_64.h:181
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_mm
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff81263bbb)
Location: arch/x86/include/asm/atomic64_64.h:181
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/hmm.c (ffffffff8126e3dc)
Location: arch/x86/include/asm/atomic64_64.h:181
Inline: True
Inline callers:
  - mm/hmm.c:hmm_devmem_release
```
```
In fs/file.c (ffffffff81295700)
Location: arch/x86/include/asm/atomic64_64.h:181
Inline: True
Inline callers:
  - fs/file.c:__fget
```
```
In fs/fs-writeback.c (ffffffff812a5eea)
Location: arch/x86/include/asm/atomic64_64.h:181
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In block/blk-core.c (ffffffff814514af)
Location: arch/x86/include/asm/atomic64_64.h:181
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff8145b6e2)
Location: arch/x86/include/asm/atomic64_64.h:181
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-cgroup.c (ffffffff81473550)
Location: arch/x86/include/asm/atomic64_64.h:181
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
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
In kernel/locking/mutex.c (ffffffff819ef00d)
Location: include/asm-generic/atomic-instrumented.h:79
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_lock_killable
  - kernel/locking/mutex.c:mutex_lock_interruptible
  - kernel/locking/mutex.c:mutex_lock
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
Location: include/asm-generic/atomic-instrumented.h:79
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/locking/mutex.c (ffffffff81a2a34d)
Location: include/asm-generic/atomic-instrumented.h:79
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_lock_killable
  - kernel/locking/mutex.c:mutex_lock_interruptible
  - kernel/locking/mutex.c:mutex_lock
```
```
In kernel/acct.c (ffffffff81141c9f)
Location: include/asm-generic/atomic-instrumented.h:79
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff8114f3a2)
Location: include/asm-generic/atomic-instrumented.h:79
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
Location: include/asm-generic/atomic-instrumented.h:79
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
```
In kernel/cgroup/freezer.c (ffffffff81152667)
Location: include/asm-generic/atomic-instrumented.h:79
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_write
  - kernel/cgroup/freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff811532de)
Location: include/asm-generic/atomic-instrumented.h:79
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff81158dd8)
Location: include/asm-generic/atomic-instrumented.h:79
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/events/core.c (ffffffff811efb42)
Location: include/asm-generic/atomic-instrumented.h:79
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
```
```
In kernel/memremap.c (ffffffff811fa08f)
Location: include/asm-generic/atomic-instrumented.h:79
Inline: True
Inline callers:
  - kernel/memremap.c:get_dev_pagemap
```
```
In mm/page-writeback.c (ffffffff81210730)
Location: include/asm-generic/atomic-instrumented.h:79
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff8122be4e)
Location: include/asm-generic/atomic-instrumented.h:79
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/memcontrol.c (ffffffff8129affb)
Location: include/asm-generic/atomic-instrumented.h:79
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
Location: include/asm-generic/atomic-instrumented.h:79
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/file.c (ffffffff812d0a71)
Location: include/asm-generic/atomic-instrumented.h:79
Inline: True
Inline callers:
  - fs/file.c:__fget
```
```
In fs/fs-writeback.c (ffffffff812e1e21)
Location: include/asm-generic/atomic-instrumented.h:79
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/aio.c (ffffffff81306a21)
Location: include/asm-generic/atomic-instrumented.h:79
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In block/bio.c (ffffffff81498155)
Location: include/asm-generic/atomic-instrumented.h:79
Inline: True
```
```
In block/blk-core.c (ffffffff8149f703)
Location: include/asm-generic/atomic-instrumented.h:79
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff814a7b4f)
Location: include/asm-generic/atomic-instrumented.h:79
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff814ad4bc)
Location: include/asm-generic/atomic-instrumented.h:79
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff814c33b9)
Location: include/asm-generic/atomic-instrumented.h:79
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/tty/tty_ldsem.c (ffffffff816379be)
Location: include/asm-generic/atomic-instrumented.h:79
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
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/locking/mutex.c (ffffffff81a9a455)
Location: include/asm-generic/atomic-instrumented.h:1501
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
Location: include/asm-generic/atomic-instrumented.h:1501
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
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff8115b233)
Location: include/asm-generic/atomic-instrumented.h:1501
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
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8115ecce)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8115fbd0)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff811654d8)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/events/core.c (ffffffff81207346)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/page-writeback.c (ffffffff8121fddf)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff8123b813)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slub.c (ffffffff812940c5)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812b62cd)
Location: include/asm-generic/atomic-instrumented.h:1501
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
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memremap.c (ffffffff812c24db)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/file.c (ffffffff812edaa3)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - fs/file.c:__fget
```
```
In fs/fs-writeback.c (ffffffff813002e3)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/aio.c (ffffffff8132801a)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffffffff813305fb)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
  - fs/io_uring.c:io_submit_sqe
```
```
In block/bio.c (ffffffff814c5ff5)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
```
```
In block/blk-core.c (ffffffff814cd82b)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff814d5bb9)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff814db752)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff814f1ac3)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/tty/tty_ldsem.c (ffffffff8166bc8e)
Location: include/asm-generic/atomic-instrumented.h:1501
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
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/locking/mutex.c (ffffffff81ad1da5)
Location: include/asm-generic/atomic-instrumented.h:1501
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
Location: include/asm-generic/atomic-instrumented.h:1501
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
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff81166ef1)
Location: include/asm-generic/atomic-instrumented.h:1501
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
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8116a92e)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8116b830)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff811713c8)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/events/core.c (ffffffff812146b6)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/page-writeback.c (ffffffff8122d88f)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff81248c93)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
```
```
In mm/slub.c (ffffffff812a3e35)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812c81a2)
Location: include/asm-generic/atomic-instrumented.h:1501
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
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memremap.c (ffffffff812d440b)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/file.c (ffffffff812ff563)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - fs/file.c:__fget
```
```
In fs/fs-writeback.c (ffffffff81314bc8)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/aio.c (ffffffff8133adba)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffffffff81343e77)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (ffffffff814de3f5)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
```
```
In block/blk-core.c (ffffffff814e6b1b)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff814eeee9)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff814f4b82)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff8150b090)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/tty/tty_ldsem.c (ffffffff8168e2fe)
Location: include/asm-generic/atomic-instrumented.h:1501
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
In kernel/locking/rwsem.c (ffffffff81bcaf40)
Location: include/asm-generic/atomic-instrumented.h:1502
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
```
In drivers/tty/tty_ldsem.c (ffffffff817405be)
Location: include/asm-generic/atomic-instrumented.h:1502
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
In kernel/locking/rwsem.c (ffffffff81c43d51)
Location: include/asm-generic/atomic-instrumented.h:1502
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_interruptible
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff8111c4cf)
Location: include/asm-generic/atomic-instrumented.h:1502
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
In drivers/tty/tty_ldsem.c (ffffffff8175c4ee)
Location: include/asm-generic/atomic-instrumented.h:1502
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
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff81c35ba1)
Location: include/asm-generic/atomic-instrumented.h:1502
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_interruptible
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff8111d47c)
Location: include/asm-generic/atomic-instrumented.h:1502
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
In drivers/tty/tty_ldsem.c (ffffffff8174038e)
Location: include/asm-generic/atomic-instrumented.h:1502
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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff814b7b8a)
Location: include/linux/atomic/atomic-instrumented.h:1149
Inline: True
Inline callers:
  - fs/libfs.c:inode_maybe_inc_iversion
```
```
In fs/ext4/dir.c (ffffffff81559754)
Location: include/linux/atomic/atomic-instrumented.h:1149
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff8157758c)
Location: include/linux/atomic/atomic-instrumented.h:1149
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/fat/namei_vfat.c (ffffffff81606381)
Location: include/linux/atomic/atomic-instrumented.h:1149
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_lookup
```
```
In fs/fuse/readdir.c (ffffffff8162f93a)
Location: include/linux/atomic/atomic-instrumented.h:1149
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
```
```
In security/integrity/ima/ima_api.c (ffffffff816f9837)
Location: include/linux/atomic/atomic-instrumented.h:1149
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
```
In block/blk-cgroup.c (ffffffff8176003b)
Location: include/linux/atomic/atomic-instrumented.h:1149
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
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
In kernel/time/posix-cpu-timers.c (ffffffff811fd9f9)
Location: include/linux/atomic/atomic-instrumented.h:2834
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
```
```
In fs/libfs.c (ffffffff814eca36)
Location: include/linux/atomic/atomic-instrumented.h:2834
Inline: True
Inline callers:
  - fs/libfs.c:inode_query_iversion
  - fs/libfs.c:inode_maybe_inc_iversion
```
```
In block/blk-cgroup.c (ffffffff8179f04b)
Location: include/linux/atomic/atomic-instrumented.h:2834
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
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
In kernel/time/posix-cpu-timers.c (ffffffff81213d19)
Location: include/linux/atomic/atomic-instrumented.h:2834
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
```
```
In fs/libfs.c (ffffffff81520986)
Location: include/linux/atomic/atomic-instrumented.h:2834
Inline: True
Inline callers:
  - fs/libfs.c:inode_query_iversion
  - fs/libfs.c:inode_maybe_inc_iversion
```
```
In block/blk-cgroup.c (ffffffff817e2b1b)
Location: include/linux/atomic/atomic-instrumented.h:2834
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
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
In kernel/fork.c (ffff8000100f1870)
Location: include/linux/atomic-fallback.h:2025
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/locking/rwsem.c (ffff800010da53a8)
Location: include/linux/atomic-fallback.h:2025
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
```
In kernel/acct.c (ffff8000101c8274)
Location: include/linux/atomic-fallback.h:2025
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffff8000101d8dac)
Location: include/linux/atomic-fallback.h:2025
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffff8000101dca38)
Location: include/linux/atomic-fallback.h:2025
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffff8000101de860)
Location: include/linux/atomic-fallback.h:2025
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffff8000101dfc08)
Location: include/linux/atomic-fallback.h:2025
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffff8000101e4b00)
Location: include/linux/atomic-fallback.h:2025
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/events/core.c (ffff80001029e724)
Location: include/linux/atomic-fallback.h:2025
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/page-writeback.c (ffff8000102bc784)
Location: include/linux/atomic-fallback.h:2025
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffff8000102de4cc)
Location: include/linux/atomic-fallback.h:2025
Inline: True
```
```
In mm/slub.c (ffff800010345b70)
Location: include/linux/atomic-fallback.h:2025
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffff800010369eb8)
Location: include/linux/atomic-fallback.h:2025
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:percpu_ref_tryget_live
```
```
In mm/hugetlb_cgroup.c (ffff80001036d758)
Location: include/linux/atomic-fallback.h:2025
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/file.c (ffff8000103b0d88)
Location: include/linux/atomic-fallback.h:2025
Inline: True
Inline callers:
  - fs/file.c:__fget
```
```
In fs/fs-writeback.c (ffff8000103cab20)
Location: include/linux/atomic-fallback.h:2025
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/aio.c (ffff8000103fbfe4)
Location: include/linux/atomic-fallback.h:2025
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffff800010405d74)
Location: include/linux/atomic-fallback.h:2025
Inline: True
Inline callers:
  - fs/io_uring.c:__arm64_sys_io_uring_enter
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (ffff8000105db7c0)
Location: include/linux/atomic-fallback.h:2025
Inline: True
```
```
In block/blk-core.c (ffff8000105e439c)
Location: include/linux/atomic-fallback.h:2025
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffff8000105ef748)
Location: include/linux/atomic-fallback.h:2025
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffff8000105f49a0)
Location: include/linux/atomic-fallback.h:2025
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffff80001060e9f0)
Location: include/linux/atomic-fallback.h:2025
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/tty/tty_ldsem.c (ffff80001085f688)
Location: include/linux/atomic-fallback.h:2025
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
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (c000000000ee7b68)
Location: include/linux/atomic-fallback.h:2025
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
```
In drivers/tty/tty_ldsem.c (c0000000008fec18)
Location: include/linux/atomic-fallback.h:2025
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
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffe0008c7ec6)
Location: include/linux/atomic-fallback.h:2025
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
```
```
In drivers/tty/tty_ldsem.c (ffffffe000537a7e)
Location: include/linux/atomic-fallback.h:2025
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
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/locking/mutex.c (ffffffff81a70c15)
Location: include/asm-generic/atomic-instrumented.h:1501
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
Location: include/asm-generic/atomic-instrumented.h:1501
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
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff8115f511)
Location: include/asm-generic/atomic-instrumented.h:1501
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
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81162f4e)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff81163e50)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff811699e8)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/events/core.c (ffffffff8120cd06)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/page-writeback.c (ffffffff81225edf)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff812412e3)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
```
```
In mm/slub.c (ffffffff8129c415)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812c0782)
Location: include/asm-generic/atomic-instrumented.h:1501
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
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memremap.c (ffffffff812cc9eb)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/file.c (ffffffff812f7b43)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - fs/file.c:__fget
```
```
In fs/fs-writeback.c (ffffffff8130d1a8)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/aio.c (ffffffff8133339a)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffffffff8133c457)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (ffffffff814d69d5)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
```
```
In block/blk-core.c (ffffffff814df0fb)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff814e74c9)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff814ed162)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff81503670)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/tty/tty_ldsem.c (ffffffff81653d7e)
Location: include/asm-generic/atomic-instrumented.h:1501
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
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/locking/mutex.c (ffffffff81a2d005)
Location: include/asm-generic/atomic-instrumented.h:1501
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
Location: include/asm-generic/atomic-instrumented.h:1501
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
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff811527a1)
Location: include/asm-generic/atomic-instrumented.h:1501
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
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8115619e)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff811570a0)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff8115cbe8)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/events/core.c (ffffffff811ffad6)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/page-writeback.c (ffffffff8121907f)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff812342e3)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
```
```
In mm/slub.c (ffffffff8128dfc6)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812b1842)
Location: include/asm-generic/atomic-instrumented.h:1501
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
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memremap.c (ffffffff812bd85b)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/file.c (ffffffff812e8763)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - fs/file.c:__fget
```
```
In fs/fs-writeback.c (ffffffff812fddb8)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/aio.c (ffffffff8132400a)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffffffff8132d127)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (ffffffff814c7395)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
```
```
In block/blk-core.c (ffffffff814cfa9b)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff814d7a39)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff814dd6b2)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff814f3b30)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/tty/tty_ldsem.c (ffffffff8163415e)
Location: include/asm-generic/atomic-instrumented.h:1501
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
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/locking/mutex.c (ffffffff81add025)
Location: include/asm-generic/atomic-instrumented.h:1501
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
Location: include/asm-generic/atomic-instrumented.h:1501
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
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff8115d2e1)
Location: include/asm-generic/atomic-instrumented.h:1501
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
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81160d1e)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff81161c20)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff811677b8)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/events/core.c (ffffffff8120aaa6)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/page-writeback.c (ffffffff81223c7f)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff8123f083)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
```
```
In mm/slub.c (ffffffff8129a225)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812be592)
Location: include/asm-generic/atomic-instrumented.h:1501
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
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memremap.c (ffffffff812ca7fb)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/file.c (ffffffff812f5953)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - fs/file.c:__fget
```
```
In fs/fs-writeback.c (ffffffff8130af98)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/aio.c (ffffffff81330e6a)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffffffff81339f27)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (ffffffff814d2a65)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
```
```
In block/blk-core.c (ffffffff814db18b)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff814e3559)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff814e91f2)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff814ff700)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/tty/tty_ldsem.c (ffffffff8168213e)
Location: include/asm-generic/atomic-instrumented.h:1501
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
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/locking/mutex.c (ffffffff81ae9b41)
Location: include/asm-generic/atomic-instrumented.h:1501
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
Location: include/asm-generic/atomic-instrumented.h:1501
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
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff8116a4f8)
Location: include/asm-generic/atomic-instrumented.h:1501
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
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8116e157)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8116f0ca)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff81174ee2)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/events/core.c (ffffffff8121987b)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/page-writeback.c (ffffffff81232f09)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff8124ebc5)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
```
```
In mm/slub.c (ffffffff812aa0cf)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812cefda)
Location: include/asm-generic/atomic-instrumented.h:1501
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
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memremap.c (ffffffff812db55b)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/file.c (ffffffff81307319)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - fs/file.c:__fget
```
```
In fs/fs-writeback.c (ffffffff8131c727)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/aio.c (ffffffff81343a65)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffffffff8134d923)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (ffffffff814eb5d2)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
```
```
In block/blk-core.c (ffffffff814f3fca)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff814fc47a)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff815021aa)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff815188de)
Location: include/asm-generic/atomic-instrumented.h:1501
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/tty/tty_ldsem.c (ffffffff8169c77e)
Location: include/asm-generic/atomic-instrumented.h:1501
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
