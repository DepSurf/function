# Function: <code>percpu_ref_put_many</code>

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
In kernel/cgroup.c (ffffffff81114b4f)
Location: include/linux/percpu-refcount.h:269
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
In kernel/cgroup_freezer.c (ffffffff81119ff8)
Location: include/linux/percpu-refcount.h:269
Inline: True
Inline callers:
  - kernel/cgroup_freezer.c:freezer_read
  - kernel/cgroup_freezer.c:freezer_write
```
```
In kernel/cpuset.c (ffffffff8111c589)
Location: include/linux/percpu-refcount.h:269
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:proc_cpuset_show
```
```
In kernel/events/core.c (ffffffff8117ed52)
Location: include/linux/percpu-refcount.h:269
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/page-writeback.c (ffffffff8119a54a)
Location: include/linux/percpu-refcount.h:269
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff811af08e)
Location: include/linux/percpu-refcount.h:269
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/memcontrol.c (ffffffff811fb23d)
Location: include/linux/percpu-refcount.h:269
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
In mm/hugetlb_cgroup.c (ffffffff81201399)
Location: include/linux/percpu-refcount.h:269
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/inode.c (ffffffff81227b52)
Location: include/linux/percpu-refcount.h:269
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff812381af)
Location: include/linux/percpu-refcount.h:269
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
In fs/block_dev.c (ffffffff812486e6)
Location: include/linux/percpu-refcount.h:269
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
```
```
In fs/aio.c (ffffffff8125c1fc)
Location: include/linux/percpu-refcount.h:269
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
In block/bio.c (ffffffff813b1a8d)
Location: include/linux/percpu-refcount.h:269
Inline: True
Inline callers:
  - block/bio.c:bio_disassociate_task
```
```
In block/blk-core.c (ffffffff813b9c65)
Location: include/linux/percpu-refcount.h:269
Inline: True
```
```
In block/blk-merge.c (ffffffff813c194d)
Location: include/linux/percpu-refcount.h:269
Inline: True
Inline callers:
  - block/blk-merge.c:attempt_merge
```
```
In block/blk-cgroup.c (ffffffff813d7efe)
Location: include/linux/percpu-refcount.h:269
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release_rcu
```
```
In lib/percpu-refcount.c (ffffffff813ff0b1)
Location: include/linux/percpu-refcount.h:269
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
In arch/x86/mm/gup.c (ffffffff8107161c)
Location: include/linux/percpu-refcount.h:267
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_huge_pmd
  - arch/x86/mm/gup.c:gup_pte_range
```
```
In kernel/cgroup.c (ffffffff81121823)
Location: include/linux/percpu-refcount.h:267
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
In kernel/cgroup_freezer.c (ffffffff81121fff)
Location: include/linux/percpu-refcount.h:267
Inline: True
Inline callers:
  - kernel/cgroup_freezer.c:freezer_write
  - kernel/cgroup_freezer.c:freezer_read
```
```
In kernel/cpuset.c (ffffffff81125928)
Location: include/linux/percpu-refcount.h:267
Inline: True
Inline callers:
  - kernel/cpuset.c:proc_cpuset_show
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
```
```
In kernel/bpf/arraymap.c (ffffffff81187acd)
Location: include/linux/percpu-refcount.h:267
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/events/core.c (ffffffff81190957)
Location: include/linux/percpu-refcount.h:267
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In kernel/memremap.c (ffffffff8119e192)
Location: include/linux/percpu-refcount.h:267
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages_release
  - kernel/memremap.c:put_zone_device_page
```
```
In mm/page-writeback.c (ffffffff811aee5a)
Location: include/linux/percpu-refcount.h:267
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff811c85d1)
Location: include/linux/percpu-refcount.h:267
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/gup.c (ffffffff811d4cad)
Location: include/linux/percpu-refcount.h:267
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/huge_memory.c (ffffffff81214a00)
Location: include/linux/percpu-refcount.h:267
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff81224528)
Location: include/linux/percpu-refcount.h:267
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
In mm/hugetlb_cgroup.c (ffffffff81225ae8)
Location: include/linux/percpu-refcount.h:267
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/inode.c (ffffffff81250282)
Location: include/linux/percpu-refcount.h:267
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff8126195e)
Location: include/linux/percpu-refcount.h:267
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
In fs/block_dev.c (ffffffff8127111c)
Location: include/linux/percpu-refcount.h:267
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
```
```
In fs/aio.c (ffffffff812867e4)
Location: include/linux/percpu-refcount.h:267
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
In block/bio.c (ffffffff813f543d)
Location: include/linux/percpu-refcount.h:267
Inline: True
Inline callers:
  - block/bio.c:bio_disassociate_task
```
```
In block/blk-core.c (ffffffff813fda45)
Location: include/linux/percpu-refcount.h:267
Inline: True
```
```
In block/blk-merge.c (ffffffff81405883)
Location: include/linux/percpu-refcount.h:267
Inline: True
```
```
In block/blk-cgroup.c (ffffffff8141e0d6)
Location: include/linux/percpu-refcount.h:267
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkg_release_rcu
  - block/blk-cgroup.c:blkg_create
```
```
In lib/percpu-refcount.c (ffffffff81446a18)
Location: include/linux/percpu-refcount.h:267
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
In arch/x86/mm/gup.c (ffffffff8107518d)
Location: include/linux/percpu-refcount.h:267
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_huge_pmd
  - arch/x86/mm/gup.c:gup_pte_range
```
```
In kernel/cgroup.c (ffffffff81129dc3)
Location: include/linux/percpu-refcount.h:267
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
In kernel/cgroup_freezer.c (ffffffff8112a62f)
Location: include/linux/percpu-refcount.h:267
Inline: True
Inline callers:
  - kernel/cgroup_freezer.c:freezer_write
  - kernel/cgroup_freezer.c:freezer_read
```
```
In kernel/cpuset.c (ffffffff8112f323)
Location: include/linux/percpu-refcount.h:267
Inline: True
Inline callers:
  - kernel/cpuset.c:proc_cpuset_show
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
```
```
In kernel/bpf/syscall.c (ffffffff8118da7f)
Location: include/linux/percpu-refcount.h:267
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
```
```
In kernel/bpf/arraymap.c (ffffffff8119598d)
Location: include/linux/percpu-refcount.h:267
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/events/core.c (ffffffff8119f825)
Location: include/linux/percpu-refcount.h:267
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In kernel/memremap.c (ffffffff811adbb1)
Location: include/linux/percpu-refcount.h:267
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages_release
  - kernel/memremap.c:put_zone_device_page
```
```
In mm/page-writeback.c (ffffffff811bf50a)
Location: include/linux/percpu-refcount.h:267
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff811d8747)
Location: include/linux/percpu-refcount.h:267
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/gup.c (ffffffff811e4ce6)
Location: include/linux/percpu-refcount.h:267
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/huge_memory.c (ffffffff81226f8c)
Location: include/linux/percpu-refcount.h:267
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff81236af8)
Location: include/linux/percpu-refcount.h:267
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
In mm/hugetlb_cgroup.c (ffffffff812380c8)
Location: include/linux/percpu-refcount.h:267
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/inode.c (ffffffff81263322)
Location: include/linux/percpu-refcount.h:267
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff81274e5e)
Location: include/linux/percpu-refcount.h:267
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
In fs/block_dev.c (ffffffff81284a89)
Location: include/linux/percpu-refcount.h:267
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
```
```
In fs/aio.c (ffffffff8129a750)
Location: include/linux/percpu-refcount.h:267
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
In block/bio.c (ffffffff8140ee5d)
Location: include/linux/percpu-refcount.h:267
Inline: True
Inline callers:
  - block/bio.c:bio_disassociate_task
```
```
In block/blk-core.c (ffffffff81417385)
Location: include/linux/percpu-refcount.h:267
Inline: True
```
```
In block/blk-merge.c (ffffffff8141faf8)
Location: include/linux/percpu-refcount.h:267
Inline: True
```
```
In block/blk-cgroup.c (ffffffff81439696)
Location: include/linux/percpu-refcount.h:267
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkg_release_rcu
  - block/blk-cgroup.c:blkg_create
```
```
In lib/percpu-refcount.c (ffffffff8146520a)
Location: include/linux/percpu-refcount.h:267
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
In kernel/cgroup/cgroup.c (ffffffff81128ba3)
Location: include/linux/percpu-refcount.h:268
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
In kernel/cgroup/cgroup-v1.c (ffffffff8112a8c4)
Location: include/linux/percpu-refcount.h:268
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
```
In kernel/cgroup/freezer.c (ffffffff8112b366)
Location: include/linux/percpu-refcount.h:268
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_write
  - kernel/cgroup/freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8112bd45)
Location: include/linux/percpu-refcount.h:268
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff8113097c)
Location: include/linux/percpu-refcount.h:268
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/bpf/syscall.c (ffffffff81192c9c)
Location: include/linux/percpu-refcount.h:268
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
```
```
In kernel/bpf/arraymap.c (ffffffff8119cd9d)
Location: include/linux/percpu-refcount.h:268
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/events/core.c (ffffffff811a94ed)
Location: include/linux/percpu-refcount.h:268
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
```
```
In kernel/memremap.c (ffffffff811b510b)
Location: include/linux/percpu-refcount.h:268
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages_release
```
```
In mm/page-writeback.c (ffffffff811c7532)
Location: include/linux/percpu-refcount.h:268
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (ffffffff811cba42)
Location: include/linux/percpu-refcount.h:268
Inline: True
```
```
In mm/backing-dev.c (ffffffff811e1969)
Location: include/linux/percpu-refcount.h:268
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffffffff811e67d0)
Location: include/linux/percpu-refcount.h:268
Inline: True
Inline callers:
  - mm/slab_common.c:kmemcg_deactivate_workfn
```
```
In mm/gup.c (ffffffff811f0bd8)
Location: include/linux/percpu-refcount.h:268
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:follow_page_pte
```
```
In mm/huge_memory.c (ffffffff812332da)
Location: include/linux/percpu-refcount.h:268
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff81242577)
Location: include/linux/percpu-refcount.h:268
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
In mm/hugetlb_cgroup.c (ffffffff81243d32)
Location: include/linux/percpu-refcount.h:268
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In fs/inode.c (ffffffff81270b4f)
Location: include/linux/percpu-refcount.h:268
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff812823a6)
Location: include/linux/percpu-refcount.h:268
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
In fs/block_dev.c (ffffffff812927af)
Location: include/linux/percpu-refcount.h:268
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/aio.c (ffffffff812a84a0)
Location: include/linux/percpu-refcount.h:268
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
In block/bio.c (ffffffff8141c97d)
Location: include/linux/percpu-refcount.h:268
Inline: True
Inline callers:
  - block/bio.c:bio_disassociate_task
```
```
In block/blk-core.c (ffffffff814250e8)
Location: include/linux/percpu-refcount.h:268
Inline: True
```
```
In block/blk-merge.c (ffffffff8142d991)
Location: include/linux/percpu-refcount.h:268
Inline: True
Inline callers:
  - block/blk-merge.c:attempt_merge
```
```
In block/blk-cgroup.c (ffffffff81446eb0)
Location: include/linux/percpu-refcount.h:268
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkg_release_rcu
  - block/blk-cgroup.c:blkg_create
```
```
In lib/percpu-refcount.c (ffffffff8146a309)
Location: include/linux/percpu-refcount.h:268
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/md/md.c (ffffffff8173fa2d)
Location: include/linux/percpu-refcount.h:268
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
In kernel/kthread.c (ffffffff810ac964)
Location: include/linux/percpu-refcount.h:269
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff811351d7)
Location: include/linux/percpu-refcount.h:269
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
In kernel/cgroup/cgroup-v1.c (ffffffff81137654)
Location: include/linux/percpu-refcount.h:269
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
```
In kernel/cgroup/freezer.c (ffffffff81138166)
Location: include/linux/percpu-refcount.h:269
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_write
  - kernel/cgroup/freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff81138b45)
