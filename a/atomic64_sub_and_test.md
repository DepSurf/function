# Function: <code>atomic64_sub_and_test</code>

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
In kernel/cgroup.c (ffffffff81114b5d)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - kernel/cgroup.c:css_killed_work_fn
  - kernel/cgroup.c:cgroup_kn_unlock
  - kernel/cgroup.c:cgroup_release_root
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup.c:cgroup_mount
```
```
In kernel/cgroup_freezer.c (ffffffff8111a09b)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - kernel/cgroup_freezer.c:freezer_read
  - kernel/cgroup_freezer.c:freezer_write
```
```
In kernel/cpuset.c (ffffffff8111c8a6)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:proc_cpuset_show
```
```
In kernel/events/core.c (ffffffff8117ee7d)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/page-writeback.c (ffffffff8119a632)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff811af0bb)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/memcontrol.c (ffffffff811fb24e)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:cancel_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:sock_release_memcg
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:task_in_mem_cgroup
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:__memcg_kmem_get_cache
  - mm/memcontrol.c:__memcg_kmem_put_cache
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:__memcg_kmem_uncharge
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
```
```
In mm/hugetlb_cgroup.c (ffffffff812013ac)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/inode.c (ffffffff81227bf0)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff812381e6)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:wbc_detach_inode
```
```
In fs/block_dev.c (ffffffff81248834)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
```
```
In fs/aio.c (ffffffff8125c20f)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - fs/aio.c:free_ioctx_users
  - fs/aio.c:aio_complete
  - fs/aio.c:SyS_io_setup
  - fs/aio.c:SyS_io_destroy
  - fs/aio.c:do_io_submit
  - fs/aio.c:do_io_submit
  - fs/aio.c:SyS_io_cancel
  - fs/aio.c:SyS_io_getevents
```
```
In block/bio.c (ffffffff813b1aa0)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - block/bio.c:bio_disassociate_task
```
```
In block/blk-core.c (ffffffff813b9ca2)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
```
```
In block/blk-merge.c (ffffffff813c1974)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - block/blk-merge.c:attempt_merge
```
```
In block/blk-cgroup.c (ffffffff813d7f80)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release_rcu
```
```
In lib/percpu-refcount.c (ffffffff813ff0c2)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_call_confirm_rcu
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
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
In arch/x86/mm/gup.c (ffffffff810716e5)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_huge_pmd
  - arch/x86/mm/gup.c:gup_pte_range
```
```
In kernel/cgroup.c (ffffffff81121835)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_sk_free
  - kernel/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup.c:css_killed_work_fn
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup.c:cgroup_kill_sb
  - kernel/cgroup.c:cgroup_mount
  - kernel/cgroup.c:cgroup_mount
  - kernel/cgroup.c:cgroup_kn_unlock
```
```
In kernel/cgroup_freezer.c (ffffffff81122068)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - kernel/cgroup_freezer.c:freezer_write
  - kernel/cgroup_freezer.c:freezer_read
```
```
In kernel/cpuset.c (ffffffff81125943)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - kernel/cpuset.c:proc_cpuset_show
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
```
```
In kernel/bpf/arraymap.c (ffffffff81187ade)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/events/core.c (ffffffff81190ae6)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In kernel/memremap.c (ffffffff8119e264)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages_release
  - kernel/memremap.c:put_zone_device_page
```
```
In mm/page-writeback.c (ffffffff811aef42)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff811c8788)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/gup.c (ffffffff811d4d49)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/huge_memory.c (ffffffff81214a97)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff81224548)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:sock_release_memcg
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:memcg_kmem_uncharge
  - mm/memcontrol.c:memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_put_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:cancel_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:task_in_mem_cgroup
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/hugetlb_cgroup.c (ffffffff81225b6e)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/inode.c (ffffffff8125031f)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff81261af2)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/block_dev.c (ffffffff8127126e)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
```
```
In fs/aio.c (ffffffff81286800)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - fs/aio.c:SyS_io_getevents
  - fs/aio.c:SyS_io_cancel
  - fs/aio.c:do_io_submit
  - fs/aio.c:do_io_submit
  - fs/aio.c:SyS_io_destroy
  - fs/aio.c:SyS_io_setup
  - fs/aio.c:aio_complete
  - fs/aio.c:free_ioctx_users
```
```
In block/bio.c (ffffffff813f5450)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - block/bio.c:bio_disassociate_task
```
```
In block/blk-core.c (ffffffff813fda82)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
```
```
In block/blk-merge.c (ffffffff814058af)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
```
```
In block/blk-cgroup.c (ffffffff8141e0e9)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkg_release_rcu
  - block/blk-cgroup.c:blkg_create
```
```
In lib/percpu-refcount.c (ffffffff81446a29)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_call_confirm_rcu
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
In arch/x86/mm/gup.c (ffffffff81075264)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_huge_pmd
  - arch/x86/mm/gup.c:gup_pte_range
```
```
In kernel/cgroup.c (ffffffff81129dd5)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_sk_free
  - kernel/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup.c:css_killed_work_fn
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup.c:cgroup_kill_sb
  - kernel/cgroup.c:cgroup_mount
  - kernel/cgroup.c:cgroup_mount
  - kernel/cgroup.c:cgroup_kn_unlock
```
```
In kernel/cgroup_freezer.c (ffffffff8112a698)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - kernel/cgroup_freezer.c:freezer_write
  - kernel/cgroup_freezer.c:freezer_read
```
```
In kernel/cpuset.c (ffffffff8112f33d)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - kernel/cpuset.c:proc_cpuset_show
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
```
```
In kernel/bpf/syscall.c (ffffffff8118dd53)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
```
```
In kernel/bpf/arraymap.c (ffffffff8119599e)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/events/core.c (ffffffff8119f9b3)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In kernel/memremap.c (ffffffff811adc93)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages_release
  - kernel/memremap.c:put_zone_device_page
