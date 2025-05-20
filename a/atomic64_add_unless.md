# Function: <code>atomic64_add_unless</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8107da05)
Location: arch/x86/include/asm/atomic64_64.h:183
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/acct.c (ffffffff8110c36e)
Location: arch/x86/include/asm/atomic64_64.h:183
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup.c (ffffffff81115200)
Location: arch/x86/include/asm/atomic64_64.h:183
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup.c:cgroup_get_e_css
  - kernel/cgroup.c:cgroup_mount
  - kernel/cgroup.c:css_tryget_online_from_dir
```
```
In kernel/cgroup_freezer.c (ffffffff81119f3e)
Location: arch/x86/include/asm/atomic64_64.h:183
Inline: True
Inline callers:
  - kernel/cgroup_freezer.c:freezer_read
  - kernel/cgroup_freezer.c:freezer_write
```
```
In kernel/cpuset.c (ffffffff8111cc5d)
Location: arch/x86/include/asm/atomic64_64.h:183
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:proc_cpuset_show
```
```
In kernel/events/core.c (ffffffff81180e26)
Location: arch/x86/include/asm/atomic64_64.h:183
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/page-writeback.c (ffffffff8119a6e3)
Location: arch/x86/include/asm/atomic64_64.h:183
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff811af46f)
Location: arch/x86/include/asm/atomic64_64.h:183
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/memcontrol.c (ffffffff811fae4f)
Location: arch/x86/include/asm/atomic64_64.h:183
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mem_cgroup_from_mm
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_try_charge
```
```
In mm/hugetlb_cgroup.c (ffffffff8120130c)
Location: arch/x86/include/asm/atomic64_64.h:183
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/file.c (ffffffff81229c5c)
Location: arch/x86/include/asm/atomic64_64.h:183
Inline: True
Inline callers:
  - fs/file.c:__fget
```
```
In fs/fs-writeback.c (ffffffff8123ac15)
Location: arch/x86/include/asm/atomic64_64.h:183
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In block/bio.c (ffffffff813b0ff4)
Location: arch/x86/include/asm/atomic64_64.h:183
Inline: True
Inline callers:
  - block/bio.c:bio_associate_current
```
```
In block/blk-core.c (ffffffff813b9aba)
Location: arch/x86/include/asm/atomic64_64.h:183
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-cgroup.c (ffffffff813d7e8b)
Location: arch/x86/include/asm/atomic64_64.h:183
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
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
In arch/x86/mm/gup.c (ffffffff810716a1)
Location: arch/x86/include/asm/atomic64_64.h:193
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_huge_pmd
  - arch/x86/mm/gup.c:gup_pte_range
```
```
In kernel/fork.c (ffffffff8107f5a5)
Location: arch/x86/include/asm/atomic64_64.h:193
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/acct.c (ffffffff81113bce)
Location: arch/x86/include/asm/atomic64_64.h:193
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup.c (ffffffff811217a8)
Location: arch/x86/include/asm/atomic64_64.h:193
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup.c:cgroup_mount
  - kernel/cgroup.c:cgroup_mount
  - kernel/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup_freezer.c (ffffffff81122013)
Location: arch/x86/include/asm/atomic64_64.h:193
Inline: True
Inline callers:
  - kernel/cgroup_freezer.c:freezer_write
  - kernel/cgroup_freezer.c:freezer_read