Location: include/linux/percpu-refcount.h:269
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff8113d8bc)
Location: include/linux/percpu-refcount.h:269
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/bpf/syscall.c (ffffffff8119ffae)
Location: include/linux/percpu-refcount.h:269
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
```
```
In kernel/bpf/arraymap.c (ffffffff811ac851)
Location: include/linux/percpu-refcount.h:269
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/events/core.c (ffffffff811bcd35)
Location: include/linux/percpu-refcount.h:269
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
```
```
In kernel/memremap.c (ffffffff811c93c0)
Location: include/linux/percpu-refcount.h:269
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages_release
```
```
In mm/page-writeback.c (ffffffff811dc348)
Location: include/linux/percpu-refcount.h:269
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (ffffffff811e0440)
Location: include/linux/percpu-refcount.h:269
Inline: True
```
```
In mm/backing-dev.c (ffffffff811f79b9)
Location: include/linux/percpu-refcount.h:269
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffffffff811fca16)
Location: include/linux/percpu-refcount.h:269
Inline: True
Inline callers:
  - mm/slab_common.c:kmemcg_deactivate_workfn
```
```
In mm/gup.c (ffffffff81205757)
Location: include/linux/percpu-refcount.h:269
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:follow_page_pte
```
```
In mm/huge_memory.c (ffffffff81250c16)
Location: include/linux/percpu-refcount.h:269
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff81262376)
Location: include/linux/percpu-refcount.h:269
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
In mm/hugetlb_cgroup.c (ffffffff81263bc9)
Location: include/linux/percpu-refcount.h:269
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/hmm.c (ffffffff8126e2d0)
Location: include/linux/percpu-refcount.h:269
Inline: True
Inline callers:
  - mm/hmm.c:hmm_devmem_release
```
```
In fs/inode.c (ffffffff8129347f)
Location: include/linux/percpu-refcount.h:269
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff812a4f16)
Location: include/linux/percpu-refcount.h:269
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
In fs/block_dev.c (ffffffff812b55bf)
Location: include/linux/percpu-refcount.h:269
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/aio.c (ffffffff812c9fa1)
Location: include/linux/percpu-refcount.h:269
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
In block/bio.c (ffffffff8144753d)
Location: include/linux/percpu-refcount.h:269
Inline: True
Inline callers:
  - block/bio.c:bio_disassociate_task
```
```
In block/blk-core.c (ffffffff81450540)
Location: include/linux/percpu-refcount.h:269
Inline: True
Inline callers:
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:__blk_put_request
  - block/blk-core.c:blk_get_request_flags
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-merge.c (ffffffff81458bc0)
Location: include/linux/percpu-refcount.h:269
Inline: True
Inline callers:
  - block/blk-merge.c:attempt_merge
```
```
In block/blk-cgroup.c (ffffffff81473a90)
Location: include/linux/percpu-refcount.h:269
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkg_release_rcu
  - block/blk-cgroup.c:blkg_create
```
```
In lib/percpu-refcount.c (ffffffff814965fa)
Location: include/linux/percpu-refcount.h:269
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffffffff8166fe0b)
Location: include/linux/percpu-refcount.h:269
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/md/md.c (ffffffff817b1a4d)
Location: include/linux/percpu-refcount.h:269
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
In kernel/kthread.c (ffffffff810b397b)
Location: include/linux/percpu-refcount.h:275
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff811438f2)
Location: include/linux/percpu-refcount.h:275
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
In kernel/cgroup/cgroup-v1.c (ffffffff81145f07)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
```
In kernel/cgroup/freezer.c (ffffffff81146924)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_write
  - kernel/cgroup/freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8114746c)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff8114c15b)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/bpf/arraymap.c (ffffffff811c3e2c)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffffffff811d2839)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
```
```
In kernel/events/core.c (ffffffff811d93c5)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In kernel/memremap.c (ffffffff811e967f)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - kernel/memremap.c:get_dev_pagemap
  - kernel/memremap.c:devm_memremap_pages
  - kernel/memremap.c:devm_memremap_pages
  - kernel/memremap.c:devm_memremap_pages_release
```
```
In mm/page-writeback.c (ffffffff811fda01)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (ffffffff812013c3)
Location: include/linux/percpu-refcount.h:275
Inline: True
```
```
In mm/backing-dev.c (ffffffff81218cf5)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffffffff8121dd66)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - mm/slab_common.c:kmemcg_deactivate_workfn
```
```
In mm/gup.c (ffffffff81226c1b)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:follow_page_pte
```
```
In mm/huge_memory.c (ffffffff8127512e)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff81286451)
Location: include/linux/percpu-refcount.h:275
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
In mm/hugetlb_cgroup.c (ffffffff81287e9a)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff812896c2)
Location: include/linux/percpu-refcount.h:275
Inline: True
```
```
In mm/hmm.c (ffffffff812927d0)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - mm/hmm.c:hmm_devmem_release
```
```
In fs/inode.c (ffffffff812b90af)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff812cbdd6)
Location: include/linux/percpu-refcount.h:275
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
In fs/block_dev.c (ffffffff812dcacf)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/aio.c (ffffffff812f31e1)
Location: include/linux/percpu-refcount.h:275
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
In block/bio.c (ffffffff8147a63d)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - block/bio.c:bio_disassociate_task
```
```
In block/blk-core.c (ffffffff81483820)
Location: include/linux/percpu-refcount.h:275
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
In block/blk-merge.c (ffffffff8148bcde)
Location: include/linux/percpu-refcount.h:275
Inline: True
```
```
In block/blk-cgroup.c (ffffffff814a7e60)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkg_release_rcu
  - block/blk-cgroup.c:blkg_create
```
```
In lib/percpu-refcount.c (ffffffff814cb85a)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffffffff816ab8db)
Location: include/linux/percpu-refcount.h:275
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (ffffffff816e224b)
Location: include/linux/percpu-refcount.h:275
Inline: True
```
```
In drivers/md/md.c (ffffffff817f55c5)
Location: include/linux/percpu-refcount.h:275
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
In kernel/kthread.c (ffffffff810bcc7b)
Location: include/linux/percpu-refcount.h:276
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8114f402)
Location: include/linux/percpu-refcount.h:276
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
In kernel/cgroup/cgroup-v1.c (ffffffff81151ac7)
Location: include/linux/percpu-refcount.h:276
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
```
In kernel/cgroup/freezer.c (ffffffff811525f4)
Location: include/linux/percpu-refcount.h:276
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_write
  - kernel/cgroup/freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8115313c)
Location: include/linux/percpu-refcount.h:276
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff81158d9d)
Location: include/linux/percpu-refcount.h:276
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
In kernel/bpf/arraymap.c (ffffffff811d5aec)
Location: include/linux/percpu-refcount.h:276
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffffffff811e25c9)
Location: include/linux/percpu-refcount.h:276
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
```
```
In kernel/events/core.c (ffffffff811e984e)
Location: include/linux/percpu-refcount.h:276
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In kernel/memremap.c (ffffffff811fa01c)
Location: include/linux/percpu-refcount.h:276
Inline: True
Inline callers:
  - kernel/memremap.c:get_dev_pagemap
  - kernel/memremap.c:devm_memremap_pages
```
```
In mm/oom_kill.c (ffffffff81205df6)
Location: include/linux/percpu-refcount.h:276
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff8121052a)
Location: include/linux/percpu-refcount.h:276
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (ffffffff81214672)
Location: include/linux/percpu-refcount.h:276
Inline: True
```
```
In mm/backing-dev.c (ffffffff8122bb45)
Location: include/linux/percpu-refcount.h:276
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffffffff81230d46)
Location: include/linux/percpu-refcount.h:276
Inline: True
Inline callers:
  - mm/slab_common.c:kmemcg_deactivate_workfn