```
```
In mm/page-writeback.c (ffffffff811bf5f2)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff811d88aa)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/gup.c (ffffffff811e4d94)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/huge_memory.c (ffffffff8122703d)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff81236b18)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:memcg_kmem_uncharge
  - mm/memcontrol.c:memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_put_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:cancel_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:task_in_mem_cgroup
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/hugetlb_cgroup.c (ffffffff8123814e)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/inode.c (ffffffff812633bf)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff81274ff2)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/block_dev.c (ffffffff81284bdb)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
```
```
In fs/aio.c (ffffffff8129a77c)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - fs/aio.c:compat_SyS_io_getevents
  - fs/aio.c:SyS_io_cancel
  - fs/aio.c:do_io_submit
  - fs/aio.c:do_io_submit
  - fs/aio.c:SyS_io_destroy
  - fs/aio.c:compat_SyS_io_setup
  - fs/aio.c:SyS_io_setup
  - fs/aio.c:aio_complete
  - fs/aio.c:free_ioctx_users
```
```
In block/bio.c (ffffffff8140ee70)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - block/bio.c:bio_disassociate_task
```
```
In block/blk-core.c (ffffffff814173c2)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
```
```
In block/blk-merge.c (ffffffff8141fb1f)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
```
```
In block/blk-cgroup.c (ffffffff814396a9)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkg_release_rcu
  - block/blk-cgroup.c:blkg_create
```
```
In lib/percpu-refcount.c (ffffffff8146522d)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
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
In kernel/cgroup/cgroup.c (ffffffff81128bb5)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_free_work_fn
  - kernel/cgroup/cgroup.c:css_free_work_fn
  - kernel/cgroup/cgroup.c:css_free_work_fn
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_mount
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8112ab8e)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
```
In kernel/cgroup/freezer.c (ffffffff8112b3b4)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_write
  - kernel/cgroup/freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8112bd60)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff811309b5)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/bpf/syscall.c (ffffffff81193a0a)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
```
```
In kernel/bpf/arraymap.c (ffffffff8119cdae)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/events/core.c (ffffffff811a968f)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
```
```
In kernel/memremap.c (ffffffff811b5224)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages_release
```
```
In mm/page-writeback.c (ffffffff811c754c)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (ffffffff811cba51)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
```
```
In mm/backing-dev.c (ffffffff811e1cfd)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffffffff811e67e4)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - mm/slab_common.c:kmemcg_deactivate_workfn
```
```
In mm/gup.c (ffffffff811f0f05)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:follow_page_pte
```
```
In mm/huge_memory.c (ffffffff8123336a)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff812425b1)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:memcg_kmem_uncharge
  - mm/memcontrol.c:memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_put_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:task_in_mem_cgroup
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/hugetlb_cgroup.c (ffffffff81243dad)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/inode.c (ffffffff81270c0c)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff8128259a)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/block_dev.c (ffffffff812927f2)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/aio.c (ffffffff812a84d1)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - fs/aio.c:compat_SyS_io_getevents
  - fs/aio.c:SyS_io_cancel
  - fs/aio.c:do_io_submit
  - fs/aio.c:do_io_submit
  - fs/aio.c:SyS_io_destroy
  - fs/aio.c:compat_SyS_io_setup
  - fs/aio.c:SyS_io_setup
  - fs/aio.c:aio_complete
  - fs/aio.c:free_ioctx_users
```
```
In block/bio.c (ffffffff8141c990)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - block/bio.c:bio_disassociate_task
```
```
In block/blk-core.c (ffffffff81425276)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
```
```
In block/blk-merge.c (ffffffff8142d9e2)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - block/blk-merge.c:attempt_merge
```
```
In block/blk-cgroup.c (ffffffff81446edc)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkg_release_rcu
  - block/blk-cgroup.c:blkg_create
```
```
In lib/percpu-refcount.c (ffffffff8146a35a)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/md/md.c (ffffffff8173fa8f)
Location: arch/x86/include/asm/atomic64_64.h:73
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_end
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
In kernel/kthread.c (ffffffff810ac97f)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff811351ea)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_free_work_fn
  - kernel/cgroup/cgroup.c:css_free_work_fn
  - kernel/cgroup/cgroup.c:css_free_work_fn
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_mount
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8113791e)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
```
In kernel/cgroup/freezer.c (ffffffff811381b4)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_write
  - kernel/cgroup/freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff81138b60)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff8113d8f5)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/bpf/syscall.c (ffffffff811a0f3e)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
```
```
In kernel/bpf/arraymap.c (ffffffff811ac863)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/events/core.c (ffffffff811bcee4)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
```
```
In kernel/memremap.c (ffffffff811c947d)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages_release
```
```
In mm/page-writeback.c (ffffffff811dc362)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (ffffffff811e044f)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In mm/backing-dev.c (ffffffff811f7d5e)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffffffff811fca2a)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/slab_common.c:kmemcg_deactivate_workfn
```
```
In mm/gup.c (ffffffff81205b22)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:follow_page_pte
```
```
In mm/huge_memory.c (ffffffff81250cb9)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff812623e8)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:memcg_kmem_uncharge
  - mm/memcontrol.c:memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_put_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:task_in_mem_cgroup
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/hugetlb_cgroup.c (ffffffff81263c03)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/hmm.c (ffffffff8126e398)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/hmm.c:hmm_devmem_release
```
```
In fs/inode.c (ffffffff8129353c)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff812a510a)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/block_dev.c (ffffffff812b5602)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/aio.c (ffffffff812c9fc6)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:SyS_io_cancel
  - fs/aio.c:do_io_submit
  - fs/aio.c:do_io_submit
  - fs/aio.c:SyS_io_destroy
  - fs/aio.c:compat_SyS_io_setup
  - fs/aio.c:SyS_io_setup
  - fs/aio.c:aio_complete
  - fs/aio.c:free_ioctx_users
```
```
In block/bio.c (ffffffff81447550)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/bio.c:bio_disassociate_task
```
```
In block/blk-core.c (ffffffff8145058f)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:__blk_put_request
  - block/blk-core.c:blk_get_request_flags
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-merge.c (ffffffff81458c11)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/blk-merge.c:attempt_merge
```
```
In block/blk-cgroup.c (ffffffff81473abc)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkg_release_rcu
  - block/blk-cgroup.c:blkg_create
