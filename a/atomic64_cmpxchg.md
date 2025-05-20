# Function: <code>atomic64_cmpxchg</code>

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
In arch/x86/kernel/pvclock.c (ffffffff81065212)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In kernel/fork.c (ffffffff8107da12)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/time/posix-cpu-timers.c (ffffffff810f2c42)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_group_cputimer
  - kernel/time/posix-cpu-timers.c:thread_group_cputimer
  - kernel/time/posix-cpu-timers.c:thread_group_cputimer
```
```
In kernel/acct.c (ffffffff8110c37b)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup.c (ffffffff8111520e)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup.c:cgroup_get_e_css
  - kernel/cgroup.c:cgroup_mount
  - kernel/cgroup.c:css_tryget_online_from_dir
```
```
In kernel/cgroup_freezer.c (ffffffff81119f4f)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - kernel/cgroup_freezer.c:freezer_read
  - kernel/cgroup_freezer.c:freezer_write
```
```
In kernel/cpuset.c (ffffffff8111cc6a)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:proc_cpuset_show
```
```
In kernel/events/core.c (ffffffff81180a01)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - kernel/events/core.c:free_event
  - kernel/events/core.c:perf_mmap_close
```
```
In mm/page-writeback.c (ffffffff8119a6f7)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff811af484)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/memcontrol.c (ffffffff811fae5c)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mem_cgroup_from_mm
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_try_charge
```
```
In mm/hugetlb_cgroup.c (ffffffff81201319)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/file.c (ffffffff81229c69)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - fs/file.c:__fget
```
```
In fs/fs-writeback.c (ffffffff8123ac22)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/nsfs.c (ffffffff812423e6)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - fs/nsfs.c:ns_get_path
```
```
In block/bio.c (ffffffff813b1005)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - block/bio.c:bio_associate_current
```
```
In block/blk-core.c (ffffffff813b9aca)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-cgroup.c (ffffffff813d7e99)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/tty/tty_ldsem.c (ffffffff814ebc5a)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_down_read_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write_trylock
```
```
In net/core/sock_diag.c (ffffffff81732f3f)
Location: arch/x86/include/asm/atomic64_64.h:164
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
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
In arch/x86/kernel/pvclock.c (ffffffff81064f99)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In arch/x86/mm/gup.c (ffffffff810716ad)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_huge_pmd
  - arch/x86/mm/gup.c:gup_pte_range
```
```
In kernel/fork.c (ffffffff8107f5b2)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/locking/rwsem-xadd.c (ffffffff8189d9b5)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
```
```
In kernel/time/posix-cpu-timers.c (ffffffff810f9d52)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_group_cputimer
  - kernel/time/posix-cpu-timers.c:thread_group_cputimer
  - kernel/time/posix-cpu-timers.c:thread_group_cputimer
```
```
In kernel/acct.c (ffffffff81113bdb)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup.c (ffffffff811217b5)
Location: arch/x86/include/asm/atomic64_64.h:174
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
In kernel/cgroup_freezer.c (ffffffff81122020)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - kernel/cgroup_freezer.c:freezer_write
  - kernel/cgroup_freezer.c:freezer_read
```
```
In kernel/cpuset.c (ffffffff811258cd)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - kernel/cpuset.c:proc_cpuset_show
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
```
```
In kernel/events/core.c (ffffffff811949da)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:free_event
```
```
In kernel/memremap.c (ffffffff8119e224)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages_release
```
```
In mm/page-writeback.c (ffffffff811af036)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff811c8713)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/gup.c (ffffffff811d4cdc)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/huge_memory.c (ffffffff81214a5e)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff81224039)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_mm
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff81225b2d)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/file.c (ffffffff812523c9)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - fs/file.c:__fget
```
```
In fs/fs-writeback.c (ffffffff81262a73)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/nsfs.c (ffffffff8126a746)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - fs/nsfs.c:ns_get_path
```
```
In block/bio.c (ffffffff813f49e3)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - block/bio.c:bio_associate_current
```
```
In block/blk-core.c (ffffffff813fe7e1)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff81406ecd)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-cgroup.c (ffffffff8141db99)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/tty/tty_ldsem.c (ffffffff8153ce23)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:__ldsem_wake_readers
```
```
In net/core/sock_diag.c (ffffffff8179e95f)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
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
In arch/x86/kernel/pvclock.c (ffffffff810684c9)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In arch/x86/mm/gup.c (ffffffff8107522c)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_huge_pmd
  - arch/x86/mm/gup.c:gup_pte_range