```
```
In kernel/cpuset.c (ffffffff811258c0)
Location: arch/x86/include/asm/atomic64_64.h:193
Inline: True
Inline callers:
  - kernel/cpuset.c:proc_cpuset_show
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
```
```
In kernel/events/core.c (ffffffff811949d6)
Location: arch/x86/include/asm/atomic64_64.h:193
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
```
```
In kernel/memremap.c (ffffffff8119e218)
Location: arch/x86/include/asm/atomic64_64.h:193
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages_release
```
```
In mm/page-writeback.c (ffffffff811af022)
Location: arch/x86/include/asm/atomic64_64.h:193
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff811c8702)
Location: arch/x86/include/asm/atomic64_64.h:193
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/gup.c (ffffffff811d4ccc)
Location: arch/x86/include/asm/atomic64_64.h:193
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/huge_memory.c (ffffffff81214a52)
Location: arch/x86/include/asm/atomic64_64.h:193
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff8122402c)
Location: arch/x86/include/asm/atomic64_64.h:193
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_mm
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff81225b20)
Location: arch/x86/include/asm/atomic64_64.h:193
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/file.c (ffffffff812523bc)
Location: arch/x86/include/asm/atomic64_64.h:193
Inline: True
Inline callers:
  - fs/file.c:__fget
```
```
In fs/fs-writeback.c (ffffffff81262a62)
Location: arch/x86/include/asm/atomic64_64.h:193
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In block/bio.c (ffffffff813f49d6)
Location: arch/x86/include/asm/atomic64_64.h:193
Inline: True
Inline callers:
  - block/bio.c:bio_associate_current
```
```
In block/blk-core.c (ffffffff813fe7d1)
Location: arch/x86/include/asm/atomic64_64.h:193
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff81406eb9)
Location: arch/x86/include/asm/atomic64_64.h:193
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-cgroup.c (ffffffff8141db87)
Location: arch/x86/include/asm/atomic64_64.h:193
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
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
In arch/x86/mm/gup.c (ffffffff81075220)
Location: arch/x86/include/asm/atomic64_64.h:193
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_huge_pmd
  - arch/x86/mm/gup.c:gup_pte_range
```
```
In kernel/fork.c (ffffffff81083c55)
Location: arch/x86/include/asm/atomic64_64.h:193
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/acct.c (ffffffff8111b2de)
Location: arch/x86/include/asm/atomic64_64.h:193
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup.c (ffffffff81129d2a)
Location: arch/x86/include/asm/atomic64_64.h:193
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup.c:cgroup_mount
  - kernel/cgroup.c:cgroup_mount
  - kernel/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup_freezer.c (ffffffff8112a643)
Location: arch/x86/include/asm/atomic64_64.h:193
Inline: True
Inline callers:
  - kernel/cgroup_freezer.c:freezer_write
  - kernel/cgroup_freezer.c:freezer_read
```
```
In kernel/cpuset.c (ffffffff8112f2ba)
Location: arch/x86/include/asm/atomic64_64.h:193
Inline: True
Inline callers:
  - kernel/cpuset.c:proc_cpuset_show
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
```
```
In kernel/events/core.c (ffffffff811a4436)
Location: arch/x86/include/asm/atomic64_64.h:193
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
```
```
In kernel/memremap.c (ffffffff811adc47)
Location: arch/x86/include/asm/atomic64_64.h:193
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages_release
```
```
In mm/page-writeback.c (ffffffff811bf698)
Location: arch/x86/include/asm/atomic64_64.h:193
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff811d870b)
Location: arch/x86/include/asm/atomic64_64.h:193
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/gup.c (ffffffff811e4d01)
Location: arch/x86/include/asm/atomic64_64.h:193
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/huge_memory.c (ffffffff81226fec)
Location: arch/x86/include/asm/atomic64_64.h:193
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff812367f3)
Location: arch/x86/include/asm/atomic64_64.h:193
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
In mm/hugetlb_cgroup.c (ffffffff81238100)
Location: arch/x86/include/asm/atomic64_64.h:193
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/file.c (ffffffff8126562c)
Location: arch/x86/include/asm/atomic64_64.h:193
Inline: True
Inline callers:
  - fs/file.c:__fget
```
```
In fs/fs-writeback.c (ffffffff81275eb2)
Location: arch/x86/include/asm/atomic64_64.h:193
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In block/bio.c (ffffffff8140e3c6)
Location: arch/x86/include/asm/atomic64_64.h:193
Inline: True
Inline callers:
  - block/bio.c:bio_associate_current