```
```
In lib/percpu-refcount.c (ffffffff8149664c)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffffffff8166fe1e)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/md/md.c (ffffffff817b1aaf)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_end
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
In kernel/kthread.c (ffffffff810b3996)
Location: include/asm-generic/atomic-instrumented.h:334
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff81143909)
Location: include/asm-generic/atomic-instrumented.h:334
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_mount
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8114620e)
Location: include/asm-generic/atomic-instrumented.h:334
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
```
In kernel/cgroup/freezer.c (ffffffff8114696f)
Location: include/asm-generic/atomic-instrumented.h:334
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_write
  - kernel/cgroup/freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff81147489)
Location: include/asm-generic/atomic-instrumented.h:334
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff8114c16d)
Location: include/asm-generic/atomic-instrumented.h:334
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/bpf/arraymap.c (ffffffff811c3e42)
Location: include/asm-generic/atomic-instrumented.h:334
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffffffff811d2855)
Location: include/asm-generic/atomic-instrumented.h:334
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
```
```
In kernel/events/core.c (ffffffff811d9471)
Location: include/asm-generic/atomic-instrumented.h:334
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In kernel/memremap.c (ffffffff811e96cd)
Location: include/asm-generic/atomic-instrumented.h:334
Inline: True
Inline callers:
  - kernel/memremap.c:get_dev_pagemap
  - kernel/memremap.c:devm_memremap_pages
  - kernel/memremap.c:devm_memremap_pages_release
```
```
In mm/page-writeback.c (ffffffff811fdbc0)
Location: include/asm-generic/atomic-instrumented.h:334
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (ffffffff812013d2)
Location: include/asm-generic/atomic-instrumented.h:334
Inline: True
```
```
In mm/backing-dev.c (ffffffff812190c9)
Location: include/asm-generic/atomic-instrumented.h:334
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffffffff8121dd7a)
Location: include/asm-generic/atomic-instrumented.h:334
Inline: True
Inline callers:
  - mm/slab_common.c:kmemcg_deactivate_workfn
```
```
In mm/gup.c (ffffffff81226c9e)
Location: include/asm-generic/atomic-instrumented.h:334
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:follow_page_pte
```
```
In mm/huge_memory.c (ffffffff812751cc)
Location: include/asm-generic/atomic-instrumented.h:334
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff812864ac)
Location: include/asm-generic/atomic-instrumented.h:334
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:memcg_kmem_uncharge
  - mm/memcontrol.c:memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_put_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:task_in_mem_cgroup
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/hugetlb_cgroup.c (ffffffff81287edf)
Location: include/asm-generic/atomic-instrumented.h:334
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff81289bf6)
Location: include/asm-generic/atomic-instrumented.h:334
Inline: True
```
```
In mm/hmm.c (ffffffff812928cd)
Location: include/asm-generic/atomic-instrumented.h:334
Inline: True
Inline callers:
  - mm/hmm.c:hmm_devmem_release
```
```
In fs/inode.c (ffffffff812b9178)
Location: include/asm-generic/atomic-instrumented.h:334
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff812cbfeb)
Location: include/asm-generic/atomic-instrumented.h:334
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/block_dev.c (ffffffff812dcb12)
Location: include/asm-generic/atomic-instrumented.h:334
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/aio.c (ffffffff812f3206)
Location: include/asm-generic/atomic-instrumented.h:334
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
  - fs/aio.c:io_submit_one
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:__x32_compat_sys_io_setup
  - fs/aio.c:__ia32_compat_sys_io_setup
  - fs/aio.c:__ia32_sys_io_setup
  - fs/aio.c:__x64_sys_io_setup
  - fs/aio.c:aio_complete
  - fs/aio.c:free_ioctx_users
```
```
In block/bio.c (ffffffff8147a650)
Location: include/asm-generic/atomic-instrumented.h:334
Inline: True
Inline callers:
  - block/bio.c:bio_disassociate_task
```
```
In block/blk-core.c (ffffffff8148387c)
Location: include/asm-generic/atomic-instrumented.h:334
Inline: True
Inline callers:
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:__blk_put_request
  - block/blk-core.c:blk_get_request
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-merge.c (ffffffff8148c064)
Location: include/asm-generic/atomic-instrumented.h:334
Inline: True
```
```
In block/blk-cgroup.c (ffffffff814a7e8c)
Location: include/asm-generic/atomic-instrumented.h:334
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkg_release_rcu
  - block/blk-cgroup.c:blkg_create
```
```
In lib/percpu-refcount.c (ffffffff814cb8ac)
Location: include/asm-generic/atomic-instrumented.h:334
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffffffff816ab8ee)
Location: include/asm-generic/atomic-instrumented.h:334
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (ffffffff816e229e)
Location: include/asm-generic/atomic-instrumented.h:334
Inline: True
```
```
In drivers/md/md.c (ffffffff817f5633)
Location: include/asm-generic/atomic-instrumented.h:334
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_end
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
In kernel/kthread.c (ffffffff810bcc96)
Location: include/asm-generic/atomic-instrumented.h:386
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8114f419)
Location: include/asm-generic/atomic-instrumented.h:386
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_mount
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81151dc4)
Location: include/asm-generic/atomic-instrumented.h:386
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
```
In kernel/cgroup/freezer.c (ffffffff8115263e)
Location: include/asm-generic/atomic-instrumented.h:386
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_write
  - kernel/cgroup/freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff81153159)
Location: include/asm-generic/atomic-instrumented.h:386
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff81158daf)
Location: include/asm-generic/atomic-instrumented.h:386
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/bpf/arraymap.c (ffffffff811d5b02)
Location: include/asm-generic/atomic-instrumented.h:386
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffffffff811e25e5)
Location: include/asm-generic/atomic-instrumented.h:386
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
```
```
In kernel/events/core.c (ffffffff811e99a4)
Location: include/asm-generic/atomic-instrumented.h:386
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In kernel/memremap.c (ffffffff811fa067)
Location: include/asm-generic/atomic-instrumented.h:386
Inline: True
Inline callers:
  - kernel/memremap.c:get_dev_pagemap
  - kernel/memremap.c:devm_memremap_pages