```
```
In mm/gup.c (ffffffff81239d1b)
Location: include/linux/percpu-refcount.h:276
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/memcontrol.c (ffffffff8129b3a3)
Location: include/linux/percpu-refcount.h:276
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
In mm/hugetlb_cgroup.c (ffffffff8129cdea)
Location: include/linux/percpu-refcount.h:276
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff8129e51b)
Location: include/linux/percpu-refcount.h:276
Inline: True
```
```
In fs/inode.c (ffffffff812ce1f8)
Location: include/linux/percpu-refcount.h:276
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff812e0cff)
Location: include/linux/percpu-refcount.h:276
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
In fs/buffer.c (ffffffff812ebeec)
Location: include/linux/percpu-refcount.h:276
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/block_dev.c (ffffffff812f2054)
Location: include/linux/percpu-refcount.h:276
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (ffffffff812f9c6a)
Location: include/linux/percpu-refcount.h:276
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (ffffffff813081e1)
Location: include/linux/percpu-refcount.h:276
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
In block/bio.c (ffffffff8149860c)
Location: include/linux/percpu-refcount.h:276
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_reset
  - block/bio.c:bio_free
```
```
In block/blk-core.c (ffffffff8149f53e)
Location: include/linux/percpu-refcount.h:276
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-merge.c (ffffffff814a5977)
Location: include/linux/percpu-refcount.h:276
Inline: True
```
```
In block/blk-cgroup.c (ffffffff814c32aa)
Location: include/linux/percpu-refcount.h:276
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffffffff814c5f9d)
Location: include/linux/percpu-refcount.h:276
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/percpu-refcount.c (ffffffff814e05aa)
Location: include/linux/percpu-refcount.h:276
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffffffff816cc67b)
Location: include/linux/percpu-refcount.h:276
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (ffffffff81705663)
Location: include/linux/percpu-refcount.h:276
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81714701)
Location: include/linux/percpu-refcount.h:276
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff81821425)
Location: include/linux/percpu-refcount.h:276
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
In kernel/kthread.c (ffffffff810c2a67)
Location: include/linux/percpu-refcount.h:284
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8115b28f)
Location: include/linux/percpu-refcount.h:284
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
In kernel/cgroup/cgroup-v1.c (ffffffff8115d937)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8115ec54)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8115fa86)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff8116551c)
Location: include/linux/percpu-refcount.h:284
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
In kernel/bpf/arraymap.c (ffffffff811ea47c)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffffffff811f9739)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In kernel/events/core.c (ffffffff81202c57)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff8121c39c)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff8121fbca)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (ffffffff8122432d)
Location: include/linux/percpu-refcount.h:284
Inline: True
```
```
In mm/backing-dev.c (ffffffff8123b9b7)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffffffff81242283)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/gup.c (ffffffff8124afb5)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/slub.c (ffffffff812959d4)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812b6627)
Location: include/linux/percpu-refcount.h:284
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
In mm/hugetlb_cgroup.c (ffffffff812b7fb0)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff812ba263)
Location: include/linux/percpu-refcount.h:284
Inline: True
```
```
In mm/memremap.c (ffffffff812c248c)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:devm_memremap_pages
  - mm/memremap.c:devm_memremap_pages
```
```
In mm/hmm.c (ffffffff812c5004)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/inode.c (ffffffff812eb0b8)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff812ff40f)
Location: include/linux/percpu-refcount.h:284
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
In fs/buffer.c (ffffffff8130d61f)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/block_dev.c (ffffffff813139f4)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (ffffffff8131a31b)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (ffffffff81329c9a)
Location: include/linux/percpu-refcount.h:284
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
In fs/io_uring.c (ffffffff8132de38)
Location: include/linux/percpu-refcount.h:284
Inline: True
```
```
In block/bio.c (ffffffff814c64a6)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_reset
  - block/bio.c:bio_free
```
```
In block/blk-core.c (ffffffff814cd63b)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-merge.c (ffffffff814d3983)
Location: include/linux/percpu-refcount.h:284
Inline: True
```
```
In block/blk-mq-sched.c (ffffffff814dd604)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff814f1976)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffffffff814f47da)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/percpu-refcount.c (ffffffff8150c54d)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffffffff8170810b)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (ffffffff8173f7be)
Location: include/linux/percpu-refcount.h:284
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81750053)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff81863cf5)
Location: include/linux/percpu-refcount.h:284
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
In kernel/kthread.c (ffffffff810c8fd7)
Location: include/linux/percpu-refcount.h:284
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff81166f4f)
Location: include/linux/percpu-refcount.h:284
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
In kernel/cgroup/cgroup-v1.c (ffffffff81169547)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8116a8b4)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8116b6e6)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff8117140c)
Location: include/linux/percpu-refcount.h:284
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
In kernel/bpf/arraymap.c (ffffffff811f6bdc)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffffffff81206809)
Location: include/linux/percpu-refcount.h:284
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
In kernel/events/core.c (ffffffff8120fb1c)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff81229d6c)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff8122d67a)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (ffffffff812320c5)
Location: include/linux/percpu-refcount.h:284
Inline: True
```
```
In mm/backing-dev.c (ffffffff81249e43)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffffffff81250713)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/gup.c (ffffffff812594a5)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/slub.c (ffffffff812a57b4)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812c84f7)
Location: include/linux/percpu-refcount.h:284
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
In mm/hugetlb_cgroup.c (ffffffff812c9ea8)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff812cc11f)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/memremap.c (ffffffff812d43bc)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:memremap_pages
```
```
In mm/hmm.c (ffffffff812d69b4)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/inode.c (ffffffff812fcbf8)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff81314add)
Location: include/linux/percpu-refcount.h:284
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
In fs/buffer.c (ffffffff813205ef)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/block_dev.c (ffffffff81326904)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (ffffffff8132d13b)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (ffffffff8133cafa)
Location: include/linux/percpu-refcount.h:284
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
In fs/io_uring.c (ffffffff81343d51)
Location: include/linux/percpu-refcount.h:284
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
In block/bio.c (ffffffff814de3b9)
Location: include/linux/percpu-refcount.h:284
Inline: True
```
```
In block/blk-core.c (ffffffff814e692b)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-merge.c (ffffffff814eccb3)
Location: include/linux/percpu-refcount.h:284
Inline: True
```
```
In block/blk-mq-sched.c (ffffffff814f6a94)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff8150b01b)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffffffff8150dd74)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/percpu-refcount.c (ffffffff8152a39d)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffffffff8172c35b)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (ffffffff8176399e)
Location: include/linux/percpu-refcount.h:284
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81774243)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff81895a35)
Location: include/linux/percpu-refcount.h:284
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
In kernel/kthread.c (ffffffff810d09c6)
Location: include/linux/percpu-refcount.h:300
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8117866a)
Location: include/linux/percpu-refcount.h:300
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
In kernel/cgroup/cgroup-v1.c (ffffffff8117a01e)
Location: include/linux/percpu-refcount.h:300
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8117c373)
Location: include/linux/percpu-refcount.h:300
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8117d2f7)
Location: include/linux/percpu-refcount.h:300
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff8118311c)
Location: include/linux/percpu-refcount.h:300
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
In kernel/bpf/arraymap.c (ffffffff8121a4ac)
Location: include/linux/percpu-refcount.h:300
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffffffff8122e429)
Location: include/linux/percpu-refcount.h:300
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
In kernel/events/core.c (ffffffff8123ab90)
Location: include/linux/percpu-refcount.h:300
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff81256c00)
Location: include/linux/percpu-refcount.h:300
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff8125b38b)
Location: include/linux/percpu-refcount.h:300
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (ffffffff8125e4d8)
Location: include/linux/percpu-refcount.h:300
Inline: True
Inline callers:
  - mm/swap.c:__put_page
```
```
In mm/backing-dev.c (ffffffff8127800a)
Location: include/linux/percpu-refcount.h:300
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffffffff8127ed71)
Location: include/linux/percpu-refcount.h:300
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/gup.c (ffffffff8128a904)
Location: include/linux/percpu-refcount.h:300
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:gup_pte_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/slub.c (ffffffff812da3d5)
Location: include/linux/percpu-refcount.h:300
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812fdd0d)
Location: include/linux/percpu-refcount.h:300
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
In mm/hugetlb_cgroup.c (ffffffff812ffcfd)
Location: include/linux/percpu-refcount.h:300
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff81300fb0)
Location: include/linux/percpu-refcount.h:300
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
```
```
In mm/memremap.c (ffffffff8130a06c)
Location: include/linux/percpu-refcount.h:300
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:memremap_pages
```
```
In fs/inode.c (ffffffff81335468)
Location: include/linux/percpu-refcount.h:300
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff8134e4bf)
Location: include/linux/percpu-refcount.h:300
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
In fs/buffer.c (ffffffff81359a4c)
Location: include/linux/percpu-refcount.h:300
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/block_dev.c (ffffffff81360e34)
Location: include/linux/percpu-refcount.h:300
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (ffffffff81366eb0)
Location: include/linux/percpu-refcount.h:300
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_final_destroy_group
```
```
In fs/aio.c (ffffffff81375eca)
Location: include/linux/percpu-refcount.h:300
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
In fs/io_uring.c (ffffffff8137fc2a)
Location: include/linux/percpu-refcount.h:300
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
  - fs/io_uring.c:io_async_task_func
  - fs/io_uring.c:io_poll_task_func
  - fs/io_uring.c:__io_free_req
  - fs/io_uring.c:__io_req_aux_free
```
```
In block/bio.c (ffffffff8153e217)
Location: include/linux/percpu-refcount.h:300
Inline: True
Inline callers:
  - block/bio.c:bio_uninit
```
```
In block/blk-core.c (ffffffff81545eac)
Location: include/linux/percpu-refcount.h:300
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-merge.c (ffffffff8154aec8)
Location: include/linux/percpu-refcount.h:300
Inline: True
Inline callers:
  - block/blk-merge.c:blk_account_io_merge_request