```
```
In block/blk-core.c (ffffffff814181d0)
Location: arch/x86/include/asm/atomic64_64.h:193
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff814213e9)
Location: arch/x86/include/asm/atomic64_64.h:193
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-cgroup.c (ffffffff81439147)
Location: arch/x86/include/asm/atomic64_64.h:193
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
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
In kernel/fork.c (ffffffff81080b25)
Location: arch/x86/include/asm/atomic64_64.h:199
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/acct.c (ffffffff8111ceef)
Location: arch/x86/include/asm/atomic64_64.h:199
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff81128b03)
Location: arch/x86/include/asm/atomic64_64.h:199
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8112ac3b)
Location: arch/x86/include/asm/atomic64_64.h:199
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
```
In kernel/cgroup/freezer.c (ffffffff8112b392)
Location: arch/x86/include/asm/atomic64_64.h:199
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_write
  - kernel/cgroup/freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8112bfb7)
Location: arch/x86/include/asm/atomic64_64.h:199
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff81130933)
Location: arch/x86/include/asm/atomic64_64.h:199
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/events/core.c (ffffffff811abac4)
Location: arch/x86/include/asm/atomic64_64.h:199
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
```
```
In kernel/memremap.c (ffffffff811b5198)
Location: arch/x86/include/asm/atomic64_64.h:199
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages_release
```
```
In mm/page-writeback.c (ffffffff811c74e9)
Location: arch/x86/include/asm/atomic64_64.h:199
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff811e1ccb)
Location: arch/x86/include/asm/atomic64_64.h:199
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/gup.c (ffffffff811f0d0d)
Location: arch/x86/include/asm/atomic64_64.h:199
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:follow_page_pte
```
```
In mm/huge_memory.c (ffffffff8123338e)
Location: arch/x86/include/asm/atomic64_64.h:199
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff81242297)
Location: arch/x86/include/asm/atomic64_64.h:199
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
In mm/hugetlb_cgroup.c (ffffffff81243d67)
Location: arch/x86/include/asm/atomic64_64.h:199
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/file.c (ffffffff81272dbc)
Location: arch/x86/include/asm/atomic64_64.h:199
Inline: True
Inline callers:
  - fs/file.c:__fget
```
```
In fs/fs-writeback.c (ffffffff81283369)
Location: arch/x86/include/asm/atomic64_64.h:199
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In block/bio.c (ffffffff8141bf8b)
Location: arch/x86/include/asm/atomic64_64.h:199
Inline: True
Inline callers:
  - block/bio.c:bio_associate_current
```
```
In block/blk-core.c (ffffffff81426056)
Location: arch/x86/include/asm/atomic64_64.h:199
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff8142fd92)
Location: arch/x86/include/asm/atomic64_64.h:199
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-cgroup.c (ffffffff814467eb)
Location: arch/x86/include/asm/atomic64_64.h:199
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
In kernel/fork.c (ffffffff810873c1)
Location: arch/x86/include/asm/atomic64_64.h:200
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/acct.c (ffffffff811285f6)
Location: arch/x86/include/asm/atomic64_64.h:200
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff8113514e)
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
In kernel/cgroup/cgroup-v1.c (ffffffff811379d1)
Location: arch/x86/include/asm/atomic64_64.h:200
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
```
In kernel/cgroup/freezer.c (ffffffff81138192)
Location: arch/x86/include/asm/atomic64_64.h:200
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_write
  - kernel/cgroup/freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff81138dc7)