```
```
In mm/oom_kill.c (ffffffff81205e02)
Location: include/asm-generic/atomic-instrumented.h:386
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff812106fc)
Location: include/asm-generic/atomic-instrumented.h:386
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (ffffffff81214681)
Location: include/asm-generic/atomic-instrumented.h:386
Inline: True
```
```
In mm/backing-dev.c (ffffffff8122be80)
Location: include/asm-generic/atomic-instrumented.h:386
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffffffff81230d5a)
Location: include/asm-generic/atomic-instrumented.h:386
Inline: True
Inline callers:
  - mm/slab_common.c:kmemcg_deactivate_workfn
```
```
In mm/gup.c (ffffffff8123a15f)
Location: include/asm-generic/atomic-instrumented.h:386
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/memcontrol.c (ffffffff8129b3ff)
Location: include/asm-generic/atomic-instrumented.h:386
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:memcg_kmem_uncharge
  - mm/memcontrol.c:memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_put_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:task_in_mem_cgroup
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/hugetlb_cgroup.c (ffffffff8129ce2b)
Location: include/asm-generic/atomic-instrumented.h:386
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff8129ea5a)
Location: include/asm-generic/atomic-instrumented.h:386
Inline: True
```
```
In fs/inode.c (ffffffff812ce2c9)
Location: include/asm-generic/atomic-instrumented.h:386
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff812e0f00)
Location: include/asm-generic/atomic-instrumented.h:386
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/buffer.c (ffffffff812ebf0a)
Location: include/asm-generic/atomic-instrumented.h:386
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/block_dev.c (ffffffff812f209b)
Location: include/asm-generic/atomic-instrumented.h:386
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (ffffffff812f9c7d)
Location: include/asm-generic/atomic-instrumented.h:386
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (ffffffff81308206)
Location: include/asm-generic/atomic-instrumented.h:386
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:__x32_compat_sys_io_setup
  - fs/aio.c:__ia32_compat_sys_io_setup
  - fs/aio.c:__ia32_sys_io_setup
  - fs/aio.c:__x64_sys_io_setup
  - fs/aio.c:aio_complete
  - fs/aio.c:free_ioctx_users
```
```
In block/bio.c (ffffffff81498696)
Location: include/asm-generic/atomic-instrumented.h:386
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_reset
  - block/bio.c:bio_free
```
```
In block/blk-core.c (ffffffff8149f5a8)
Location: include/asm-generic/atomic-instrumented.h:386
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-merge.c (ffffffff814a5c9e)
Location: include/asm-generic/atomic-instrumented.h:386
Inline: True
```
```
In block/blk-cgroup.c (ffffffff814c33e5)
Location: include/asm-generic/atomic-instrumented.h:386
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffffffff814c6241)
Location: include/asm-generic/atomic-instrumented.h:386
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/percpu-refcount.c (ffffffff814e05fc)
Location: include/asm-generic/atomic-instrumented.h:386
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffffffff816cc68e)
Location: include/asm-generic/atomic-instrumented.h:386
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (ffffffff817056b6)
Location: include/asm-generic/atomic-instrumented.h:386
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81714795)
Location: include/asm-generic/atomic-instrumented.h:386
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff81821493)
Location: include/asm-generic/atomic-instrumented.h:386
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_end
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
In kernel/kthread.c (ffffffff810c2a82)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8115b2bd)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115dba0)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8115eca0)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8115faa3)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff81165531)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/bpf/arraymap.c (ffffffff811ea48d)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffffffff811f9755)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In kernel/events/core.c (ffffffff81202ddc)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff8121c3b5)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff8121fdaf)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (ffffffff81224344)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
```
```
In mm/backing-dev.c (ffffffff8123bb12)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffffffff8124232c)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/gup.c (ffffffff8124b36b)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/slub.c (ffffffff81295a7a)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812b6649)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:__memcg_kmem_uncharge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_put_cache
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/hugetlb_cgroup.c (ffffffff812b7fd4)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff812ba2c6)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
```
```
In mm/memremap.c (ffffffff812c24ef)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:devm_memremap_pages
```
```
In mm/hmm.c (ffffffff812c502f)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/file_table.c (ffffffff812cd835)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
```
```
In fs/inode.c (ffffffff812eb188)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff812ff57e)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/buffer.c (ffffffff8130d64a)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/block_dev.c (ffffffff81313a3b)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (ffffffff8131a32e)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (ffffffff81329cd6)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:__x32_compat_sys_io_setup
  - fs/aio.c:__ia32_compat_sys_io_setup
  - fs/aio.c:__ia32_sys_io_setup
  - fs/aio.c:__x64_sys_io_setup
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (ffffffff8132de7e)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
```
```
In block/bio.c (ffffffff814c6530)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_reset
  - block/bio.c:bio_free