```
```
In kernel/fork.c (ffffffff81083c62)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/locking/mutex.c (ffffffff818d05ea)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_trylock
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__ww_mutex_lock_slowpath
  - kernel/locking/mutex.c:__ww_mutex_lock_slowpath
  - kernel/locking/mutex.c:__ww_mutex_lock_slowpath
  - kernel/locking/mutex.c:__ww_mutex_lock_slowpath
  - kernel/locking/mutex.c:mutex_lock_killable
  - kernel/locking/mutex.c:mutex_lock_interruptible
  - kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__mutex_lock_killable_slowpath
  - kernel/locking/mutex.c:__mutex_lock_killable_slowpath
  - kernel/locking/mutex.c:__mutex_lock_killable_slowpath
  - kernel/locking/mutex.c:__mutex_lock_killable_slowpath
  - kernel/locking/mutex.c:mutex_unlock
  - kernel/locking/mutex.c:mutex_optimistic_spin
  - kernel/locking/mutex.c:mutex_lock
  - kernel/locking/mutex.c:__mutex_lock_slowpath
  - kernel/locking/mutex.c:__mutex_lock_slowpath
  - kernel/locking/mutex.c:__mutex_lock_slowpath
  - kernel/locking/mutex.c:__mutex_lock_slowpath
```
```
In kernel/locking/rwsem-xadd.c (ffffffff818d285b)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811076e2)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_group_cputimer
  - kernel/time/posix-cpu-timers.c:thread_group_cputimer
  - kernel/time/posix-cpu-timers.c:thread_group_cputimer
```
```
In kernel/acct.c (ffffffff8111b2eb)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup.c (ffffffff81129d37)
Location: arch/x86/include/asm/atomic64_64.h:174
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
In kernel/cgroup_freezer.c (ffffffff8112a650)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - kernel/cgroup_freezer.c:freezer_write
  - kernel/cgroup_freezer.c:freezer_read
```
```
In kernel/cpuset.c (ffffffff8112f2c7)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - kernel/cpuset.c:proc_cpuset_show
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
```
```
In kernel/events/core.c (ffffffff811a443a)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:free_event
```
```
In kernel/memremap.c (ffffffff811adc53)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages_release
```
```
In mm/page-writeback.c (ffffffff811bf6ac)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff811d8720)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/gup.c (ffffffff811e4d0d)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/huge_memory.c (ffffffff81226ffc)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff81236800)
Location: arch/x86/include/asm/atomic64_64.h:174
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
In mm/hugetlb_cgroup.c (ffffffff8123810d)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/file.c (ffffffff81265639)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - fs/file.c:__fget
```
```
In fs/fs-writeback.c (ffffffff81275ec3)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/nsfs.c (ffffffff8127d648)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - fs/nsfs.c:__ns_get_path
```
```
In block/bio.c (ffffffff8140e3d3)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - block/bio.c:bio_associate_current
```
```
In block/blk-core.c (ffffffff814181e5)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff814213fd)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-cgroup.c (ffffffff81439159)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/tty/tty_ldsem.c (ffffffff81569473)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:__ldsem_wake_readers
```
```
In net/core/sock_diag.c (ffffffff817cd32f)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
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
In arch/x86/kernel/pvclock.c (ffffffff810677f9)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In kernel/locking/mutex.c (ffffffff81907b45)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_trylock
  - kernel/locking/mutex.c:mutex_lock_killable
  - kernel/locking/mutex.c:mutex_lock_interruptible
  - kernel/locking/mutex.c:mutex_unlock
  - kernel/locking/mutex.c:mutex_lock
```
```
In kernel/locking/rwsem-xadd.c (ffffffff81909727)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81109a72)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_group_cputimer
  - kernel/time/posix-cpu-timers.c:thread_group_cputimer
  - kernel/time/posix-cpu-timers.c:thread_group_cputimer
```
```
In kernel/events/core.c (ffffffff811a96b1)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - kernel/events/core.c:free_event
```
```
In fs/nsfs.c (ffffffff8128b207)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - fs/nsfs.c:__ns_get_path
```
```
In drivers/tty/tty_ldsem.c (ffffffff8157c9bc)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
```
In net/core/sock_diag.c (ffffffff817ece1f)
Location: arch/x86/include/asm/atomic64_64.h:174
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
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
In arch/x86/kernel/pvclock.c (ffffffff8106ba59)
Location: arch/x86/include/asm/atomic64_64.h:175
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In kernel/locking/mutex.c (ffffffff81991c35)
Location: arch/x86/include/asm/atomic64_64.h:175
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_trylock
  - kernel/locking/mutex.c:mutex_lock_killable
  - kernel/locking/mutex.c:mutex_lock_interruptible
  - kernel/locking/mutex.c:mutex_unlock
  - kernel/locking/mutex.c:mutex_lock
```
```
In kernel/locking/rwsem-xadd.c (ffffffff819938bf)
Location: arch/x86/include/asm/atomic64_64.h:175
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81114c52)
Location: arch/x86/include/asm/atomic64_64.h:175
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_group_cputimer
  - kernel/time/posix-cpu-timers.c:thread_group_cputimer
  - kernel/time/posix-cpu-timers.c:thread_group_cputimer
```
```
In kernel/events/core.c (ffffffff811bcf01)
Location: arch/x86/include/asm/atomic64_64.h:175
Inline: True
Inline callers:
  - kernel/events/core.c:free_event
```
```
In fs/nsfs.c (ffffffff812add53)
Location: arch/x86/include/asm/atomic64_64.h:175
Inline: True
Inline callers:
  - fs/nsfs.c:__ns_get_path
```
```
In drivers/tty/tty_ldsem.c (ffffffff815e14d7)
Location: arch/x86/include/asm/atomic64_64.h:175
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
```
In net/core/skbuff.c (ffffffff81831186)
Location: arch/x86/include/asm/atomic64_64.h:175
Inline: True
```
```
In net/core/sock_diag.c (ffffffff8186900f)
Location: arch/x86/include/asm/atomic64_64.h:175
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
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
In arch/x86/kernel/pvclock.c (ffffffff8106e6ef)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In kernel/locking/mutex.c (ffffffff819ee0c4)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_trylock
  - kernel/locking/mutex.c:mutex_unlock
