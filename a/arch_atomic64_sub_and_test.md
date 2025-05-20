# Function: <code>arch_atomic64_sub_and_test</code>

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
In kernel/kthread.c (ffffffff810b3996)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff81143909)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
```
In kernel/cgroup/freezer.c (ffffffff8114696f)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_write
  - kernel/cgroup/freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff81147489)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff8114c16d)
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
In kernel/bpf/arraymap.c (ffffffff811c3e42)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffffffff811d2855)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
```
```
In kernel/events/core.c (ffffffff811d9471)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In kernel/memremap.c (ffffffff811e96cd)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/memremap.c:get_dev_pagemap
  - kernel/memremap.c:devm_memremap_pages
  - kernel/memremap.c:devm_memremap_pages_release
```
```
In mm/page-writeback.c (ffffffff811fdbc0)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (ffffffff812013d2)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In mm/backing-dev.c (ffffffff812190c9)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffffffff8121dd7a)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/slab_common.c:kmemcg_deactivate_workfn
```
```
In mm/gup.c (ffffffff81226c9e)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:follow_page_pte
```
```
In mm/huge_memory.c (ffffffff812751cc)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff812864ac)
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
In mm/hugetlb_cgroup.c (ffffffff81287edf)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff81289bf6)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In mm/hmm.c (ffffffff812928cd)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/hmm.c:hmm_devmem_release
```
```
In fs/inode.c (ffffffff812b9178)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff812cbfeb)
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
In fs/block_dev.c (ffffffff812dcb12)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/aio.c (ffffffff812f3206)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/bio.c:bio_disassociate_task
```
```
In block/blk-core.c (ffffffff8148387c)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In block/blk-cgroup.c (ffffffff814a7e8c)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkg_release_rcu
  - block/blk-cgroup.c:blkg_create
```
```
In lib/percpu-refcount.c (ffffffff814cb8ac)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffffffff816ab8ee)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (ffffffff816e229e)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In drivers/md/md.c (ffffffff817f5633)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8114f419)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
```
In kernel/cgroup/freezer.c (ffffffff8115263e)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_write
  - kernel/cgroup/freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff81153159)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff81158daf)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffffffff811e25e5)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
```
```
In kernel/events/core.c (ffffffff811e99a4)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In kernel/memremap.c (ffffffff811fa067)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/memremap.c:get_dev_pagemap
  - kernel/memremap.c:devm_memremap_pages
```
```
In mm/oom_kill.c (ffffffff81205e02)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff812106fc)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (ffffffff81214681)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In mm/backing-dev.c (ffffffff8122be80)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffffffff81230d5a)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/slab_common.c:kmemcg_deactivate_workfn
```
```
In mm/gup.c (ffffffff8123a15f)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/memcontrol.c (ffffffff8129b3ff)
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
In mm/hugetlb_cgroup.c (ffffffff8129ce2b)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff8129ea5a)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In fs/inode.c (ffffffff812ce2c9)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff812e0f00)
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
In fs/buffer.c (ffffffff812ebf0a)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/block_dev.c (ffffffff812f209b)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (ffffffff812f9c7d)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (ffffffff81308206)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_reset
  - block/bio.c:bio_free
```
```
In block/blk-core.c (ffffffff8149f5a8)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In block/blk-cgroup.c (ffffffff814c33e5)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/percpu-refcount.c (ffffffff814e05fc)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffffffff816cc68e)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (ffffffff817056b6)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81714795)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff81821493)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8115b2bd)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8115eca0)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8115faa3)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff81165531)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffffffff811f9755)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In kernel/events/core.c (ffffffff81202ddc)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff8121c3b5)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff8121fdaf)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (ffffffff81224344)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In mm/backing-dev.c (ffffffff8123bb12)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffffffff8124232c)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/gup.c (ffffffff8124b36b)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/slub.c (ffffffff81295a7a)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812b6649)
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff812ba2c6)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In mm/memremap.c (ffffffff812c24ef)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:devm_memremap_pages
```
```
In mm/hmm.c (ffffffff812c502f)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/file_table.c (ffffffff812cd835)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In fs/inode.c (ffffffff812eb188)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff812ff57e)
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
In fs/buffer.c (ffffffff8130d64a)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/block_dev.c (ffffffff81313a3b)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (ffffffff8131a32e)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (ffffffff81329cd6)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In block/bio.c (ffffffff814c6530)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_reset
  - block/bio.c:bio_free