```
```
In block/blk-mq.c (ffffffff8154f950)
Location: include/linux/percpu-refcount.h:300
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
```
```
In block/blk-mq-sched.c (ffffffff81557534)
Location: include/linux/percpu-refcount.h:300
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff8156bfee)
Location: include/linux/percpu-refcount.h:300
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffffffff8156e30a)
Location: include/linux/percpu-refcount.h:300
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/percpu-refcount.c (ffffffff8158db7c)
Location: include/linux/percpu-refcount.h:300
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffffffff817e7b1b)
Location: include/linux/percpu-refcount.h:300
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (ffffffff818237ce)
Location: include/linux/percpu-refcount.h:300
Inline: True
Inline callers:
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
```
```
In drivers/scsi/scsi_lib.c (ffffffff81836b69)
Location: include/linux/percpu-refcount.h:300
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff81962f65)
Location: include/linux/percpu-refcount.h:300
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
In kernel/kthread.c (ffffffff810cb5ab)
Location: include/linux/percpu-refcount.h:313
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8117541a)
Location: include/linux/percpu-refcount.h:313
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
In kernel/cgroup/cgroup-v1.c (ffffffff81176d85)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81179221)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8117a157)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff811800b5)
Location: include/linux/percpu-refcount.h:313
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
In kernel/bpf/syscall.c (ffffffff811fb635)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_free_deferred
```
```
In kernel/bpf/arraymap.c (ffffffff8121d11c)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/trampoline.c (ffffffff81222b60)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_tramp_exit
```
```
In kernel/bpf/cgroup.c (ffffffff81236967)
Location: include/linux/percpu-refcount.h:313
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
In kernel/events/core.c (ffffffff81243fb9)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff81261810)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff812652cd)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (ffffffff81268818)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/backing-dev.c (ffffffff81282787)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/percpu.c (ffffffff812860b1)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_memcg_free_hook
```
```
In mm/gup.c (ffffffff812945b4)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:gup_pte_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/mmap_lock.c (ffffffff81295f83)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - mm/mmap_lock.c:get_mm_memcg_path
```
```
In mm/hugetlb.c (ffffffff812d3a2e)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:coalesce_file_region
  - mm/hugetlb.c:coalesce_file_region
```
```
In mm/slub.c (ffffffff812e6ab6)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memcontrol.c (ffffffff8130a167)
Location: include/linux/percpu-refcount.h:313
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
In mm/hugetlb_cgroup.c (ffffffff8130c09d)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff8130ddbe)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
```
```
In mm/memremap.c (ffffffff81315d24)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:pagemap_range
```
```
In fs/inode.c (ffffffff81340dd8)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff8135b36d)
Location: include/linux/percpu-refcount.h:313
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
In fs/buffer.c (ffffffff81367b73)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/block_dev.c (ffffffff8136d11f)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (ffffffff81374200)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_final_destroy_group
```
```
In fs/aio.c (ffffffff81383e49)
Location: include/linux/percpu-refcount.h:313
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
In fs/io_uring.c (ffffffff8138e734)
Location: include/linux/percpu-refcount.h:313
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
In block/bio.c (ffffffff8155a537)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - block/bio.c:bio_uninit
```
```
In block/blk-core.c (ffffffff815618c8)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio_noacct_mq
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff8156bd32)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
```
```
In block/blk-mq-sched.c (ffffffff81573b4e)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff81585a54)
Location: include/linux/percpu-refcount.h:313
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
In block/blk-throttle.c (ffffffff81589857)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/percpu-refcount.c (ffffffff815aa85a)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffffffff817fc9fa)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (ffffffff8183256a)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
```
```
In drivers/scsi/scsi_lib.c (ffffffff81847606)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff81969805)
Location: include/linux/percpu-refcount.h:313
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
In kernel/kthread.c (ffffffff810cceec)
Location: include/linux/percpu-refcount.h:313
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff81175f8a)
Location: include/linux/percpu-refcount.h:313
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
In kernel/cgroup/cgroup-v1.c (ffffffff81177907)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81179d91)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8117acd7)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff81180b85)
Location: include/linux/percpu-refcount.h:313
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
In kernel/bpf/syscall.c (ffffffff811fc355)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_free_deferred
```
```
In kernel/bpf/arraymap.c (ffffffff81220c2c)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/trampoline.c (ffffffff812273a0)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_tramp_exit
```
```
In kernel/bpf/cgroup.c (ffffffff8123abc7)
Location: include/linux/percpu-refcount.h:313
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
In kernel/events/core.c (ffffffff81248f8b)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff81266023)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff812694dc)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (ffffffff8126e588)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/backing-dev.c (ffffffff81287855)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/percpu.c (ffffffff8128ac97)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_memcg_free_hook
```
```
In mm/gup.c (ffffffff8129a004)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:gup_pte_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/mmap_lock.c (ffffffff8129b8a0)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - mm/mmap_lock.c:get_mm_memcg_path
```
```
In mm/memory_hotplug.c (ffffffff812c6447)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - mm/memory_hotplug.c:pfn_to_online_page
```
```
In mm/hugetlb.c (ffffffff812da8ad)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:coalesce_file_region
  - mm/hugetlb.c:coalesce_file_region
```
```
In mm/slub.c (ffffffff812ee28c)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memcontrol.c (ffffffff813109e5)
Location: include/linux/percpu-refcount.h:313
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
In mm/hugetlb_cgroup.c (ffffffff8131269d)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff813140d9)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
```
```
In mm/memremap.c (ffffffff8131bf14)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:pagemap_range
```
```
In fs/inode.c (ffffffff813471c8)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff81361f6d)
Location: include/linux/percpu-refcount.h:313
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
In fs/block_dev.c (ffffffff8137398f)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (ffffffff8137ab8b)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (ffffffff8138aa99)
Location: include/linux/percpu-refcount.h:313
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
In fs/io_uring.c (ffffffff8139ea48)
Location: include/linux/percpu-refcount.h:313
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
In block/bio.c (ffffffff81562d17)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - block/bio.c:bio_uninit
```
```
In block/blk-core.c (ffffffff81569d02)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff81573811)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
```
```
In block/blk-mq-sched.c (ffffffff8157bbde)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff8158c424)
Location: include/linux/percpu-refcount.h:313
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
In block/blk-throttle.c (ffffffff81590257)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/percpu-refcount.c (ffffffff815b547a)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffffffff817e15ca)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (ffffffff8181535a)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
```
```
In drivers/scsi/scsi_lib.c (ffffffff8182a7c6)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff8194db85)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_end
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
In kernel/kthread.c (ffffffff810df929)
Location: include/linux/percpu-refcount.h:313
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8119d53d)
Location: include/linux/percpu-refcount.h:313
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
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8119f217)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff811a16b1)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff811a2724)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff811a8975)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/syscall.c (ffffffff8122dc85)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_free_deferred
```
```
In kernel/bpf/arraymap.c (ffffffff812585ec)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/trampoline.c (ffffffff8125f4a0)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_tramp_exit
```
```
In kernel/bpf/cgroup.c (ffffffff812757a7)
Location: include/linux/percpu-refcount.h:313
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
In kernel/events/core.c (ffffffff81283d89)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff812a2843)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff812a5f56)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (ffffffff812ab591)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/backing-dev.c (ffffffff812c6082)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/percpu.c (ffffffff812caa4a)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_memcg_free_hook
  - mm/percpu.c:pcpu_memcg_post_alloc_hook
```
```
In mm/gup.c (ffffffff812da9b8)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:gup_pte_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/mmap_lock.c (ffffffff812dc390)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - mm/mmap_lock.c:get_mm_memcg_path
```
```
In mm/memory.c (ffffffff812e22d2)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/memory_hotplug.c (ffffffff8130af37)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - mm/memory_hotplug.c:pfn_to_online_page
```
```
In mm/swap_state.c (ffffffff81310e5a)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:find_get_incore_page
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff81317ce3)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
  - mm/swapfile.c:get_swap_device
```
```
In mm/hugetlb.c (ffffffff81321852)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:coalesce_file_region
  - mm/hugetlb.c:coalesce_file_region
```
```
In mm/slub.c (ffffffff81338c42)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memcontrol.c (ffffffff8135bcd9)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_swapin_charge_page
  - mm/memcontrol.c:__mem_cgroup_charge
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
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/hugetlb_cgroup.c (ffffffff8135e0fa)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff81360258)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
```
```
In mm/memremap.c (ffffffff813691f4)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:pagemap_range
```
```
In fs/inode.c (ffffffff81394c28)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff813b07e1)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:cleanup_offline_cgwb
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
In fs/notify/group.c (ffffffff813c786b)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (ffffffff813d7da9)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
  - fs/aio.c:__x64_compat_sys_io_submit
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
  - fs/aio.c:__x64_compat_sys_io_setup
  - fs/aio.c:__ia32_compat_sys_io_setup
  - fs/aio.c:__ia32_sys_io_setup
  - fs/aio.c:__x64_sys_io_setup
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (ffffffff813eeba0)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_uring_show_fdinfo
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_submit_flush_completions
  - fs/io_uring.c:ctx_flush_and_put
  - fs/io_uring.c:__io_free_req
  - fs/io_uring.c:io_dismantle_req
  - fs/io_uring.c:io_req_complete_post
  - fs/io_uring.c:io_fallback_req_func
```
```
In block/bio.c (ffffffff815c6987)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - block/bio.c:bio_uninit
```
```
In block/blk-core.c (ffffffff815cd53b)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:blk_try_enter_queue
```
```
In block/blk-mq.c (ffffffff815d7e14)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
```
```
In block/blk-mq-sched.c (ffffffff815e0fb9)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff815f1a54)
Location: include/linux/percpu-refcount.h:313
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
In block/blk-throttle.c (ffffffff815f7062)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/percpu-refcount.c (ffffffff8161b89b)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffffffff8186fb94)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_free_idle_workers
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/dax/super.c (ffffffff8189fb91)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - drivers/dax/super.c:generic_fsdax_supported
  - drivers/dax/super.c:generic_fsdax_supported
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b6213)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff819f2f85)
Location: include/linux/percpu-refcount.h:313
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_end
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void percpu_ref_put_many(struct percpu_ref *ref, long unsigned int nr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107e925)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
```
```
In kernel/kthread.c (ffffffff810f9c9e)
Location: include/linux/percpu-refcount.h:326
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff811cd87d)
Location: include/linux/percpu-refcount.h:326
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
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811cf86d)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff811d1ffb)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff811d318b)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff811d9b0c)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/syscall.c (ffffffff8126ff5b)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_free_deferred
```
```
In kernel/bpf/arraymap.c (ffffffff812a13cc)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/trampoline.c (ffffffff812a9bf8)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_tramp_exit
```
```
In kernel/bpf/cgroup.c (ffffffff812c51e9)
Location: include/linux/percpu-refcount.h:326
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
In kernel/events/core.c (ffffffff812d6f8e)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff812fa4cd)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff812fec27)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff813234f2)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/percpu.c (ffffffff81328351)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_memcg_post_alloc_hook
```
```
In mm/gup.c (ffffffff8133a525)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:gup_pte_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/mmap_lock.c (ffffffff8133c309)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/mmap_lock.c:get_mm_memcg_path
```
```
In mm/memory.c (ffffffff81343f4b)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
```
```
In mm/memory_hotplug.c (ffffffff81374611)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/memory_hotplug.c:pfn_to_online_page
```
```
In mm/swap_state.c (ffffffff8137bce9)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:find_get_incore_page
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff8138337d)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
Direct callers:
  - mm/swapfile.c:get_swap_device