Location: arch/x86/include/asm/atomic64_64.h:200
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff8113d873)
Location: arch/x86/include/asm/atomic64_64.h:200
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/events/core.c (ffffffff811bf437)
Location: arch/x86/include/asm/atomic64_64.h:200
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
```
```
In kernel/memremap.c (ffffffff811c94a0)
Location: arch/x86/include/asm/atomic64_64.h:200
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages_release
```
```
In mm/page-writeback.c (ffffffff811dc2ff)
Location: arch/x86/include/asm/atomic64_64.h:200
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff811f7d2c)
Location: arch/x86/include/asm/atomic64_64.h:200
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/gup.c (ffffffff81205867)
Location: arch/x86/include/asm/atomic64_64.h:200
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:follow_page_pte
```
```
In mm/huge_memory.c (ffffffff81250ce0)
Location: arch/x86/include/asm/atomic64_64.h:200
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff8126208d)
Location: arch/x86/include/asm/atomic64_64.h:200
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
In mm/hugetlb_cgroup.c (ffffffff81263bae)
Location: arch/x86/include/asm/atomic64_64.h:200
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/hmm.c (ffffffff8126e3c8)
Location: arch/x86/include/asm/atomic64_64.h:200
Inline: True
Inline callers:
  - mm/hmm.c:hmm_devmem_release
```
```
In fs/file.c (ffffffff812956f3)
Location: arch/x86/include/asm/atomic64_64.h:200
Inline: True
Inline callers:
  - fs/file.c:__fget