```
```
In block/blk-core.c (ffffffff814cd6a5)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-merge.c (ffffffff814d3d43)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In block/blk-mq-sched.c (ffffffff814dd65a)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff814f1ae0)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/percpu-refcount.c (ffffffff8150c5a2)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffffffff8170811e)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (ffffffff8173f9b0)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff817500a7)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff81863d63)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff81166f7d)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8116a900)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8116b703)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff81171421)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffffffff81206825)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff81229d85)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff8122d85f)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (ffffffff812320dc)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In mm/backing-dev.c (ffffffff81249e63)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffffffff812507bc)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/gup.c (ffffffff8125985b)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/slub.c (ffffffff812a585a)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812c8519)
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff812cc414)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/memremap.c (ffffffff812d441f)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:memremap_pages
```
```
In mm/hmm.c (ffffffff812d69df)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/file_table.c (ffffffff812df255)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In fs/inode.c (ffffffff812fccc8)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff81314b9b)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/block_dev.c (ffffffff8132694b)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (ffffffff8132d14e)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (ffffffff8133cb36)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In block/blk-core.c (ffffffff814e6995)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-merge.c (ffffffff814ed073)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In block/blk-mq-sched.c (ffffffff814f6aea)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff8150b0c0)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/percpu-refcount.c (ffffffff8152a3f2)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffffffff8172c36e)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (ffffffff81763b90)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81774297)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff81895aa3)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff81178698)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8117c3be)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8117d314)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff81183131)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffffffff8122e445)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff81256c2a)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff8125b3cf)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (ffffffff8125e4f0)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/swap.c:__put_page
```
```
In mm/backing-dev.c (ffffffff8127818a)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffffffff8127ee0a)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/gup.c (ffffffff8128a93a)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:gup_pte_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/slub.c (ffffffff812da523)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812fddb4)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
```
```
In mm/memremap.c (ffffffff8130a0d2)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:memremap_pages
```
```
In fs/file_table.c (ffffffff813160b5)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In fs/inode.c (ffffffff81335568)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff8134e557)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/block_dev.c (ffffffff81360e7e)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (ffffffff81366ecf)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_final_destroy_group
```
```
In fs/aio.c (ffffffff81375f06)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/bio.c:bio_uninit
```
```
In block/blk-core.c (ffffffff81545f08)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-merge.c (ffffffff8154aee8)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/blk-merge.c:blk_account_io_merge_request
```
```
In block/blk-mq.c (ffffffff8154f994)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
```
```
In block/blk-mq-sched.c (ffffffff8155758a)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff8156c027)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/percpu-refcount.c (ffffffff8158dbd1)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffffffff817e7b2e)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (ffffffff81823a84)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
```
```
In drivers/scsi/scsi_lib.c (ffffffff81836bf8)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff81962fdc)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff81175452)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8117928c)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8117a179)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff811800cf)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_free_deferred
```
```
In kernel/bpf/arraymap.c (ffffffff8121d137)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/trampoline.c (ffffffff81222b81)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_tramp_exit
```
```
In kernel/bpf/cgroup.c (ffffffff81236993)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff8126183f)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff812654db)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (ffffffff81268b32)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/backing-dev.c (ffffffff81282914)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/percpu.c (ffffffff812860c8)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_memcg_free_hook
```
```
In mm/gup.c (ffffffff812945f2)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:gup_pte_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/mmap_lock.c (ffffffff81295fac)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/mmap_lock.c:get_mm_memcg_path
```
```
In mm/hugetlb.c (ffffffff812d3ba8)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:coalesce_file_region
  - mm/hugetlb.c:coalesce_file_region
```
```
In mm/slub.c (ffffffff812e6b95)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memcontrol.c (ffffffff8130a230)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
```
```
In mm/memremap.c (ffffffff81315da3)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:pagemap_range
```
```
In fs/file_table.c (ffffffff813215d5)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - fs/file_table.c:fput
```
```
In fs/inode.c (ffffffff81340edd)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff8135b470)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/block_dev.c (ffffffff8136d16e)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (ffffffff81374224)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_final_destroy_group
```
```
In fs/aio.c (ffffffff81383e8b)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/bio.c:bio_uninit
```
```
In block/blk-core.c (ffffffff81561978)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio_noacct_mq
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff8156bd77)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
```
```
In block/blk-mq-sched.c (ffffffff81573ba2)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff81585a99)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/percpu-refcount.c (ffffffff815aa8bb)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffffffff817fca12)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (ffffffff8183276e)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
```
```
In drivers/scsi/scsi_lib.c (ffffffff8184768b)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff81969881)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff81175fc2)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81179dfc)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8117acf9)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff81180b9f)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_free_deferred
```
```
In kernel/bpf/arraymap.c (ffffffff81220c47)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/trampoline.c (ffffffff812273c1)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_tramp_exit
```
```
In kernel/bpf/cgroup.c (ffffffff8123abf3)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff81266052)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff812696ea)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (ffffffff8126e8c3)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/backing-dev.c (ffffffff81287a39)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/percpu.c (ffffffff8128acae)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_memcg_free_hook
```
```
In mm/gup.c (ffffffff8129a042)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:gup_pte_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/mmap_lock.c (ffffffff8129b8c9)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/mmap_lock.c:get_mm_memcg_path
```
```
In mm/memory_hotplug.c (ffffffff812c645f)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/memory_hotplug.c:pfn_to_online_page
```
```
In mm/hugetlb.c (ffffffff812daa8c)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:coalesce_file_region
  - mm/hugetlb.c:coalesce_file_region