```
```
In block/blk-core.c (ffffffff814cd6a5)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-merge.c (ffffffff814d3d43)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
```
```
In block/blk-mq-sched.c (ffffffff814dd65a)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff814f1ae0)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffffffff814f4a87)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/percpu-refcount.c (ffffffff8150c5a2)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffffffff8170811e)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (ffffffff8173f9b0)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff817500a7)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff81863d63)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_end
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
In kernel/kthread.c (ffffffff810c8ff2)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff81166f7d)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811697b0)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8116a900)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8116b703)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff81171421)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/arraymap.c (ffffffff811f6bed)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffffffff81206825)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In kernel/events/core.c (ffffffff8120fc68)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff81229d85)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff8122d85f)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (ffffffff812320dc)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
```
```
In mm/backing-dev.c (ffffffff81249e63)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffffffff812507bc)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/gup.c (ffffffff8125985b)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/slub.c (ffffffff812a585a)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812c8519)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:__memcg_kmem_uncharge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_put_cache
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/hugetlb_cgroup.c (ffffffff812c9ef2)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff812cc414)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/memremap.c (ffffffff812d441f)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:memremap_pages
```
```
In mm/hmm.c (ffffffff812d69df)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/file_table.c (ffffffff812df255)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
```
```
In fs/inode.c (ffffffff812fccc8)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff81314b9b)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/buffer.c (ffffffff8132061a)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/block_dev.c (ffffffff8132694b)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (ffffffff8132d14e)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (ffffffff8133cb36)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:__x32_compat_sys_io_setup
  - fs/aio.c:__ia32_compat_sys_io_setup
  - fs/aio.c:__ia32_sys_io_setup
  - fs/aio.c:__x64_sys_io_setup
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (ffffffff81343e96)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:__io_free_req
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (ffffffff814de41e)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
```
```
In block/blk-core.c (ffffffff814e6995)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-merge.c (ffffffff814ed073)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
```
```
In block/blk-mq-sched.c (ffffffff814f6aea)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff8150b0c0)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffffffff8150e020)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/percpu-refcount.c (ffffffff8152a3f2)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffffffff8172c36e)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (ffffffff81763b90)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81774297)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff81895aa3)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_end
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
In kernel/kthread.c (ffffffff810d09e5)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff81178698)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8117a1e4)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8117c3be)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8117d314)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff81183131)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_root_domains
```
```
In kernel/bpf/arraymap.c (ffffffff8121a4bd)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffffffff8122e445)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_link_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In kernel/events/core.c (ffffffff8123ac4c)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff81256c2a)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff8125b3cf)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (ffffffff8125e4f0)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - mm/swap.c:__put_page
```
```
In mm/backing-dev.c (ffffffff8127818a)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffffffff8127ee0a)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/gup.c (ffffffff8128a93a)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:gup_pte_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/slub.c (ffffffff812da523)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812fddb4)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:__memcg_kmem_uncharge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:memcg_kmem_put_cache
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:drain_stock
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/hugetlb_cgroup.c (ffffffff812ffd10)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff81301030)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
```
```
In mm/memremap.c (ffffffff8130a0d2)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:memremap_pages
```
```
In fs/file_table.c (ffffffff813160b5)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
```
```
In fs/inode.c (ffffffff81335568)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff8134e557)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/buffer.c (ffffffff81359a6a)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/block_dev.c (ffffffff81360e7e)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (ffffffff81366ecf)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_final_destroy_group
```
```
In fs/aio.c (ffffffff81375f06)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:__x32_compat_sys_io_setup
  - fs/aio.c:__ia32_compat_sys_io_setup
  - fs/aio.c:__ia32_sys_io_setup
  - fs/aio.c:__x64_sys_io_setup
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (ffffffff8137fc5c)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_show_fdinfo
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:__io_file_put_work
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_cleanup_req
  - fs/io_uring.c:io_async_task_func
  - fs/io_uring.c:io_poll_task_func
  - fs/io_uring.c:__io_free_req
  - fs/io_uring.c:__io_req_aux_free
```
```
In block/bio.c (ffffffff8153e25f)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - block/bio.c:bio_uninit
```
```
In block/blk-core.c (ffffffff81545f08)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-merge.c (ffffffff8154aee8)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - block/blk-merge.c:blk_account_io_merge_request
```
```
In block/blk-mq.c (ffffffff8154f994)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
```
```
In block/blk-mq-sched.c (ffffffff8155758a)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff8156c027)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffffffff8156e39f)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/percpu-refcount.c (ffffffff8158dbd1)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffffffff817e7b2e)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (ffffffff81823a84)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
```
```
In drivers/scsi/scsi_lib.c (ffffffff81836bf8)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff81962fdc)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_end
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
In kernel/kthread.c (ffffffff810cb5d2)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff81175452)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81176f61)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8117928c)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8117a179)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff811800cf)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_root_domains
```
```
In kernel/bpf/syscall.c (ffffffff811fb64d)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_free_deferred
```
```
In kernel/bpf/arraymap.c (ffffffff8121d137)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/trampoline.c (ffffffff81222b81)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_tramp_exit
```
```
In kernel/bpf/cgroup.c (ffffffff81236993)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_link_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In kernel/events/core.c (ffffffff81244086)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff8126183f)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff812654db)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (ffffffff81268b32)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/backing-dev.c (ffffffff81282914)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/percpu.c (ffffffff812860c8)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_memcg_free_hook
```
```
In mm/gup.c (ffffffff812945f2)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:gup_pte_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/mmap_lock.c (ffffffff81295fac)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - mm/mmap_lock.c:get_mm_memcg_path
```
```
In mm/hugetlb.c (ffffffff812d3ba8)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:coalesce_file_region
  - mm/hugetlb.c:coalesce_file_region
```
```
In mm/slub.c (ffffffff812e6b95)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memcontrol.c (ffffffff8130a230)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_charge
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:obj_cgroup_charge
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:__memcg_kmem_uncharge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:drain_stock
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:memcg_expand_shrinker_maps
  - mm/memcontrol.c:memcg_reparent_objcgs
  - mm/memcontrol.c:obj_cgroup_release
```
```
In mm/hugetlb_cgroup.c (ffffffff8130c0b5)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff8130de9d)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
```
```
In mm/memremap.c (ffffffff81315da3)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:pagemap_range
```
```
In fs/file_table.c (ffffffff813215d5)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - fs/file_table.c:fput
```
```
In fs/inode.c (ffffffff81340edd)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff8135b470)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/buffer.c (ffffffff81367b97)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/block_dev.c (ffffffff8136d16e)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (ffffffff81374224)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_final_destroy_group
```
```
In fs/aio.c (ffffffff81383e8b)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:__x32_compat_sys_io_setup
  - fs/aio.c:__ia32_compat_sys_io_setup
  - fs/aio.c:__ia32_sys_io_setup
  - fs/aio.c:__x64_sys_io_setup
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (ffffffff8138e778)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_show_fdinfo
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_file_put_work
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_async_task_func
  - fs/io_uring.c:io_async_task_func
  - fs/io_uring.c:io_poll_task_func
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_req_free_batch
  - fs/io_uring.c:io_req_task_submit
  - fs/io_uring.c:io_req_task_cancel
  - fs/io_uring.c:__io_free_req
  - fs/io_uring.c:io_dismantle_req
  - fs/io_uring.c:io_req_clean_work