```
```
In mm/zswap.c (ffffffff81386262)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_free_entry
```
```
In mm/hugetlb.c (ffffffff8138e95f)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:clear_vma_resv_huge_pages
  - mm/hugetlb.c:coalesce_file_region
  - mm/hugetlb.c:coalesce_file_region
```
```
In mm/slub.c (ffffffff813aaa60)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memcontrol.c (ffffffff813d5c9b)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/memcontrol.c:obj_cgroup_may_zswap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_swapin_charge_page
  - mm/memcontrol.c:__mem_cgroup_charge
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:obj_cgroup_charge
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:__memcg_kmem_uncharge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:obj_cgroup_uncharge_pages
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:drain_local_stock
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/hugetlb_cgroup.c (ffffffff813d8526)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff813db107)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
```
```
In mm/memremap.c (ffffffff813e7005)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
```
```
In fs/inode.c (ffffffff81416fcb)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff814355d0)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:cleanup_offline_cgwb
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
In fs/notify/group.c (ffffffff8144ec56)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (ffffffff814624c9)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
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
  - fs/aio.c:__ia32_compat_sys_io_setup
  - fs/aio.c:__ia32_sys_io_setup
  - fs/aio.c:__x64_sys_io_setup
  - fs/aio.c:free_ioctx_users
```
```
In block/bio.c (ffffffff81671848)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - block/bio.c:bio_uninit
```
```
In block/blk-core.c (ffffffff81679f3c)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - block/blk-core.c:bio_poll
  - block/blk-core.c:bio_poll
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff81684564)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_end_request_batch
```
```
In block/blk-mq-sched.c (ffffffff8168fb83)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff816a4b2b)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-cgroup-fc-appid.c (ffffffff816a54aa)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid
  - block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid
```
```
In block/blk-throttle.c (ffffffff816a877e)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In io_uring/io_uring.c (ffffffff816d6aa7)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/io_uring.c:io_free_batch_list
  - io_uring/io_uring.c:ctx_flush_and_put
  - io_uring/io_uring.c:io_free_req
  - io_uring/io_uring.c:__io_req_complete_put
Direct callers:
  - io_uring/io_uring.c:io_uring_show_fdinfo
  - io_uring/io_uring.c:io_req_caches_free
  - io_uring/io_uring.c:io_fallback_req_func
  - io_uring/io_uring.c:io_rsrc_refs_drop
```
```
In lib/percpu-refcount.c (ffffffff816e9129)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffffffff819b7714)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_free_idle_workers
```
```
In drivers/scsi/scsi_lib.c (ffffffff81a0176b)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff81b5b616)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_start
  - drivers/md/md.c:mddev_init_writes_pending
```
**Symbols:**

```
ffffffff8137d060-ffffffff8137d0a8: percpu_ref_put_many.constprop.0 (STB_LOCAL)
ffffffff816c7190-ffffffff816c71e3: percpu_ref_put_many (STB_LOCAL)
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8108ff65)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
```
```
In kernel/kthread.c (ffffffff8111c9de)
Location: include/linux/percpu-refcount.h:326
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff81210f2d)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff812130ad)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81215d2b)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff81217116)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff8121efdc)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/syscall.c (ffffffff812c9415)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_free_deferred
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
```
```
In kernel/bpf/helpers.c (ffffffff812f4416)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_cgroup_release
```
```
In kernel/bpf/arraymap.c (ffffffff812fe1bc)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/trampoline.c (ffffffff81308ba8)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_tramp_exit
```
```
In kernel/bpf/memalloc.c (ffffffff8131c4b0)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:bpf_mem_alloc_destroy
  - kernel/bpf/memalloc.c:bpf_mem_alloc_destroy
  - kernel/bpf/memalloc.c:alloc_bulk
```
```
In kernel/bpf/cgroup_iter.c (ffffffff81325582)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - kernel/bpf/cgroup_iter.c:bpf_iter_detach_cgroup
  - kernel/bpf/cgroup_iter.c:cgroup_iter_seq_fini
```
```
In kernel/bpf/bpf_cgrp_storage.c (ffffffff813259d1)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete_elem
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_update_elem
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_lookup_elem
```
```
In kernel/bpf/cgroup.c (ffffffff8132a709)
Location: include/linux/percpu-refcount.h:326
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
In kernel/events/core.c (ffffffff8133fd2b)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff81364c4d)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff813693a3)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
```
```
In mm/vmscan.c (ffffffff81382558)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/vmscan.c:run_cmd
  - mm/vmscan.c:lru_gen_del_mm
```
```
In mm/backing-dev.c (ffffffff81397d42)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/percpu.c (ffffffff8139d5c1)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_memcg_post_alloc_hook
```
```
In mm/gup.c (ffffffff813b1fa2)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:gup_pte_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/mmap_lock.c (ffffffff813b3e49)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/mmap_lock.c:get_mm_memcg_path
```
```
In mm/memory.c (ffffffff813bbd8c)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
```
```
In mm/memory_hotplug.c (ffffffff813f176e)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/memory_hotplug.c:pfn_to_online_page
```
```
In mm/swap_state.c (ffffffff813f9629)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:filemap_get_incore_folio
  - mm/swap_state.c:swap_cache_get_folio
```
```
In mm/swapfile.c (ffffffff81400d7d)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
  - mm/swapfile.c:get_swap_device
```
```
In mm/zswap.c (ffffffff81404092)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_free_entry
```
```
In mm/hugetlb.c (ffffffff8140d2b2)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:clear_vma_resv_huge_pages
  - mm/hugetlb.c:coalesce_file_region
  - mm/hugetlb.c:coalesce_file_region
```
```
In mm/slub.c (ffffffff8142cc72)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__kmem_cache_free
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:__kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memcontrol.c (ffffffff8145b682)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/memcontrol.c:obj_cgroup_may_zswap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_swapin_charge_folio
  - mm/memcontrol.c:__mem_cgroup_charge
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:obj_cgroup_charge
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:__memcg_kmem_uncharge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:obj_cgroup_uncharge_pages
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:drain_local_stock
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/hugetlb_cgroup.c (ffffffff8145e206)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff81461474)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
```
```
In mm/memremap.c (ffffffff8146fb31)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/memremap.c:free_zone_device_page
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
```
```
In fs/inode.c (ffffffff814a25cb)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff814c363d)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:cleanup_offline_cgwb
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
In fs/notify/group.c (ffffffff814dd3f6)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (ffffffff814f2b19)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
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
  - fs/aio.c:__ia32_compat_sys_io_setup
  - fs/aio.c:__ia32_sys_io_setup
  - fs/aio.c:__x64_sys_io_setup
  - fs/aio.c:free_ioctx_users
```
```
In block/bio.c (ffffffff8172d0b8)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - block/bio.c:bio_uninit
```
```
In block/blk-core.c (ffffffff817363e1)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - block/blk-core.c:bio_poll
  - block/blk-core.c:bio_poll
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff8174238f)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_end_request_batch
```
```
In block/blk-mq-sched.c (ffffffff8174e6f3)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff817638bb)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_rstat_flush
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-cgroup-fc-appid.c (ffffffff81764372)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid
  - block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid
```
```
In block/blk-throttle.c (ffffffff8176718e)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In io_uring/io_uring.c (ffffffff8178b868)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_req_caches_free
  - io_uring/io_uring.c:io_free_batch_list
  - io_uring/io_uring.c:__io_req_task_work_add
  - io_uring/io_uring.c:__io_req_task_work_add
  - io_uring/io_uring.c:ctx_flush_and_put
  - io_uring/io_uring.c:io_free_req
  - io_uring/io_uring.c:__io_req_complete_post
  - io_uring/io_uring.c:io_fallback_req_func
```
```
In io_uring/fdinfo.c (ffffffff8179b946)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - io_uring/fdinfo.c:io_uring_show_fdinfo
```
```
In io_uring/rsrc.c (ffffffff817a07cd)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_rsrc_refs_drop
```
```
In lib/percpu-refcount.c (ffffffff817d9229)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/pci/p2pdma.c (ffffffff8191ce67)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pmem_free_sgl
  - drivers/pci/p2pdma.c:p2pdma_page_free
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/block/loop.c (ffffffff81b2ca14)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_free_idle_workers
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b7fdbb)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff81cf4fe6)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_start
  - drivers/md/md.c:mddev_init_writes_pending
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81092e7b)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
```
```
In kernel/kthread.c (ffffffff81129b6e)
Location: include/linux/percpu-refcount.h:326
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8122691d)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:cgroup_css_set_put_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff812289bd)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8122b65f)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8122ca36)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff8123510c)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/syscall.c (ffffffff812f0b6f)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_free_deferred
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_kvcalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
```
```
In kernel/bpf/helpers.c (ffffffff8132147c)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_cgroup_release
```
```
In kernel/bpf/arraymap.c (ffffffff8132cdcc)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/trampoline.c (ffffffff81337ac8)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_tramp_exit
```
```
In kernel/bpf/memalloc.c (ffffffff8134c4b9)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:bpf_mem_cache_alloc_flags
  - kernel/bpf/memalloc.c:bpf_mem_alloc_destroy
  - kernel/bpf/memalloc.c:bpf_mem_alloc_destroy
  - kernel/bpf/memalloc.c:alloc_bulk