```
```
In mm/slub.c (ffffffff812ee3d6)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memcontrol.c (ffffffff81310ab7)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
```
```
In mm/memremap.c (ffffffff8131bf96)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:pagemap_range
```
```
In fs/file_table.c (ffffffff813276b5)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In fs/inode.c (ffffffff813472cd)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff81362070)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (ffffffff8137abc3)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (ffffffff8138aadb)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/bio.c:bio_uninit
```
```
In block/blk-core.c (ffffffff81569f0e)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff81573869)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
```
```
In block/blk-mq-sched.c (ffffffff8157bc32)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff8158c469)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/percpu-refcount.c (ffffffff815b54db)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffffffff817e15e2)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (ffffffff8181555e)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
```
```
In drivers/scsi/scsi_lib.c (ffffffff8182a84b)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff8194dc01)
Location: arch/x86/include/asm/atomic64_64.h:74
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
In kernel/kthread.c (ffffffff810df954)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8119d57b)
Location: arch/x86/include/asm/atomic64_64.h:74
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
In kernel/cgroup/cgroup-v1.c (ffffffff8119f40b)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff811a171c)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff811a2748)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff811a898f)
Location: arch/x86/include/asm/atomic64_64.h:74
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
In kernel/bpf/syscall.c (ffffffff8122dc9d)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_free_deferred
```
```
In kernel/bpf/arraymap.c (ffffffff81258607)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/trampoline.c (ffffffff8125f4c1)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_tramp_exit
```
```
In kernel/bpf/cgroup.c (ffffffff812757d3)
Location: arch/x86/include/asm/atomic64_64.h:74
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
In kernel/events/core.c (ffffffff81283e45)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff812a2872)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff812a6172)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (ffffffff812ab8bf)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/backing-dev.c (ffffffff812c6134)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/percpu.c (ffffffff812cb0a1)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_memcg_free_hook
  - mm/percpu.c:pcpu_memcg_post_alloc_hook
```
```
In mm/gup.c (ffffffff812da9ce)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:gup_pte_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/mmap_lock.c (ffffffff812dc3b9)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/mmap_lock.c:get_mm_memcg_path
```
```
In mm/memory.c (ffffffff812e266f)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/memory_hotplug.c (ffffffff8130af4f)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/memory_hotplug.c:pfn_to_online_page
```
```
In mm/swap_state.c (ffffffff81310f60)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:find_get_incore_page
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff81317e6c)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
  - mm/swapfile.c:get_swap_device
```
```
In mm/hugetlb.c (ffffffff81321a62)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:coalesce_file_region
  - mm/hugetlb.c:coalesce_file_region
```
```
In mm/slub.c (ffffffff81338efe)
Location: arch/x86/include/asm/atomic64_64.h:74
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
In mm/memcontrol.c (ffffffff8135bd81)
Location: arch/x86/include/asm/atomic64_64.h:74
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
In mm/hugetlb_cgroup.c (ffffffff8135e112)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff81360327)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
```
```
In mm/memremap.c (ffffffff81369276)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:pagemap_range
```
```
In fs/file_table.c (ffffffff81374cb5)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In fs/inode.c (ffffffff81394d2d)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff813b0889)
Location: arch/x86/include/asm/atomic64_64.h:74
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
In fs/notify/group.c (ffffffff813c78a3)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (ffffffff813d7deb)
Location: arch/x86/include/asm/atomic64_64.h:74
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
In fs/io_uring.c (ffffffff813eedac)
Location: arch/x86/include/asm/atomic64_64.h:74
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
In block/bio.c (ffffffff815c69d4)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/bio.c:bio_uninit
```
```
In block/blk-core.c (ffffffff815cd5e6)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:blk_try_enter_queue
```
```
In block/blk-mq.c (ffffffff815d7e6c)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
```
```
In block/blk-mq-sched.c (ffffffff815e100d)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff815f1a99)
Location: arch/x86/include/asm/atomic64_64.h:74
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
In block/blk-throttle.c (ffffffff815f713e)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/percpu-refcount.c (ffffffff8161b8e4)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffffffff8186fbed)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_free_idle_workers
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/dax/super.c (ffffffff8189fd4a)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - drivers/dax/super.c:generic_fsdax_supported
  - drivers/dax/super.c:generic_fsdax_supported
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b62a7)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff819f3001)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_end
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107e94b)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
```
```
In kernel/kthread.c (ffffffff810f9cd2)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff811cd8d5)
Location: arch/x86/include/asm/atomic64_64.h:74
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
In kernel/cgroup/cgroup-v1.c (ffffffff811cfa6f)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff811d2066)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff811d31c5)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff811d9b2b)
Location: arch/x86/include/asm/atomic64_64.h:74
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
In kernel/bpf/syscall.c (ffffffff8126ff77)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_free_deferred
```
```
In kernel/bpf/arraymap.c (ffffffff812a13f4)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/trampoline.c (ffffffff812a9c26)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_tramp_exit
```
```
In kernel/bpf/cgroup.c (ffffffff812c522e)
Location: arch/x86/include/asm/atomic64_64.h:74
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
In kernel/events/core.c (ffffffff812d706f)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff812fa51b)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff812fee02)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff813235b1)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/percpu.c (ffffffff81328a7a)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_memcg_post_alloc_hook
```
```
In mm/gup.c (ffffffff8133a54a)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:gup_pte_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/mmap_lock.c (ffffffff8133c346)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/mmap_lock.c:get_mm_memcg_path
```
```
In mm/memory.c (ffffffff81344328)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/memory_hotplug.c (ffffffff8137463a)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/memory_hotplug.c:pfn_to_online_page
```
```
In mm/swap_state.c (ffffffff8137bec0)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:find_get_incore_page
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff81383535)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
```
```
In mm/zswap.c (ffffffff813864e5)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_free_entry
```
```
In mm/hugetlb.c (ffffffff8138eb6e)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:clear_vma_resv_huge_pages
  - mm/hugetlb.c:coalesce_file_region
  - mm/hugetlb.c:coalesce_file_region