```
```
In block/bio.c (ffffffff8155a584)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - block/bio.c:bio_uninit
```
```
In block/blk-core.c (ffffffff81561978)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio_noacct_mq
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff8156bd77)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
```
```
In block/blk-mq-sched.c (ffffffff81573ba2)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff81585a99)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - block/blk-cgroup.c:bio_clone_blkg_association
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffffffff815898f1)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/percpu-refcount.c (ffffffff815aa8bb)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffffffff817fca12)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (ffffffff8183276e)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
```
```
In drivers/scsi/scsi_lib.c (ffffffff8184768b)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff81969881)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_end
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
In kernel/kthread.c (ffffffff810ccf0f)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff81175fc2)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81177add)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81179dfc)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8117acf9)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff81180b9f)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/syscall.c (ffffffff811fc36d)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_free_deferred
```
```
In kernel/bpf/arraymap.c (ffffffff81220c47)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/trampoline.c (ffffffff812273c1)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_tramp_exit
```
```
In kernel/bpf/cgroup.c (ffffffff8123abf3)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_link_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In kernel/events/core.c (ffffffff8124904a)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff81266052)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff812696ea)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (ffffffff8126e8c3)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/backing-dev.c (ffffffff81287a39)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/percpu.c (ffffffff8128acae)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_memcg_free_hook
```
```
In mm/gup.c (ffffffff8129a042)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:gup_pte_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/mmap_lock.c (ffffffff8129b8c9)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - mm/mmap_lock.c:get_mm_memcg_path
```
```
In mm/memory_hotplug.c (ffffffff812c645f)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - mm/memory_hotplug.c:pfn_to_online_page
```
```
In mm/hugetlb.c (ffffffff812daa8c)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:coalesce_file_region
  - mm/hugetlb.c:coalesce_file_region
```
```
In mm/slub.c (ffffffff812ee3d6)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memcontrol.c (ffffffff81310ab7)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_swapin_charge_page
  - mm/memcontrol.c:mem_cgroup_charge
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:__memcg_kmem_uncharge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:obj_cgroup_charge_pages
  - mm/memcontrol.c:obj_cgroup_uncharge_pages
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:drain_stock
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:obj_cgroup_release
```
```
In mm/hugetlb_cgroup.c (ffffffff813126b5)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff813141aa)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
```
```
In mm/memremap.c (ffffffff8131bf96)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:pagemap_range
```
```
In fs/file_table.c (ffffffff813276b5)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
```
```
In fs/inode.c (ffffffff813472cd)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff81362070)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/block_dev.c (ffffffff813739de)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (ffffffff8137abc3)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (ffffffff8138aadb)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:__x32_compat_sys_io_setup
  - fs/aio.c:__ia32_compat_sys_io_setup
  - fs/aio.c:__ia32_sys_io_setup
  - fs/aio.c:__x64_sys_io_setup
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (ffffffff8139eb54)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_uring_show_fdinfo
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_free_work
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_put_req_deferred_cb
  - fs/io_uring.c:io_submit_flush_completions
  - fs/io_uring.c:tctx_task_work
  - fs/io_uring.c:tctx_task_work
  - fs/io_uring.c:io_dismantle_req
  - fs/io_uring.c:io_req_complete_post