```
```
In kernel/bpf/cgroup_iter.c (ffffffff813557c2)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - kernel/bpf/cgroup_iter.c:bpf_iter_detach_cgroup
  - kernel/bpf/cgroup_iter.c:cgroup_iter_seq_fini
```
```
In kernel/bpf/bpf_cgrp_storage.c (ffffffff81355c1e)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete_elem
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_update_elem
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_lookup_elem
```
```
In kernel/bpf/cgroup.c (ffffffff8135a849)
Location: include/linux/percpu-refcount.h:326
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
In kernel/events/core.c (ffffffff81370cf7)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff8139710d)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff8139b543)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
```
```
In mm/vmscan.c (ffffffff813b4101)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/vmscan.c:run_cmd
  - mm/vmscan.c:shrink_many
  - mm/vmscan.c:shrink_many
  - mm/vmscan.c:lru_gen_del_mm
```
```
In mm/shmem.c (ffffffff813beb2d)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_swapin_folio
```
```
In mm/backing-dev.c (ffffffff813cacc2)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/percpu.c (ffffffff813d070f)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_memcg_post_alloc_hook
```
```
In mm/gup.c (ffffffff813e6d42)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:gup_pte_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/mmap_lock.c (ffffffff813e8799)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/mmap_lock.c:get_mm_memcg_path
```
```
In mm/memory.c (ffffffff813f07aa)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
```
```
In mm/memory_hotplug.c (ffffffff814252ac)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/memory_hotplug.c:pfn_to_online_page
```
```
In mm/swap_state.c (ffffffff8142c3a4)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:filemap_get_incore_folio
```
```
In mm/swapfile.c (ffffffff81433c5d)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:get_swap_device
```
```
In mm/zswap.c (ffffffff81436e64)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_free_entry
```
```
In mm/hugetlb.c (ffffffff81440855)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:clear_vma_resv_huge_pages
  - mm/hugetlb.c:coalesce_file_region
  - mm/hugetlb.c:coalesce_file_region
```
```
In mm/slub.c (ffffffff81462282)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__kmem_cache_free
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:__kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memcontrol.c (ffffffff814912f2)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/memcontrol.c:obj_cgroup_may_zswap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_swapin_charge_folio
  - mm/memcontrol.c:__mem_cgroup_charge
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:obj_cgroup_charge
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:__memcg_kmem_uncharge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:obj_cgroup_uncharge_pages
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:drain_local_stock
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/hugetlb_cgroup.c (ffffffff81493ef6)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff814980c4)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
```
```
In mm/memremap.c (ffffffff814a4311)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/memremap.c:free_zone_device_page
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
```
```
In fs/inode.c (ffffffff814d772b)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff814f8a20)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:cleanup_offline_cgwb
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
In fs/notify/group.c (ffffffff81513c56)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (ffffffff815298c9)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
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
  - fs/aio.c:__ia32_compat_sys_io_setup
  - fs/aio.c:__ia32_sys_io_setup
  - fs/aio.c:__x64_sys_io_setup
  - fs/aio.c:free_ioctx_users
```
```
In block/bio.c (ffffffff81769458)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - block/bio.c:bio_uninit
```
```
In block/blk-core.c (ffffffff81772a4d)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - block/blk-core.c:bio_poll
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff8177f3df)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_dispatch_plug_list
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_end_request_batch
```
```
In block/blk-cgroup.c (ffffffff817a2956)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_activate_policy
  - block/blk-cgroup.c:blkcg_activate_policy
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:blkg_free_workfn
```
```
In block/blk-cgroup-fc-appid.c (ffffffff817a348c)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid
  - block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid
```
```
In block/blk-throttle.c (ffffffff817a6253)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In io_uring/io_uring.c (ffffffff817c90de)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_activate_pollwq
  - io_uring/io_uring.c:io_activate_pollwq_cb
  - io_uring/io_uring.c:io_req_caches_free
  - io_uring/io_uring.c:io_fallback_tw
  - io_uring/io_uring.c:io_fallback_tw
  - io_uring/io_uring.c:ctx_flush_and_put
```
```
In io_uring/fdinfo.c (ffffffff817dca77)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - io_uring/fdinfo.c:io_uring_show_fdinfo
```
```
In lib/percpu-refcount.c (ffffffff81818439)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/pci/p2pdma.c (ffffffff81960427)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pmem_free_sgl
  - drivers/pci/p2pdma.c:p2pdma_page_free
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/block/loop.c (ffffffff81b7ccd1)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_free_idle_workers
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd3e0e)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff81d5f726)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - drivers/md/md.c:md_end_io_acct
  - drivers/md/md.c:md_write_start
  - drivers/md/md.c:mddev_init_writes_pending
  - drivers/md/md.c:md_handle_request
  - drivers/md/md.c:md_handle_request
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109a2bb)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
```
```
In kernel/kthread.c (ffffffff811341ae)
Location: include/linux/percpu-refcount.h:326
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8123e5ad)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:cgroup_css_set_put_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:cpu_local_stat_show
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff812407d0)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8124364f)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff81244af6)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff8124ed50)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/syscall.c (ffffffff8130f965)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_free_deferred
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_kvcalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
```
```
In kernel/bpf/helpers.c (ffffffff81343bac)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_cgroup_release_dtor
  - kernel/bpf/helpers.c:bpf_cgroup_release
```
```
In kernel/bpf/arraymap.c (ffffffff8135111e)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/trampoline.c (ffffffff8135d908)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_tramp_exit
```
```
In kernel/bpf/memalloc.c (ffffffff81373a47)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:bpf_mem_cache_alloc_flags
  - kernel/bpf/memalloc.c:bpf_mem_alloc_destroy
  - kernel/bpf/memalloc.c:bpf_mem_alloc_destroy
  - kernel/bpf/memalloc.c:alloc_bulk
```
```
In kernel/bpf/cgroup_iter.c (ffffffff8137e142)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - kernel/bpf/cgroup_iter.c:bpf_iter_detach_cgroup
  - kernel/bpf/cgroup_iter.c:cgroup_iter_seq_fini
```
```
In kernel/bpf/bpf_cgrp_storage.c (ffffffff8137e74e)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete_elem
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_update_elem
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_lookup_elem
```
```
In kernel/bpf/cgroup.c (ffffffff81383439)
Location: include/linux/percpu-refcount.h:326
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
In kernel/events/core.c (ffffffff81399ff7)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff813c0f13)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff813c54b3)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
```
```
In mm/vmscan.c (ffffffff813dd781)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/vmscan.c:run_cmd
  - mm/vmscan.c:shrink_many
  - mm/vmscan.c:shrink_many
  - mm/vmscan.c:lru_gen_del_mm
```
```
In mm/shmem.c (ffffffff813e9b32)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_swapin_folio
```
```
In mm/backing-dev.c (ffffffff813f5ca2)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/percpu.c (ffffffff813fabce)
Location: include/linux/percpu-refcount.h:326
Inline: True
```
```
In mm/workingset.c (ffffffff8140c3b0)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/workingset.c:workingset_test_recent
```
```
In mm/gup.c (ffffffff814119cf)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:gup_pte_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/mmap_lock.c (ffffffff81413429)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/mmap_lock.c:get_mm_memcg_path
```
```
In mm/memory.c (ffffffff81420494)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
```
```
In mm/memory_hotplug.c (ffffffff814524ed)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/memory_hotplug.c:pfn_to_online_page
```
```
In mm/slub.c (ffffffff81455aef)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/slub.c:__memcg_slab_free_hook
```
```
In mm/swap_state.c (ffffffff81465add)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:filemap_get_incore_folio
```
```
In mm/swapfile.c (ffffffff8146d09f)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:get_swap_device
```
```
In mm/zswap.c (ffffffff8147086f)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/zswap.c:zswap_store
  - mm/zswap.c:zswap_store
  - mm/zswap.c:zswap_store
  - mm/zswap.c:zswap_store
  - mm/zswap.c:zswap_store
  - mm/zswap.c:shrink_worker
  - mm/zswap.c:zswap_free_entry
```
```
In mm/hugetlb.c (ffffffff8147a789)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:clear_vma_resv_huge_pages
  - mm/hugetlb.c:coalesce_file_region
  - mm/hugetlb.c:coalesce_file_region
```
```
In mm/memcontrol.c (ffffffff814c0c62)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/memcontrol.c:obj_cgroup_may_zswap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_swapin_charge_folio
  - mm/memcontrol.c:__mem_cgroup_charge
  - mm/memcontrol.c:mem_cgroup_exit
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:obj_cgroup_charge
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:__memcg_kmem_uncharge_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:obj_cgroup_uncharge_pages
  - mm/memcontrol.c:current_objcg_update
  - mm/memcontrol.c:current_objcg_update
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:drain_local_stock
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
Direct callers:
  - mm/memcontrol.c:mem_cgroup_handle_over_high
```
```
In mm/hugetlb_cgroup.c (ffffffff814c37d6)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff814c773b)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
```
```
In mm/memremap.c (ffffffff814d514f)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - mm/memremap.c:free_zone_device_page
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
```
```
In fs/inode.c (ffffffff81509a3b)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff8152d27f)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:cleanup_offline_cgwb
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
In fs/notify/group.c (ffffffff81548126)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (ffffffff8155e799)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
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
  - fs/aio.c:__ia32_compat_sys_io_setup
  - fs/aio.c:__ia32_sys_io_setup
  - fs/aio.c:__x64_sys_io_setup
  - fs/aio.c:free_ioctx_users
```
```
In block/bio.c (ffffffff817ab4d8)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - block/bio.c:bio_uninit
```
```
In block/blk-core.c (ffffffff817b4dea)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - block/blk-core.c:bio_poll
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff817c1ecf)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_dispatch_plug_list
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_end_request_batch
```
```
In block/blk-cgroup.c (ffffffff817e6499)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_activate_policy
  - block/blk-cgroup.c:blkcg_activate_policy
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:blkg_free_workfn
```
```
In block/blk-cgroup-fc-appid.c (ffffffff817e6fdc)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid
  - block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid
```
```
In block/blk-throttle.c (ffffffff817e9f93)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In io_uring/io_uring.c (ffffffff81816ede)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_activate_pollwq
  - io_uring/io_uring.c:io_activate_pollwq_cb
  - io_uring/io_uring.c:io_req_caches_free
  - io_uring/io_uring.c:io_fallback_tw
  - io_uring/io_uring.c:io_fallback_tw
  - io_uring/io_uring.c:ctx_flush_and_put
  - io_uring/io_uring.c:io_fallback_req_func
```
```
In lib/percpu-refcount.c (ffffffff8185d739)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/pci/p2pdma.c (ffffffff819a9b17)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pmem_free_sgl
  - drivers/pci/p2pdma.c:p2pdma_page_free
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/block/loop.c (ffffffff81bd0c1e)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_free_idle_workers
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c28a8b)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff81e16ac5)
Location: include/linux/percpu-refcount.h:326
Inline: True
Inline callers:
  - drivers/md/md.c:md_end_clone_io
  - drivers/md/md.c:md_write_start
  - drivers/md/md.c:mddev_init
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_handle_request
  - drivers/md/md.c:md_handle_request
```
**Symbols:**

```
ffffffff814b41e0-ffffffff814b4228: percpu_ref_put_many.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void percpu_ref_put_many(struct percpu_ref *ref, long unsigned int nr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kthread.c (ffff800010128894)
Location: include/linux/percpu-refcount.h:284
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffff8000101d0800)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_killed_work_fn
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
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
In kernel/cgroup/cgroup-v1.c (ffff8000101dc8a0)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffff8000101de774)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffff8000101df9bc)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffff8000101e4a9c)
Location: include/linux/percpu-refcount.h:284
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
In kernel/bpf/arraymap.c (ffff80001027b8c4)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffff80001028ff00)
Location: include/linux/percpu-refcount.h:284
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
In kernel/events/core.c (ffff80001029bca4)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
Direct callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/oom_kill.c (ffff8000102b7c54)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffff8000102bc4fc)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (0)
Location: include/linux/percpu-refcount.h:284
Inline: False
```
```
In mm/backing-dev.c (ffff8000102df534)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffff8000102e776c)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/gup.c (ffff8000102f26dc)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/slub.c (ffff8000103465f8)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
Direct callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffff800010364c80)
Location: include/linux/percpu-refcount.h:284
Inline: False
Direct callers:
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
In mm/hugetlb_cgroup.c (ffff80001036d6c4)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (0)
Location: include/linux/percpu-refcount.h:284
Inline: False
```
```
In mm/hmm.c (ffff80001037b87c)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/inode.c (ffff8000103acdb8)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffff8000103ca9d0)
Location: include/linux/percpu-refcount.h:284
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
In fs/buffer.c (ffff8000103d9278)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/block_dev.c (ffff8000103e13e0)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (ffff8000103e8f2c)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (ffff8000103fc500)
Location: include/linux/percpu-refcount.h:284
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
In fs/io_uring.c (ffff800010405be0)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - fs/io_uring.c:__arm64_sys_io_uring_enter
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:__io_free_req
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (ffff8000105db5a0)
Location: include/linux/percpu-refcount.h:284
Inline: True
```
```
In block/blk-core.c (ffff8000105e40f8)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-merge.c (ffff8000105eb698)
Location: include/linux/percpu-refcount.h:284
Inline: True
```
```
In block/blk-mq-sched.c (ffff8000105f7150)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffff80001060e8a8)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffff8000106119d4)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/percpu-refcount.c (ffff8000106354d8)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffff8000109222d0)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (0)
Location: include/linux/percpu-refcount.h:284
Inline: False
```
```
In drivers/scsi/scsi_lib.c (ffff8000109782b0)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffff800010aeaa78)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_end
```
**Symbols:**

```
ffff8000101d1730-ffff8000101d17a8: percpu_ref_put_many.constprop.0 (STB_LOCAL)
ffff8000102963f0-ffff80001029646c: percpu_ref_put_many.constprop.0 (STB_LOCAL)
ffff800010344ec0-ffff800010344f44: percpu_ref_put_many (STB_LOCAL)
ffff800010364c80-ffff800010364d04: percpu_ref_put_many (STB_LOCAL)
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
In kernel/kthread.c (c037ad0c)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_associate_blkcg
```
```
In kernel/cgroup/cgroup.c (c041bc88)
Location: include/linux/percpu-refcount.h:284
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
In kernel/cgroup/cgroup-v1.c (c041ea60)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (c042022c)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (c0421324)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (c0425860)
Location: include/linux/percpu-refcount.h:284
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
In kernel/bpf/arraymap.c (c04ad31c)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (c04bf5a8)
Location: include/linux/percpu-refcount.h:284
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
In kernel/events/core.c (c04c79d0)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (c04e47f8)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (c04e8b3c)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (0)
Location: include/linux/percpu-refcount.h:284
Inline: False
```
```
In mm/backing-dev.c (c05043d0)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (c050b8a0)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/gup.c (0)
Location: include/linux/percpu-refcount.h:284
Inline: True
```
```
In mm/slub.c (c054b21c)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (c055cacc)
Location: include/linux/percpu-refcount.h:284
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
  - mm/memcontrol.c:drain_stock
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/hmm.c (c056659c)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/inode.c (c058dc94)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (c05a6f48)
Location: include/linux/percpu-refcount.h:284
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
In fs/buffer.c (c05b1fdc)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/block_dev.c (c05b9918)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (c05c0648)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (c05cfaf8)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__se_sys_io_cancel
  - fs/aio.c:__se_sys_io_submit
  - fs/aio.c:__se_sys_io_submit
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
In fs/io_uring.c (c05d73a4)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_enter
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:__io_free_req
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (c078831c)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - block/bio.c:__bio_associate_blkg
```
```
In block/blk-core.c (c079141c)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-merge.c (c0797c54)
Location: include/linux/percpu-refcount.h:284
Inline: True
```
```
In block/blk-mq-sched.c (c07a28a4)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (c07b91c4)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (c07bc144)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/percpu-refcount.c (c07db610)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (c0a07bf8)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (0)
Location: include/linux/percpu-refcount.h:284
Inline: False
```
```
In drivers/scsi/scsi_lib.c (c0a4c0a8)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (c0bccc70)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_end
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
In kernel/kthread.c (c000000000173520)
Location: include/linux/percpu-refcount.h:284
Inline: True
```
```
In kernel/cgroup/cgroup.c (c0000000002462f0)
Location: include/linux/percpu-refcount.h:284
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
In kernel/cgroup/cgroup-v1.c (c00000000024a750)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (c00000000024c82c)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (c00000000024e0b0)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (c0000000002552b0)
Location: include/linux/percpu-refcount.h:284
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
In kernel/bpf/arraymap.c (c000000000324ab0)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (c00000000033cc00)
Location: include/linux/percpu-refcount.h:284
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
In kernel/events/core.c (c00000000034be10)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (c00000000036fab0)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (c000000000374c1c)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (c00000000037be40)
Location: include/linux/percpu-refcount.h:284
Inline: True
```
```
In mm/backing-dev.c (c00000000039f1a0)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (c0000000003a9538)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/gup.c (c0000000003b7140)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/slub.c (c000000000424598)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (c00000000045ad80)
Location: include/linux/percpu-refcount.h:284
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
In mm/hugetlb_cgroup.c (c00000000045d820)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (c000000000461364)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/memremap.c (c00000000046da68)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:memremap_pages
```
```
In mm/hmm.c (c000000000470a20)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/inode.c (c0000000004a8594)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (c0000000004cc44c)
Location: include/linux/percpu-refcount.h:284
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
In fs/buffer.c (c0000000004dd2c0)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/block_dev.c (c0000000004e73c8)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (c0000000004efaa0)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (c000000000505248)
Location: include/linux/percpu-refcount.h:284
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
In fs/io_uring.c (c00000000050e8d0)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_enter
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:__io_free_req
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (c00000000076b64c)
Location: include/linux/percpu-refcount.h:284
Inline: True
```
```
In block/blk-core.c (c000000000777dd8)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-merge.c (c000000000780cd0)
Location: include/linux/percpu-refcount.h:284
Inline: True
```
```
In block/blk-mq-sched.c (c00000000078f744)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (c0000000007abe10)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (c0000000007afa04)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/percpu-refcount.c (c0000000007daf18)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (c0000000009c77c0)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (c000000000a19fd4)
Location: include/linux/percpu-refcount.h:284
Inline: True
```
```
In drivers/scsi/scsi_lib.c (c000000000a32740)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (c000000000bd6e90)
Location: include/linux/percpu-refcount.h:284
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
In kernel/kthread.c (ffffffe0000df53e)
Location: include/linux/percpu-refcount.h:284
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffe000151dce)
Location: include/linux/percpu-refcount.h:284
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
In kernel/cgroup/cgroup-v1.c (ffffffe0001546ca)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffe000155b76)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffe000156a08)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffe00015ac3c)
Location: include/linux/percpu-refcount.h:284
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
In kernel/bpf/arraymap.c (ffffffe0001b30b8)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffffffe0001c2b10)
Location: include/linux/percpu-refcount.h:284
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
In kernel/events/core.c (ffffffe0001c97ea)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffe0001dbec4)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffe0001df350)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (0)
Location: include/linux/percpu-refcount.h:284
Inline: False
```
```
In mm/backing-dev.c (ffffffe0001f7220)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffffffe0001fd2ce)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/gup.c (ffffffe000204bb4)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/slub.c (ffffffe0002394c4)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffe000248af8)
Location: include/linux/percpu-refcount.h:284
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
In mm/hugetlb_cgroup.c (ffffffe00024a3da)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/hmm.c (ffffffe000251f74)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/inode.c (ffffffe000271be2)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffe000288b6a)
Location: include/linux/percpu-refcount.h:284
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
In fs/buffer.c (ffffffe000291df4)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/block_dev.c (ffffffe000297c1a)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (ffffffe00029d9d2)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_final_destroy_group
```
```
In fs/aio.c (ffffffe0002aa16e)
Location: include/linux/percpu-refcount.h:284
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
In fs/io_uring.c (ffffffe0002b0e74)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_enter
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:__io_free_req
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (ffffffe00041e3f0)
Location: include/linux/percpu-refcount.h:284
Inline: True
```
```
In block/blk-core.c (ffffffe0004259fe)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-merge.c (ffffffe00042b718)
Location: include/linux/percpu-refcount.h:284
Inline: True
```
```
In block/blk-mq-sched.c (ffffffe000434870)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffe000446d36)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffffffe0004492a4)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/percpu-refcount.c (ffffffe000462f0c)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffffffe0005a0fc8)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (0)
Location: include/linux/percpu-refcount.h:284
Inline: False
```
```
In drivers/scsi/scsi_lib.c (ffffffe0005dfd44)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffe0006de2ec)
Location: include/linux/percpu-refcount.h:284
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
In kernel/kthread.c (ffffffff810c3357)
Location: include/linux/percpu-refcount.h:284
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8115f56f)
Location: include/linux/percpu-refcount.h:284
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
In kernel/cgroup/cgroup-v1.c (ffffffff81161b67)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81162ed4)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff81163d06)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff81169a2c)
Location: include/linux/percpu-refcount.h:284
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
In kernel/bpf/arraymap.c (ffffffff811ef1fc)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffffffff811fee29)
Location: include/linux/percpu-refcount.h:284
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
In kernel/events/core.c (ffffffff8120813c)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff812223bc)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff81225cca)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (ffffffff8122a715)
Location: include/linux/percpu-refcount.h:284
Inline: True
```
```
In mm/backing-dev.c (ffffffff81242493)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffffffff81248d63)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/gup.c (ffffffff81251af5)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/slub.c (ffffffff8129dd94)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812c0ad7)
Location: include/linux/percpu-refcount.h:284
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
In mm/hugetlb_cgroup.c (ffffffff812c2488)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff812c46ff)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/memremap.c (ffffffff812cc99c)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:memremap_pages
```
```
In mm/hmm.c (ffffffff812cef94)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/inode.c (ffffffff812f51d8)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff8130d0bd)
Location: include/linux/percpu-refcount.h:284
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
In fs/buffer.c (ffffffff81318bcf)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/block_dev.c (ffffffff8131eee4)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (ffffffff8132571b)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (ffffffff813350da)
Location: include/linux/percpu-refcount.h:284
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
In fs/io_uring.c (ffffffff8133c331)
Location: include/linux/percpu-refcount.h:284
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
In block/bio.c (ffffffff814d6999)
Location: include/linux/percpu-refcount.h:284
Inline: True
```
```
In block/blk-core.c (ffffffff814def0b)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-merge.c (ffffffff814e5293)
Location: include/linux/percpu-refcount.h:284
Inline: True
```
```
In block/blk-mq-sched.c (ffffffff814ef074)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff815035fb)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffffffff81506354)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/percpu-refcount.c (ffffffff8152297d)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffffffff816f213b)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (ffffffff8171808e)
Location: include/linux/percpu-refcount.h:284
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81728933)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff8183b8b5)
Location: include/linux/percpu-refcount.h:284
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
In kernel/kthread.c (ffffffff810b1b97)
Location: include/linux/percpu-refcount.h:284
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff811527ff)
Location: include/linux/percpu-refcount.h:284
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
In kernel/cgroup/cgroup-v1.c (ffffffff81154dc7)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81156124)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff81156f56)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff8115cc2c)
Location: include/linux/percpu-refcount.h:284
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
In kernel/bpf/arraymap.c (ffffffff811e1f8c)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffffffff811f1b79)
Location: include/linux/percpu-refcount.h:284
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
In kernel/events/core.c (ffffffff811fb263)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff8121556c)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff81218e6a)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (ffffffff8121d835)
Location: include/linux/percpu-refcount.h:284
Inline: True
```
```
In mm/backing-dev.c (ffffffff81235463)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffffffff8123bd0d)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/gup.c (ffffffff81244a8c)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/slub.c (ffffffff8128f910)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812b1b63)
Location: include/linux/percpu-refcount.h:284
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
In mm/hugetlb_cgroup.c (ffffffff812b34d8)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff812b573f)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/memremap.c (ffffffff812bd80c)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:memremap_pages
```
```
In mm/hmm.c (ffffffff812bfc26)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/inode.c (ffffffff812e5df8)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff812fdccd)
Location: include/linux/percpu-refcount.h:284
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
In fs/buffer.c (ffffffff813097bf)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/block_dev.c (ffffffff8130fa84)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (ffffffff813162bb)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (ffffffff81325a6a)
Location: include/linux/percpu-refcount.h:284
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
In fs/io_uring.c (ffffffff8132d001)
Location: include/linux/percpu-refcount.h:284
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
In block/bio.c (ffffffff814c7359)
Location: include/linux/percpu-refcount.h:284
Inline: True
```
```
In block/blk-core.c (ffffffff814cf8ab)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-merge.c (ffffffff814d5942)
Location: include/linux/percpu-refcount.h:284
Inline: True
```
```
In block/blk-mq-sched.c (ffffffff814df5b4)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff814f3abb)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffffffff814f6814)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/percpu-refcount.c (ffffffff81512c5d)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffffffff816cc23b)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (ffffffff816f05be)
Location: include/linux/percpu-refcount.h:284
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81701d63)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff81802f15)
Location: include/linux/percpu-refcount.h:284
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
In kernel/kthread.c (ffffffff810c28a7)
Location: include/linux/percpu-refcount.h:284
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8115d33f)
Location: include/linux/percpu-refcount.h:284
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
In kernel/cgroup/cgroup-v1.c (ffffffff8115f937)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81160ca4)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff81161ad6)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff811677fc)
Location: include/linux/percpu-refcount.h:284
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
In kernel/bpf/arraymap.c (ffffffff811ecfcc)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffffffff811fcbf9)
Location: include/linux/percpu-refcount.h:284
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
In kernel/events/core.c (ffffffff81205f0c)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff8122015c)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff81223a6a)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (ffffffff812284b5)
Location: include/linux/percpu-refcount.h:284
Inline: True
```
```
In mm/backing-dev.c (ffffffff81240233)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffffffff81246b03)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/gup.c (ffffffff8124f895)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/slub.c (ffffffff8129bba4)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812be8e7)
Location: include/linux/percpu-refcount.h:284
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
In mm/hugetlb_cgroup.c (ffffffff812c0298)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff812c250f)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/memremap.c (ffffffff812ca7ac)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:memremap_pages
```
```
In mm/hmm.c (ffffffff812ccda4)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/inode.c (ffffffff812f2fe8)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff8130aead)
Location: include/linux/percpu-refcount.h:284
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
In fs/buffer.c (ffffffff8131669f)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/block_dev.c (ffffffff8131c9b4)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (ffffffff813231eb)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (ffffffff81332baa)
Location: include/linux/percpu-refcount.h:284
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
In fs/io_uring.c (ffffffff81339e01)
Location: include/linux/percpu-refcount.h:284
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
In block/bio.c (ffffffff814d2a29)
Location: include/linux/percpu-refcount.h:284
Inline: True
```
```
In block/blk-core.c (ffffffff814daf9b)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-merge.c (ffffffff814e1323)
Location: include/linux/percpu-refcount.h:284
Inline: True
```
```
In block/blk-mq-sched.c (ffffffff814eb104)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff814ff68b)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffffffff815023e4)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/percpu-refcount.c (ffffffff8151ea0d)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffffffff8171f81b)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (ffffffff81756e5e)
Location: include/linux/percpu-refcount.h:284
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81767703)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff8188aee5)
Location: include/linux/percpu-refcount.h:284
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
In kernel/kthread.c (ffffffff810caeac)
Location: include/linux/percpu-refcount.h:284
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8116a53f)
Location: include/linux/percpu-refcount.h:284
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
In kernel/cgroup/cgroup-v1.c (ffffffff8116cc02)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8116e09d)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8116ef2a)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff81174e8d)
Location: include/linux/percpu-refcount.h:284
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
In kernel/bpf/arraymap.c (ffffffff811fb46c)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffffffff8120b889)
Location: include/linux/percpu-refcount.h:284
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
In kernel/events/core.c (ffffffff81214daa)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff8122f268)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff81232ec8)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (ffffffff81237805)
Location: include/linux/percpu-refcount.h:284
Inline: True
```
```
In mm/backing-dev.c (ffffffff8124f965)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffffffff8125630f)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/gup.c (ffffffff8125f205)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/slub.c (ffffffff812aba8e)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812cf347)
Location: include/linux/percpu-refcount.h:284
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
In mm/hugetlb_cgroup.c (ffffffff812d0cf5)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff812d2f9a)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/memremap.c (ffffffff812db4ae)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
```
```
In mm/hmm.c (ffffffff812ddb34)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/inode.c (ffffffff81304918)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff8131c5cb)
Location: include/linux/percpu-refcount.h:284
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
In fs/buffer.c (ffffffff8132848f)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/block_dev.c (ffffffff8132ea92)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (ffffffff81334f2b)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (ffffffff81345d3a)
Location: include/linux/percpu-refcount.h:284
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
In fs/io_uring.c (ffffffff8134d7f3)
Location: include/linux/percpu-refcount.h:284
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
In block/bio.c (ffffffff814eb549)
Location: include/linux/percpu-refcount.h:284
Inline: True
```
```
In block/blk-core.c (ffffffff814f3d37)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-merge.c (ffffffff814fa1af)
Location: include/linux/percpu-refcount.h:284
Inline: True
```
```
In block/blk-mq-sched.c (ffffffff815040e8)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff81518836)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffffffff8151b724)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/percpu-refcount.c (ffffffff815382cd)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffffffff8173ac4b)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (ffffffff817722be)
Location: include/linux/percpu-refcount.h:284
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81782e2c)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff818aa125)
Location: include/linux/percpu-refcount.h:284
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_end
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
</ul>