```
```
In mm/slub.c (ffffffff813aab14)
Location: arch/x86/include/asm/atomic64_64.h:74
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
In mm/memcontrol.c (ffffffff813d5cee)
Location: arch/x86/include/asm/atomic64_64.h:74
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
In mm/hugetlb_cgroup.c (ffffffff813d8542)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff813db310)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
```
```
In mm/memremap.c (ffffffff813e7079)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
```
```
In fs/inode.c (ffffffff814170e7)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff81435665)
Location: arch/x86/include/asm/atomic64_64.h:74
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
In fs/notify/group.c (ffffffff8144eca6)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (ffffffff8146252c)
Location: arch/x86/include/asm/atomic64_64.h:74
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
In block/bio.c (ffffffff8167189d)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/bio.c:bio_uninit
```
```
In block/blk-core.c (ffffffff8167a045)
Location: arch/x86/include/asm/atomic64_64.h:74
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
In block/blk-mq.c (ffffffff816845a2)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_end_request_batch
```
```
In block/blk-mq-sched.c (ffffffff8168fc02)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff816a4bf7)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-cgroup-fc-appid.c (ffffffff816a5560)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid
  - block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid
```
```
In block/blk-throttle.c (ffffffff816a8869)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In io_uring/io_uring.c (ffffffff816d6d97)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/io_uring.c:io_free_batch_list
  - io_uring/io_uring.c:ctx_flush_and_put
  - io_uring/io_uring.c:io_free_req
  - io_uring/io_uring.c:__io_req_complete_put
```
```
In lib/percpu-refcount.c (ffffffff816e91aa)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffffffff819b77f7)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_free_idle_workers
```
```
In drivers/scsi/scsi_lib.c (ffffffff81a0180a)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff81b5b692)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_start
  - drivers/md/md.c:mddev_init_writes_pending
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8108ff8b)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
```
```
In kernel/kthread.c (ffffffff8111ca12)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff81210f85)
Location: arch/x86/include/asm/atomic64_64.h:74
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
In kernel/cgroup/cgroup-v1.c (ffffffff812132d3)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81215d96)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff81217155)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff8121effb)
Location: arch/x86/include/asm/atomic64_64.h:74
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
In kernel/bpf/syscall.c (ffffffff812c9465)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_free_deferred
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
```
```
In kernel/bpf/helpers.c (ffffffff812f4447)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_cgroup_release
```
```
In kernel/bpf/arraymap.c (ffffffff812fe1e4)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/trampoline.c (ffffffff81308bd6)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_tramp_exit
```
```
In kernel/bpf/memalloc.c (ffffffff8131c60c)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:bpf_mem_alloc_destroy
  - kernel/bpf/memalloc.c:bpf_mem_alloc_destroy
  - kernel/bpf/memalloc.c:alloc_bulk
```
```
In kernel/bpf/cgroup_iter.c (ffffffff813255aa)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/bpf/cgroup_iter.c:bpf_iter_detach_cgroup
  - kernel/bpf/cgroup_iter.c:cgroup_iter_seq_fini
```
```
In kernel/bpf/bpf_cgrp_storage.c (ffffffff81325a1a)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete_elem
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_update_elem
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_lookup_elem
```
```
In kernel/bpf/cgroup.c (ffffffff8132a74e)
Location: arch/x86/include/asm/atomic64_64.h:74
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
In kernel/events/core.c (ffffffff8133fe0d)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff81364c9b)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff81369589)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
```
```
In mm/vmscan.c (ffffffff8138262c)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/vmscan.c:run_cmd
  - mm/vmscan.c:lru_gen_del_mm
```
```
In mm/backing-dev.c (ffffffff81397e01)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/percpu.c (ffffffff8139dcb0)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_memcg_post_alloc_hook
```
```
In mm/gup.c (ffffffff813b2008)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:gup_pte_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/mmap_lock.c (ffffffff813b3e86)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/mmap_lock.c:get_mm_memcg_path
```
```
In mm/memory.c (ffffffff813bc41e)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/memory_hotplug.c (ffffffff813f1797)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/memory_hotplug.c:pfn_to_online_page
```
```
In mm/swap_state.c (ffffffff813f96c8)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:filemap_get_incore_folio
  - mm/swap_state.c:swap_cache_get_folio