```
```
In block/bio.c (ffffffff81562d64)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - block/bio.c:bio_uninit
```
```
In block/blk-core.c (ffffffff81569f0e)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff81573869)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
```
```
In block/blk-mq-sched.c (ffffffff8157bc32)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff8158c469)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - block/blk-cgroup.c:bio_clone_blkg_association
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffffffff815902f1)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/percpu-refcount.c (ffffffff815b54db)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffffffff817e15e2)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (ffffffff8181555e)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
```
```
In drivers/scsi/scsi_lib.c (ffffffff8182a84b)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff8194dc01)
Location: include/asm-generic/atomic-instrumented.h:1546
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_end
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
In kernel/kthread.c (ffff8000101288f8)
Location: include/linux/atomic-fallback.h:2124
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffff8000101d082c)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_killed_work_fn
```
```
In kernel/cgroup/cgroup-v1.c (ffff8000101dca60)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffff8000101de818)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffff8000101dfa00)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffff8000101e4acc)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/arraymap.c (ffff80001027b8fc)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffff80001028ff58)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In kernel/events/core.c (ffff80001029bf6c)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffff8000102b7c90)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffff8000102bc748)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (0)
Location: include/linux/atomic-fallback.h:2124
Inline: True
```
```
In mm/backing-dev.c (ffff8000102df660)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffff8000102e783c)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/gup.c (ffff8000102f2794)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/slub.c (ffff8000103466cc)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffff800010364cc8)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - mm/memcontrol.c:percpu_ref_put_many
```
```
In mm/hugetlb_cgroup.c (ffff80001036d724)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (0)
Location: include/linux/atomic-fallback.h:2124
Inline: True
```
```
In mm/hmm.c (ffff80001037b988)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/file_table.c (ffff800010385af4)
Location: include/linux/atomic-fallback.h:2124
Inline: True
```
```
In fs/inode.c (ffff8000103acee8)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffff8000103caaec)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/buffer.c (ffff8000103d92c8)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/block_dev.c (ffff8000103e1478)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (ffff8000103e8f5c)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (ffff8000103fc564)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__arm64_sys_io_cancel
  - fs/aio.c:__arm64_compat_sys_io_submit
  - fs/aio.c:__arm64_sys_io_submit
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:__arm64_sys_io_destroy
  - fs/aio.c:__arm64_compat_sys_io_setup
  - fs/aio.c:__arm64_sys_io_setup
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (ffff800010405dc0)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - fs/io_uring.c:__arm64_sys_io_uring_enter
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:__io_free_req
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (ffff8000105db5dc)
Location: include/linux/atomic-fallback.h:2124
Inline: True
```
```
In block/blk-core.c (ffff8000105e4184)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-merge.c (ffff8000105eb908)
Location: include/linux/atomic-fallback.h:2124
Inline: True
```
```
In block/blk-mq-sched.c (ffff8000105f71c4)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffff80001060ea38)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffff800010611c50)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/percpu-refcount.c (ffff80001063559c)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffff800010922318)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (0)
Location: include/linux/atomic-fallback.h:2124
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffff80001097831c)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffff800010aeab08)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_end
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
In kernel/kthread.c (c0000000001735a0)
Location: include/linux/atomic-fallback.h:2124
Inline: True
```
```
In kernel/cgroup/cgroup.c (c000000000246354)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
```
```
In kernel/cgroup/cgroup-v1.c (c00000000024a9d8)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (c00000000024c8d4)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (c00000000024e108)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (c000000000255334)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/arraymap.c (c000000000324b04)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (c00000000033cc84)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In kernel/events/core.c (c00000000034c1a4)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (c00000000036fb24)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (c000000000374c84)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (c00000000037beb0)
Location: include/linux/atomic-fallback.h:2124
Inline: True
```
```
In mm/backing-dev.c (c00000000039f1f4)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (c0000000003a9630)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/gup.c (c0000000003b7484)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/slub.c (c0000000004246e4)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (c00000000045adc4)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:__memcg_kmem_uncharge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_put_cache
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/hugetlb_cgroup.c (c00000000045d8a4)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (c0000000004618a0)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/memremap.c (c00000000046db50)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:memremap_pages
```
```
In mm/hmm.c (c000000000470c1c)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/file_table.c (c00000000047bcb4)
Location: include/linux/atomic-fallback.h:2124
Inline: True
```
```
In fs/inode.c (c0000000004a8734)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (c0000000004cc624)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/buffer.c (c0000000004dd330)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/block_dev.c (c0000000004e7474)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (c0000000004efadc)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (c0000000005052f0)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__se_sys_io_cancel
  - fs/aio.c:__se_compat_sys_io_submit
  - fs/aio.c:__se_sys_io_submit
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:__se_sys_io_destroy
  - fs/aio.c:__se_compat_sys_io_setup
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (c00000000050eb60)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_enter
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:__io_free_req
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (c00000000076b73c)
Location: include/linux/atomic-fallback.h:2124
Inline: True
```
```
In block/blk-core.c (c000000000777ea4)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-merge.c (c000000000780f4c)
Location: include/linux/atomic-fallback.h:2124
Inline: True
```
```
In block/blk-mq-sched.c (c00000000078f7a0)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (c0000000007ac030)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (c0000000007afd44)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/percpu-refcount.c (c0000000007dafd0)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (c0000000009c7834)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (c000000000a1a260)
Location: include/linux/atomic-fallback.h:2124
Inline: True
```
```
In drivers/scsi/scsi_lib.c (c000000000a327e0)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (c000000000bd6f74)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_end
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
In kernel/kthread.c (ffffffe0000df5ac)
Location: include/linux/atomic-fallback.h:2124
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffe000151e2c)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
```
```
In kernel/cgroup/cgroup-v1.c (ffffffe0001546d2)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffe000155b7e)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffe000156a3e)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffe00015aca8)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/bpf/arraymap.c (ffffffe0001b30f4)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffffffe0001c2b66)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In kernel/events/core.c (ffffffe0001c9a42)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffe0001dbf14)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffe0001df416)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (0)
Location: include/linux/atomic-fallback.h:2124
Inline: True
```
```
In mm/backing-dev.c (ffffffe0001f73bc)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffffffe0001fd2da)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/gup.c (ffffffe000204d60)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/slub.c (ffffffe00023957c)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffe000248b3e)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:__memcg_kmem_uncharge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_put_cache
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/hugetlb_cgroup.c (ffffffe00024a44e)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/hmm.c (ffffffe00025214e)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/file_table.c (ffffffe000258774)
Location: include/linux/atomic-fallback.h:2124
Inline: True
```
```
In fs/inode.c (ffffffe000271cdc)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffe000288c6c)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/buffer.c (ffffffe000291e2a)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/block_dev.c (ffffffe000297c88)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (ffffffe00029da1a)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_final_destroy_group
```
```
In fs/aio.c (ffffffe0002aa1cc)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__se_sys_io_cancel
  - fs/aio.c:__se_sys_io_submit
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:__se_sys_io_destroy
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (ffffffe0002b1042)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_enter
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:__io_free_req
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (ffffffe00041e49c)
Location: include/linux/atomic-fallback.h:2124
Inline: True
```
```
In block/blk-core.c (ffffffe000425a7c)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-merge.c (ffffffe00042b8f8)
Location: include/linux/atomic-fallback.h:2124
Inline: True
```
```
In block/blk-mq-sched.c (ffffffe0004348b4)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffe000446e60)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffffffe0004494b4)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/percpu-refcount.c (ffffffe000462f8e)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffffffe0005a0ffe)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (0)
Location: include/linux/atomic-fallback.h:2124
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffe0005dfdb0)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffe0006de386)
Location: include/linux/atomic-fallback.h:2124
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_end
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
In kernel/kthread.c (ffffffff810c3372)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8115f59d)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81161dd0)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81162f20)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff81163d23)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff81169a41)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/arraymap.c (ffffffff811ef20d)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffffffff811fee45)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In kernel/events/core.c (ffffffff81208288)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff812223d5)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff81225eaf)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (ffffffff8122a72c)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
```
```
In mm/backing-dev.c (ffffffff812424b3)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffffffff81248e0c)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/gup.c (ffffffff81251eab)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/slub.c (ffffffff8129de3a)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812c0af9)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:__memcg_kmem_uncharge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_put_cache
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/hugetlb_cgroup.c (ffffffff812c24d2)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff812c49f4)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/memremap.c (ffffffff812cc9ff)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:memremap_pages
```
```
In mm/hmm.c (ffffffff812cefbf)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/file_table.c (ffffffff812d7835)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
```
```
In fs/inode.c (ffffffff812f52a8)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff8130d17b)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/buffer.c (ffffffff81318bfa)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/block_dev.c (ffffffff8131ef2b)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (ffffffff8132572e)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (ffffffff81335116)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:__x32_compat_sys_io_setup
  - fs/aio.c:__ia32_compat_sys_io_setup
  - fs/aio.c:__ia32_sys_io_setup
  - fs/aio.c:__x64_sys_io_setup
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (ffffffff8133c476)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:__io_free_req
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (ffffffff814d69fe)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
```
```
In block/blk-core.c (ffffffff814def75)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-merge.c (ffffffff814e5653)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
```
```
In block/blk-mq-sched.c (ffffffff814ef0ca)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff815036a0)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffffffff81506600)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/percpu-refcount.c (ffffffff815229d2)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffffffff816f214e)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (ffffffff81718280)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81728987)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff8183b923)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_end
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
In kernel/kthread.c (ffffffff810b1bb2)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8115282d)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81155030)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81156170)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff81156f73)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff8115cc41)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/arraymap.c (ffffffff811e1f9d)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffffffff811f1b95)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In kernel/events/core.c (ffffffff811fb405)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff81215585)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff8121904f)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (ffffffff8121d84c)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
```
```
In mm/backing-dev.c (ffffffff81235483)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffffffff8123bdb6)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/gup.c (ffffffff81244ae7)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/slub.c (ffffffff8128f9b3)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812b1b85)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:__memcg_kmem_uncharge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_put_cache
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/hugetlb_cgroup.c (ffffffff812b3522)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff812b5a34)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/memremap.c (ffffffff812bd86f)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:memremap_pages
```
```
In mm/hmm.c (ffffffff812bfc51)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/file_table.c (ffffffff812c84b5)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
```
```
In fs/inode.c (ffffffff812e5ec8)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff812fdd8b)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/buffer.c (ffffffff813097ea)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/block_dev.c (ffffffff8130facb)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (ffffffff813162ce)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (ffffffff81325aa6)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:__x32_compat_sys_io_setup
  - fs/aio.c:__ia32_compat_sys_io_setup
  - fs/aio.c:__ia32_sys_io_setup
  - fs/aio.c:__x64_sys_io_setup
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (ffffffff8132d146)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:__io_free_req
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (ffffffff814c73be)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
```
```
In block/blk-core.c (ffffffff814cf915)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-merge.c (ffffffff814d5c84)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
```
```
In block/blk-mq-sched.c (ffffffff814df60a)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff814f3b60)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffffffff814f6ac0)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/percpu-refcount.c (ffffffff81512cb2)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffffffff816cc24e)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (ffffffff816f07b0)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81701db7)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff81802f83)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_end
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
In kernel/kthread.c (ffffffff810c28c2)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8115d36d)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115fba0)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81160cf0)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff81161af3)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff81167811)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/arraymap.c (ffffffff811ecfdd)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffffffff811fcc15)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In kernel/events/core.c (ffffffff81206058)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff81220175)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff81223c4f)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (ffffffff812284cc)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
```
```
In mm/backing-dev.c (ffffffff81240253)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffffffff81246bac)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/gup.c (ffffffff8124fc4b)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/slub.c (ffffffff8129bc4a)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812be909)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:__memcg_kmem_uncharge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_put_cache
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/hugetlb_cgroup.c (ffffffff812c02e2)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff812c2804)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/memremap.c (ffffffff812ca80f)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:memremap_pages
```
```
In mm/hmm.c (ffffffff812ccdcf)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/file_table.c (ffffffff812d5645)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
```
```
In fs/inode.c (ffffffff812f30b8)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff8130af6b)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/buffer.c (ffffffff813166ca)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/block_dev.c (ffffffff8131c9fb)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (ffffffff813231fe)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (ffffffff81332be6)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:__x32_compat_sys_io_setup
  - fs/aio.c:__ia32_compat_sys_io_setup
  - fs/aio.c:__ia32_sys_io_setup
  - fs/aio.c:__x64_sys_io_setup
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (ffffffff81339f46)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:__io_free_req
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (ffffffff814d2a8e)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
```
```
In block/blk-core.c (ffffffff814db005)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-merge.c (ffffffff814e16e3)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
```
```
In block/blk-mq-sched.c (ffffffff814eb15a)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff814ff730)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffffffff81502690)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/percpu-refcount.c (ffffffff8151ea62)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffffffff8171f82e)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (ffffffff81757050)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81767757)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff8188af53)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_end
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
In kernel/kthread.c (ffffffff810caed4)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8116a591)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8116ce9c)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8116e125)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8116ef53)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff81174ebb)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/arraymap.c (ffffffff811fb499)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffffffff8120b8b1)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In kernel/events/core.c (ffffffff81214f0f)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff8122f28f)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff81232f26)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (ffffffff8123782f)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
```
```
In mm/backing-dev.c (ffffffff8124faab)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffffffff812563d7)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/gup.c (ffffffff8125f5e5)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/slub.c (ffffffff812abb48)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812cf371)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:__memcg_kmem_uncharge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_put_cache
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/hugetlb_cgroup.c (ffffffff812d0d53)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff812d329e)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/memremap.c (ffffffff812db530)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:memremap_pages
```
```
In mm/hmm.c (ffffffff812ddb76)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/file_table.c (ffffffff812e6495)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
```
```
In fs/inode.c (ffffffff81304a0d)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff8131c6fa)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/buffer.c (ffffffff813284c2)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/block_dev.c (ffffffff8132eaf0)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (ffffffff81334f53)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (ffffffff81345d86)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:__x32_compat_sys_io_setup
  - fs/aio.c:__ia32_compat_sys_io_setup
  - fs/aio.c:__ia32_sys_io_setup
  - fs/aio.c:__x64_sys_io_setup
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (ffffffff8134d972)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:__io_free_req
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (ffffffff814eb5e5)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
```
```
In block/blk-core.c (ffffffff814f3dd4)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-merge.c (ffffffff814fa59f)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
```
```
In block/blk-mq-sched.c (ffffffff81504162)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff815188ff)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffffffff8151bad4)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/percpu-refcount.c (ffffffff81538332)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffffffff8173ac73)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (ffffffff817724e4)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81782e8c)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff818aa1aa)
Location: include/asm-generic/atomic-instrumented.h:1545
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_end
```
</details>
</li>
</ul>

## Differences