```
```
In kernel/locking/rwsem-xadd.c (ffffffff819efe7c)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811213f2)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_group_cputimer
  - kernel/time/posix-cpu-timers.c:thread_group_cputimer
  - kernel/time/posix-cpu-timers.c:thread_group_cputimer
```
```
In kernel/events/core.c (ffffffff811dd100)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - kernel/events/core.c:free_event
```
```
In fs/inode.c (ffffffff812b89c2)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - fs/inode.c:generic_update_time
```
```
In fs/nsfs.c (ffffffff812d5b63)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
```
```
In fs/ext4/dir.c (ffffffff813382de)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff8134e337)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffffffff813554b3)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff8136d87a)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffffffff813a7fe8)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff813aed86)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/namei_vfat.c (ffffffff813b2810)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
```
```
In security/integrity/ima/ima_api.c (ffffffff814536ba)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
```
In drivers/tty/tty_ldsem.c (ffffffff8161a75e)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
```
In net/core/skbuff.c (ffffffff8187b623)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
```
```
In net/core/sock_diag.c (ffffffff818b8e8f)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/xdp/xdp_umem.c (ffffffff819cd136)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In arch/x86/kernel/pvclock.c (ffffffff8107470f)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In kernel/locking/mutex.c (ffffffff81a29334)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_trylock
  - kernel/locking/mutex.c:mutex_unlock
```
```
In kernel/locking/rwsem-xadd.c (ffffffff81a2b8ae)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8112cb12)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_group_cputimer
  - kernel/time/posix-cpu-timers.c:thread_group_cputimer
  - kernel/time/posix-cpu-timers.c:thread_group_cputimer
```
```
In kernel/events/core.c (ffffffff811ed500)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - kernel/events/core.c:free_event
```
```
In fs/inode.c (ffffffff812cdb12)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - fs/inode.c:generic_update_time
```
```
In fs/nsfs.c (ffffffff812eaf33)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
```
```
In fs/ext4/dir.c (ffffffff8134f573)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff813664d3)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffffffff8136d7e2)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff81385cfa)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffffffff813c0dd6)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff813c7f65)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff813c98a4)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
```
```
In fs/fat/namei_vfat.c (ffffffff813cbf01)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
```
```
In fs/fuse/dir.c (ffffffff813ddfa8)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/readdir.c (ffffffff813eaaa7)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
```
In security/integrity/ima/ima_api.c (ffffffff8147089a)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
```
In block/blk-cgroup.c (ffffffff814c0a8b)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In net/core/skbuff.c (ffffffff8189c463)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
```
```
In net/core/sock_diag.c (ffffffff818dfadf)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/xdp/xdp_umem.c (ffffffff81a06497)
Location: include/asm-generic/atomic-instrumented.h:61
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In arch/x86/kernel/pvclock.c (ffffffff81078267)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In kernel/locking/mutex.c (ffffffff81a999c4)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_trylock
  - kernel/locking/mutex.c:mutex_unlock
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811374e2)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_group_cputimer
  - kernel/time/posix-cpu-timers.c:thread_group_cputimer
  - kernel/time/posix-cpu-timers.c:thread_group_cputimer