```
```
In mm/swapfile.c (ffffffff81400f35)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
  - mm/swapfile.c:get_swap_device
```
```
In mm/zswap.c (ffffffff8140430a)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_free_entry
```
```
In mm/hugetlb.c (ffffffff8140d61e)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:clear_vma_resv_huge_pages
  - mm/hugetlb.c:coalesce_file_region
  - mm/hugetlb.c:coalesce_file_region
```
```
In mm/slub.c (ffffffff8142cd6c)
Location: arch/x86/include/asm/atomic64_64.h:74
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
In mm/memcontrol.c (ffffffff8145b6d5)
Location: arch/x86/include/asm/atomic64_64.h:74
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
In mm/hugetlb_cgroup.c (ffffffff8145e222)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff81461705)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
```
```
In mm/memremap.c (ffffffff8146fb6e)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/memremap.c:free_zone_device_page
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
```
```
In fs/inode.c (ffffffff814a26e7)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff814c36d2)
Location: arch/x86/include/asm/atomic64_64.h:74
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
In fs/notify/group.c (ffffffff814dd446)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (ffffffff814f2b7c)
Location: arch/x86/include/asm/atomic64_64.h:74
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
In block/bio.c (ffffffff8172d10d)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/bio.c:bio_uninit
```
```
In block/blk-core.c (ffffffff817364ea)
Location: arch/x86/include/asm/atomic64_64.h:74
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
In block/blk-mq.c (ffffffff817423cd)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_end_request_batch
```
```
In block/blk-mq-sched.c (ffffffff8174e7bf)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff81763986)
Location: arch/x86/include/asm/atomic64_64.h:74
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
In block/blk-cgroup-fc-appid.c (ffffffff817643fa)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid
  - block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid
```
```
In block/blk-throttle.c (ffffffff8176727e)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In io_uring/io_uring.c (ffffffff8178b897)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_req_caches_free
  - io_uring/io_uring.c:io_free_batch_list
  - io_uring/io_uring.c:__io_req_task_work_add
  - io_uring/io_uring.c:ctx_flush_and_put
  - io_uring/io_uring.c:io_free_req
  - io_uring/io_uring.c:__io_req_complete_post
  - io_uring/io_uring.c:io_fallback_req_func
```
```
In io_uring/fdinfo.c (ffffffff8179b990)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - io_uring/fdinfo.c:io_uring_show_fdinfo
```
```
In io_uring/rsrc.c (ffffffff817a0809)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_rsrc_refs_drop
```
```
In lib/percpu-refcount.c (ffffffff817d92aa)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/pci/p2pdma.c (ffffffff8191ce77)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pmem_free_sgl
  - drivers/pci/p2pdma.c:p2pdma_page_free
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/block/loop.c (ffffffff81b2caf7)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_free_idle_workers
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b7fe5a)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff81cf5062)
Location: arch/x86/include/asm/atomic64_64.h:74
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81092ea1)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
```
```
In kernel/kthread.c (ffffffff81129ba2)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff81226975)
Location: arch/x86/include/asm/atomic64_64.h:37
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
In kernel/cgroup/cgroup-v1.c (ffffffff81228be3)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8122b6cf)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8122ca75)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff8123512b)
Location: arch/x86/include/asm/atomic64_64.h:37
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
In kernel/bpf/syscall.c (ffffffff812f0bb5)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_free_deferred
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_kvcalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
```
```
In kernel/bpf/helpers.c (ffffffff813214a4)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_cgroup_release
```
```
In kernel/bpf/arraymap.c (ffffffff8132cdf4)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/trampoline.c (ffffffff81337af6)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_tramp_exit
```
```
In kernel/bpf/memalloc.c (ffffffff8134c53e)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:bpf_mem_cache_alloc_flags
  - kernel/bpf/memalloc.c:bpf_mem_alloc_destroy
  - kernel/bpf/memalloc.c:bpf_mem_alloc_destroy
  - kernel/bpf/memalloc.c:alloc_bulk
```
```
In kernel/bpf/cgroup_iter.c (ffffffff813557ea)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - kernel/bpf/cgroup_iter.c:bpf_iter_detach_cgroup
  - kernel/bpf/cgroup_iter.c:cgroup_iter_seq_fini
```
```
In kernel/bpf/bpf_cgrp_storage.c (ffffffff81355c68)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete_elem
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_update_elem
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_lookup_elem
```
```
In kernel/bpf/cgroup.c (ffffffff8135a88e)
Location: arch/x86/include/asm/atomic64_64.h:37
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
In kernel/events/core.c (ffffffff81370daa)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff8139715b)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff8139b729)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
```
```
In mm/vmscan.c (ffffffff813b41eb)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - mm/vmscan.c:run_cmd
  - mm/vmscan.c:shrink_many
  - mm/vmscan.c:shrink_many
  - mm/vmscan.c:lru_gen_del_mm
