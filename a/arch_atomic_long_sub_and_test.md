# Function: <code>arch_atomic_long_sub_and_test</code>

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
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810df954)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8119d57b)
Location: include/linux/atomic/atomic-long.h:459
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
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff811a171c)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff811a2748)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff811a898f)
Location: include/linux/atomic/atomic-long.h:459
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
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_free_deferred
```
```
In kernel/bpf/arraymap.c (ffffffff81258607)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/trampoline.c (ffffffff8125f4c1)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_tramp_exit
```
```
In kernel/bpf/cgroup.c (ffffffff812757d3)
Location: include/linux/atomic/atomic-long.h:459
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
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff812a2872)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff812a6172)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (ffffffff812ab8bf)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/backing-dev.c (ffffffff812c6134)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/percpu.c (ffffffff812cb0a1)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_memcg_free_hook
  - mm/percpu.c:pcpu_memcg_post_alloc_hook
```
```
In mm/gup.c (ffffffff812da9ce)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:gup_pte_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/mmap_lock.c (ffffffff812dc3b9)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - mm/mmap_lock.c:get_mm_memcg_path
```
```
In mm/memory.c (ffffffff812e266f)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/memory_hotplug.c (ffffffff8130af4f)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - mm/memory_hotplug.c:pfn_to_online_page
```
```
In mm/swap_state.c (ffffffff81310f60)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:find_get_incore_page
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff81317e6c)
Location: include/linux/atomic/atomic-long.h:459
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
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:coalesce_file_region
  - mm/hugetlb.c:coalesce_file_region
```
```
In mm/slub.c (ffffffff81338efe)
Location: include/linux/atomic/atomic-long.h:459
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
Location: include/linux/atomic/atomic-long.h:459
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
Location: include/linux/atomic/atomic-long.h:459
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
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
```
```
In mm/memremap.c (ffffffff81369276)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:pagemap_range
```
```
In fs/file_table.c (ffffffff81374cb5)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
```
```
In fs/inode.c (ffffffff81394d2d)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff813b0889)
Location: include/linux/atomic/atomic-long.h:459
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
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (ffffffff813d7deb)
Location: include/linux/atomic/atomic-long.h:459
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
Location: include/linux/atomic/atomic-long.h:459
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
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - block/bio.c:bio_uninit
```
```
In block/blk-core.c (ffffffff815cd5e6)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:blk_try_enter_queue
```
```
In block/blk-mq.c (ffffffff815d7e6c)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
```
```
In block/blk-mq-sched.c (ffffffff815e100d)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff815f1a99)
Location: include/linux/atomic/atomic-long.h:459
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
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/percpu-refcount.c (ffffffff8161b8e4)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffffffff8186fbed)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_free_idle_workers
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/dax/super.c (ffffffff8189fd4a)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - drivers/dax/super.c:generic_fsdax_supported
  - drivers/dax/super.c:generic_fsdax_supported
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b62a7)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff819f3001)
Location: include/linux/atomic/atomic-long.h:459
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
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
```
```
In kernel/kthread.c (ffffffff810f9cd2)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff811cd8d5)
Location: include/linux/atomic/atomic-long.h:459
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
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff811d2066)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff811d31c5)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff811d9b2b)
Location: include/linux/atomic/atomic-long.h:459
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
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_free_deferred
```
```
In kernel/bpf/arraymap.c (ffffffff812a13f4)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/trampoline.c (ffffffff812a9c26)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_tramp_exit
```
```
In kernel/bpf/cgroup.c (ffffffff812c522e)
Location: include/linux/atomic/atomic-long.h:459
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
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff812fa51b)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff812fee02)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff813235b1)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/percpu.c (ffffffff81328a7a)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_memcg_post_alloc_hook
```
```
In mm/gup.c (ffffffff8133a54a)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:gup_pte_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/mmap_lock.c (ffffffff8133c346)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - mm/mmap_lock.c:get_mm_memcg_path
```
```
In mm/memory.c (ffffffff81344328)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/memory_hotplug.c (ffffffff8137463a)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - mm/memory_hotplug.c:pfn_to_online_page
```
```
In mm/swap_state.c (ffffffff8137bec0)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:find_get_incore_page
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff81383535)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
```
```
In mm/zswap.c (ffffffff813864e5)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_free_entry
```
```
In mm/hugetlb.c (ffffffff8138eb6e)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:clear_vma_resv_huge_pages
  - mm/hugetlb.c:coalesce_file_region
  - mm/hugetlb.c:coalesce_file_region
```
```
In mm/slub.c (ffffffff813aab14)
Location: include/linux/atomic/atomic-long.h:459
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
Location: include/linux/atomic/atomic-long.h:459
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
Location: include/linux/atomic/atomic-long.h:459
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
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
```
```
In mm/memremap.c (ffffffff813e7079)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
```
```
In fs/inode.c (ffffffff814170e7)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff81435665)
Location: include/linux/atomic/atomic-long.h:459
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
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (ffffffff8146252c)
Location: include/linux/atomic/atomic-long.h:459
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
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - block/bio.c:bio_uninit
```
```
In block/blk-core.c (ffffffff8167a045)
Location: include/linux/atomic/atomic-long.h:459
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
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_end_request_batch
```
```
In block/blk-mq-sched.c (ffffffff8168fc02)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff816a4bf7)
Location: include/linux/atomic/atomic-long.h:459
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
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid
  - block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid
```
```
In block/blk-throttle.c (ffffffff816a8869)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In io_uring/io_uring.c (ffffffff816d6d97)
Location: include/linux/atomic/atomic-long.h:459
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
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (ffffffff819b77f7)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_free_idle_workers
```
```
In drivers/scsi/scsi_lib.c (ffffffff81a0180a)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff81b5b692)
Location: include/linux/atomic/atomic-long.h:459
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
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
```
```
In kernel/kthread.c (ffffffff8111ca12)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff81210f85)
Location: include/linux/atomic/atomic-long.h:459
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
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81215d96)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_change_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff81217155)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff8121effb)
Location: include/linux/atomic/atomic-long.h:459
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
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_free_deferred
  - kernel/bpf/syscall.c:bpf_map_alloc_percpu
  - kernel/bpf/syscall.c:bpf_map_kzalloc
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
```
```
In kernel/bpf/helpers.c (ffffffff812f4447)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_cgroup_release
```
```
In kernel/bpf/arraymap.c (ffffffff812fe1e4)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/trampoline.c (ffffffff81308bd6)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_tramp_exit
```
```
In kernel/bpf/memalloc.c (ffffffff8131c60c)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:bpf_mem_alloc_destroy
  - kernel/bpf/memalloc.c:bpf_mem_alloc_destroy
  - kernel/bpf/memalloc.c:alloc_bulk
```
```
In kernel/bpf/cgroup_iter.c (ffffffff813255aa)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - kernel/bpf/cgroup_iter.c:bpf_iter_detach_cgroup
  - kernel/bpf/cgroup_iter.c:cgroup_iter_seq_fini
```
```
In kernel/bpf/bpf_cgrp_storage.c (ffffffff81325a1a)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete_elem
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_update_elem
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_lookup_elem
```
```
In kernel/bpf/cgroup.c (ffffffff8132a74e)
Location: include/linux/atomic/atomic-long.h:459
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
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In mm/oom_kill.c (ffffffff81364c9b)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff81369589)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
```
```
In mm/vmscan.c (ffffffff8138262c)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - mm/vmscan.c:run_cmd
  - mm/vmscan.c:lru_gen_del_mm
```
```
In mm/backing-dev.c (ffffffff81397e01)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/percpu.c (ffffffff8139dcb0)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_memcg_post_alloc_hook
```
```
In mm/gup.c (ffffffff813b2008)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:gup_pte_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/mmap_lock.c (ffffffff813b3e86)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - mm/mmap_lock.c:get_mm_memcg_path
```
```
In mm/memory.c (ffffffff813bc41e)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/memory_hotplug.c (ffffffff813f1797)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - mm/memory_hotplug.c:pfn_to_online_page
```
```
In mm/swap_state.c (ffffffff813f96c8)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:filemap_get_incore_folio
  - mm/swap_state.c:swap_cache_get_folio
```
```
In mm/swapfile.c (ffffffff81400f35)
Location: include/linux/atomic/atomic-long.h:459
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
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_free_entry
```
```
In mm/hugetlb.c (ffffffff8140d61e)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:clear_vma_resv_huge_pages
  - mm/hugetlb.c:coalesce_file_region
  - mm/hugetlb.c:coalesce_file_region
```
```
In mm/slub.c (ffffffff8142cd6c)
Location: include/linux/atomic/atomic-long.h:459
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
Location: include/linux/atomic/atomic-long.h:459
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
Location: include/linux/atomic/atomic-long.h:459
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
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
```
```
In mm/memremap.c (ffffffff8146fb6e)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - mm/memremap.c:free_zone_device_page
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
```
```
In fs/inode.c (ffffffff814a26e7)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff814c36d2)
Location: include/linux/atomic/atomic-long.h:459
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
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (ffffffff814f2b7c)
Location: include/linux/atomic/atomic-long.h:459
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
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - block/bio.c:bio_uninit
```
```
In block/blk-core.c (ffffffff817364ea)
Location: include/linux/atomic/atomic-long.h:459
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
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_end_request_batch
```
```
In block/blk-mq-sched.c (ffffffff8174e7bf)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff81763986)
Location: include/linux/atomic/atomic-long.h:459
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
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid
  - block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid
```
```
In block/blk-throttle.c (ffffffff8176727e)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In io_uring/io_uring.c (ffffffff8178b897)
Location: include/linux/atomic/atomic-long.h:459
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
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - io_uring/fdinfo.c:io_uring_show_fdinfo
```
```
In io_uring/rsrc.c (ffffffff817a0809)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_rsrc_refs_drop
```
```
In lib/percpu-refcount.c (ffffffff817d92aa)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/pci/p2pdma.c (ffffffff8191ce77)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pmem_free_sgl
  - drivers/pci/p2pdma.c:p2pdma_page_free
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/block/loop.c (ffffffff81b2caf7)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_free_idle_workers
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b7fe5a)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff81cf5062)
Location: include/linux/atomic/atomic-long.h:459
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_start
  - drivers/md/md.c:mddev_init_writes_pending
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