```
```
In fs/fs-writeback.c (ffffffff812a5ed9)
Location: arch/x86/include/asm/atomic64_64.h:200
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In block/blk-core.c (ffffffff8145149f)
Location: arch/x86/include/asm/atomic64_64.h:200
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff8145b6d2)
Location: arch/x86/include/asm/atomic64_64.h:200
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-cgroup.c (ffffffff814733bb)
Location: arch/x86/include/asm/atomic64_64.h:200
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
</details>
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81092301)
Location: include/linux/atomic.h:1184
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/acct.c (ffffffff81141c92)
Location: include/linux/atomic.h:1184
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff8114f395)
Location: include/linux/atomic.h:1184
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81151e3c)
Location: include/linux/atomic.h:1184
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
```
In kernel/cgroup/freezer.c (ffffffff8115265a)
Location: include/linux/atomic.h:1184
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_write
  - kernel/cgroup/freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff811532d1)
Location: include/linux/atomic.h:1184
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff81158dcb)
Location: include/linux/atomic.h:1184
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/events/core.c (ffffffff811efb32)
Location: include/linux/atomic.h:1184
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
```
```
In kernel/memremap.c (ffffffff811fa083)
Location: include/linux/atomic.h:1184
Inline: True
Inline callers:
  - kernel/memremap.c:get_dev_pagemap
```
```
In mm/page-writeback.c (ffffffff8121071c)
Location: include/linux/atomic.h:1184
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff8122be3d)
Location: include/linux/atomic.h:1184
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/memcontrol.c (ffffffff8129afee)
Location: include/linux/atomic.h:1184
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
In mm/hugetlb_cgroup.c (ffffffff8129ce4a)
Location: include/linux/atomic.h:1184
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/file.c (ffffffff812d0a64)
Location: include/linux/atomic.h:1184
Inline: True
Inline callers:
  - fs/file.c:__fget
```
```
In fs/fs-writeback.c (ffffffff812e1e10)
Location: include/linux/atomic.h:1184
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/aio.c (ffffffff81306a15)
Location: include/linux/atomic.h:1184
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In block/bio.c (ffffffff81498148)
Location: include/linux/atomic.h:1184
Inline: True
```
```
In block/blk-core.c (ffffffff8149f6f2)
Location: include/linux/atomic.h:1184
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff814a7b3f)
Location: include/linux/atomic.h:1184
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff814ad4ac)
Location: include/linux/atomic.h:1184
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff814c33ac)
Location: include/linux/atomic.h:1184
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
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
In kernel/fork.c (ffffffff8109665c)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/acct.c (ffffffff8114d05f)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff8115b226)
Location: include/linux/atomic-fallback.h:2219
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
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8115ecc0)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8115fbc3)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff811654cb)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/events/core.c (ffffffff81207389)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/page-writeback.c (ffffffff8121fdcf)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff8123b803)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slub.c (ffffffff812940b8)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812b62c0)
Location: include/linux/atomic-fallback.h:2219
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
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memremap.c (ffffffff812c24cf)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/file.c (ffffffff812eda96)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - fs/file.c:__fget
```
```
In fs/fs-writeback.c (ffffffff813002d6)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/aio.c (ffffffff8132800e)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffffffff813305ef)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
  - fs/io_uring.c:io_submit_sqe
```
```
In block/bio.c (ffffffff814c5fe8)
Location: include/linux/atomic-fallback.h:2219
Inline: True
```
```
In block/blk-core.c (ffffffff814cd81a)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff814d5ba9)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff814db73e)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff814f1ab6)
Location: include/linux/atomic-fallback.h:2219
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
In kernel/fork.c (ffffffff8109cc1c)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/acct.c (ffffffff81158d2f)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff81166ee4)
Location: include/linux/atomic-fallback.h:2219
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
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8116a920)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8116b823)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff811713bb)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/events/core.c (ffffffff812146f9)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/page-writeback.c (ffffffff8122d87f)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff81248c82)
Location: include/linux/atomic-fallback.h:2219
Inline: True
```
```
In mm/slub.c (ffffffff812a3e28)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812c8195)
Location: include/linux/atomic-fallback.h:2219
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
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memremap.c (ffffffff812d43ff)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/file.c (ffffffff812ff556)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - fs/file.c:__fget
```
```
In fs/fs-writeback.c (ffffffff81314bbb)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/aio.c (ffffffff8133adae)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffffffff81343e6b)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (ffffffff814de3e8)
Location: include/linux/atomic-fallback.h:2219
Inline: True
```
```
In block/blk-core.c (ffffffff814e6b0a)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff814eeed9)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff814f4b6e)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff8150b083)
Location: include/linux/atomic-fallback.h:2219
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
In kernel/fork.c (ffffffff810a3855)
Location: include/asm-generic/atomic-instrumented.h:1596
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/cgroup/cgroup.c (ffffffff81178557)
Location: include/asm-generic/atomic-instrumented.h:1596
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
```
```
In kernel/cgroup/rdma.c (ffffffff8117d453)
Location: include/asm-generic/atomic-instrumented.h:1596
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff811830cb)
Location: include/asm-generic/atomic-instrumented.h:1596
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In kernel/bpf/task_iter.c (ffffffff812166ed)
Location: include/asm-generic/atomic-instrumented.h:1596
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_file_seq_get_next
```
```
In mm/page-writeback.c (ffffffff8125b39c)
Location: include/asm-generic/atomic-instrumented.h:1596
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff81276e82)
Location: include/asm-generic/atomic-instrumented.h:1596
Inline: True
```
```
In mm/memcontrol.c (ffffffff812fd9ed)
Location: include/asm-generic/atomic-instrumented.h:1596
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff812ff99c)
Location: include/asm-generic/atomic-instrumented.h:1596
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In fs/file.c (ffffffff8133882d)
Location: include/asm-generic/atomic-instrumented.h:1596
Inline: True
Inline callers:
  - fs/file.c:__fget_files
```
```
In fs/fs-writeback.c (ffffffff8134e598)
Location: include/asm-generic/atomic-instrumented.h:1596
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/eventpoll.c (ffffffff8136cf16)
Location: include/asm-generic/atomic-instrumented.h:1596
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_loop_check_proc
```
```
In fs/io_uring.c (ffffffff8137fc3d)
Location: include/asm-generic/atomic-instrumented.h:1596
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_show_fdinfo
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_submit_sqes
```
```
In block/bio.c (ffffffff8153d9c2)
Location: include/asm-generic/atomic-instrumented.h:1596
Inline: True
Inline callers:
  - block/bio.c:__bio_associate_blkg
```
```
In block/blk-mq.c (ffffffff8154f964)
Location: include/asm-generic/atomic-instrumented.h:1596
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff81555541)
Location: include/asm-generic/atomic-instrumented.h:1596
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff8156c004)
Location: include/asm-generic/atomic-instrumented.h:1596
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
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
Location: include/asm-generic/atomic-instrumented.h:1596
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/cgroup/cgroup.c (ffffffff811752bf)
Location: include/asm-generic/atomic-instrumented.h:1596
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
```
```
In kernel/cgroup/rdma.c (ffffffff8117a2bc)
Location: include/asm-generic/atomic-instrumented.h:1596
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff8118005c)
Location: include/asm-generic/atomic-instrumented.h:1596
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In kernel/bpf/task_iter.c (ffffffff81218626)
Location: include/asm-generic/atomic-instrumented.h:1596
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_file_seq_get_next
```
```
In mm/page-writeback.c (ffffffff81265509)
Location: include/asm-generic/atomic-instrumented.h:1596
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff8128175f)
Location: include/asm-generic/atomic-instrumented.h:1596
Inline: True
```
```
In mm/memcontrol.c (ffffffff81309e35)
Location: include/asm-generic/atomic-instrumented.h:1596
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
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
Location: include/asm-generic/atomic-instrumented.h:1596
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In fs/file.c (ffffffff813441c0)
Location: include/asm-generic/atomic-instrumented.h:1596
Inline: True
Inline callers:
  - fs/file.c:__fget_files
```
```
In fs/fs-writeback.c (ffffffff8135b3bd)
Location: include/asm-generic/atomic-instrumented.h:1596
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/io_uring.c (ffffffff8138e751)
Location: include/asm-generic/atomic-instrumented.h:1596
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_show_fdinfo
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_submit_sqes
```
```
In block/blk-mq.c (ffffffff8156bd4c)
Location: include/asm-generic/atomic-instrumented.h:1596
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff81571c0b)
Location: include/asm-generic/atomic-instrumented.h:1596
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff81586d2c)
Location: include/asm-generic/atomic-instrumented.h:1596
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In net/mptcp/subflow.c (ffffffff81bc37c9)
Location: include/asm-generic/atomic-instrumented.h:1596
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
Location: include/asm-generic/atomic-instrumented.h:1596
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/cgroup/cgroup.c (ffffffff81175e25)
Location: include/asm-generic/atomic-instrumented.h:1596
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
```
```
In kernel/cgroup/rdma.c (ffffffff8117ae3c)
Location: include/asm-generic/atomic-instrumented.h:1596
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff81180b2c)
Location: include/asm-generic/atomic-instrumented.h:1596
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
```
```
In kernel/bpf/task_iter.c (ffffffff8121bdd9)
Location: include/asm-generic/atomic-instrumented.h:1596
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_file_seq_get_next
```
```
In mm/page-writeback.c (ffffffff81269718)
Location: include/asm-generic/atomic-instrumented.h:1596
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff8128660f)
Location: include/asm-generic/atomic-instrumented.h:1596
Inline: True
```
```
In mm/memcontrol.c (ffffffff813106a5)
Location: include/asm-generic/atomic-instrumented.h:1596
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:obj_cgroup_charge_pages
  - mm/memcontrol.c:obj_cgroup_uncharge_pages
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff813122e9)
Location: include/asm-generic/atomic-instrumented.h:1596
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In fs/file.c (ffffffff8134a560)
Location: include/asm-generic/atomic-instrumented.h:1596
Inline: True
Inline callers:
  - fs/file.c:__fget_files
```
```
In fs/fs-writeback.c (ffffffff81361fbd)
Location: include/asm-generic/atomic-instrumented.h:1596
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/io_uring.c (ffffffff8139ecc5)
Location: include/asm-generic/atomic-instrumented.h:1596
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_uring_show_fdinfo
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_req_complete_post
```
```
In block/blk-mq.c (ffffffff81573842)
Location: include/asm-generic/atomic-instrumented.h:1596
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff81579c11)
Location: include/asm-generic/atomic-instrumented.h:1596
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff8158db7c)
Location: include/asm-generic/atomic-instrumented.h:1596
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In net/mptcp/subflow.c (ffffffff81bb3e66)
Location: include/asm-generic/atomic-instrumented.h:1596
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
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
In <code>6.2</code>: Absent ⚠️
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffff8000100f1868)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/acct.c (ffff8000101c826c)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffff8000101d8da0)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffff8000101dca34)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffff8000101de85c)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffff8000101dfc00)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffff8000101e4af8)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/events/core.c (ffff80001029e718)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/page-writeback.c (ffff8000102bc77c)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffff8000102de4c4)
Location: include/linux/atomic-fallback.h:2219
Inline: True
```
```
In mm/slub.c (ffff800010345b6c)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffff800010369eb0)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:percpu_ref_tryget_live
```
```
In mm/hugetlb_cgroup.c (ffff80001036d74c)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/file.c (ffff8000103b0d80)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - fs/file.c:__fget
```
```
In fs/fs-writeback.c (ffff8000103cab14)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/aio.c (ffff8000103fbfe0)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffff800010405d6c)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - fs/io_uring.c:__arm64_sys_io_uring_enter
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (ffff8000105db7b8)
Location: include/linux/atomic-fallback.h:2219
Inline: True
```
```
In block/blk-core.c (ffff8000105e4398)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffff8000105ef73c)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffff8000105f4994)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffff80001060e9e4)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
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
In arch/powerpc/mm/book3s64/iommu_api.c (c0000000000a0528)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/iommu_api.c:mm_iommu_mapped_dec
```
```
In kernel/fork.c (c000000000136624)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In fs/file.c (c0000000004ac3ac)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - fs/file.c:__fget
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
In kernel/fork.c (ffffffe0000beef0)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/fork.c:get_task_exe_file
  - kernel/fork.c:dup_mmap
```
```
In kernel/acct.c (ffffffe0001481d0)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffe000151d1a)
Location: include/linux/atomic-fallback.h:2219
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
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffe000155c64)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffe000156b8a)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffe00015ac6e)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/events/core.c (ffffffe0001c9bae)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/page-writeback.c (ffffffe0001df3b6)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffe0001f61ae)
Location: include/linux/atomic-fallback.h:2219
Inline: True
```
```
In mm/slub.c (ffffffe000238082)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffe000248804)
Location: include/linux/atomic-fallback.h:2219
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
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/file.c (ffffffe000274de4)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - fs/file.c:__fget
```
```
In fs/fs-writeback.c (ffffffe000288c80)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/aio.c (ffffffe0002a9308)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffffffe0002b101e)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_enter
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (ffffffe00041e422)
Location: include/linux/atomic-fallback.h:2219
Inline: True
```
```
In block/blk-core.c (ffffffe000425bda)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffe00042d4ec)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffe0004328d6)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffe000446e42)
Location: include/linux/atomic-fallback.h:2219
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
In kernel/fork.c (ffffffff8109653c)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/acct.c (ffffffff8115134f)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff8115f504)
Location: include/linux/atomic-fallback.h:2219
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
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81162f40)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff81163e43)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff811699db)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/events/core.c (ffffffff8120cd49)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/page-writeback.c (ffffffff81225ecf)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff812412d2)
Location: include/linux/atomic-fallback.h:2219
Inline: True
```
```
In mm/slub.c (ffffffff8129c408)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812c0775)
Location: include/linux/atomic-fallback.h:2219
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
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memremap.c (ffffffff812cc9df)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/file.c (ffffffff812f7b36)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - fs/file.c:__fget
```
```
In fs/fs-writeback.c (ffffffff8130d19b)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/aio.c (ffffffff8133338e)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffffffff8133c44b)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (ffffffff814d69c8)
Location: include/linux/atomic-fallback.h:2219
Inline: True
```
```
In block/blk-core.c (ffffffff814df0ea)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff814e74b9)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff814ed14e)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff81503663)
Location: include/linux/atomic-fallback.h:2219
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
In kernel/fork.c (ffffffff81084fbc)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/acct.c (ffffffff8114462f)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff81152794)
Location: include/linux/atomic-fallback.h:2219
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
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81156190)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff81157093)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff8115cbdb)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/events/core.c (ffffffff811ffb19)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/page-writeback.c (ffffffff8121906f)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff812342d2)
Location: include/linux/atomic-fallback.h:2219
Inline: True
```
```
In mm/slub.c (ffffffff8128dfb9)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812b1835)
Location: include/linux/atomic-fallback.h:2219
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
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memremap.c (ffffffff812bd84f)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/file.c (ffffffff812e8756)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - fs/file.c:__fget
```
```
In fs/fs-writeback.c (ffffffff812fddab)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/aio.c (ffffffff81323ffe)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffffffff8132d11b)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (ffffffff814c7388)
Location: include/linux/atomic-fallback.h:2219
Inline: True
```
```
In block/blk-core.c (ffffffff814cfa8a)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff814d7a29)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff814dd69e)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff814f3b23)
Location: include/linux/atomic-fallback.h:2219
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
In kernel/fork.c (ffffffff810964ec)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/acct.c (ffffffff8114f1ff)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff8115d2d4)
Location: include/linux/atomic-fallback.h:2219
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
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81160d10)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff81161c13)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff811677ab)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/events/core.c (ffffffff8120aae9)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/page-writeback.c (ffffffff81223c6f)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff8123f072)
Location: include/linux/atomic-fallback.h:2219
Inline: True
```
```
In mm/slub.c (ffffffff8129a218)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812be585)
Location: include/linux/atomic-fallback.h:2219
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
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memremap.c (ffffffff812ca7ef)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/file.c (ffffffff812f5946)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - fs/file.c:__fget
```
```
In fs/fs-writeback.c (ffffffff8130af8b)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/aio.c (ffffffff81330e5e)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffffffff81339f1b)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (ffffffff814d2a58)
Location: include/linux/atomic-fallback.h:2219
Inline: True
```
```
In block/blk-core.c (ffffffff814db17a)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff814e3549)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff814e91de)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff814ff6f3)
Location: include/linux/atomic-fallback.h:2219
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
In kernel/fork.c (ffffffff8109e4b7)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/acct.c (ffffffff8115c008)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff8116a4eb)
Location: include/linux/atomic-fallback.h:2219
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
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8116e149)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8116f0bd)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffffffff81174ed5)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/events/core.c (ffffffff812198cd)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/page-writeback.c (ffffffff81232ef9)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff8124ebb4)
Location: include/linux/atomic-fallback.h:2219
Inline: True
```
```
In mm/slub.c (ffffffff812aa0c2)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812cefcd)
Location: include/linux/atomic-fallback.h:2219
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
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memremap.c (ffffffff812db54f)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
```
```
In fs/file.c (ffffffff8130730b)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - fs/file.c:__fget
```
```
In fs/fs-writeback.c (ffffffff8131c71a)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/aio.c (ffffffff81343a59)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffffffff8134d913)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (ffffffff814eb5c5)
Location: include/linux/atomic-fallback.h:2219
Inline: True
```
```
In block/blk-core.c (ffffffff814f3fb9)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff814fc46a)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff81502196)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffffffff815188d1)
Location: include/linux/atomic-fallback.h:2219
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
```
</details>
</li>
</ul>

## Differences