```
```
In mm/shmem.c (ffffffff813bedac)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_swapin_folio
```
```
In mm/backing-dev.c (ffffffff813cad81)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/percpu.c (ffffffff813d0e16)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_memcg_post_alloc_hook
```
```
In mm/gup.c (ffffffff813e6da8)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:gup_pte_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/mmap_lock.c (ffffffff813e87d6)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - mm/mmap_lock.c:get_mm_memcg_path
```
```
In mm/memory.c (ffffffff813f0c83)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/memory_hotplug.c (ffffffff814252d5)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - mm/memory_hotplug.c:pfn_to_online_page
```
```
In mm/swap_state.c (ffffffff8142c46e)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:filemap_get_incore_folio
```
```
In mm/swapfile.c (ffffffff81433e14)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:get_swap_device
```
```
In mm/zswap.c (ffffffff81437131)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_free_entry
```
```
In mm/hugetlb.c (ffffffff814409db)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:clear_vma_resv_huge_pages
  - mm/hugetlb.c:coalesce_file_region
  - mm/hugetlb.c:coalesce_file_region
```
```
In mm/slub.c (ffffffff8146237e)
Location: arch/x86/include/asm/atomic64_64.h:37
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
In mm/memcontrol.c (ffffffff81491345)
Location: arch/x86/include/asm/atomic64_64.h:37
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
In mm/hugetlb_cgroup.c (ffffffff81493f12)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff81498349)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
```
```
In mm/memremap.c (ffffffff814a434e)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - mm/memremap.c:free_zone_device_page
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
```
```
In fs/inode.c (ffffffff814d7849)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff814f8ab5)
Location: arch/x86/include/asm/atomic64_64.h:37
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
In fs/notify/group.c (ffffffff81513ca6)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (ffffffff8152992c)
Location: arch/x86/include/asm/atomic64_64.h:37
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
In block/bio.c (ffffffff817694ad)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - block/bio.c:bio_uninit
```
```
In block/blk-core.c (ffffffff81772afa)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - block/blk-core.c:bio_poll
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff8177f41d)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_dispatch_plug_list
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_end_request_batch
```
```
In block/blk-cgroup.c (ffffffff817a2a15)
Location: arch/x86/include/asm/atomic64_64.h:37
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
In block/blk-cgroup-fc-appid.c (ffffffff817a3508)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid
  - block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid
```
```
In block/blk-throttle.c (ffffffff817a6343)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In io_uring/io_uring.c (ffffffff817c910c)
Location: arch/x86/include/asm/atomic64_64.h:37
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
In io_uring/fdinfo.c (ffffffff817dcac2)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - io_uring/fdinfo.c:io_uring_show_fdinfo
```
```
In lib/percpu-refcount.c (ffffffff81818493)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/pci/p2pdma.c (ffffffff81960437)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pmem_free_sgl
  - drivers/pci/p2pdma.c:p2pdma_page_free
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/block/loop.c (ffffffff81b7cdd1)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_free_idle_workers
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd3ead)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff81d5f753)
Location: arch/x86/include/asm/atomic64_64.h:37
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
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81093900)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109a2e1)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
```
```
In kernel/fork.c (ffffffff810fe9f7)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
```
```
In kernel/ptrace.c (ffffffff811118c1)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/kthread.c (ffffffff811341e2)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
```
```
In kernel/nsproxy.c (ffffffff8113c84f)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - kernel/nsproxy.c:put_nsset
```
```
In kernel/cred.c (ffffffff8113f138)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:revert_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
```
```
In kernel/cgroup/cgroup.c (ffffffff8123e605)
Location: arch/x86/include/asm/atomic64_64.h:37
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
In kernel/cgroup/cgroup-v1.c (ffffffff81240a2e)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff812436bf)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff81244b35)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff8124ed7a)
Location: arch/x86/include/asm/atomic64_64.h:37
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
In kernel/user_namespace.c (ffffffff81251af5)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - kernel/user_namespace.c:unshare_userns
```
```
In kernel/trace/trace_events_user.c (ffffffff812e14aa)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_set_call_visible
```
```
In kernel/bpf/syscall.c (ffffffff8130f9b5)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_free_deferred
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_kvcalloc
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
```
```
In kernel/bpf/helpers.c (ffffffff81343bd4)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_cgroup_release_dtor
  - kernel/bpf/helpers.c:bpf_cgroup_release
```
```
In kernel/bpf/arraymap.c (ffffffff81351148)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/trampoline.c (ffffffff8135d936)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_tramp_exit
```
```
In kernel/bpf/memalloc.c (ffffffff81373a9a)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:bpf_mem_cache_alloc_flags
  - kernel/bpf/memalloc.c:bpf_mem_alloc_destroy
  - kernel/bpf/memalloc.c:bpf_mem_alloc_destroy
  - kernel/bpf/memalloc.c:alloc_bulk
```
```
In kernel/bpf/cgroup_iter.c (ffffffff8137e16a)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - kernel/bpf/cgroup_iter.c:bpf_iter_detach_cgroup
  - kernel/bpf/cgroup_iter.c:cgroup_iter_seq_fini