```
```
In kernel/events/core.c (ffffffff81204f40)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - kernel/events/core.c:free_event
```
```
In fs/inode.c (ffffffff812ea8b2)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/inode.c:generic_update_time
```
```
In fs/nsfs.c (ffffffff813099a6)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
```
```
In fs/io_uring.c (ffffffff81330ee1)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/ext4/dir.c (ffffffff81377b01)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff8138f856)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffffffff81396dcc)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff813afcdb)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffffffff813eb626)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff813f2b4e)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff813f4443)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
```
```
In fs/fat/namei_vfat.c (ffffffff813f6710)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
```
```
In fs/fuse/dir.c (ffffffff81409658)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/readdir.c (ffffffff81416a5a)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
```
In security/integrity/ima/ima_api.c (ffffffff8149e24a)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
```
In block/blk-cgroup.c (ffffffff814ef2e0)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In net/core/skbuff.c (ffffffff818e6ce3)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
```
```
In net/core/sock_diag.c (ffffffff8192e12e)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/xdp/xdp_umem.c (ffffffff81a75dc1)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In arch/x86/kernel/pvclock.c (ffffffff810792d7)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In kernel/locking/mutex.c (ffffffff81ad146e)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_unlock
  - kernel/locking/mutex.c:mutex_trylock_recursive
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81142f2e)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
```
```
In kernel/futex.c (ffffffff8114a8c2)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/core.c (ffffffff81211b30)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - kernel/events/core.c:free_event
```
```
In fs/inode.c (ffffffff812fc2e2)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/inode.c:generic_update_time
```
```
In fs/nsfs.c (ffffffff8131ca16)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
```
```
In fs/io_uring.c (ffffffff81344f7f)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/ext4/dir.c (ffffffff8138fe81)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff813a82b6)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffffffff813af7fc)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff813c8c9b)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffffffff81404fd6)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff8140cb0f)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff8140e313)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
```
```
In fs/fat/namei_vfat.c (ffffffff814105e0)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
```
```
In fs/fuse/dir.c (ffffffff81422fb8)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/readdir.c (ffffffff8143097a)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
```
In security/integrity/ima/ima_api.c (ffffffff814b86eb)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
```
In block/blk-cgroup.c (ffffffff81508770)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In net/core/skbuff.c (ffffffff819190c3)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
```
```
In net/core/sock_diag.c (ffffffff819603be)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/xdp/xdp_umem.c (ffffffff81aacb24)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In arch/x86/kernel/pvclock.c (ffffffff810805bd)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81152c7e)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
```
```
In kernel/events/core.c (ffffffff8123da60)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - kernel/events/core.c:free_event
```
```
In fs/inode.c (ffffffff813352d0)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
```
```
In fs/nsfs.c (ffffffff8135669e)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - fs/nsfs.c:__ns_get_path
```
```
In fs/io_uring.c (ffffffff81385801)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/ext4/dir.c (ffffffff813db451)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff813f4363)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/inode.c (ffffffff813fb85c)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff8141475b)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffffffff81452f94)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff8145a179)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_root
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff8145c107)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
```
```
In fs/fat/namei_vfat.c (ffffffff8145e8ed)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
```
```
In fs/fuse/dir.c (ffffffff814726e8)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/readdir.c (ffffffff8148054c)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
```
```
In security/integrity/ima/ima_api.c (ffffffff8151832b)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
```
In block/blk-cgroup.c (ffffffff81569a8a)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In net/core/skbuff.c (ffffffff819ecd2e)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
```
```
In net/core/net_namespace.c (ffffffff819f9934)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_gen_cookie
```
```
In net/core/sock_diag.c (ffffffff81a3391e)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/xdp/xdp_umem.c (ffffffff81ba856e)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
```
In net/mptcp/options.c (ffffffff81bb14be)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
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
In arch/x86/kernel/pvclock.c (ffffffff810801cd)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff8111c845)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:desc_push_tail
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8114ef0e)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
```
```
In kernel/events/core.c (ffffffff81247e20)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - kernel/events/core.c:free_event
```
```
In fs/inode.c (ffffffff81340c40)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
```
```
In fs/nsfs.c (ffffffff81363043)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - fs/nsfs.c:__ns_get_path
```
```
In fs/io_uring.c (ffffffff81396835)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_buffer_account_pin
```
```
In fs/ext4/dir.c (ffffffff813ece81)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff81406af3)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/inode.c (ffffffff8140dfd8)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff81427dab)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffffffff8146f444)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff814764c9)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_root
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff81478007)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
```
```
In fs/fat/namei_vfat.c (ffffffff8147a5bd)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
```
```
In fs/fuse/dir.c (ffffffff8148d058)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/readdir.c (ffffffff8149bc2f)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
```
```
In security/integrity/ima/ima_api.c (ffffffff815352fb)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
```
In block/blk-cgroup.c (ffffffff8158433a)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In net/core/skbuff.c (ffffffff819ec9ee)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
```
```
In net/core/net_namespace.c (ffffffff819f9453)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - net/core/net_namespace.c:__net_gen_cookie
```
```
In net/core/sock_diag.c (ffffffff81a35cbd)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - net/core/sock_diag.c:__sock_gen_cookie
```
```
In net/xdp/xdp_umem.c (ffffffff81bb82d4)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
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
In arch/x86/kernel/pvclock.c (ffffffff81081060)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff8111d432)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_reserve
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8115039e)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
```
```
In kernel/events/core.c (ffffffff8124bce0)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - kernel/events/core.c:free_event
```
```
In fs/inode.c (ffffffff81347061)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
```
```
In fs/nsfs.c (ffffffff81369ae3)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - fs/nsfs.c:__ns_get_path
```
```
In fs/io_uring.c (ffffffff8139183a)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - fs/io_uring.c:io_buffer_account_pin
```
```
In fs/ext4/dir.c (ffffffff813f33b1)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff8140cf6d)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/inode.c (ffffffff81414198)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff8142ea22)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffffffff81474914)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff8147bf39)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_root
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff8147da9d)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_update_time
```
```
In fs/fat/namei_vfat.c (ffffffff8147fffd)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
```
```
In fs/fuse/dir.c (ffffffff814928d8)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/readdir.c (ffffffff814a0d4f)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
```
```
In security/integrity/ima/ima_api.c (ffffffff8153d91b)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
```
In block/blk-cgroup.c (ffffffff8158b13d)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In net/core/skbuff.c (ffffffff819d2ece)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
```
```
In net/core/sock_diag.c (ffffffff81a1ce10)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - net/core/sock_diag.c:__sock_gen_cookie
```
```
In net/xdp/xdp_umem.c (ffffffff81ba7492)
Location: include/asm-generic/atomic-instrumented.h:1462
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
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
In arch/x86/kernel/pvclock.c (ffffffff8108fff6)
Location: include/linux/atomic/atomic-instrumented.h:1051
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811745f8)
Location: include/linux/atomic/atomic-instrumented.h:1051
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
```
```
In fs/inode.c (ffffffff81394a91)
Location: include/linux/atomic/atomic-instrumented.h:1051
Inline: True
```
```
In fs/ext4/dir.c (ffffffff814453f2)
Location: include/linux/atomic/atomic-instrumented.h:1051
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff8145fdad)
Location: include/linux/atomic/atomic-instrumented.h:1051
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/inode.c (ffffffff814674f8)
Location: include/linux/atomic/atomic-instrumented.h:1051
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff814831c2)
Location: include/linux/atomic/atomic-instrumented.h:1051
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffffffff814cb654)
Location: include/linux/atomic/atomic-instrumented.h:1051
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff814d3576)
Location: include/linux/atomic/atomic-instrumented.h:1051
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_root
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff814d531d)
Location: include/linux/atomic/atomic-instrumented.h:1051
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_update_time
```
```
In fs/fat/namei_vfat.c (ffffffff814d789d)
Location: include/linux/atomic/atomic-instrumented.h:1051
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
```
```
In fs/fuse/dir.c (ffffffff814ea2b8)
Location: include/linux/atomic/atomic-instrumented.h:1051
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/readdir.c (ffffffff814f8c8f)
Location: include/linux/atomic/atomic-instrumented.h:1051
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
```
```
In security/integrity/ima/ima_api.c (ffffffff8159c7ab)
Location: include/linux/atomic/atomic-instrumented.h:1051
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
```
In block/blk-cgroup.c (ffffffff815f013d)
Location: include/linux/atomic/atomic-instrumented.h:1051
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In net/core/sock_diag.c (ffffffff81ad0690)
Location: include/linux/atomic/atomic-instrumented.h:1051
Inline: True
Inline callers:
  - net/core/sock_diag.c:__sock_gen_cookie
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
In arch/x86/kernel/pvclock.c (ffffffff810a0f46)
Location: include/linux/atomic/atomic-instrumented.h:1119
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811a9410)
Location: include/linux/atomic/atomic-instrumented.h:1119
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
```
```
In fs/inode.c (ffffffff81416d33)
Location: include/linux/atomic/atomic-instrumented.h:1119
Inline: True
```
```
In fs/ext4/dir.c (ffffffff814c14b4)
Location: include/linux/atomic/atomic-instrumented.h:1119
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff814de51c)
Location: include/linux/atomic/atomic-instrumented.h:1119
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/inode.c (ffffffff814e7105)
Location: include/linux/atomic/atomic-instrumented.h:1119
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff81507cac)
Location: include/linux/atomic/atomic-instrumented.h:1119
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffffffff81557bed)
Location: include/linux/atomic/atomic-instrumented.h:1119
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff8156098a)
Location: include/linux/atomic/atomic-instrumented.h:1119
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_root
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff81562328)
Location: include/linux/atomic/atomic-instrumented.h:1119
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_update_time
```
```
In fs/fat/namei_vfat.c (ffffffff81564f0b)
Location: include/linux/atomic/atomic-instrumented.h:1119
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
```
```
In fs/fuse/dir.c (ffffffff81578e58)
Location: include/linux/atomic/atomic-instrumented.h:1119
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/readdir.c (ffffffff815892d2)
Location: include/linux/atomic/atomic-instrumented.h:1119
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
```
```
In security/integrity/ima/ima_api.c (ffffffff81641826)
Location: include/linux/atomic/atomic-instrumented.h:1119
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
```
In block/blk-cgroup.c (ffffffff816a121b)
Location: include/linux/atomic/atomic-instrumented.h:1119
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In net/core/sock_diag.c (ffffffff81c4df10)
Location: include/linux/atomic/atomic-instrumented.h:1119
Inline: True
Inline callers:
  - net/core/sock_diag.c:__sock_gen_cookie
```
```
In net/mptcp/options.c (ffffffff81e2b21d)
Location: include/linux/atomic/atomic-instrumented.h:1119
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
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
In arch/x86/kernel/pvclock.c (ffffffff810b8db6)
Location: include/linux/atomic/atomic-instrumented.h:1119
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811e9300)
Location: include/linux/atomic/atomic-instrumented.h:1119
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
```
```
In net/core/sock_diag.c (ffffffff81e02d5d)
Location: include/linux/atomic/atomic-instrumented.h:1119
Inline: True
```
```
In net/mptcp/options.c (ffffffff820033cd)
Location: include/linux/atomic/atomic-instrumented.h:1119
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
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
In net/core/sock_diag.c (ffffffff81e752dd)
Location: include/linux/atomic/atomic-instrumented.h:2755
Inline: True
```
```
In net/mptcp/options.c (ffffffff8207f55d)
Location: include/linux/atomic/atomic-instrumented.h:2755
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
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
In net/core/sock_diag.c (ffffffff81f34b7d)
Location: include/linux/atomic/atomic-instrumented.h:2755
Inline: True
```
```
In net/mptcp/options.c (ffffffff82154a50)
Location: include/linux/atomic/atomic-instrumented.h:2755
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
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
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - kernel/fork.c:get_mm_exe_file
```
```
In kernel/locking/rwsem.c (ffff800010da53a8)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
```
In kernel/time/posix-cpu-timers.c (ffff8000101ad854)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
```
```
In kernel/acct.c (ffff8000101c8274)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
```
In kernel/cgroup/cgroup.c (ffff8000101d8dac)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cgroup-v1.c (ffff8000101dca38)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffff8000101de860)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffff8000101dfc08)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (ffff8000101e4b00)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/trace/ring_buffer.c (ffff80001021abe4)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/events/core.c (ffff8000102a0790)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_set_period
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:free_event
```
```
In kernel/events/ring_buffer.c (ffff8000102a2730)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
```
In mm/page-writeback.c (ffff8000102bc784)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffff8000102de4cc)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
```
```
In mm/slub.c (ffff800010345b70)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffff800010369eb8)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:percpu_ref_tryget_live
```
```
In mm/hugetlb_cgroup.c (ffff80001036d758)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/inode.c (ffff8000103ac8cc)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/inode.c:generic_update_time
```
```
In fs/file.c (ffff8000103b0d88)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/file.c:__fget
```
```
In fs/fs-writeback.c (ffff8000103cab20)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/nsfs.c (ffff8000103d4668)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
```
```
In fs/aio.c (ffff8000103fbfe4)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffff800010405d74)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/io_uring.c:__arm64_sys_io_uring_enter
  - fs/io_uring.c:io_account_mem
  - fs/io_uring.c:io_get_req
```
```
In fs/ext4/dir.c (ffff8000104627c0)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffff80001047bab8)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffff800010488e3c)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffff8000104a06c8)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffff8000104e5d04)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffff8000104ed74c)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffff8000104eee78)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
```
```
In fs/fat/namei_vfat.c (ffff8000104f19cc)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
```
```
In fs/fuse/dir.c (ffff800010506a10)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/readdir.c (ffff800010515444)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
```
In security/integrity/ima/ima_api.c (ffff8000105b0a40)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
```
In block/bio.c (ffff8000105db7c0)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
```
```
In block/blk-core.c (ffff8000105e439c)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffff8000105ef748)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
```
In block/blk-mq-tag.c (ffff8000105f49a0)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-cgroup.c (ffff80001060e9f0)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_scale_delay
  - block/blk-cgroup.c:blkg_create