```
```
In kernel/bpf/bpf_cgrp_storage.c (ffffffff8137e798)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete_elem
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_update_elem
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_lookup_elem
```
```
In kernel/bpf/cgroup.c (ffffffff8138347e)
Location: arch/x86/include/asm/atomic64_64.h:37
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
In kernel/events/core.c (ffffffff8139a0aa)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In kernel/watch_queue.c (ffffffff813b2ab0)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - kernel/watch_queue.c:free_watch
```
```
In mm/oom_kill.c (ffffffff813c0f6d)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff813c5699)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
```
```
In mm/vmscan.c (ffffffff813dd86b)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - mm/vmscan.c:run_cmd
  - mm/vmscan.c:shrink_many
  - mm/vmscan.c:shrink_many
  - mm/vmscan.c:lru_gen_del_mm
```
```
In mm/shmem.c (ffffffff813e9dcf)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_swapin_folio
```
```
In mm/backing-dev.c (ffffffff813f5d61)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/percpu.c (ffffffff813fadeb)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
```
```
In mm/workingset.c (ffffffff8140c42b)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - mm/workingset.c:workingset_test_recent
```
```
In mm/gup.c (ffffffff81411a35)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:gup_pte_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/mmap_lock.c (ffffffff81413466)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - mm/mmap_lock.c:get_mm_memcg_path
```
```
In mm/memory.c (ffffffff814205c4)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/memory_hotplug.c (ffffffff81452516)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - mm/memory_hotplug.c:pfn_to_online_page
```
```
In mm/slub.c (ffffffff81455b3a)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - mm/slub.c:__memcg_slab_free_hook
```
```
In mm/swap_state.c (ffffffff81465bb4)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:filemap_get_incore_folio
```
```
In mm/swapfile.c (ffffffff8146d21b)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:get_swap_device
```
```
In mm/zswap.c (ffffffff81470e7c)
Location: arch/x86/include/asm/atomic64_64.h:37
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
In mm/hugetlb.c (ffffffff8147ab0b)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:clear_vma_resv_huge_pages
  - mm/hugetlb.c:coalesce_file_region
  - mm/hugetlb.c:coalesce_file_region
```
```
In mm/memcontrol.c (ffffffff814c0cb5)
Location: arch/x86/include/asm/atomic64_64.h:37
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
```
```
In mm/hugetlb_cgroup.c (ffffffff814c37f2)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff814c7930)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
```
```
In mm/memremap.c (ffffffff814d518c)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - mm/memremap.c:free_zone_device_page
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
```
```
In fs/open.c (ffffffff814d8d40)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - fs/open.c:do_faccessat
```
```
In fs/file_table.c (ffffffff814e29ba)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:init_file
```
```
In fs/inode.c (ffffffff81509b59)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff8152d314)
Location: arch/x86/include/asm/atomic64_64.h:37
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
In fs/fs_context.c (ffffffff81538c2d)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/notify/group.c (ffffffff81548176)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (ffffffff8155e7fc)
Location: arch/x86/include/asm/atomic64_64.h:37
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
In fs/coredump.c (ffffffff8158670d)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffff815abbb2)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In security/keys/keyctl.c (ffffffff816c953e)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/keys/process_keys.c (ffffffff816cb5c7)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff816cbee6)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff816cccb8)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
```
```
In security/apparmor/audit.c (ffffffff81736e4a)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
```
```
In security/apparmor/domain.c (ffffffff81742035)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:may_change_ptraced_domain
```
```
In security/apparmor/lsm.c (ffffffff81752a76)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
```
In block/bio.c (ffffffff817ab52d)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - block/bio.c:bio_uninit
```
```
In block/blk-core.c (ffffffff817b4e94)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - block/blk-core.c:bio_poll
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-mq.c (ffffffff817c1f0d)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_dispatch_plug_list
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_end_request_batch
```
```
In block/blk-cgroup.c (ffffffff817e6558)
Location: arch/x86/include/asm/atomic64_64.h:37
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
In block/blk-cgroup-fc-appid.c (ffffffff817e7058)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid
  - block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid
```
```
In block/blk-throttle.c (ffffffff817ea083)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In io_uring/io_uring.c (ffffffff81816f09)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_activate_pollwq
  - io_uring/io_uring.c:io_activate_pollwq_cb
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_req_caches_free
  - io_uring/io_uring.c:io_init_req
  - io_uring/io_uring.c:io_fallback_tw
  - io_uring/io_uring.c:io_fallback_tw
  - io_uring/io_uring.c:ctx_flush_and_put
  - io_uring/io_uring.c:io_clean_op
  - io_uring/io_uring.c:io_fallback_req_func
```
```
In io_uring/register.c (ffffffff8182bdb8)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - io_uring/register.c:__io_uring_register
  - io_uring/register.c:io_unregister_personality
```
```
In lib/percpu-refcount.c (ffffffff8185d793)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/pci/p2pdma.c (ffffffff819a9b27)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pmem_free_sgl
  - drivers/pci/p2pdma.c:p2pdma_page_free
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/base/firmware_loader/main.c (ffffffff81bb3c9c)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/block/loop.c (ffffffff81bd0d67)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_free_idle_workers
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c28b27)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/usb/core/devio.c (ffffffff81d4df56)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
```
In drivers/md/md.c (ffffffff81e16b0f)
Location: arch/x86/include/asm/atomic64_64.h:37
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
```
In net/core/sock.c (ffffffff81ec668f)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
```
```
In net/unix/af_unix.c (ffffffff8207c11f)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
```
In net/dns_resolver/dns_key.c (ffffffff83d5212c)
Location: arch/x86/include/asm/atomic64_64.h:37
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:exit_dns_resolver
  - net/dns_resolver/dns_key.c:init_dns_resolver
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
In kernel/kthread.c (ffffffff810c3372)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8115f59d)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81162f20)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff81163d23)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff81169a41)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffffffff811fee45)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff812223d5)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff81225eaf)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (ffffffff8122a72c)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In mm/backing-dev.c (ffffffff812424b3)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffffffff81248e0c)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/gup.c (ffffffff81251eab)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/slub.c (ffffffff8129de3a)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812c0af9)
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff812c49f4)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/memremap.c (ffffffff812cc9ff)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:memremap_pages
```
```
In mm/hmm.c (ffffffff812cefbf)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/file_table.c (ffffffff812d7835)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In fs/inode.c (ffffffff812f52a8)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff8130d17b)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/block_dev.c (ffffffff8131ef2b)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (ffffffff8132572e)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (ffffffff81335116)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In block/blk-core.c (ffffffff814def75)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-merge.c (ffffffff814e5653)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In block/blk-mq-sched.c (ffffffff814ef0ca)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff815036a0)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/percpu-refcount.c (ffffffff815229d2)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffffffff816f214e)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (ffffffff81718280)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81728987)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff8183b923)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8115282d)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81156170)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff81156f73)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff8115cc41)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffffffff811f1b95)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff81215585)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff8121904f)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (ffffffff8121d84c)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In mm/backing-dev.c (ffffffff81235483)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffffffff8123bdb6)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/gup.c (ffffffff81244ae7)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/slub.c (ffffffff8128f9b3)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812b1b85)
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff812b5a34)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/memremap.c (ffffffff812bd86f)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:memremap_pages
```
```
In mm/hmm.c (ffffffff812bfc51)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/file_table.c (ffffffff812c84b5)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In fs/inode.c (ffffffff812e5ec8)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff812fdd8b)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/block_dev.c (ffffffff8130facb)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (ffffffff813162ce)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (ffffffff81325aa6)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In block/blk-core.c (ffffffff814cf915)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-merge.c (ffffffff814d5c84)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In block/blk-mq-sched.c (ffffffff814df60a)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff814f3b60)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/percpu-refcount.c (ffffffff81512cb2)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffffffff816cc24e)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (ffffffff816f07b0)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81701db7)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff81802f83)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8115d36d)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81160cf0)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff81161af3)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff81167811)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffffffff811fcc15)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff81220175)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff81223c4f)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (ffffffff812284cc)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In mm/backing-dev.c (ffffffff81240253)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffffffff81246bac)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/gup.c (ffffffff8124fc4b)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/slub.c (ffffffff8129bc4a)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812be909)
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff812c2804)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/memremap.c (ffffffff812ca80f)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:memremap_pages
```
```
In mm/hmm.c (ffffffff812ccdcf)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/file_table.c (ffffffff812d5645)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In fs/inode.c (ffffffff812f30b8)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff8130af6b)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/block_dev.c (ffffffff8131c9fb)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (ffffffff813231fe)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (ffffffff81332be6)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In block/blk-core.c (ffffffff814db005)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-merge.c (ffffffff814e16e3)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In block/blk-mq-sched.c (ffffffff814eb15a)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff814ff730)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/percpu-refcount.c (ffffffff8151ea62)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffffffff8171f82e)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (ffffffff81757050)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81767757)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff8188af53)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8116a591)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8116e125)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8116ef53)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff81174ebb)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (ffffffff8120b8b1)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff8122f28f)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff81232f26)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (ffffffff8123782f)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In mm/backing-dev.c (ffffffff8124faab)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (ffffffff812563d7)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/gup.c (ffffffff8125f5e5)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/slub.c (ffffffff812abb48)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812cf371)
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff812d329e)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/memremap.c (ffffffff812db530)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:memremap_pages
```
```
In mm/hmm.c (ffffffff812ddb76)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/file_table.c (ffffffff812e6495)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In fs/inode.c (ffffffff81304a0d)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff8131c6fa)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/block_dev.c (ffffffff8132eaf0)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (ffffffff81334f53)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (ffffffff81345d86)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In block/blk-core.c (ffffffff814f3dd4)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-merge.c (ffffffff814fa59f)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In block/blk-mq-sched.c (ffffffff81504162)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff815188ff)
Location: arch/x86/include/asm/atomic64_64.h:74
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
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/percpu-refcount.c (ffffffff81538332)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffffffff8173ac73)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (ffffffff817724e4)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81782e8c)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff818aa1aa)
Location: arch/x86/include/asm/atomic64_64.h:74
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_end
```
</details>
</li>
</ul>

## Differences