```
```
In drivers/tty/tty_ldsem.c (ffff80001085f688)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
```
In drivers/perf/arm-cci.c (ffff800010b912b4)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - drivers/perf/arm-cci.c:pmu_event_update
```
```
In drivers/perf/arm_pmu.c (ffff800010b94fdc)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - drivers/perf/arm_pmu.c:armpmu_event_update
```
```
In drivers/perf/hisilicon/hisi_uncore_pmu.c (ffff800010b965fc)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - drivers/perf/hisilicon/hisi_uncore_pmu.c:hisi_uncore_pmu_event_update
```
```
In drivers/perf/qcom_l2_pmu.c (ffff800010b98e4c)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - drivers/perf/qcom_l2_pmu.c:l2_cache_event_update
```
```
In drivers/perf/qcom_l3_pmu.c (ffff800010b9a69c)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__32bit_counter_update
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__64bit_counter_update
```
```
In drivers/perf/xgene_pmu.c (ffff800010b9c09c)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - drivers/perf/xgene_pmu.c:xgene_perf_event_update
```
```
In net/core/skbuff.c (ffff800010bb2d64)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
```
```
In net/core/sock_diag.c (ffff800010c03c60)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/xdp/xdp_umem.c (ffff800010d813b0)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In arch/arm/mach-imx/mmdc.c (c0333568)
Location: include/linux/atomic-fallback.h:2003
Inline: True
Inline callers:
  - arch/arm/mach-imx/mmdc.c:mmdc_pmu_event_update
```
```
In kernel/time/posix-cpu-timers.c (c03f8844)
Location: include/linux/atomic-fallback.h:2003
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
```
```
In kernel/events/core.c (c04d070c)
Location: include/linux/atomic-fallback.h:2003
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_set_period
```
```
In fs/inode.c (c058db60)
Location: include/linux/atomic-fallback.h:2003
Inline: True
Inline callers:
  - fs/inode.c:generic_update_time
```
```
In fs/ext4/dir.c (c06233fc)
Location: include/linux/atomic-fallback.h:2003
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (c063d40c)
Location: include/linux/atomic-fallback.h:2003
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/inode.c (c064586c)
Location: include/linux/atomic-fallback.h:2003
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (c06627f0)
Location: include/linux/atomic-fallback.h:2003
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (c06a2f9c)
Location: include/linux/atomic-fallback.h:2003
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (c06ab4d0)
Location: include/linux/atomic-fallback.h:2003
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (c06ac9b4)
Location: include/linux/atomic-fallback.h:2003
Inline: True
```
```
In fs/fat/namei_vfat.c (c06af4a4)
Location: include/linux/atomic-fallback.h:2003
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
```
```
In fs/fuse/dir.c (c06c4a30)
Location: include/linux/atomic-fallback.h:2003
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_create_open
```
```
In fs/fuse/readdir.c (c06d0200)
Location: include/linux/atomic-fallback.h:2003
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
```
```
In security/integrity/ima/ima_api.c (c07600d0)
Location: include/linux/atomic-fallback.h:2003
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
```
In block/blk-cgroup.c (c07b6180)
Location: include/linux/atomic-fallback.h:2003
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In drivers/perf/arm-cci.c (c0c7aed8)
Location: include/linux/atomic-fallback.h:2003
Inline: True
Inline callers:
  - drivers/perf/arm-cci.c:pmu_event_update
```
```
In drivers/perf/arm_pmu.c (c0c7e630)
Location: include/linux/atomic-fallback.h:2003
Inline: True
Inline callers:
  - drivers/perf/arm_pmu.c:armpmu_event_update
```
```
In net/core/sock_diag.c (c0d1cfdc)
Location: include/linux/atomic-fallback.h:2003
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/riscv/kernel/perf_event.c (ffffffe0000b95fa)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - arch/riscv/kernel/perf_event.c:riscv_pmu_read
```
```
In kernel/locking/mutex.c (ffffffe0008c75fc)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
  - kernel/locking/mutex.c:mutex_lock_killable
  - kernel/locking/mutex.c:mutex_lock_interruptible
  - kernel/locking/mutex.c:mutex_unlock
  - kernel/locking/mutex.c:mutex_lock
  - kernel/locking/mutex.c:mutex_trylock_recursive
```
```
In kernel/locking/rwsem.c (ffffffe00010a882)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_write_trylock
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read_trylock
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
```
```
In kernel/time/posix-cpu-timers.c (ffffffe0001370a0)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
```
```
In kernel/futex.c (ffffffe00013ca30)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/trace/ring_buffer.c (ffffffe0001795d6)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/events/core.c (ffffffe0001c5450)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_overflow
  - kernel/events/core.c:free_event
```
```
In kernel/events/ring_buffer.c (ffffffe0001d13a8)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
```
In fs/inode.c (ffffffe00027122a)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - fs/inode.c:generic_update_time
```
```
In fs/nsfs.c (ffffffe00028eb30)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
```
```
In fs/io_uring.c (ffffffe0002b06c0)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/ext4/dir.c (ffffffe0002f1ac8)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffe000305e48)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffffffe00030c70a)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffe0003229f2)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffffffe000357292)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffe00035dcee)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffe00035ef18)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
```
```
In fs/fat/namei_vfat.c (ffffffe00036129a)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
```
```
In fs/fuse/dir.c (ffffffe00037262c)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/readdir.c (ffffffe00037edae)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
```
In security/integrity/ima/ima_api.c (ffffffe0003f8544)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
```
In block/blk-cgroup.c (ffffffe0004443e4)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In drivers/tty/tty_ldsem.c (ffffffe000537a7e)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
```
In net/core/skbuff.c (ffffffe000743840)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
```
```
In net/core/sock_diag.c (ffffffe000782552)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_save_cookie
```
```
In net/xdp/xdp_umem.c (ffffffe0008ad84a)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In arch/x86/kernel/pvclock.c (ffffffff810782d7)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In kernel/locking/mutex.c (ffffffff81a702de)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_unlock
  - kernel/locking/mutex.c:mutex_trylock_recursive
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8113b6de)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
```
```
In kernel/futex.c (ffffffff81142ee2)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/core.c (ffffffff8120a180)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - kernel/events/core.c:free_event
```
```
In fs/inode.c (ffffffff812f48c2)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/inode.c:generic_update_time
```
```
In fs/nsfs.c (ffffffff81314ff6)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
```
```
In fs/io_uring.c (ffffffff8133d55f)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/ext4/dir.c (ffffffff81388461)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff813a0896)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffffffff813a7ddc)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff813c127b)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffffffff813fd5b6)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff814050ef)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff814068f3)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
```
```
In fs/fat/namei_vfat.c (ffffffff81408bc0)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
```
```
In fs/fuse/dir.c (ffffffff8141b598)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/readdir.c (ffffffff81428f5a)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
```
In security/integrity/ima/ima_api.c (ffffffff814b0ccb)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
```
In block/blk-cgroup.c (ffffffff81500d50)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In net/core/skbuff.c (ffffffff818b90c3)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
```
```
In net/core/sock_diag.c (ffffffff8190038e)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/xdp/xdp_umem.c (ffffffff81a4beb4)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In arch/x86/kernel/pvclock.c (ffffffff81067b87)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In kernel/locking/mutex.c (ffffffff81a2c6ce)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_unlock
  - kernel/locking/mutex.c:mutex_trylock_recursive
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8112e11e)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
```
```
In kernel/futex.c (ffffffff81136242)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/core.c (ffffffff811fcf70)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - kernel/events/core.c:free_event
```
```
In fs/inode.c (ffffffff812e54e2)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/inode.c:generic_update_time
```
```
In fs/nsfs.c (ffffffff81305be6)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
```
```
In fs/io_uring.c (ffffffff8132e21f)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/ext4/dir.c (ffffffff81378ef1)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff81391326)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffffffff8139886c)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff813b1d0b)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffffffff813ee036)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff813f5b6f)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff813f7373)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
```
```
In fs/fat/namei_vfat.c (ffffffff813f9640)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
```
```
In fs/fuse/dir.c (ffffffff8140c018)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/readdir.c (ffffffff814199da)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
```
In security/integrity/ima/ima_api.c (ffffffff814a16eb)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
```
In block/blk-cgroup.c (ffffffff814f1260)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In net/core/skbuff.c (ffffffff81873013)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
```
```
In net/core/sock_diag.c (ffffffff818ba1be)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/xdp/xdp_umem.c (ffffffff81a08aa4)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In arch/x86/kernel/pvclock.c (ffffffff81078287)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In kernel/locking/mutex.c (ffffffff81adc6ee)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_unlock
  - kernel/locking/mutex.c:mutex_trylock_recursive
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811393fe)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
```
```
In kernel/futex.c (ffffffff81140d92)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/core.c (ffffffff81207f20)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - kernel/events/core.c:free_event
```
```
In fs/inode.c (ffffffff812f26d2)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/inode.c:generic_update_time
```
```
In fs/nsfs.c (ffffffff81312de6)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
```
```
In fs/io_uring.c (ffffffff8133b02f)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/ext4/dir.c (ffffffff81385dc1)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff8139e0f6)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffffffff813a563c)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff813be72b)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffffffff813fa936)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff8140246f)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff81403c73)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
```
```
In fs/fat/namei_vfat.c (ffffffff81405f40)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
```
```
In fs/fuse/dir.c (ffffffff81417738)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/readdir.c (ffffffff814250fa)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
```
In security/integrity/ima/ima_api.c (ffffffff814acd5b)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
```
In block/blk-cgroup.c (ffffffff814fcde0)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In net/core/skbuff.c (ffffffff8190a0c3)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
```
```
In net/core/sock_diag.c (ffffffff819513be)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/xdp/xdp_umem.c (ffffffff81ab7d64)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In arch/x86/kernel/pvclock.c (ffffffff8107a387)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_clocksource_read
```
```
In kernel/locking/mutex.c (ffffffff81ae8ade)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_unlock
  - kernel/locking/mutex.c:mutex_trylock_recursive
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81145e9e)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
  - kernel/time/posix-cpu-timers.c:cpu_clock_sample_group
```
```
In kernel/futex.c (ffffffff8114dfed)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/core.c (ffffffff81216cc0)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - kernel/events/core.c:free_event
```
```
In fs/inode.c (ffffffff81303de2)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/inode.c:generic_update_time
```
```
In fs/nsfs.c (ffffffff81324621)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
```
```
In fs/io_uring.c (ffffffff8134e1df)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/ext4/dir.c (ffffffff81399ab1)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff813b2666)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffffffff813b9d7c)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/namei.c (ffffffff813d380b)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/fat/dir.c (ffffffff81410596)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_remove_entries
```
```
In fs/fat/inode.c (ffffffff8141843f)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff814198e3)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
```
```
In fs/fat/namei_vfat.c (ffffffff8141bc00)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_lookup
```
```
In fs/fuse/dir.c (ffffffff8142e528)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_changed
```
```
In fs/fuse/readdir.c (ffffffff8143bf92)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
```
In security/integrity/ima/ima_api.c (ffffffff814c57ab)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
```
In block/blk-cgroup.c (ffffffff81515e90)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_scale_delay
```
```
In net/core/skbuff.c (ffffffff8192b1c3)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
```
```
In net/core/sock_diag.c (ffffffff81972dae)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_gen_cookie
```
```
In net/xdp/xdp_umem.c (ffffffff81ac4184)
Location: include/asm-generic/atomic-instrumented.h:1461
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
</details>
</li>
</ul>

## Differences
